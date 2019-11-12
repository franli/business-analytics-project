# Business Analytics Project

This is the repository for the project done in the Business Analytics course in Fall 2018. In this project, I analyzed data on the [Mathematics Stack Exchange](https://math.stackexchange.com/) website. I built a logistic regression model to predict user reputations based on their answer and question data. 



### Report

The final report (in pdf format) can be found and downloaded from the following link

* [report.pdf](report.pdf)

The report is written using LaTeX. Source files can be found in [this](report) folder.

### Data

The data is downloaded from [ Stack Exchange Data Explorer](https://data.stackexchange.com/help). At the time of the analysis, the website has around 465K users, and 2.4 million posts (questions or answers). 



### Code

The website data downloaded from the Data Explorer are in xml format. I first extracted the relevant information, then aggregated and transformed the tables and computed the features. Exploratory data analysis was also done. Finally, a logistic regression model was built. All of the code can be found respectively in the following links

* [data-aggregation.py](code/data-aggregation.py)
* [data-extraction.py](code/data-extraction.py)
* [eda.py](code/eda.py)
* [model.py](model.py)

