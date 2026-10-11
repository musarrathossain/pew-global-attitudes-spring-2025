# Pew AI survey data walkthrough

A beginner notebook exploring the data behind Pew Research Center's **How People Around the World View AI** report, published October 15, 2025.

## What I explored

- The global dataset contains 28,333 respondents, 24 countries, and 483 variables.
- I counted respondents in each country and previewed individual records.
- I used the data dictionary to read question wording and decode numeric responses.
- I created working topic groups, with AI and internet use as separate groups.
- I explored six AI questions covering awareness, concern or excitement, and regulatory trust.
- I plotted Canadian respondents' combined trust in the EU and U.S.

The chart uses unweighted sample counts. It is a data walkthrough, not an estimate of public opinion. The topic groups are my organizational choices, not official Pew categories.

## Run the notebook

Use Python 3.12, open a terminal in this repository folder, and run:

```sh
python -m pip install -r requirements.txt
jupyter lab
```

Open `Pew_AI_Analysis.ipynb` and run the cells from the top. Keep the dataset folder beside the notebook. This sharing copy uses a relative data path and places the catalogue setup before the grouping cell. The original local notebook is unchanged.

## Data and attribution

Source: Pew Research Center, Spring 2025 Global Attitudes Survey. The CSV, dictionary, and original data-information PDF are included in the prepared local folder. Data rights remain with their original owner; this project does not apply a new license to Pew's materials.

- [How People Around the World View AI](https://www.pewresearch.org/global/2025/10/15/how-people-around-the-world-view-ai/)
- [Spring 2025 survey data](https://www.pewresearch.org/dataset/spring-2025-survey-data/)
- [Pew terms of use](https://www.pewresearch.org/about/terms-and-conditions/)

The global CSV excludes U.S. respondents. The downloaded U.S. Wave 166 dataset is separate and is not used in this notebook.
