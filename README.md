# Genre Classification in Historical Newspapers: A Project Using the National Library of New Zealand’s Papers Past Open Data

This project explores feature sets and machine learning methods for classifying the genre of newspaper articles in the [National Library of New Zealand’s Papers Past open data pilot dataset](https://natlib.govt.nz/about-us/open-data/papers-past-metadata/papers-past-newspaper-open-data-pilot/dataset-papers-past-newspaper-open-data-pilot).

The genre classification pipeline is documented in a series of Jupyter notebooks designed to allow other researchers to easily apply and build on the results of this project. In addition, stand-alone notebooks are available for poetry, fiction, family notices, and letters to the editor, allowing the pipeline to be run end-to-end to discover examples of those genres in the dataset.

The [end-to-end notebooks](https://github.com/karinstahel/Papers-Past-Genre-Classification/tree/main/end-to-end-notebook-files) are provided in two versions, either including or excluding a TF-IDF feature, which is computationally expensive but improves precision for some genres. Further information is provided in the notebooks.

This project was carried out through the [UC Arts Digital Lab at the University of Canterbury](http://dh.canterbury.ac.nz/).

## The genre classification pipeline

![Genre classification pipeline](https://github.com/karinstahel/Papers-Past-Genre-Classification/blob/main/pp_genre_pipeline-01.png?raw=true)
