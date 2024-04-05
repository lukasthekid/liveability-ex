# Livability Analysis Project

![image.png](https://zenodo.org/badge/DOI/10.5281/zenodo.10931591.svg)

To run your Jupyter notebook on Python 3.10, a person will need the following:

1. **Python 3.10**: This is the programming language you're using. It can be downloaded and installed from the official Python website.

2. **Jupyter Notebook**: This is the environment where you're running your code. It can be installed via pip (`pip install notebook`) or with Anaconda.

3. **Required Libraries**: Any Python libraries that your notebook uses, such as pandas and matplotlib as mentioned in your project. These can be installed via pip (e.g., `pip install pandas matplotlib`).

4. **Data Files**: The CSV files that your notebook uses. These should be in the same directory as your notebook or in a place where your notebook can access them.

5. **GitHub Repository**: If the data and Jupyter notebook are stored in a GitHub repository, the person will need to clone this repository to their local machine.

6. **An IDE or a text editor**: To view and edit the .ipynb files, tools like Jupyter, PyCharm, or even text editors like Sublime Text or Visual Studio Code can be used.

Please note that the exact instructions might vary depending on the person's operating system and setup. It's a good practice to include a README file in your repository with setup instructions and any other important information about your project. This will make it easier for others to use and contribute to your project.


## Data Description

This project uses three main datasets to analyze livability in cities worldwide. Below is a brief description of each dataset:

### 1. World Happiness Report
This dataset is available on [Kaggle](https://www.kaggle.com/datasets/unsdsn/world-happiness). It uses data from the Gallup World Poll to rank countries based on their happiness scores. The scores are derived from the Cantril ladder, which asks respondents to rate their current lives on a scale of 0 to 10. The dataset includes nationally representative samples for the years 2013-2016. It also provides six factors that contribute to life evaluations in each country: GDP per Capita, Family, Life Expectancy, Freedom, Generosity, Trust Government Corruption.

### 2. Movehub City Rankings
This dataset provides key metrics for over 200 cities. It includes two CSV files:

- `movehubqualityoflife.csv`: This file ranks cities based on Movehub Rating, Purchase Power, Health Care, Pollution, and Quality of Life.
- `movehubcostofliving.csv`: This file provides cost of living data for different cities, including the cost of Cappuccino, Cinema, Wine, Gasoline, Average Rent, and Average Disposable Income.

### 3. Global Liveability Ranking
This dataset is a yearly assessment published by the Economist Intelligence Unit (EIU). It ranks 172 global cities for their urban quality of life based on assessments of stability, healthcare, culture and environment, education, and infrastructure. Each feature can achieve a score between 0 and 100. The dataset also includes a Crime Rating, where a lower score indicates that people feel safer in the city.

Please note that all these datasets are open source and can be freely used for research purposes. For any questions or clarifications, feel free to raise an issue in this repository.
