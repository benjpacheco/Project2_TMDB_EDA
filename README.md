<h1 align="center">TMDB Exporatory Data Analysis</h1>

### Table of Contents

- [Installation](#installation)
- [Source of Data](#source)
- [Description](#desc)
- [Results](#results)

## Installation <a name="installation"></a>

You need to be able to work in a Jupyter Notebook on your computer. The following packages (libraries) need to be installed. You can install these packages via conda, pip, or by creating an environment from my environment.yml file.

- Pandas
- Matplotlib
- Seaborn
- conda env create -f environment.yml

## Source of Data <a name="source"></a>

Click this [link](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/July/5b57919a_data-set-options/data-set-options.pdf) to get more information on the dataset of this project.

## Description <a name="desc"></a>

In this project I perform exploratory data analysis on The Movie Database which contains information of about 10,000 movies. I measure key values such as revenue and user ratings. The purpose of the project is to insight curiousity and put the EDA process into practice. Some questions that I pondered on where:
- Which genres are most popular from year to year?
- Which director produced the most amount of movies?
- What year were the most movies released?
- Which movie had the highest budget and highest payout?

## Results <a name="results"></a>

- Western was the most popular genre over time
- Woody Allen and Steven Spielberg produced the most amount of movies
- Net Profit increased as Revenue did for all movie genres with and without accounting for inflation implying a positive correlation between budget and revenue.

