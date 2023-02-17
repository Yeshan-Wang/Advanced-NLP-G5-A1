# Advanced-NLP-G5-A1
The code was carried out by Yeshan Wang during the course ‘Advanced NLP' taught by Luis Morgado da Costa and Jose Angel Daza at VU Amsterdam.

## REQUIREMENTS
- NLTK 3.7
- SpaCy 3.3
- NetworkX 2.7
- Pandas 1.5

## Data
The folder [**data**](https://github.com/Yeshan-Wang/Advanced-NLP-G5-A1/tree/main/data) contains the small set of English data in 'article.txt' is obtained from NL Times (https://nltimes.nl/2023/02/10/dutch-universities-still-struggling-uncover-work-written-chatgpt). All rights reserved.

## Code
### feature_extraction.ipynb
The notebook extracts several syntactic features from the original set of English data in 'article.txt' and save as corresponding conll files in the data directory:
- data/token-level-features.conll
- data/sentence-level-features.conll

### The following features have been extracted:
Token level:
- The full constituent starting from a head word
- The head of each token
- The dependent(s) of each token
- The Syntactic dependency relation from each token
- Part-of-speech tag of each token

Sentence level:
- Shortest dependency path of each sentence
- The length of shortest dependency path of each sentence
