Inexact-Search
==============

This is a Fuzzy string search application. This application illustrates the combined use of Edit distance and Indic Soundex algorithm.

By mixing both written like(edit distance) and sounds like(soundex), we achieve an efficient aproximate string searching. 
This application is capable of cross language string search too. 
That means, you can search Hindi words in Malayalam text. 
If there is any Malayalam word, which is approximate transliteration of hindi word, or sounds alike the hindi words, it will be returned as an approximate match.
The "written like" algorithm used here is a bigram average algorithm. The ratio of common bigrams in two strings and average number of bigrams will give a factor which is greater than zero and less than 1. Similarly the soundex algorithm also gives a weight. By selecting words which has comparison weight more than the threshold weight(which 0.6), we get the search results.

This module is a Java implementation of Inexact-Search module - [SILPA](http://silpa.org.in/) and is a part of SILPA Android SDK.

### Note :
1. This module is still under development and is part of SILPA Android SDK
2. This module belongs to SILPA project. Please check http://silpa.org.in/ApproxSearch


### Important Links
  -  [Try online Inexactsearch](http://silpa.org.in/ApproxSearch)
  -  [Inexactsearch source code](https://github.com/Project-SILPA/inexactsearch)
