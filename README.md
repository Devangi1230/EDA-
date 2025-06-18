# EDA-
# GOOGLE PLAY STORE Exploratory Data Analysis 
📝 Overview
Google play store dataset is about what kinds of apps are being download.
this dataset shows which kind of app is more popular in which category and 
what price is charged and also customer reviews about each apps . 

❓What's the objective of the analysis?
1.Understand app trends on the Google Play Store by category, installs, ratings, and prices.
2.Find out what drives the success of an app (e.g., good ratings, high number of installs).
3.Identify patterns in user behavior by looking at app reviews, size, content rating, and so on.
4.Examine app distribution by category, free vs. paid apps, and price distribution.
5.Clean and preprocess the dataset to deal with missing values, outliers, and inconsistent data types.

❓Any key questions being answered?
1.Which Category has largest Number of installations?
2.What are the top 5 most installed Apps in Each popular Categories?
3.How many apps are there on google Play store Which get 5 Ratings?

📂 Dataset
Source of the data (Kaggle Google playstore)

Brief description (Size ~10,000 app records, Format - Csv)

KEY FEATURES
1.App: Name of the app
2.Category: Type of app (e.g., GAME, TOOLS, EDUCATION)
3.Rating: Average user rating (out of 5)
4.Reviews: Number of user reviews
5.Size: Size of the app (e.g., 19M, 25k)
6.Installs: Number of installations(10,000+,15000+)
7.Type: Free or Paid
8.Price: App price (if paid)
9.Content Rating: Suitable age group (e.g., Everyone, Teen)
10.Genres: App genres
11.Last Updated: Last date the app was updated
12.Current Ver / Android Ver: App version and minimum Android version required

📊 Analysis Summary
Key steps taken (cleaning, Exploring data, visualization, removing and filling null values )

Tools/libraries used ( pandas, matplotlib, seaborn)

🔍 Key Findings
1. Paid apps are least priority
2. Popular App is family but Games apps are most Installed
3. Subway sufer is the most installed app in Games Categrory
4. Facebook,instagram and Whatsapp is most popular in socai apps
5. Google Drive is most installed in the productivity Category 




# MYNTRA  Exploratory Data Analysis
📝 Overview
Myntra Fashion dataset is about what kinds of retails items especially cloths are being Purchased.
this dataset shows which the diference of purchasing in men and women and profit depends upon which year 
and season also what is the highest price in which category what kind of cloth plus who is the buyer as per gender 
with reviews and purchaed by  which age groups . What kind of discounts are given and in what size does the cloth came 
and which brand is most purchased by which gender and it's price amd in which seasons.

❓What's the objective of the analysis?
1.Understand  trends on the Myntra Ecommerce by category, brandname, ratings,gender, prices.
2.What is the highest price of which brand.
3.Identify patterns in user behavior by looking at reviews, price, rating, and so on.
4.Examine app distribution by category, discounts,seasons, and price distribution.
5.Clean and preprocess the dataset to deal with missing values, outliers, and inconsistent data types.

❓Any key questions being answered?
1.Top 10 Brand Purchase?
2.Gender based Catgory purchase in acording to price and brand ?
3.Most Purchased Individual Category by Women and Men?

📂 Dataset
Source of the data(Kaggle Myntra fashion csv)

Brief description (size 526563, format csv)

KEY FEATURES
1 Product Id: Ids of product
2 Brand Name: like Roadster, locomative, H&M etc
3 Category: like bottom wear , top etc
4 Indiviual Category: jeans , shirt etc
5 Gender: Male & Female 
6 Discription: cloth material and color
7 Discount Price: price discounted
8 orginal Price:  price 
9 Discount Offer: like 25% off , rs 349 off etc 
10 size option: S,M,L,XL etc
11 Rating: ratings (3.4,5 etc)
12 Reviews:Reviews counts ( 999,100)

📊 Analysis Summary
Key steps taken (cleaning, Exploring data, visualization, removing and filling null values )

Tools/libraries used ( pandas, matplotlib, seaborn)

🔍 Key Findings
1. Price anaylsis for category and individual Category
2. Category based on brand , highest brand purchase
3. highest Category respective to Orginal Price
4. Highest in price Purchased by which gender



# Flight Exploratory Data Analysis
📝 Overview
Flight dataset is about the flight being take of from which source to destination.
There many airlies that means there reviews it's journey , and it's stopage plus any additinal information 
for the travels , evaluating the price people spend on flights and which one of the most expense and what duration it take.

❓What's the objective of the analysis?
1.Understand of the airlines  by category, brandname, ratings,gender, prices.
2.What is the highest price of which airline .
3.Identify patterns in user behavior by looking at reviews, price, and so on.
4.Examine app distribution by price distribution.
5.Clean and preprocess the dataset to deal with missing values, outliers, and inconsistent data types.
6.The cleaning values are more on complex like arrival time , and the duration 

❓Any key questions being answered?
1.Highest Purchase of which airlines ?
2.How to wrok on column like Arrival time and duration ?
3.Which month traveling through flight take place?

📂 Dataset
Source of the data(Kaggle flight excel)

Brief description (size 4897, format excel)

KEY FEATURES
Airline: Jet Airways, IndiGo ,Air India etc
Date of Journey: 30-1-19
Source: New delhi , kolkata etc
Destination:banglore , chennai etc 
Route: BLR → DEL	etc
Deptaure Time:22:20etc
Arrival Time: 1:10 , 10 june etc 
Duration: 2h 30 m 
Total Stops: 1, 2 etc 
Additional Info: food availabilty etc 
Price: 35000 etc 

📊 Analysis Summary
Key steps taken (cleaning, Exploring data, visualization, removing and filling null values )

Tools/libraries used ( pandas, matplotlib, seaborn)

🔍 Key Findings
1. Which airline is most used for  traveled
2. which is the most popular destination and source
3. Which month traveling through flight take place
4. Highest Airline in Price


# White Wine Exploratory Data Analysis
White dataset is about the how and what kind of mixture are used to create it .
and compares it with quality

❓What's the objective of the analysis?
1.the dataset was not in tabular form  changs made by delimiter=';', quotechar='"'
2.Correlation between the materials added in wine  .
3.Identify patterns in user behavior by looking at 'fixed acidity', 'volatile acidity', 'citric acid', 'residual sugar', 'chlorides', 'free sulfur dioxide', 'total sulfur dioxide', 'density', 'pH', 'sulphates', 'alcohol', 'quality'
4. All data in numerical format 

❓Any key questions being answered?
1.Outliers?
2.Wine quality rating  ?
3.Correalation of Wine Features?

📂 Dataset
Source of the data(Kaggle White wine csv)

Brief description (size 4897, format csv)

KEY FEATURES
'fixed acidity', 'volatile acidity', 'citric acid', 'residual sugar',
'chlorides', 'free sulfur dioxide', 'total sulfur dioxide', 'density',
'pH', 'sulphates', 'alcohol', 'quality'

📊 Analysis Summary
Key steps taken (cleaning, Exploring data, visualization, Correlation )

Tools/libraries used ( pandas, matplotlib, seaborn)

🔍 Key Findings
1. KDE plots for each feature (e.g., alcohol, pH, residual sugar)
2. Boxplots to check for outliers
3. Alcohol vs Quality and  density vs alochol
4. Average Feature Values by Wine Quality after gouping them 
