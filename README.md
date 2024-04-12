# NLP Analysis
>### HuffPost Article Classification <br />
<img src="https://github.com/chloecode86/NLP-Analysis--Financial-News/blob/main/image/HuffPost.jpeg" width="400" height="80"> <br /> 
<br /> 

#### Business Objective
To predict the category of the article based on headline.
<br /> 

#### Exploratory Data Analysis

df.head() <br />
<img src="https://github.com/chloecode86/NLP-Analysis--Financial-News/blob/main/image/df.head.png" width="800" height="200"> <br /> 
<br />
<img src="https://github.com/chloecode86/NLP-Analysis--Financial-News/blob/main/image/WordCloud.png" width="400" height="200"> <br /> 
<br /> 
<img src="https://github.com/chloecode86/NLP-Analysis--Financial-News/blob/main/image/Count_of_category.png" width="400" height="300"> <br /> 
<br /> 
<img src="https://github.com/chloecode86/NLP-Analysis--Financial-News/blob/main/image/Top_10_Unigrams.png" width="400" height="230"> <br /> 
<br /> 
<img src="https://github.com/chloecode86/NLP-Analysis--Financial-News/blob/main/image/Top_10_Bigrams.png" width="450" height="230"> <br /> 
<br /> 
<img src="https://github.com/chloecode86/NLP-Analysis--Financial-News/blob/main/image/Top_10_Trigrams.png" width="510" height="230"> <br /> 
<br /> 

#### Models Evaluation
<br /> 
<img src="https://github.com/chloecode86/NLP-Analysis--Financial-News/blob/main/image/Models_comparison.png" width="650" height="160"> <br /> 
<br /> 
Logistic Regression was suggested to be the best model based on its highest accuracy rate (0.49696) <br /> 
<br /> 
Yet, in light of the imbalanced class distributions of the sample, precision score and recall have also been taken into consideration. <br />
The SVC model gives the highest precision, suggesting a higher ratio of correctly predicted positives to the total predicted positives. <br />
Nevertheless, if misclassifying an article is costly, then the LR model would be a better choice as it gives a higher recall (correctly predicted positive to the actual positive). <br /> 
<br /> 
In addition, LR requires less computational power (run-time about 3–5 minutes) compared to SVC (1 hour). <br /> 
<br /> 
Thus, this report concludes that LR is much preferable and should be chosen to classify the articles. <br /> 
<br /> 
<img src="https://github.com/chloecode86/NLP-Analysis--Financial-News/blob/main/image/Confusion_matrix_LR.png" width="650" height="530"> <br /> 
<br /> 
