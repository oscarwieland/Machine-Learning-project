# About this project

## Context
During the first semester of my master in Business Analytics, I took a machine learning course where I learned different models to make predictions. Throughout the year, I had the opportunity to participate in a group competition where:

## Goal 
The purpose of this project is to create a highly accurate machine learning model that Stack Overflow may utilize to automate the process of single-tagging user-generated articles.  These tags facilitate efficient information retrieval and contribute significantly to the platform's usability, allowing users to filter and access content pertinent to their interests and expertise levels. Our approach is designed to anticipate these tags by assessing the content and structure of the text.

The project will start with a comprehensive exploratory data analysis that looks at the distributions and patterns in the datasets, which includes the postings and the tags that go with them. This phase is critical for understanding the structure and nuances of the data we aim to model.

Then we will try some models seen in the lecture without any specified parameters and select 2 of them based on their training time, test time and accuracy. Subsequently, we will explain the maths behind those models and the differents features they can utilize. Next, we will explore the field of feature engineering, which transforms unprocessed textual input into a format appropriate for machine learning systems. This includes applying methods like vectorization, tokenization, and term frequency-inverse document frequency (TF-IDF) to highlight the significance of particular terms in the dataset.

Finally, we will evaluate the performance of our machine learning models for tag prediction on Stack Overflow employing a measure of accuracy defined by the proportion of correct predictions out of all predictions made, as per the standard formula:

$$
\text{Accuracy} = \frac{\text{Number of correct predictions}}{\text{Total number of predictions}}
$$



This statistic measures the frequency with which the model correctly recognizes the tags associated with each post, providing a simple way to assess the prediction effectiveness of our model.
