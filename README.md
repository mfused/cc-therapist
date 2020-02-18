cc-therapist demo forked from inquire-boulder-chatbot
==============================
A chatbot for the climate change comforting<br>

This ongoing project was created as response to WOE bot, which I reallz like.


Keywords: RunwayML, GTP2, Python, Flask, Docker, Google Cloud Products, Dialogflow

This project is first test using RunwayML for exploration and prototyping and Flask and Docker for deployment on Google Cloud Products. The cloud service connects with a Dialogflow agent via webhooks, which provides the public interface.

The goal is to provide a working, better-than-baseline chatbot that is publicly accessible and can be flexibly scaled up and/or iterated with different datasets.


The text dataset was obtained from a webmaster at the City of Boulder. It has purpose just for the demo. Dataset on climate change is in the works.



Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── test           <- Handmade dataset for testing accuracy.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, ca nonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    |
    ├── evaluation         <- Scripts to automate model evaluation
    |
    ├── index.html         <- Github.io project page 
    |
    ├── lib                <- External tools library
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks for EDA and prototyping
    |   
    ├── planning           <- Project goals and journal
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │
    ├── scripts            <- Scripts to automate text cleaning and test set creation
    │   ├── deployment     <- Scripts for containerization and cloud deployment   
    │    
    ├── vizualization       <- Images for EDA and masks to generate images
    │
    └── test_environment.py <- tests correct version of python

--------

Project organization based on the cookiecutter data science project template.
https://drivendata.github.io/cookiecutter-data-science/
