# COVIDPatents

The goal of the COVID Patents project is to identify patents of potential relevance to COVID-19, or coronaviruses in general.

The approach taken is relatively straightforward: A classifier is used to identify the relevant patents via their (textual) features. That classifier having been trained using scientific articles in the [CORD-19](https://www.semanticscholar.org/cord19) corpus as true positives and randomly selected scientific articles in PubMed as true negatives.

This project is intended to be self contained to the extent possible. Unfortunately some of the data is of a size that makes it inefficient to store in GitHub. Those files can be found in a Google Drive folder [here](https://drive.google.com/drive/folders/1I8uM1gWa9J93au8fuRZ-RTd3n15DnBsi?usp=sharing).

For a more indepth, but sometimes raw, overview of the project and its components please refer to ProjectOverview.ipynb.

The project as a whole can be run as a binder [here](https://mybinder.org/v2/gh/openner/COVIDPatents/master). Once the binder is up and running, replacing "tree" with "lab" will run it as a JupyterLab. Although, please note that because the data is not also stored in GitHub the extent to which you can actually run the notebooks is (for now) limited.

The project is being actively developed and is still in its early stages. I ([Orion Penner](mailto:orion.penner@gmail.com)) encourage you to reach out with questions, concerns, or if you are interested in being involved.