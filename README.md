# Negra's big data derby competition

## Repo for Big Data Derby 2022 kaggle competition

### How to start

First make sure to have installed `python 3.8` and `pip`.
I could make this more walktrhough like, but, paja.

After that you have to get `poetry`

- linux or mac:
    `curl -sSL https://install.python-poetry.org | python3 -`

- windows (powershell):
    `(Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | py -`

Now, with your terminal in ~/repo/root/bid-data-derby-kaggle exec:
    `poetry install`


You should have now installed all the dependencies (e.g `kaggle`) to be able to run the project. Now follow the steps in [kaggle api documentation](https://www.kaggle.com/docs/api) to authenticate and then download the data for the competition.
cmd to download data: `poetry run kaggle competitions download -c big-data-derby-2022`

this .md is in WIP state, don't kill me
