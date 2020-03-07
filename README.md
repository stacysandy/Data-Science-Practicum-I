# Data-Science-Practicum-I
A repository for my Data Science Practicum I Project at Regis University.

## Project Title: Food is the Fuel to our Lives, but What Are We Really Consuming?

### Overview
This project assignment will be working with USDA's FoodData Central Data Sets and API. The API will allow me to retrieve a variety of data from a specific data repository of my choice or from the five data types available through FoodData central. First, I will conduct an analysis of nutrient labels for two types of food: sticky rice and 100% whole wheat bread. This will include visualizations that will help compare those food types to others within the same category and find how the nutritional values compare to one another. Another analysis will follow using the Nutrient List data from the USDA Standard Reference Legacy (2018). This analysis will display the data collected on macronutrients: Carbohydrates, Polyunsaturated fat, Protein, Saturated fat, Fiber, Sugar, and Kilocalories (energy). Keep in mind that the selections within this project are primarily random. It must also be taken into consideration that each human has their own unique health history, health needs, nutritional goals, and health focus. The goal of the project is first to compare nutritional label data against other related food products. As well as to see what we should be avoiding in relation to foods ranked by macronutrients.

### Objective
The research question at hand is that we need food to live and food is what makes our lives either better or worst. So, are we making the best food choices? What does nutritional value in food really mean? Are we eating nutritious food or are we eating what is easy, fast, and cheap? Perhaps, we have a favorite type of food or brand, does that effect our food decisions? Are we really selecting the healthiest food options? Or is our food selection based on other nutritional values or for other reasons? What if we could look at nutritional values, compare them based on our own health needs, and then decide if our choice of food is healthiest for us or if an healthier alternative option is available?

### Data
* FoodData Central Data https://fdc.nal.usda.gov/download-datasets.html
* FoodData Central API Guide https://fdc.nal.usda.gov/api-guide.html
* Nutrient List from Standard Reference Legacy (2018) https://www.nal.usda.gov/fnic/nutrient-lists-standard-reference-legacy-2018

