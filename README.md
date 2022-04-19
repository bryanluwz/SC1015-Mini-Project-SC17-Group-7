# Welcome to Movie Review Sentiment Analysis Repository (WIP)

## About

This is a Mini Project for SC1015 (Introduction to Data Science and Artificial Intelligence) of Nanyang Technological University (NTU).

This project focuses on sentiment analysis of reviews from IMDB, using MLP Classification with `sklearn`. For detailed walkthrough, please view the notebooks in the follwing order:

1. [P1_data_preparation.ipynb](./P1_data_preparation.ipynb)
2. [P2_classification_model.ipynb](./P2_classification_model.ipynb)

## Table of Contents

1. [Problem Definition and Motivation](#problem-definition-and-motivation)
2. [Datasets](#datasets)
3. [How we approach our problems](#how-we-approach-our-problems)
4. [Exploratory Data Analysis](#exploratory-data-analysis)
5. [Neural Netowrk Model](#neural-network-model)
6. [Outcome](#outcome)
7. [What we had learnt](#what-we-had-learnt)
8. [Conclusion](#conclusion)
9. [Demo](#demo)
10. [References](#references)
11. [Contributors](#contributors)
12. [Others](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

## Problem Definition and Motivation

How can we predict a movie's rating (positive or negative) solely based on its review?

## Datasets

We used a couple of datasets for training and testing purposes, which are the [IMDB review dataset from kaggle](https://www.kaggle.com/datasets/utathya/imdb-review-dataset) and another [control IMDB dataset from kaggle](https://www.youtube.com/watch?v=dQw4w9WgXcQ) as a benchmark for our model.

We went ahead and cleaned the datasets to our needs and save it into a separate zipped csv file. ผ(•̀_•́ผ)

- [imdb_master_cleaned.csv](./datasets/imdb_master_cleaned.zip)
- [IMDB_dataset_cleaned.csv](./datasets/IMDB_dataset_cleaned.zip)

## How we approach our problems

| Problems | Our solution |
| :------: | ------------ |
| Long training time | We tried reducing the amount of input features for our model by removing words that did not appeat frequent enough, by doing so we can train our model in a couple minutes. |
| Long dataset preprocessing time | We saved the processed dataset into a csv file so we can just load the cleaned dataset whenever we need to use it in the future. |

## Exploratory Data Analysis

- We used `matplotlib`, `wordcloud`, `seaborn` and other modules to help us visualise the data we had in hand.

- Insert some images here

![image 1](./images/temp.jpg)
![image 2](./images/temp.jpg)

## Neural Network model

- We tried training the model using `sklearn`'s many already pre-built model, we ended using `sklearn`'s neural network Multi-Layer Preceptron [`sklearn.neural_network.MLPClassifier`](https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPClassifier.html) as our machine learning model on classifying the movie reviees into positive or negative.

![another_image_here](./images/temp.jpg)

## Outcome

After optimising the parameters of our model, we managed to get a maximum of around 76% accuracy on our control dataset.

We had save the model into our pretrained_models directory for future use. Here are more details on the score of the model.

![model score stuff](./images/temp.jpg)

## What we had learnt

- We learned that they are many data preprocessing to be done before even starting to make and train the machine learning model.
- Being exposure to the MLP Classifier using Scikit Learn 

- We also learnt that idk

## Conclusion

- Machine Learning can be used for Natural Language Processing and idk...

## Demo

We can go to [the demo file](./demo.ipynb) to test our pretrained model on the test dataset. There, we can even input our own movie review (and label) to test our machine learning model.

## References

1. [Kaggle IMDB review dataset](https://www.kaggle.com/datasets/utathya/imdb-review-dataset)
2. [Kaggle IMDB control dataset](https://www.kaggle.com/datasets/utathya/imdb-review-dataset)
3. [scikit-learn working with text data](https://scikit-learn.org/stable/tutorial/text_analytics/working_with_text_data.html)
4. [Other source](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

## Contributors

(add github links)

- Bryan [@bryanluwz](https://github.com/bryanluwz)
- Justin [@speaklouderplease](https://github.com/speaklouderplease)
- Harish [@idk](https://www.youtube.com/watch?v=dQw4w9WgXcQ)
