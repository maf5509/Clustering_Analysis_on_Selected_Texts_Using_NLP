# Clustering Analysis on Selected Texts Using NLP

### How to group a disparate collection of short texts using unsupervised learning techniques

![Image description](https://tclibraryblog.files.wordpress.com/2016/10/projectgutenburg.jpg?w=526&h=315)

## The Task

The corpus to be studied consists of 105 short stories downloaded from various sources on the internet. Sources include the Gutenberg Project and textfiles.com. Authors range from Jack London to Emile Zola, to Fyodor Dostoevsky, to a number of lesser-known authors. The texts are drawn from the romance, science fiction, detective and occult genres. Texts that cannot be easily identified as being from any of those genres are classified as 'miscellaneous'.

In the analysis, each text will be identified by its author and title, and categorized according to its genre and the collection, if applicable, from which it was taken. Publication dates span the period from 1880 to 1992. Note that only the first 6000 characters of each text were used, due to the limited available processor power. Sparse representations were created for each text using the TF-IDF algorithm. A variety of unsupervised and then supervised modeling techniques were then carried out on these representations. For further details, please look through the notebook or see the write-up [here](https://www.markferguson.info/post/clustering-analysis-on-selected-texts-using-natural-language-processing/ "NLP Project Page").
