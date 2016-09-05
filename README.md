# ASD_Abs_Dataset

## Autism Spectrum Disorder Abstracts Dataset

Autism spectrum disorder (ASD) is a lifelong, pervasive
neurodevelopmental disorder that typically manifests at an
early age. Affecting approximately 1.5% of the population,
it is characterised by persisting deficits in social and reciprocal communication and interactions, alongside restricted and repetitive interests, activities and behaviours. It is estimated that ASD costs between $1.5 to $2.2 million per lifetime for developed countries.

Consequently, the research interest in ASD has increased dramatically. For example, there has been a five-fold growth in the number of related publications over the past decade. This massive amount of data provide us with new opportunities for knowledge discovery and data mining using computational approaches.

The present dataset consists of abstracts of all ASD-related papers retrieved from [Scopus](https://www.scopus.com/). A publication is assumed to be related if the term "Autism" is present in its title, abstract, or indexed keywords. The dataset comprises of 46,218 publications spanning from 1977 to 2015. 

To reduce the dimensionality and the effect of words inflexions, a soft lemmatization using WordNet lexicon is performed on the corpus, following by removing the so-called stop-words. Then a vocabulary is constructed by selecting a subset of the most frequent terms such that it explains 90% of the energy of the corpus. This method resulted in a vocabulary of 4,763 terms and a corpus of 3,735,764 tokens in total.

This dataset has been used in the following publications by now:

+ Analysing the History of Autism Spectrum Disorder using Topic Models  
Beykikhoshk, Adham and Phung, Dinh and  Arandjelović, Ognjen and Venkatesh, 
Svetha. To appear in the proceedings of IEEE International Conference on Data Science and 
Advanced Analytics (DSAA), Montreal, Canada, October 2016.    
<a href="https://adham.github.io/bib/2016-DSAA.bib" target="_blank">bib</a> | 
<a href="https://adham.github.io/abstract/2016-DSAA.txt" target="_blank">abstract</a> | 
<a href="https://sites.ualberta.ca/~dsaa16/" target="_blank">pdf</a>


+ Discovering Topic Structure of a Temporally Evolving Document Corpus  
Beykikhoshk, Adham and Arandjelović, Ognjen and Venkatesh, Svetha and 
Phung, Dinh. To appear in Knowledge and Information Systems Journal. December 2015, 
arXiv preprint arXiv:1512.08008.    
<a href="https://adham.github.io/bib/2015-KAIS.bib" target="_blank">bib</a> | 
<a href="https://adham.github.io/abstract/2015-KAIS.txt" target="_blank">abstract</a> | 
<a href="http://arxiv.org/pdf/1512.08008.pdf" target="_blank">pdf</a>


+ Hierarchical Dirichlet Process for Tracking Complex Topical Structure Evolution 
and its Application to Autism Research Literature  
Beykikhoshk, Adham and Arandjelović, Ognjen and Phung, Dinh and Venkatesh, 
Svetha. In the proceedings of Pacific Asia Conference on Knowledge Discovery and Data 
Mining (PAKDD), pages 550-562, 2015.   
<a href="https://adham.github.io/bib/2015-PAKDD.bib" target="_blank">bib</a> | 
<a href="https://adham.github.io/abstract/2015-PAKDD.txt" target="_blank">abstract</a> | 
<a href="http://link.springer.com/chapter/10.1007/978-3-319-18038-0_43" target="_blank">pdf</a>


Please cite the following if you have used this dataset in your research.  



    @inproceedings{beykikhoshk2015hierarchical,
    title={Hierarchical Dirichlet process for tracking complex topical structure evolution and its application to autism research literature},
    author={Beykikhoshk, Adham and Arandjelovi{\'c}, Ognjen and Venkatesh, Svetha and Phung, Dinh},
    booktitle={Proceedings of 19th Pacific-Asia Conference on Knowledge Discovery and Data Mining},
    pages={550--562},
    year={2015},
    organization={Springer}
    }