Other available websites that contain supplemental data for the USDA FoodData Central website also include the following websites Center for Disease Control - National Center for Health Statistics: National Health and Nutrition Examination Survey (https://wwwn.cdc.gov/nchs/nhanes/default.aspx) And the USDA Agricultural Research Service (U.S. Department of Agriculture) - Food Surveys Research Group : Beltsville, MD (https://www.ars.usda.gov/northeast-area/beltsville-md-bhnrc/beltsville-human-nutrition-research-center/food-surveys-research-group/docs/whats-in-the-foods-you-eat-emsearch-toolem/). These supplemental websites may be used as a reference for further supporting material on my journey in looking at food consumption in the United States and the nutritional information of food.

### Data Documentation
* FoodData Central Data Type https://fdc.nal.usda.gov/data-documentation.html
* Food and Nutrient Database for Dietary Studies https://www.ars.usda.gov/northeast-area/beltsville-md-bhnrc/beltsville-human-nutrition-research-center/food-surveys-research-group/docs/fndds-download-databases/


### Research Questions
The research question at hand is that we need food to live and food is what makes our lives either better or worst. So, are we making the best food choices? What does nutritional value in food really mean? Are we eating nutritious food or are we eating what is easy, fast, and cheap? Do we really select the healthiest food? Or is our food selection based on other nutritional values or for other reasons? These high level research questions may expand upon themselves as the exploratory data analysis (EDA) can lead to other areas of interest or the unknown world of what is contained in the data.

### Data
The following data sets are available in csv format and can be downloaded at the following link https://fdc.nal.usda.gov/download-datasets.html. In summary, the available files include Foundation Foods, Branded Foods, SR Legacy, Supporting data for Downloads, and Full Download of All Data Types. These files are the most recent data up to December 2019. A full description of these data sets are defined in the USDA FoodData Central website under "Notes on Downloads".

### Available Documentations
FoodData Central Documentation for the data sets can be found at the following link https://fdc.nal.usda.gov/data-documentation.html.
FoodData Central API provides REST access to FoodData Central (FDC) and an API guide can be found at the following link: https://fdc.nal.usda.gov/api-guide.html

### Background: FoodData Central Data Types

FoodData Central mentions that the USDA website includes <u>five</u> data types:
1.	<b>Foundation Foods</b> – Which includes nutrient and food component values on a diverse range of ingredient and commodity foods as well as extensive underlying metadata.
2.	<b>Experimental Foods</b> – This links to relevant agricultural research data from multiple sources, such as as the Agricultural Collaborative Research Outcome System (AgCROS) (https://agcros-usdaars.opendata.arcgis.com/).
3.	<b>SR Legacy</b> – released in April 2018 and formerly hosted on the USDA Food Composition Databases website, is the final release of this data type.
4.	<b>Food and Nutrient Database for Dietary Studies 2013-2014 (FNDDS 2013-2014)</b> – contains data on the nutrient and food component values and weights for foods and beverages reported in the What We Eat in America dietary survey component of the National Health and Nutrition Examination Survey.
5. <b>USDA Global Branded Food Products Database (Branded Foods)</b> – formerly hosted on the USDA Food Composition Databases website, are data from a public-private partnership that provides values for nutrients in branded and private label foods that appear on the product label.

### History about the establishment of FoodData Central
Note that the prior USDA Food Composition Databases website (https://ndb.nal.usda.gov/) is no longer available due to the creation of FoodData Central which replaced the old USDA Food Composition Database. The USDA mentions that prior API usage on the USDA Food Composition Databases website is no longer being updated and will be discontinued in March 31, 2020

Source https://fdc.nal.usda.gov/faq.html

#### The following websites are available for direct food searchs:
* FoodData Central Search https://fdc.nal.usda.gov/index.html
* What's In The Foods You Eat Search Tool https://www.ars.usda.gov/northeast-area/beltsville-md-bhnrc/beltsville-human-nutrition-research-center/food-surveys-research-group/docs/whats-in-the-foods-you-eat-emsearch-toolem/

### Project Process:
* Conduct a Food Search endpoint to retrieve a list of foods that match search criteria: Sticky Rice.
* Exploratory Data Analysis (EDA) on retrieved food data, wrangle, clean, and create a data frame on Sticky Rice foods.
* Conduct a <b>Food Details endpoint</b> to obtain detail nutritional information for each particular food: Sticky Rice.
* Exploratory Data Analysis (EDA) on retrieved nutritional data, wrangle, clean, and create a data frame on Sticky Rice foods.
* Compile the foods with the nutritional data.
* Create visualizations with the data for analysis purposes.

Repeat the above on 100% Whole Wheat bread:
* Search for a list of 100% Whole Wheat Breads and EDA.
* Search for nutritional data on all 100% Whole Wheat Breads from the list and EDA.
* Compile the list with the nutritional data and create visualizations.

In final, compare and contrast findings. Answer research questions. Did you accomplish what your project objective detailed?

### Exploratory Data Analysis (EDA) - Collection, Preparation, cleaning and Data Visualizations
See Jupyter Notebook: Stacey_Sandy-Practicum_I.ipnyb

# Summary of FoodData Central Data Science Practicum I Project

### Original Goal: Are We Really Consuming the Healthiest Food?

### What Objective's did I meet?
* So Are we making the healthiest food choices?
Well, we can make healthy food choice if we want to and now that we know more about the highest macronutrients; we can try our best to consume less syrup and desserts such as chocolate mouse.

* What does nutritional value in food really mean?
It means we get energy from the nutrients within our food so it’s important for us to be knowledgeable on what we eat and what is in the food we eat.

* Are we eating nutritious food or are we eating what is easy, fast, and cheap?
Well I usually eat certain types of food if it tastes good, what ever the price it may be. So I didn’t get price values of the foods with my sticky rice and 100% Whole wheat bread food items from FoodData Central. But that could be a future endeavor if cost was of concern.

* Is our food selection based on nutritional values or for other reasons?</b><br> 
Our food should be based on nutritional values or at least as I mentioned before, we all have our own dietary needs and health needs. Therefore, we should be knowledgeable about what we eat.<br>

### Primary Question in this project:
* What if we could look take the nutritional values of a type of food, and then compare those values to see if our choice of food is the healthiest for us or if a healthier option is available?</b>

In fact, we did succeed at this. We learned 100% whole wheat bread is healthier than sticky rice. And the honey 100% whole wheat bread had the lowest sugars, highest protein, and lowest carbohydrate values. It also had the lowest calories.<br>

We looked at a number of Visualizations from my EDA process and compared my findings.
I attempted to apply two Machine Learning Algorithms: the Decision Tree and CatBoost library but both were unsuccessful.

### What did I learn? What challenges did I encounter?
•	I learned that exploratory data analysis takes a great amount of time to synthesize. Therefore, I should allow myself ample time for EDA!
•	Cleaning data is a hassle when dealing with centralize data.
•	I had to deal with differing unique values, foreign keys, and a number of varying attributes that was a challenge to pull together.
•	I also learned to take the time to breath and not overthink each piece of code that I write.
•	I also got to play with coding Python and R within a single Juptyer Notebook. That was fun! I wish I could have done more of it.

# Conclusion
This project and the data within this project became a large feat to overcome. It all resulted in a small dataset to bring information to light on nutritional data. If time were not of the essence, I could have conducted multiple food searches to emphasize the potential of the data and information being pulled from FoodData Central. However, I would like to think this was a huge accomplishment.

### So, where do we go from here?
We continue on to be more conscientious of our food consumption and the nutritional values. Or perhaps what can come next is if someone can create a method that can retrieve the nutritional data through an app. Could it be possible to scan the bar code on a food label and have the app return healthier alternatives? That would neat!

### Link to my PowerPoint presentation on YouTube:  
https://youtu.be/HBlV4Ib2FEk

### References and Sources

CatBoost documentation https://catboost.ai/

Center for Disease Control (CDC). (2018, October 30). NHANES Questionnaires, Datasets, and Related Documentation. CDC/National Center for Health Statistics. Retrieved from https://wwwn.cdc.gov/nchs/nhanes/default.aspx

Hsu, J. (2019, September 26). How To Flatten a Dictionary With Nested Lists and Dictionaries in Python. Retrieved from https://medium.com/better-programming/how-to-flatten-a-dictionary-with-nested-lists-and-dictionaries-in-python-524fd236365

pandas.DataFrame.plot documentation https://pandas.pydata.org/pandas-docs/version/0.23.4/generated/pandas.DataFrame.plot.html

Ray, S. (2017, August 14). CatBoost: A machine learning library to handle categorical (CAT) data automatically. © Copyright 2013-2020 Analytics Vidhya. Retrieved from https://www.analyticsvidhya.com/blog/2017/08/catboost-automated-categorical-data/

Rpy2 Documentation https://rpy2.github.io/doc/v2.9.x/html/index.html

U.S. Department of Agriculture, Agricultural Research Service. FoodData Central, 2019. fdc.nal.usda.gov.

U.S. Department of Agriculture (USDA), Agricultural Research Service. FoodData Central: Foundation Foods. Version Current: December 2019. Internet: fdc.nal.usda.gov.

U.S. Department of Agriculture (USDA), Agricultural Research Service. FoodData Central: USDA Global Branded Food Products Database. Version Current: July 2018. Internet: fdc.nal.usda.gov.

U.S. Department of Agriculture (USDA). (n.d.). Download FoodData Central Data. Retrieved from https://fdc.nal.usda.gov/download-datasets.html

U.S. Department of Agriculture (USDA). (2018). Nutrient List from Standard Reference Legacy (2018).  Retrieved from https://www.nal.usda.gov/fnic/nutrient-lists-standard-reference-legacy-2018

U.S. Department of Agriculture (USDA). (2019, October 17.). What's In The Foods You Eat Search Tool, 2015-2016. Retrieved from https://www.ars.usda.gov/northeast-area/beltsville-md-bhnrc/beltsville-human-nutrition-research-center/food-surveys-research-group/docs/whats-in-the-foods-you-eat-emsearch-toolem/

U.S. Department of Agriculture (USDA). (2019, October 17.). What's In The Foods You Eat Search Tool, 2015-2016. Retrieved from https://reedir.arsnet.usda.gov/codesearchwebapp/(S(lou5yebe332endidvuoarlyu))/CodeSearch.aspx

Yandex. (n.d.). CatBoost is a high-performance open source library for gradient boosting on decision trees. © 2020 Yandex. Retrieved from https://catboost.ai/

