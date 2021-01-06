# GooglePlayStore

*Introduction:*

1) Internet is a true gold mine of data. E-commerce and review sites have a lot of untapped data with a prominent potential to convert into meaningful insights that can help with robust decision making.
Google Play Store is one such avenue on the internet.
2) Although any public datasets provide Apple App Store data, there are not many datasets available for Google Play Store apps anywhere on the web
3) Also Google Play Store uses sophisticated modern-day techniques (like dynamic page load) using JQuery making scraping more challenging.

*About the dataset:* The dataset is chosen from Kaggle. It is the web scraped data of 10k Play Store apps for analyzing the Android market. It consists of in total of 10841 rows and 13 columns.


*The variables in the dataset:*
1) App (Name)
2) Category (App)
3) Rating (App)
4) Reviews (User)
5) Size (App)
6) Installs (App)
7) Type (Free/Paid)
8) Price (App)
9) Content Rating (Everyone/Teenager/Adult)
10) Genres (Detailed Category)
11) Last Updated (App)
12) Current Version (App)
13) Android Version (Support)


*Packages Used:*
1) Pandas
2) Numpy
3) Matplotlib
4) Sklearn
5) Itertools
6) Seaborn
7) XGBoost
8) CatBoost


*Models Applied*
1) Logistic Regression
2) Decision Tree
3) Random Forrest
4) Naive Bayes

Note: Grid Search and Boosting techniques are also applied


*Conclusions*
1. We have applied several machine learning models on the google play store review dataset
2. Number of family category apps are highest on playstore (paid and unpaid), family apps also falls in top highest prices price, hence maximum total revenue is generated from the family category apps
Hence it can be said that family apps are highly prefered
3. After applying various models to the available dataset, we can see that random forest model with various parameters changes has given the best accuracy i.e. 78.92%~79% without overfitting the model (like in the case of decision tree).
