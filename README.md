# CaseOutcomePrediction
Domain Legal Analytics

In this project we have tried to explore different supervised machine learning techniques on US Supreme Court data and ensemble with Principal Component Analysis(PCA). Our objective was to find a comparative result of different algorithms and bring in the impact of unsupervised learning techniques like PCA. We have applied Logistic Regression, Multinomial Logistic regression and Gaussian Naive Bayes method individually as well as ensembled with PCA. We found Multinomial Logistic regression has high level of predictive accuracy even without PCA. Where as in case of Logistic Regression and Gaussian Naïve Bayes were very poor in accuracy if applied individually. But when applying PCA with Logistic Regression and Gaussian Naïve Bayes we found a significant improvement in accuracy to 93%, whereas Multinomial Logistic Regression which already achieved higher accuracy of 93%, after applying PCA it has achieved even higher accuracy to 97% for many of the outcomes. Thus, we establish that PCA is just not only an image processing algorithm it can create a significant impact even is legal analytics. At the end we have provided a table of comparison and a good granularity of predictive strength of each outcome feature, its contributing dependent variable and its limitation. This study can be an initial platform and reference for all legal analytics on US Supreme Court Data.

Skills and Tools

Big Data Analytics, Classification, Cluster Analysis

Conclusion

From this project it is very evident that unsupervised Learning Like Principal Component analysis which was traditionally used in healthcare and image processing, it has proved to be of good use for Legal Domain as well. One of its major benefit to reduce the classification and dimensional complexity has actually helped in Legal Domain Data Analysis. In case of Large Data Set like for US Supreme Court case outcome PCA does not need large computational time. PCA also helps where data collection is less, thus in case of India or other country where structured data collection is still not present or small can be beneficial Multinomial Logistic Regression: Multinomial Logistic regression has also given high accuracy even without PCA. Where ensembling with PCA it has reached even higher accuracy. As this algorithm helps us in non-linearity and multiclassification problem, it has helped in Legal Case also. So in both the algorithm which deals very well for classification complexity has helped in better accuracy. Algorithm Accuracy Without PCA Accuracy With PCA Logistic Regression Low Very Good (significant improvement) Multinomial Logistic Regression Very Good Very Good Gaussian Naïve Bayes Low Good (significant improvement)  
