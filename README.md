# Cricket World Cup-2019-Prediction

This repository will guide you through the basic analysis of dataset on international cricket matches played before CWC 2019.

## What the project is about?

The main objective of this project is to handle, explore, analyze the match stats for different matches played to represent the performance of each team playing CWC 2019 and subsequently using it to predict the result for different matches in the tournament.


## What is the task?

The task is to build an algorithm that predicts the outcome of a cricket match between two teams in a World Cup.

## What action did I take?

To predict the result, I merged all the scattered datasets to merge into one single CSV file. This dataset is the used to analyse the performance of each team based on which the prediction will be done. 

## Codes

 * merge_dataset.ipynb: The task of the code can be subdivided in following groups:
   - setting up the environment
   - wrangling the data
   - performing basic descriptive analysis from the features
   - getting rid of redundant features
   - handling missing values
   - merging scattered dataset
   - further getting rid of redundant features
   - compiling the final dataset as 'data.csv'
   
* CWC 2019.ipynb: The task of the code can be subdivided in following groups:
   - setting up the environment
   - performing basic descriptive analysis from the features
   - slight data wrangling
   - findining the correlation among features
   - graphical representation of features
   - identifying relevant features
   - training a machine learning model using it
   - wrangling the train data into a format suitable for the model
   - making prediction
   

## Summurizing the knowledge from our EDA.

- All necessary data wrangling to be done to train a machine learning model.
- The model is then used to make prediction.
- The prediction is matched with actual result to measure accuracy.


## What could be done in the future?

- Collecting more data and features will help to understand the factors impacting the outcome of a cricket match.
- More data will open the doors of deep learning algorithms.
- More in depth availability of data can enable us to make real time match predictions.
