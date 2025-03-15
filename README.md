# Ecommerce_Product_Recommendation_Using_Reviews

This project demonstrates how to build a recommendation system for e-commerce products based on customer reviews. The goal is to recommend products to users based on the sentiment of their reviews, allowing for personalized product suggestions based on past experiences and ratings.

## Problem Statement

E-commerce platforms often face the challenge of recommending relevant products to customers based on reviews. By analyzing customer reviews and product ratings, we can create a recommendation system that suggests products that are likely to be appreciated by users with similar preferences.

## Dataset

The dataset used in this project is from the Kaggle competition [E-Commerce Product Reviews](https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews).

The dataset includes:
- **Reviews**: Text data about customer opinions on products.
- **Ratings**: Numeric ratings given by customers to products.
- **Product Info**: Information about the product being reviewed.

## Project Overview

This notebook demonstrates the steps to build a recommendation system that:
1. Processes customer reviews and ratings.
2. Applies Natural Language Processing (NLP) techniques to analyze review sentiment.
3. Uses collaborative filtering and content-based filtering methods to recommend products.
4. Evaluates the performance of the recommendation system.

### Steps Involved:
1. **Data Preprocessing**: Loading and cleaning the dataset, including handling missing data and preprocessing text reviews for NLP.
2. **Sentiment Analysis**: Using NLP models to classify reviews as positive or negative, and processing text data into numerical form (e.g., using TF-IDF).
3. **Recommendation Algorithm**: Using collaborative filtering and content-based filtering methods to recommend products.
4. **Model Evaluation**: Evaluating the performance of the recommendation system based on metrics like precision and recall.

### **Model Performance:**
- **Precision:** 76%
- **F1-Score for Bad Reviews:** 73%
- **F1-Score for Good Reviews:** 92%
- **Overall F1-Score:** 88%

## Setup and Installation

To set up and run the project locally, follow the steps below:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Manishkatel/Ecommerce_Product_Recommendation_Using_Reviews.git
   cd Ecommerce_Product_Recommendation_Using_Reviews
   ```
   **OR**run it either on jupyter notebook or google_collab

   <p align="center"><b></b>Feel free to reach out for better model performance suggestions<b></b><p>

   
