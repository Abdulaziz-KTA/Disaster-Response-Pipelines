# Disaster-Response-Pipelines
### This project is to classify disaster response messages through machine learning.
## Content
<ol>
  <li>Data
  <ol>
  <li>process_data.py: reads in the data, cleans and stores it in a SQL database. Basic usage is python process_data.py MESSAGES_DATA        CATEGORIES_DATA NAME_FOR_DATABASE
  <li>disaster_categories.csv and disaster_messages.csv (dataset)
  <li>DisasterResponse.db: created database from transformed and cleaned data.
    </ol>
<li>Models
  <ol>
  <li>train_classifier.py: includes the code necessary to load data, transform it using natural language processing, run a machine learning model using GridSearchCV and train it. Basic usage is python train_classifier.py DATABASE_DIRECTORY SAVENAME_FOR_MODEL
  <li>classifier.pkl : after training
  </ol>
<li>App
  <ol>
    <li>run.py: Flask app and the user interface used to predict results and display them.
     <li>templates: folder containing the html templates
  </ol>
</ol>

## Libraries:

<b> I am ues <a href="https://www.anaconda.com/">Anaconda</a>, Anaconda command line and <a href="https://anaconda.org/anaconda/spyder">Spyder(3.3.6)</a>,all Libraries you can find in Environments Anaconda Navigator</b>


## Acknowledgements
This project was prepared as part of the <a href="https://www.udacity.com/">Udacity</a> Data Scientist nanodegree programme. The data was provided by <a href="https://www.figure-eight.com/">Figure Eight</a>.
