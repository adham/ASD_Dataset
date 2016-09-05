# Guide

This document provides the information required for using the dataset.  The data is saved in two zipped archives: 'bow.zip' and 'nn2eid.zip'.



## bow.zip
The data is provided in the Bag of Words (BOW) representation. The file 'bow.zip' contains the BOW representation of papers ordered by the publication year. For example, '1977_bow.txt' includes the abstracts of ASD-related publications in 1977. 

Each text file has *four* columns which are separated by space:

+ the first column represents the document ID, 
+ the second columns shows the sentence, 
+ the third column represents the word shown by its vocabulary ID,
+ and the fourth column is the number of repetition of the word in that sentence

For example, consider the following line in '1977_bow.txt':

    10 5 9 2

This line means the 9th word of the vocabulary is repeated twice in the 5-th sentence of the 10-th paper in 1977.


## nn2eid.zip
This file provides the equivalent *Scopus eid* of paper ids ordered by the publication year. For example, '1977_nn2eid.txt' contains the eid of papers published in 1977 and ordered by their paper id.

For example, consider the following line in '1977_nn2eid.txt':

    10 2-s2.0-7344233213
    
This line means the eid of the 10-th paper in 1977 is 2-s2.0-7344233213. This article can be accessed from 

To browse the article, you can use the following pattern and construct the URL to the Scopus document page: 

     https://www.scopus.com/record/display.uri?eid=EID&origin=resultslist
    
For example:

https://www.scopus.com/record/display.uri?eid=2-s2.0-7344233213&origin=resultslist




## Note
**This dataset uses a 0-based indexing.** 
 
