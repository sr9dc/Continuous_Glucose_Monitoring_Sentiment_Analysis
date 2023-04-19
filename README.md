# [Analyzing Social Media Sentiment of Continuous Glucose Monitoring Tools](https://github.com/sr9dc/Continuous_Glucose_Monitoring_Sentiment_Analysis/blob/main/Final%20Report.pdf)

<!--
*** Thanks for checking out this project. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
-->



### Built With

* [Jupyter Notebook](https://github.com/sr9dc/Continuous_Glucose_Monitoring_Sentiment_Analysis/blob/main/final_notebook.ipynb)



<!-- ABOUT -->
## Topic
The purpose of this project is to analyze and research the status quo around current Diabetes technologies/research in order to fast-track solutions to existing problems. In 2019, diabetes was the direct cause of 1.5 million deaths in 2019. Thus, it is imperative that solutions are effective and quickly implemented. In this notebook we analyze current CGM sentiment, compare Dexcom and FreeStyle Libre, and make recommendations for existing companies to market their strengths and bolster the weaknesses, or for disruptors to enter the market and capitalize on the unmet needs of the consumer.


## Overview

We analyzed the dataset “Diabetes Continuous Glucose Monitoring – Data Export.xlsx.” provided by Anupam Singh and the team at 113 Industries. This set contains information about continuous glucose monitoring (CGM) which analyzes data from a sensor inserted under the skin for diabetic patients.


Diabetes is a metabolic disease that causes high blood sugar when the body cannot produce enough insulin (Type 1 – 10%) or cannot use the insulin it does make (Type 2 – 90%). In 2019, diabetes was the direct cause of 1.5 million deaths, and with the advent of the COVID-19 pandemic, is a significant contributor to mortality from COVID-19. Diabetes cannot be cured but can be managed. The goal of diabetes management is to reduce A1C levels, which measure the amount of hemoglobin (a protein in red blood cells) that has glucose attached to it. Glucose levels are usually measured with finger-stick blood glucose tests, but an emerging alternative is the use of continuous glucose monitoring (CGM) which analyzes data from a sensor inserted under the skin. Since CGM is always on, glucose levels can be tracked in real-time to see how glucose levels change throughout the day. CGMs are usually used for type 1 diabetes.


## Methodology

We utilized different 3 stages for modeling: an overall sentiment analysis of opinions from the entire data frame, a Dexcom-specified product sentiment analysis, and a Libre-specified product sentiment analysis.
For each one of these stages, we utilized 3 machine-learning classification models from the Scikit-learn package distribution: Multinomial Naive Bayes, Random Forest, and XGBoost. This resulted in a total of 9 models. The purpose of utilizing a larger number of classification models was to isolate key findings between each of the 3 datasets. By starting with general takeaways on the topic of CGM, we then focused our efforts on differentiating sentiment between Dexcom and Libre products.

TF-IDF vectorization was used on the cleaned and lemmatized data to create the three different train and test sets (‘df’, ‘df_dexcom’, and ‘df_libre’). We utilized an 80% to 20% train/test split, enabled hyperparameters, and ran an accuracy, F1 score, and classification report on each model.


## Code

#### [Combined Notebook](https://github.com/sr9dc/Continuous_Glucose_Monitoring_Sentiment_Analysis/blob/main/final_notebook.ipynb)



## Results

View the report pdf to see our detailed findings. 


#### [Final Report](https://github.com/sr9dc/Continuous_Glucose_Monitoring_Sentiment_Analysis/blob/main/Final%20Report.pdf)


## Presentation

View the presentation slides. 


#### [Presentation](https://github.com/sr9dc/Continuous_Glucose_Monitoring_Sentiment_Analysis/blob/main/Final%20Presentation.pdf)


## Team 

Sai Rajuladevi

Jonathan Wang

Nehal Chaturvedi


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.


<!-- CONTACT -->
## Contact

Sai Rajuladevi: https://www.linkedin.com/in/sai-rajuladevi/





