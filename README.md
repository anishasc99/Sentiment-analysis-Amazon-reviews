 # Sentiment-analysis-Amazon-reviews
Spacy sentiment analysis on Amazon reviews, scraped using Scrapy tool
<br/> Scrapy is a open-source, web-crawling tool used to scrape data. In this project, data has been scraped from Amazon reviews page and stored in reviews2.csv. 
<br/><br/> Once the data is scraped, it is loaded to the python notebook using pandas. 
<br/><br/> The multi-class problem is converted to binary classification problem for simplicity.  By default, 5/4/3 stars are considered as POSITIVE and 1/2 stars as NEGATIVE.
<br/><br/> There are some challenges faced in the reviews dataset, such as severe class imbalance problem. The positive reviews overshadows the negative reviews. Hence, it is  important to tackle this problem first.
<br/><br/> Downsampling has been performed to solve this issue. There are several other methods which could also be used such as SMOTE, upsampling, etc.
<br/><br/> After downsampling, the dataset is ready to be used for training and testing. Spacy is used for custom text classification. The precision, recall, F1 score and loss show how our model is performing.
<br/> <br/>References:
* https://blog.datahut.co/scraping-amazon-reviews-python-scrapy/
* https://www.machinelearningplus.com/nlp/custom-text-classification-spacy/
