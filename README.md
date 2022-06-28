# kaz-nlp
NLP tools and resources for Kazakh language.
Join telegram group https://t.me/+TZchOYqlcAtjOTgy

# Near term goals

1. Build a corpus from high quality sources
2. Created a spell checker dictionary
3. ...



# Book parsing technique

1. Get a publicly available epub/pdf/dvju/etc. book.
2. If it consists of non-textual data, try to do OCR (a totally different stuff to take care of).
3. Otherwise there has to be some heuristical way to parse different epubs (usually epubs are just bunch of xhtml/xml files in a zip, the part with heuristics is important, due to that fact that there might be different markups/styles).
4. Break it down to sentences, index it somehow (NL index is not possible rn , since it has to be developed :D).
5. Build basic NLP tools with the data available (parser, lexer, tokenizer, morph analyzer, etc.)
6. With given basic NLP tools one can implement a search engine or an NL index (major PostgreSQL, MySQL, etc.) for kazakh language.

# Existing Corporas
## Text
* Kazakhstani news corpus for social significance identification with topic modelling results https://data.mendeley.com/datasets/hwj24p9gkh/1
* Kazakh Corpora Leipzig https://wortschatz.uni-leipzig.de/en/download/Kazakh
* Kazakh Corpora OSCAR https://oscar-corpus.com/
* Kazakh words database https://github.com/Epimetheus84/kazakh_words
* TenforFlow Kazkh Wiki dataset https://www.tensorflow.org/datasets/catalog/wikiann#wikiannkk
* WebCrawl https://data.statmt.org/cc-100/

## Speech
* IARPA Babel Kazakh Language Pack https://catalog.ldc.upenn.edu/LDC2018S13
* Mozilla https://commonvoice.mozilla.org/en/datasets

## Handwritten Kazakh
* Handwritten Kazakh and Russian (HKR) database for text recognition https://github.com/abdoelsayed2016/HKR_Dataset

# Resources on Kazakh that can be used to build corpora
* https://thehack.kz/
* https://book.chettam.kz/

# Other Resources
* Tree Visualizer for Universal Dependencies and Immediate Catena Analysis https://github.com/KoichiYasuoka/deplacy/blob/master/doc/kk.md
* UD Kazakh KTB https://universaldependencies.org/treebanks/kk_ktb/index.html
* Natural Language Processing Pipeline https://github.com/adobe/NLP-Cube#languages
* Turku neural parser pipeline https://turkunlp.org/Turku-neural-parser-pipeline/
* Frequency https://tbi.kz/ru/dictionary-frq
* NLP Tools from NU https://github.com/nlacslab/kaznlp
* Stemmer for ElasticSearch https://github.com/maximgorbatyuk/Kazakh-Stemmer-Elasticsearch-Plugin
* Apertium translation pair for English and Kazakh https://github.com/apertium/apertium-eng-kaz
* Apertium linguistic data for Kazakh https://github.com/taruen/apertium-kaz
* Hanspell Dict https://extensions.openoffice.org/en/projectrelease/kazakh-spelling-dictionary-200991
* Translated Text https://opus.nlpl.eu/
* Text recognition system for kazakh language https://github.com/Epimetheus84/kazakh_trs
* Part-of-speech taggers for Kazakh language https://github.com/tamirOK/Pos-taggers
* Neural LSTM Language Modeling experiments for Kazakh https://github.com/Baghdat/LSTM-LM
* Склонение слов по правилам казахского языка https://github.com/timurt/kazakh-grammar
* kazlemmatizer https://github.com/salamatin/kzlangtools/blob/master/lemmatizer/kazlemmatizer.py
