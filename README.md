# Analyzing Unstructured Data: Craigslist Categorization Enhancement

This project explores the intelligent categorization and tagging of Craigslist's computer and computer parts listings using advanced NLP and image recognition algorithms. The aim is to enhance search efficiency and user experience by auto-suggesting categories and generating precise tags.

## Table of Contents
- [Overview](#overview)
- [Background](#background)
- [Problem Definition](#problem-definition)
- [Proposed Solution](#proposed-solution)
- [Business Analysis](#business-analysis)
- [Data Analysis](#data-analysis)
  - [Text Classification Preparation](#text-classification-preparation)
  - [Image Classification Preparation](#image-classification-preparation)
- [Conclusion](#conclusion)
- [References](#references)

## Overview

This repository contains code and documentation related to our project on improving the categorization of computer and computer parts listings on Craigslist. By leveraging machine learning and data analytics techniques, we aim to significantly enhance user experience and create new monetization opportunities for Craigslist.

## Background

Craigslist, a pioneering marketplace, has a vast presence in over 700 cities across 70 countries. Despite its success, the platform faces challenges in categorizing listings, especially in the computer and computer parts section. This misclassification undermines user experience and dilutes the platform's usability.

## Problem Definition

In the computer and computer parts section, users often encounter unrelated items, leading to a disjointed search experience. This highlights a critical flaw in Craigslist's categorization capabilities, necessitating an intelligent solution to improve user satisfaction and marketplace efficiency.

## Proposed Solution

We propose an intelligent categorization and tagging system tailored for Craigslist's computer and computer parts listings. By leveraging advanced NLP and image recognition algorithms, our solution promises to auto-suggest the most fitting categories and generate precise tags, refining the listing process and enhancing search efficiency.

## Business Analysis

Our solution addresses Craigslist's weaknesses in monetization and adaptability by potentially increasing user engagement and reducing operational costs. By ensuring precise categorization, we aim to enhance the user experience and keep Craigslist competitive.

## Data Analysis

### Text Classification Preparation

- **Data Cleaning:** Removing non-alphanumeric characters, emojis, and graphical elements.
- **Tokenization:** Breaking down text into individual words or tokens.
- **Stopwords Elimination:** Discarding common words with negligible analytical weight.
- **Stemming:** Reducing words to their root forms.
- **Lemmatization:** Converting words to their canonical form based on context.
- **TF-IDF Vectorization:** Transforming text into a numerical format interpretable by machine learning classifiers.

### Image Classification Preparation

- **Reshaping to 64x64 Pixels:** Ensuring uniformity in input dimensions.
- **Normalization:** Scaling pixel values to a range of 0 to 1.
- **Uniform Color Space:** Converting images to RGB.
- **Model Architecture:** Using VGG16 for convolutional neural networks (CNNs) with ReLU activation.

## Conclusion

Our intelligent categorization and tagging system, leveraging NLP and machine learning algorithms, significantly improves the accuracy of Craigslist's listings. This enhancement streamlines the user journey, increases user engagement, and opens new avenues for monetization. By setting a new standard in classified ad categorization, our project influences the broader online advertising ecosystem, promoting data-driven approaches and elevating digital advertising quality.

## References

- [Craigslist Business Model Analysis](https://businessmodelanalyst.com/craigslist-business-model/#Craigslist_Value_Propositions)
- [Craigslist Value Propositions](https://businessmodelanalyst.com/craigslist-business-model/#Craigslist_Value_Propositions)

---

Feel free to add any additional information or customize it further as needed.
