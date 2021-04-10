# Flipkart-Ecommerce-Product-Categorization

## Objective:

We have been given an Ecommerce Flipkart Dataset with exactly 20,000 samples. It has 15 columns with a lot of information. Our aim is to consider “Description” for a product, analyze it and predict which category it might fall under. There are few categories which are do not qualify as valid product categories. We will also see how we will handle that.

We will follow a holistic approach of step-by-step going through the data and predict product categories with highest possible true positives, thereby achieving maximum accuracy.


## Approach:

The steps involved are given as follows and have been explained in detail along with outputs inside the Google Colab Notebook

1.	Data Preparation: Cleaning and Analyzing data
2.	Visualize this Data
3.	Preprocessing textual Data
4.	Model Preparation for product categorization
5.	Measure the accuracy of the model
6.	Can we improve the accuracy of the model?
7.	What other algorithms can we try?

## Requirements:

Google Colab Notebook was chosen due to two reasons:

1.	RAM required (hosted on Cloud)
2.	GPU required for parallel processing (for saving time)

Since the functionality remains the same as Jupyter Notebook, we would utilize the resources provided by Colab platform.

The libraries used are generic and are as follows:

1.	Pandas (Library for handling tables and help in Data manipulation and analysis)
2.	Numpy (Library for mathematical and computational operations)
3.	Matplotlib (Library for plotting and visualization purposes)
4.	NLTK (Tool kit for natural language processing)
5.	Sklearn (Library for direct methods of Data splitting, Label encoding, Feature Extraction, Model implementation, Metrics like Accuracy calculation, etc)
6.	Keras (for providing python deep learning APIs and assist in Model creation)
