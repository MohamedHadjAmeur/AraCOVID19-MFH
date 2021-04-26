# AraCOVID19-MFH:  Arabic COVID-19 Multi-label Fake News & Hate Speech Detection Dataset

## Description
AraCOVID19-MFH is a manually annotated multi-label Arabic COVID-19 fake news and hate speech detection dataset. The dataset contains 10,828 Arabic tweets annotated with 10 different labels. AraCOVID19-MFH labels, values, and their signification are provided in the below Table:

<p align="center">
<img src="https://github.com/MohamedHadjAmeur/AraCOVID19-MFH/blob/main/desc.JPG" width="600">
</p>
 
An example of the instances present in the dataset are provided in the below Table:

<p align="center">
<img src="https://github.com/MohamedHadjAmeur/AraCOVID19-MFH/blob/main/examples.JPG" width="600">
</p>

## CONTENT


This repository contains three files:
* Dataset in XML format.
* Dataset in TEXT format: Each instance in one line, the annotations of each instance are separated by the symbol ``|||||`` and their (value, types) separated by ``||``. 
* Dataset in CSV format.

Statistics about the number of tweets in each topic are provided in the below Table:

<p align="center">
<img src="https://github.com/MohamedHadjAmeur/AraCOVID19-MFH/blob/main/stats.JPG" width="600">
</p>

## Usage

The labels have been designed to consider some aspects relevant to the fact-checking task, such as the tweet's check worthiness, positivity/negativity, and factuality.  Though the dataset is mainly designed for fake news detection, it can also be used for hate speech detection, opinion/news classification, dialect identification, and many other tasks.


# Data Retrieval 

We provided only the user IDs following Twitter’s [Terms of Service](https://developer.twitter.com/en/developer-terms/agreement-and-policy).

Tools such as [Twarc](https://github.com/DocNow/twarc) or [Hydrator](https://github.com/DocNow/hydrator) can be used to retrieve the tweets using their IDs. In case of any problem you can contact the authors using the email provided in the below section.


# License

The AraCOVID19-MFH dataset is licensed under ``Creative Commons Attribution-Noncommercial-ShareAlike 4.0`` [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). 


## Citations
If you want to use the AraCOVID19-MFH dataset please cite the following paper:


## Contacts:
For all questions please contact ``mohamedhadjameur@gmail.com`` 




