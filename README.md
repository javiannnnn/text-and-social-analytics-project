In this project, I perform the whole machine learning workflow from data scraping to text classification and model evaluation in an attempt to predict hotel review sentiment whilst comparing classical machine learning and deep learning based approaches for text classification. 

The project is split into 3 runnable Google Colab notebooks: scraper.ipynb is used to scrape the reviews as well as the relevant data as outlined in the notebook (change the link to change websites to scrape data for.), the data_preprocessing.ipynb file preprocesses the raw scraped data into data that is ready for the modelling portion of the project. The text_classification.ipynb file then applies 4 models onto the text classification tasks, and evaluates the performance of each one. 

Datasets I used are uploaded to git for reproducibility purposes. 
datasetA_cleaned.csv is used to train the models, while DatasetB.csv is the raw test dataset that should be used for an unbiased evaluation of the model's performance, and DatasetA.csv is the raw version of datasetA_cleaned.csv and should not be used for training of the models. 

If some of the visualisations in the text_classification.ipynb are not visible when being ran on your local computer's IDE then you should upload the python notebook onto Google Colab in order to view them.
