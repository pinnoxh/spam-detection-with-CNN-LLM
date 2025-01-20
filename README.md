# Spam Detection in Short Message Service Using Convolutional Neural Networks with Word Embeddings from Large Language Models

## Table of Contents
+ [About](#about)
+ [Usage](#usage)

## About <a name = "about"></a>
This repository serves as documentation for the thesis of Muhammad Basil Musyaffa Amin, submitted as a requirement for graduation from the Informatics Engineering program, Faculty of Computer Science, Brawijaya University.

The repository aims to detect spam in Indonesian, English, and Bilingual texts using word vector representations from Large Language Models.

For any inquiries, feel free to contact via email at basilmusyaffa@gmail.com.

## Usage Folder <a name = "usage"></a>
+ Preprocessing -> It contains code for performing preprocessing tasks such as text cleaning, removing stopwords, stemming/lemmatizing, and tokenization. Preprocessing is done for both Indonesian and English datasets. The bilingual dataset is a mixture of the cleaned Indonesian and English datasets. You can download the .ipynb file to use the preprocessing workflow, adjusting the file directory for the dataset you are using. This preprocessing code will generate tokenization results in .pickle format, which are then used to create the embedding matrix.
+ Pembuatan Embedding Matrix -> It contains code used to create an embedding matrix from various LLM models. You can download the .ipynb file according to the language and LLM model you wish to use, and adjust the file directory of the tokenization results in .pickle format generated from the previous preprocessing code.
+ Pengujian Arsitektur & Pengujian Hyperparameter -> It contains code to obtain the most optimal model for each dataset used. You can use the code from the "Pengujian Hyperparameter" folder to apply the most optimal model by downloading the .ipynb file based on the language you want to use. Then, adjust the file directory for the dataset being used, the embedding matrix that has been generated, and the tokenization results in .pickle format.