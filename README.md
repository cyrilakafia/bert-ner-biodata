# Finetuning BERT to perform Named Entity Recognition (NER) 

Named entity recognition is also called token classification and it is a subtask of information extraction that seeks to locate and classify named entities mentioned in unstructured text into pre-defined categories such as person names, organizations, locations, medical codes, time expressions, quantities, monetary values, percentages, etc.

This repo serves as a starting point for finetuning a pre-trained BERT model to do token classification.

## How to

The notebook runs fine on google colab without any gpu however gpu may be required when data size increases. 

The following steps are covered:

1. Data preparation
2. Data preprocession
3. Tokenization
4. Finetuning
5. Evaluating
6. Saving Weights
7. Inferenct
