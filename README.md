
![Dawn of Analytics Header](https://github.com/DawnGRoy/Consumer-Bliss-Brand-Success/assets/147440813/f74a86be-25e0-4f13-8981-f391e5f1eea2)

# Consumer Bliss, Brand Success 

## Project Overview
------
I'm Dawn Gleeson-Roy, a data analyst graduate from Lighthouse Labs with a passion for market and business analysis, and a background in education and theatre. Welcome to my project - Consumer Bliss, Brand Success.

## Project/Goals
-----
Since the pandemic and the rise of TikTok, there has been a significant increase in product purchasing driven by influencer reviews. However, individual differences in skin type and personal style can lead to a disparity between product expectations and reality. This can result in a loss of trust and potentially harm the brand-consumer relationship. Even if customers go through the process of returning a product, the inconvenience may lead them to avoid the brand in the future. As consumers, we don't want to spend extensive time researching products; we just want a product that works. This project aims to answer the question: Can we predict, based on consumer reviews and ratings, what products they may or may not enjoy?

## Process
------
 -[x] Step 1 - Data Retrieval and Cleaning:
 
 * Identified and cleaned diverse data types within the Sephora products and reviews dataset.

 -[x] Step 2 - Exploratory Data Analysis (EDA):
 
 * Utilized Python for exploratory data analysis to gain insights into the dataset.
 
 -[x] Step 3 - Hypothesis Testing Models:
 
 * Developed and implemented hypothesis testing models to analyze consumer behaviour patterns.
 
 -[x] Step 4 - Personalized Data Analysis:
 
 * Tailored the data analysis to specific consumer profiles for a more personalized understanding.
 
 -[x] Step 5 - Conclusion and Future Steps:
 
* Concluded the project by summarizing findings.
* Identified key areas for future analysis and exploration.


## Results
--------

### Correlation Analysis ###
Utilizing a Chi-Square test, the assessment of the correlation between skin types and products containing AHA or BHA in their name revealed a significant relationship, as indicated by the obtained p-value. Furthermore, a sentiment analysis on skin type versus reviews unveiled predominantly neutral sentiments, with minimal negativity. Notably, individuals with normal skin types showed a slight majority in positive sentiments.

![image](https://github.com/DawnGRoy/Consumer-Bliss-Brand-Success/assets/147440813/878c29f9-3509-4596-8e15-6991b41ba5bc)


### In-Depth Analysis of Top Reviewer (Author A) ###
Taking a closer look at the top reviewer in the dataset with 155 reviews (referred to as Author A), the distribution of reviews showcased a focus on skincare categories. The most-reviewed groups included moisturizers, face serums, and face wash & cleansers. Author A consistently provided 5-star reviews throughout, with the exception of facial peels.

![image](https://github.com/DawnGRoy/Consumer-Bliss-Brand-Success/assets/147440813/71c982ee-7788-4c4d-b85e-ed3aa8b6fa4d)


### Rating and Recommendation Trends ###
Examining the distribution of Rating and Recommendations for Author A revealed a predominance of 5-star reviews, with minimal instances of 1-star ratings. Author A recommended products 78.1% of the time, encompassing all 4 and 5-star reviews. Some 3-star reviews and even one 2-star review were deemed recommendable upon further analysis.

![image](https://github.com/DawnGRoy/Consumer-Bliss-Brand-Success/assets/147440813/303c910f-51ef-43b6-a764-5c935d714c86)
![image](https://github.com/DawnGRoy/Consumer-Bliss-Brand-Success/assets/147440813/e8af59eb-2bc8-438c-a2b4-7826a5331dcf)



### Rating Distribution Across Price Groups ###
Observing the distribution of ratings across different price groups for Author A, it became apparent that the majority of reviews were for products ranging from 0-125$. As prices increased, Author A was more inclined to leave 3-star or lower reviews, suggesting higher expectations with higher-priced items. However, noteworthy outliers existed in the first two categories, indicating that for lower-priced products, Author A needed to be particularly dissatisfied to provide a negative review.

![image](https://github.com/DawnGRoy/Consumer-Bliss-Brand-Success/assets/147440813/0b62c0a3-d9c4-41ab-b170-9564c8008160)


### Total Spending Analysis ###
In scrutinizing the total spending of Author A over the years, a significant increase occurred starting in 2018, peaking in 2019, followed by a gradual decrease until 2022, and a sharp decline in 2023. This drop is most likely attributed to the fact that the dataset only contains information up till late March of 2024. However, it is noteworthy that most reviews in 2023 were negative.

![image](https://github.com/DawnGRoy/Consumer-Bliss-Brand-Success/assets/147440813/8d245c84-2a55-4704-9b10-a0445d29eed2)


### Word Cloud Analysis ###
A word cloud was employed to identify aspects of products disliked by Author A. The analysis revealed that smell and eye irritation issues were prominent factors in both negative and positive reviews. Specifically mentioned in her 2023 reviews, the scent issue led to further investigation into ingredients. Negative reviews often included essential oils like Pineapple Peel Oil and Lavender Oil, known for strong and potentially irritating scents. In contrast, positive reviews tended to feature ingredients like Watermelon Seed Extract and Aloe Vera Leaf Juice, contributing to a milder and more neutral scent profile, aligning better with her preferences.

![image](https://github.com/DawnGRoy/Consumer-Bliss-Brand-Success/assets/147440813/d0e263e3-7722-46e2-8acb-23e71953dde1)
![image](https://github.com/DawnGRoy/Consumer-Bliss-Brand-Success/assets/147440813/e8a86603-82b2-4ece-8397-7d8661ed3256)



## Challenges 
------
Some of the challenges faced during this project include:

* Limited consumer knowledge: Uncertainty about whether the product was free or purchased.
* Inability to account for repurchase amount.
* Lack of information regarding the age and specific skin concerns of Author A.
* The dataset, while extensive, is still small compared to the true number of products and reviews for Sephora.
* Working with new libraries such as wordbubbles and sentiment analysis had a learning curve.

## Future Goals
-------
My future goals for this project include:

* Conducting consumer research to fill in gaps such as repurchasing behavior, age, and specific skin concerns.
* Utilizing Association Rule Mining to discover patterns and associations between different product features, ingredients, and consumer satisfaction.
* Performing temporal analysis to identify trends and changes in consumer preferences over time.

## Codes and Resources Used
------
* __Editor Used:__ Jupyter Notebook
* __Python Version:__ 3.12.0 

## Python Packages Used
------
* __General Purpose:__ os 
* __Data Manipulation:__ Numpy, Pandas, Wordcloud
* __Data Visualization:__ Seaborn, Matplotlib, WordCloud
* __Sentiment Analysis:__ Textblob, nltk (vader lexicon), nltk (Sentiment Intensity Analyzer)


## Source Data & Acknowledgements
------
The dataset used in this project was sourced from Kaggle, a platform for data science and machine learning. The dataset, titled "Sephora Products and Skincare Reviews", was collected and shared by the Kaggle user "Nady Inky" and is available at the following link:
[Click here to view the dataset on Kaggle](https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews/data)

__Data Collection:__ 
This dataset was collected via Python scraper in March 2023 and contains:
Information about all beauty products (over 8,000) from the Sephora online store, including product and brand names, prices, ingredients, ratings, and all features. User reviews (over 1 million on over 2,000 products) of all products from the Skincare category, including user appearances, and review ratings by other users

__License:__ [Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)
