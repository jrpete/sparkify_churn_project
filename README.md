# README

## Instructions:
This project was created using a Jupyter notebook deployed onto an IBM Watson Cluster. You will need access to IBM Watson Studio 
in order to execute this code.  Run the Udacity Spark Notebook.ipynb Notebook in Watosn studio, linkking the 'medium-sparkify-event-data.zip' file 
dataset as an asset to the notebook or by downloading this dataset from the following link:
https://video.udacity-data.com/topher/2018/December/5c1d6681_medium-sparkify-event-data/medium-sparkify-event-data.json

Execute the code in SEQUENTIAL order, from top-to-bottom. Depending on the configuration of your Watson Cluster, some of the cells
may take hours to complete. 

## Motivation
This projects explores the topic of 'churn' rates among users of the fictional 'Sparkify' Music Streaming Serivce. The motivation for this
projects was to explore how features could be explored, engineered, modelled, and evaluated to predict if a user will upgrade or downgrade
their subscription from the Sparkify service. 


## Libraries
This project was built using Python 3.6 and the following libraries are needed to run this Notebook: 

	ibmos2spark 1.0.2
	pyspark 2.4.3
	pandas 1.1.4
	numpy 1.16.5
	matplotlib 3.1.1
	seaborn 0.9.0
	dateutil 2.8.0


## Files
There are only 2 files associated with this project: the Udacity Spark Notebook.ipynb Notebook containing the original code, and the 
medium-sparkify-event-data.zip file or link containing the Sparkify user data. 

## Acknowledgements

Credit goes to the approach laid out in the following Blog Post for how to use Oversampling to balance the dataset used in this project

https://medium.com/@junwan01/oversampling-and-undersampling-with-pyspark-5dbc25cdf253