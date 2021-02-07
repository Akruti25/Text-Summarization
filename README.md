# Text-Summarization
Automatic text summarization is the task of producing a concise and fluent summary while preserving key information content and overall meaning. 
The particular approach we’ve used here is extractive based:
In Extractive Summarization, we identify the important sentences or phrases from the original text and extract only those from the text. 
Those extracted sentences would be the required summary.

The extraction is made according to the defined metric without making any changes to the texts. For this purpose, we have used TF*IDF algorithm. 
TF*IDF is an information retrieval technique that weighs a term’s frequency (TF) and its inverse document frequency (IDF). 
Each word or term that occurs in the text has its respective TF and IDF score. The product of the TF and IDF scores of a term is called the TF*IDF weight of that term.
