<div class="LI-profile-badge"  data-version="v1" data-size="medium" data-locale="en_US" data-type="vertical" data-theme="dark" data-vanity="mohit-kundu"><a class="LI-simple-link" href='https://in.linkedin.com/in/mohit-kundu?trk=profile-badge'>Mohit Kundu</a></div>


# Text-Summarization
<img src="https://github.com/favicon.ico" width="48">

**Automatic summarization** is the process of shortening a text document with software, in order to create a summary with the major points of the original document. Technologies that can make a coherent summary take into account variables such as length, writing style and syntax.

Automatic data summarization is part of the real machine learning and data mining. The main idea of summarization is to find a subset of data which contains the "information" of the entire set. Such techniques are widely used in industry today. Search engines are an example; others include summarization of documents, image collections and videos. Document summarization tries to create a representative summary or abstract of the entire document, by finding the most informative sentences, while in image summarization the system finds the most representative and important (i.e. salient) images. For surveillance videos, one might want to extract the important events from the uneventful context.

There are two general approaches to automatic summarization:  Extraction and Abstraction. 
1.  *Extractive Summarization* : These methods rely on extracting several parts, such as phrases and sentences, from a piece of text and stack them together to create a summary. Therefore, identifying the right sentences for summarization is of utmost importance in an extractive method.
2.  *Abstractive Summarization* : These methods use advanced NLP techniques to generate an entirely new summary. Some parts of this summary may not even appear in the original text. Such a summary might include verbal innovations. 
Research to date has focused primarily on extractive methods, which are appropriate for image collection summarization and video summarization.

In this Jupyter notebook, TextRank algorithm for extractive text summarization is implemented using Google's PageRank search algorithm to generate corelations among sentences.

<img src="https://github.com/m0-k1/Text-Summarization/blob/master/images/nlp.png">

## Libraries Used
- [Numpy](http://www.numpy.org)
- [Pandas](https://pandas.pydata.org/)
- [Natural Language Toolkit](https://www.nltk.org/)

## Algorithms and Concepts
- TextRank
- [PageRank](https://en.wikipedia.org/wiki/PageRank)
- [Cosine Similarity](https://en.wikipedia.org/wiki/Cosine_similarity)

## How to run
- Install the required libraries using pip, virtual environment or conda.
- Run `jupyter notebook` in your terminal.

## Objective of the Jupyter Notebook

The dataset contains long descriptions (Introduction) of products. 
The task is to make a text summariser that takes these descriptions as input and summarises them into shorter versions without loosing the context.
The length of the summary is also adjustable by the user.

>Dataset- TASK.xlxs
