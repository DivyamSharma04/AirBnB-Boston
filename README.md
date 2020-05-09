# `Udacity Data Scientist Nanodegree`

## Project: _Wrting a Blog Post based on Findings in Airbnb Boston Data_

### Table of Contents
 1. Motivation
 2. Installation
 3. File Descriptions
 4. Results
 5. Licensing, Authors, and Acknowledgements

#### Motivation

Using the Airbnb Boston dataset, this project aims to answer three business questions of interest using descriptive analysis, inferential statistics.
 ``` sh
   > What are the features that highly correlate to price? 
   > How price and rating relate with each other?
   > What’s the major factor that influence price and ratings?
 ```
 
#### Installation

This project requires Python 3.x and the following Python libraries installed:

>NumPy
>Pandas
>matplotlib
>seaborn

You will also need to have software installed to run and execute an iPython Notebook.
Install Anaconda, a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

#### File Descriptions

**AirBnB Boston Analysis.ipynb** : A Jupyter Notebook with all the codes following the steps of CRISP-DM for analyzing Airbnb data in Boston and Seattle.

The following Airbnb activity is included in this Boston dataset:

**Listings.csv** : Including full descriptions and average review score
**Reviews.csv** :  Including unique id for each reviewer and detailed comments
**Calendar.csv** : Including listing id and the price and availability for that day


#### Results
Answer to Question 1:
The main features that highly correlate to price are:
 > Bedrooms
 > Beds
 > Accomodates
 > Room Type
 > Number of bedrooms
 > Number of guests

Answer to Question 2:

 >low ratings are associate with lower prices.
 >however high rating dose not mean high price.

Answer to Question 2:
The factor that influence price and rating are:

 >property_type : Ghesthouse
 >room_type : Entire Home/Apt
 >bed_type : Real Bed
 >host_response_time : within a few hours
 >zipcode : 02111
 >neighbourhood_cleansed : South Boston waterfront

#### Licensing, Authors, and Acknowledgements
Please feel free to folk this repository. I will be glad that if you can find some other interesting insights from the data, and plese let me know. You can leave comments on my blog post [here](https://medium.com/@divyams962/here-is-the-detail-analysis-of-airbnb-boston-data-set-b7acb616a9dc)

All data are downloaded from [here]((https://www.kaggle.com/airbnb/boston)). You can find the Licensing for the data and other descriptive information at the same link  available above.