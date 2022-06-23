h# kaz-nlp
NLP tools and resources for Kazakh language

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
