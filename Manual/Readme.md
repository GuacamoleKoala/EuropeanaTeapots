# INFO ON FOLDER 'MANUAL'

This folder contains a manual of how to reproduce this (or a similar) project. 
In four chapter I explain different aspects, techniques, software, and so on.

**Chapter 1**: ManualEuropeanaTeapot_Chapter1_API.ipynb

The first chapter handles on how to retrieve metadata through Europeana API 
with the use of [Google Collab](https://colab.research.google.com/) or [Jupyter Notebook](https://jupyter.org/), and [Python](https://www.python.org/) language. 
The goal here is to write a script that search for teapots (f.e. through the query 'teapot'),
but also to improve the script by making it look for translations (f.e. 'theepot') and spelling variant (f.e. 'tea pot'). 
In the end I also want to make improvements to the script to look for specific forms of metadata. 

**Chapter 2**: ManualEuropeanaTeapots_Chapter2_DataRefinement.ipynb

This dataset can then be further refined and can be further analyzed. 
Therefore, in the second chapter I explain how I cleaned and enriched the dataset with software OpenRefine. 
The goal here is to use some techniques that are commonly used in OpenRefine and to achieve a dataset about teapots that is relatively clean. 
This is important for the visualisation and analysis in chapter three.

**Chapter 3**: ManualEuropeanaTeapots_Chapter3_AnalysisAndVisualisation.ipynb

In chapter three I look at how to calculate some extra parameters with the use of Excel. 
Next I visualize the data in the software Tableau Public. I create some sheets and some dashboards with the data. 

**Chapter 4**: ManualEuropeanaTeapots_Chapter4_IIIF_GITHUB.ipynb

In chapter four I give an overview of what I did in GITHUB to upload the project and I also give an overview of what files can be found there. 
This can be usefull when you want to follow the developments of this project. 
In chapter four I also have a look at the use of IIIF viewers for our dataset and I look for a solution to show this dataset with a viewer. 
Here I have a look at writing a HTML script to load the collection into a Mirador viewer.

**PDF version**

I also provided a pdf version of the chapter, instead of only the notebook version. In Google Colab it is not always possible to properly convert to pdf. Therefore, I used the Ploomber tool to make sure the conversion to pdf was clean and complete.

**Note**

Most of the programming/scripting in this project is realized with the help of generative AI ([Gemini 2.0 Flash](https://gemini.google.com/app?hl=nl-BE) 
and [Chatgpt 4.0](https://chatgpt.com/)).
