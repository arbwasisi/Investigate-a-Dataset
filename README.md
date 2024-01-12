# Investigate a Dataset

For this project, I conducted my own data analysis within a Jupyter Notebook and used it to create a shareable file that documents my findings. I started by taking a look at my dataset and brainstorming what questions I could answer using it. Then I used `pandas` and `NumPy` to answer the questions I'm most interested in, and created a report sharing the answers.

## Choosen Dataset
Several dataset were provided by Udacity for this project, here is the [link](https://docs.google.com/document/d/e/2PACX-1vTlVmknRRnfy_4eTrjw5hYGaiQim5ctr9naaRd4V9du2B5bxpd8FEH3KtDgp8qVekw7Cj1GLk1IXdZi/pub?embedded=True). I have choosen to investigate the TMDb dataset. This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue. Some of the features of this dataset to keep in mind are:
- Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters
- There are some odd characters in the ‘cast’ column, which we won't worry about
- The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time

## Questions
Here are the questions posed in this analysis:
1. What is the ideal movie runtime for higher revenue?
2. Does higher budget equate to more revenue?
3. What month of the year has the highest revenue?
4. Is there a correlation between a movies popularity and its revenue?
