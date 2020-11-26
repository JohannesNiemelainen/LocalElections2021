# PredictingLocalElections2021

# Project Title

Predicting Local Elections (Kuntavaalit) 2021 - Final project for the Building AI course.

## Summary

The aim of the project is to predict Finnish local elections (kuntavaalit) in April 2021 without polling data. Kuntavaalit is actually not a single election, rather ~300 elections in Finland.


## Background

Major pollster and news media have their interest in predicting the overall election results of Finland. However, predicting national result in local elections is a nice-to-know thing, and gives only a topic for pundits to discuss. I have not come across any public actor predicting results of all local elections in every municipality in Finland. I am a political geek myself, and in lack of accurate information, I feel necessary to provide the information myself.

The information is required to have an actual understanding about what is happening in Finland. Municipalities are the areas most relevant to everyday life of people in Finland, and being able to predict election results gives a view on the ideological composition of decision-makers in different municipalities. Also, if the prediction accuracy is high, it gives political actors information where they should concentrate their resources during the election campaign.

* No public predictions of local elections exist.
* Lack of information creates obscurity, and campaign managers do not know where they should put their resources.


## How is it used?

The solution is published on a web page as an spreadsheet or similar, low-complexity solution. The web page is open for everyone interested.

The solution will be published after the candidates have been officially confirmed in 18th March 2021. So basically I am trying to provide only the end results of different simulations, not a tool.


## Data sources and AI methods
Data for Predicting Kuntavaalit 2021 comes from Statistics Finland (Tilastokeskus). They have diverse data on both municipalities (demographics, industrial structure etc.) and previous local elections (number of candidates, mean age of candidates for each party etc.). Combining these data from 2008, 2012, and 2017 local elections provides a dataset of approx. 1,000 municipal election results, and approx. 7,000 municipal results for different political parties.

I have not collected the data yet.

AI methods that I will use are linear regression and K-nearest-neighbors. I will predict the results with both methods to see where I will receive the most accurate predictions.


## Challenges

The aim of the project is to learn if predicting local elections is possible without polling data. Polling is expensive, and that is the primary reason why there are no public predictions of results in local elections. The goal might not be reached, as there are limitations on the data, and it is unclear still if predicting Finnish local elections is possible based on demographic data and past elections data.

The project might not solve the initial problem, and thus, it might not give anyone any valuable input to their debates or decision-making processes.


## What next?

If the project succeeds, there are multiple future avenues to take.
* Create an actual tool to predict the election results in national parliamentary elections (national elections are also a combination of 13 separate elections in Finland. Only the European elections and presidential elections are truely national, thus, in those national polling gives a reliable prediction of the results).
* Predict local elections in other countries.
* To be able to move on, I will need a project group, so anyone interested in predicting election results, please contact me.


## Acknowledgments

* The inspiration to the topic comes from FiveThirtyEight and Nate Silver.
* So far I have not started to code anything. I will later on add 
