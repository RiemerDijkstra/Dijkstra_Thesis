# Dijkstra Thesis

### Main files:

1. subset_wiki.txt: a subset of the human dataset. It contains cleaned Wikipedia articles with a precise token size of 1000 tokens. Longer articles were cut in order to obtain 1000 token size. (See the link at bullet point 7. for the full dataset).

2. subset_GPT.txt: a set of generated articles based on the subset_wiki texts as input. This dataset therefore also contains articles with a token size of 1000 tokens. Each entry of the subset_GPT set corresponds to the entry in the subset_wiki set. This means that the first text of the GPT subset is based on the first text of the wiki subset and so on. (See the link at bullet point 7. for the full dataset).

3. Rejection_Sampling.ipynb: the code used for the implementation of the rejection sampling method. 

4. Generator.ipynb: the code used for generating new articles based on Wikipedia articles as input (using GPT-2 model).  

5. wiki_cleaning.ipynb: contains the code for extracting and cleaning Wikipedia dump files from the enwiki (English Wikipedia) database.

6. wikiextractor: folder containing all files needed for partly extracting and cleaning the Wikipedia dump files. Only the extract.py file has been altered in order to suit this project better. More details can be found in wiki_cleaning.ipynb.

7. The following link directs you to the complete GPT dataset and human dataset: https://drive.google.com/drive/folders/1RaizuBNXwcyICJ0FfanTDHGeGIh0R4ID?usp=sharing


