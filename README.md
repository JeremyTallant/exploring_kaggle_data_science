# Exploring the Kaggle Data Science Survey
## Description
When beginning a career in data science, one often wonders what programming tools and languages are being used in the industry, and what skills one should learn first. By exploring the 2017 Kaggle Data Science Survey results, you can learn about the tools used by 10,000+ people in the professional data science community.

This project uses a subset of the [2017 Kaggle Machine Learning and Data Science Survey](https://www.kaggle.com/datasets/kaggle/kaggle-survey-2017?utm_medium=partner&utm_source=datacamp.com&utm_campaign=ml+survey+case+study) dataset. If you want to know more about the tools and techniques Kaggle participants use, check out the full [report of the Kaggle 2017 survey results](https://www.kaggle.com/code/amberthomas/kaggle-2017-survey-results/report?utm_medium=partner&utm_source=datacamp.com&utm_campaign=ml+survey+case+study).
## Usage
Clone this repository and open the Jupyter notebook file (`*.ipynb`) in a Jupyter environment with R kernel support. Make sure to install the required packages such as `tidyverse`. You can do this by running the following commands in a code cell within the notebook:
``` r
install.packages("tidyverse")
```
Once the packages are installed, run the code cells in the notebook to generate the plots and analyses.

If you don't have a Jupyter environment set up, you can install Jupyter Notebook and the R kernel using the following steps:

1. Install Jupyter Notebook by following the instructions on the [official Jupyter website](https://jupyter.org/install).

2. Install the R kernel for Jupyter Notebook by running the following commands in your R console:
``` r 
install.packages("IRkernel")
IRkernel::installspec()
```
After completing the installation, launch Jupyter Notebook, navigate to the folder containing the notebook file, and open it to begin running the analysis.
## Contents
1. **Welcome to the world of data science:** Load the data and look at the first 10 responses.
2. **Using multiple tools:** Split the tools each respondent uses into separate rows.
3. **Counting users of each tool:** Find the number of respondents that use each language or tool.
4. **Plotting the most popular tools:** Create a bar chart that displays tool popularity.
5. **The R vs Python debate:** Calculate the number of respondents that use R, Python, and both tools.
6. **Plotting R vs Python users:** Calculate the total number of users that use R, Python, or both, and plot the results.
7. **Language recommendations:** Find language recommendations for users that use R, Python, or both languages.
8. **The most recommended language by the language used:** Create a faceted plot showing the top four language recommendations from users of R, Python, both, and neither.
9. **The moral of the story:** Determine if R-users find the statement "R is the language I recommend for new data scientists" to be TRUE or FALSE.