# Sentimental-Analysis-Project-R

## Overview

This repository contains the code for a Sentiment Analysis project in R, utilizing the e1071 Naive Bayes classifier. The project also includes a Swing-based user interface for a seamless user experience. Key text processing techniques such as removing stop words, tokenization, creating a sparse matrix, and generating a TF-IDF matrix are employed for effective sentiment analysis. A test dataset is given in this repository so you can format your file similar to this before feeding it into the swing interface.

## Dependencies

Ensure you have the following dependencies installed before running the project:

- R (latest version)
- RStudio (optional but recommended)
- Required R packages:
  - e1071
  - tm
  - Matrix
  - Swing

### NOTE:
There is a maximum file size limit for this classifier. Any file that exceeds this limit cannot be used in the classifier.

## Installation
Clone the repository:
```bash
git clone https://github.com/Poseidon284/sentiment-analysis-r.git
```

1. Open RStudio and set the working directory to the cloned repository.

2. Run the following command to install additional dependencies:

```R
install.packages(c("e1071", "tm", "Matrix","Swing"))
```

## Usage
Run the main R script:

```R
## Example for running the main script
source("UI.R")
```

- The Swing UI will be launched, allowing users to input text for sentiment analysis.

- The application will process the input, perform sentiment analysis using the e1071 Naive Bayes classifier, and display the results.

## Features
- Stop Words Removal: The project includes a mechanism to remove common stop words for more accurate sentiment analysis.

- Tokenization: Text data is tokenized into individual words, facilitating analysis at a granular level to use "bag of words" approach.

- Sparse Matrix: A sparse matrix is created for efficient storage and computation of text data.

- TF-IDF Matrix: The Term Frequency-Inverse Document Frequency (TF-IDF) matrix is generated to capture the importance of words in the dataset.

## Contributions
Contributions are welcome! If you want to contribute to the project, please follow these steps:

  1. Fork the repository.
  2. Create a new branch for your feature/bugfix.
  3. Make your changes.
  4. Test thoroughly.
  5. Submit a pull request.
