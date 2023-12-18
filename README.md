Sentiment analysis Aigents for Chinese text
=============

What purpose does this project serve?
-------------
To explored the performance of sentiment analysis models of different combinations for the Chinese text in social media and to make experiment to study how performance varies with the change of combination of different segmentation strategies and Lexicon.

**Segmentation strategies:**
SnowNLP default
JIeba
N-grams from Aigents
Distinct word

**Lexicon:**
SnowNLP default Lexicon
Aigents Chinese text Lexicon

How to use it?
-------------
Check the .csv in repository and make your own input. And pay attention to the "colunm name" in JupyterNotebook file(2nd block)
A .xlsx file with sentiment analysis result is expected to be received

Lexicon of positive and negative N-grams are provided in the Lexicon_positive/negative_chinese.txt and can be modified.

Requirments
-------------
Check the requirements.txt file in repository and use it to install related dependent libraries.
