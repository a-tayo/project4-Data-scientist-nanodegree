
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results/Conclusions](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

The following libraries were used in the project
* Matplotlib
* Pandas
* Seaborn
* Scikit Learn
* Numpy

## Project Motivation<a name="motivation"></a>

For this project, i was interested in exploring the provided Starbucks dataset provided by Udacity and which can also be found [here on kaggle](https://www.kaggle.com/datasets/blacktile/starbucks-app-customer-reward-program-data) to build a machine learning model that predicts whether or not someone will respond to an offer. To do this, i took the following steps.

* Carried out exploratory data analysis to determine how much people respond to starbucks offer based on the type of offer, the reward, the medium through which they received the offer and other metrics present in the dataset by answering the following questions.
> * What is the event distribution by gender and age?
> * What is the income level of people who completed the offer and those who do not?
> * How does reward, difficlty, duration and offer type affects the event outcome?
> * Do recent customers complete more offer than older customers?

* Clean the data, then build a machine learning model to predict whether an offer is completed or not.

## File Descriptions <a name="files"></a>

There is only one notebook (Starbucks-capstone-project) in this project which is used to carry out the exploratory analysis of the dataset and also contains the machine learning model used to make predictions on the dataset. 

The project also includes this README file which explains the motivations for the project, installation guides, file descriptions conclusions as well as acknowledgements.

## Results<a name="results"></a>
Below is a summary of the conclusion reached from the exploration exploration carried out in this project.

* Most customers do not show interest in the offers at all as it seems most people would rather buy than take advantage of the offer.
* Seeing as most offers sent to the male customers and those between the age bracket of 40 to 80 years were not completed, the company should target more people outside of this category for offers if they want more offers completed.

The technical details of the findings from the code can be found at the post available [here](https://medium.com/@a-tayo/starbucks-offers-a-technical-overview-e5fc3e1dd005).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The credit for the dataset used in this project goes to [Udacity](https://www.udacity.com).  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/datasets/blacktile/starbucks-app-customer-reward-program-data).

