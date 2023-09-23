# Topic Modeling, Aspect Extraction, and Sentiment Analysis

This repository contains Python code for performing topic modeling, aspect extraction, sentiment analysis, and visualization of results using a sample dataset of comments. Dataset obtained through [webscraping](https://github.com/KiradaLeBg/Zillow-scraping) 

## Overview

The code in this repository is designed to help you:

1. Perform Topic Modeling using Latent Dirichlet Allocation (LDA) to identify key topics within a collection of text data (comments).
2. Extract aspects related to each identified topic based on top keywords.
3. Analyze the sentiment of comments within each aspect and visualize the sentiment distribution.

## Prerequisites

Before running the code, ensure you have the following libraries installed:

- NumPy
- Pandas
- Matplotlib
- Sklearn
- TextBlob 

You can install these libraries using pip:

```shell
pip install numpy pandas matplotlib  sklearn textblob
```

## Usage
**Topic Modeling:**
The code performs LDA topic modeling on a provided dataset of comments. Adjust the dataset and LDA parameters as needed.

## Aspect Extraction:

After obtaining keywords for each topic, the code extracts aspects by finding sentences or comments related to those keywords. This provides context for each aspect.

## Sentiment Analysis:

Sentiment analysis is performed on the extracted aspects to understand the sentiment distribution within each aspect. Sentiment scores are visualized using box plots.

## Visualization:

The code generates visualizations to display the sentiment distribution for each aspect as box plots.

## Customization:

Modify the code to fit your specific dataset, adjust the number of topics, or fine-tune LDA parameters to suit your needs.

## Sample Dataset
A sample dataset of comments is provided in the code for demonstration purposes. Replace this dataset with your own data.

## License
This code is provided under the [MIT License](License). Feel free to modify and use it for your projects.

## Acknowledgments
This code was created as a sample project for educational purposes. If you find it helpful, please consider acknowledging this repository.

## Note: 
This README provides a high-level overview of the code and its functionality. Detailed instructions for running the code and customizing it are included within the code comments.

# DATA STORYTELLING 
[**MEDIUM**](https://medium.com/@delonisnr/from-client-satisfaction-to-business-growth-the-secrets-behind-stephanie-youngers-real-estate-e8a5548e5d1f)
