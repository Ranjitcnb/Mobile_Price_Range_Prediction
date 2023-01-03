# Mobile_Price_Range_Prediction
AlmaBetter Supervised Machine Learning Project
Mobile Prize Range Prediction:
ABSTRACT
During the purchase of mobile phones, various features like memory, display, battery, camera, etc., are considered. People fail to make correct decisions, due to the non-availability of necessary resources to cross-validate the price. To address this issue, a machine learning model is developed using the data related to the key features of the mobile phone. The developed model is then used to predict the price range of the new mobile phone. Three machine learning algorithms namely Support Vector Machine (SVM), Random Forest Classifier (RFC), Logistic Regression are used to train the model and predict the output as low, medium, high, or very high. The dataset used in this study is taken from Kaggle platform. In order to improve the classification accuracy, Chi-Squared based feature selection method is used. Among 21 features available in the dataset, only top 10 features namely RAM, pixel height, battery power, pixel width, mobile weight, internal memory, screen width, talk time, front camera and screen height are selected and used to train the model. Before applying feature selection, the accuracy obtained using SVM, RFC and Logistic Regression is 95%, 83% and 76% respectively. After feature selection, the accuracy of SVM, RFC and Logistic Regression improved to 97%, 87% and 81% respectively. From the experiments conducted, it is found that SVM gave superior performance when compared to other two classifiers.

Mobile phones come in all sorts of prices, features, specifications, and all. Price estimation and prediction is an important part of consumer strategy. Deciding on the correct price of a product is very important for the market success of a product. A new product that has to be launched, must have the correct price so that consumers find it appropriate to buy the product.

The Problem
The data contains information regarding mobile phone features, specifications etc and their price range. The various features and information can be used to predict the price range of a mobile phone.


The data features are as follows:
1.	Battery Power in MAH
2.	Has Bluetooth or not
3.	Microprocessor clock speed
4.	The phone has dual sim support or not
5.	Front Camera Megapixels
6.	Has 4G support or not
7.	Internal Memory in Gigabytes
8.	Mobile Depth in Cm
9.	Weight of Mobile Phone
10.	Number of processor
11.	Primary Camera Megapixels
12.	Pixel Resolution height
13.	Pixel resolution width
14.	RAM in MB
15.	Mobile screen height in cm
16.	Mobile screen width in cm
17.	Longest time after a single charge
18.	3g or not
19.	Has touch screen or not
20.	Has WIFI or not
Methodology
We will proceed with reading the data, and then perform data analysis. The practice of examining data using analytical or statistical methods in order to identify meaningful information is known as data analysis. After data analysis, we will find out the data distribution and data types. We will train 4 classification algorithms to predict the output. We will also compare the outputs. Let us get started with the project implementation.
