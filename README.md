# Blackcoffer-Text-Analysis-Assignment
Main implementation performing sentiment scoring, text Preprocessing, and generating final results.
This repository contains the completed text-processing assignment implemented entirely in a Jupyter Notebook. The goal was to automate the sentiment scoring and text metric calculation pipeline using the provided input files and dictionaries. The notebook extracts article content, preprocesses text, applies sentiment rules, and generates the final output in the expected format.
Notebook Functionality
The notebook performs the following key operations:
1.Reads the input dataset containing article URLs
2.Extracts and cleans the article text
3.Removes stopwords and performs token-level preprocessing
4.Applies sentiment scoring using the Master Dictionary
5.Computes additional linguistic and readability metrics
6.Writes the final output into the formatted Excel output file

Requirements:
1.pandas
2.nltk
3.openpyxl
4.regex

How to Run:
1.Place the following required files and folders in the same working directory as the notebook:(Input.xlsx,StopWords,MasterDictionary)
2.Open the notebook.
3.Execute all cells sequentially.

Notes:
Only the .ipynb file is shared publicly here, as other support files were part of the original assessment submission and are not included in this repository.
