# Dijkstra Thesis

### Main files:

1. ***generate_wiki.ipynb***: describes several models used for language processing. Individual runtimes are shown. The output generated by the distilGPT-2 model is saved in 'news_gen.txt'. This output is generated via input from BBC news articles (stated in 'news_raw.txt'). Each model can be used independantly. The GPT-2 model is slower than the distil version, hence the distilGPT-2 model was used for generation due to computing limitations.

2. ***corpus_maker.ipynb***: describes the methods used for obtaining a usable wikipedia corpus. At first, WikiCorpus was used in order to preprocess a wiki dump file. However, the WikiCorpus module preprocesses too intensively, discarding stop words, non-alphabetical characters and punctuation. The output of this method is stated in 'wikicorpus.txt'. The original dump file: 'enwiki-latest-pages-articles16.xml-p20460153p20570392.bz2'. The corpus_maker notebook also states the use of WikiExtractor. The output of this method is saved in 'new_wiki.txt'. The original file is the same dump file used for wikicorpus.txt.

3. ***enwiki-latest-pages-articles16.xml-p20460153p20570392.bz2***: used dump file (I have a bigger set downloaded on my computer)

4. ***wikicorpus.txt***: output of WikiCorpus module.

5. ***new_wiki.txt***: output of WikiExtractor module.

6. ***news_raw.txt***: set of BBC news articles written by humans (used as input for distilGPT-2)

7. ***news_gen.txt***: set of generated news articles (output of distilGPT-2)

8. ***wiki_human.txt***: set of Wikipedia articles written by humans (~650 samples, all around 500 tokens = 325.000 tokens)

9. ***wiki_gen.txt***: set of Wikipedia articles generated by GPT-2 (small) (~650 samples, all around 500 tokens = 325.000 tokens)


Dit is een test

