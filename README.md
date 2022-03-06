# Genre Classification in Historical Newspapers: A Project Using the National Library of New Zealand’s Papers Past Open Data

This project explores feature sets and machine learning methods for classifying the genre of newspaper articles in the [National Library of New Zealand’s Papers Past open data pilot dataset](https://natlib.govt.nz/about-us/open-data/papers-past-metadata/papers-past-newspaper-open-data-pilot/dataset-papers-past-newspaper-open-data-pilot).

The genre classification pipeline is documented in a [series of Jupyter notebooks](https://github.com/karinstahel/Papers-Past-Genre-Classification/tree/main/pipeline-files) designed to allow other researchers to easily apply and build on the results of this project. In addition, stand-alone notebooks are available for poetry, fiction, family notices, and letters to the editor, allowing the pipeline to be run end-to-end to discover examples of those genres in the dataset.

Two versions of the [end-to-end notebooks](https://github.com/karinstahel/Papers-Past-Genre-Classification/tree/main/end-to-end-notebook-files) are provided: including or excluding the TF-IDF feature. Including the TF-IDF feature is computationally expensive but improves precision for some genres. Further information is provided in the notebooks.

The original labelled dataset of 4,628 articles used for this project is included as a pickle file in the [pipeline-files folder](https://github.com/karinstahel/Papers-Past-Genre-Classification/tree/main/pipeline-files). The filename is '20220110_PP_4628articles_labelled.pkl'. A user who wants to experiment with different feature sets or models without sampling and labelling new data can load this dataset into [Notebook 3: Linguistic Features and Text Statistics])https://github.com/karinstahel/Papers-Past-Genre-Classification/blob/main/pipeline-files/3%20PapersPast_GenreClassification_LinguisticFeatures.ipynb) and go from there.

This project was carried out through the [UC Arts Digital Lab at the University of Canterbury](http://dh.canterbury.ac.nz/).

## The genre classification pipeline

![Genre classification pipeline](https://github.com/karinstahel/Papers-Past-Genre-Classification/blob/main/pp_genre_pipeline-01.png?raw=true)
