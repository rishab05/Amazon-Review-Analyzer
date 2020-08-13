# Amazon-Review-Analyzer
A simple sentimental analyzer which can scrap product reviews from amazon and analyse them according to predefined features then show ouput as a bar graph.

## Run
1. install all the requirements by simply runing below coomand
```pip3 install -r requirements.txt```
2. after that run ```python3 Scraper/reviews.py```
3. All the reviews will be saved in "data.csv".

For Sentiment analysis run model notebook.
ps first install anaconda

## Features
* Scrap user reviwes with date,images links, author, ratings. And save to csv file
* Categerize reviews according to predefined features like camera, battery, display, processor etc.
* generate table and create plot according to positive, negative, nuetral reviews for each features by Sentimental analyzer trained model.

## Instruction
1. One have to define amazon review urls in "urls.txt". As a sample there are 10 links of Iphone 11 pro user reviews(india) form page 1 to 10.
2. The training data is saved in train_data.csv .
3. As a sample it showing plot for iphone11 pro reviews and save as "iphone11pro.png" and output csv as "attr_df.csv". You can chnage name of the file and also generate same for other products too.
4. features are defined only for Smartphones, for other prodcuts one have to define new features in notebook.

## Output
![](iphone11pro.png?raw=true "plot")


Created with :heart: by Rishabh Sharma
