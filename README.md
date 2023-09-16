# Report on Factors that Affect Term Deposit Subscription Rate  (STAT201-Project)                                   

This project will dive into marketing data from a Portuguese banking institution to evaluate the effect of direct marketing campaigns on term deposit subscriptions. This dataset was obtained from the UCI machine learning repository from the following link:

https://archive.ics.uci.edu/ml/datasets/Bank+Marketing

In recent years, research has shown promising results of ‘direct marketing’ as an effective strategy to offer services directly to a specific customer (Menon et al., 2004). As the field of direct marketing has evolved, we want to further investigate the potential factors that could affect a client’s likelihood of subscribing to a term deposit via direct marketing, we have chosen this dataset which contains 1 dependent variable - successful/unsuccessful term deposit subscription, and other explanatory variables that could be potential determining factors that affect consumer decisions.

A recent study conducted by Hülsheger et al. (2022) suggested lower levels of positive affect at the beginning of the week, uncovering patterns largely in line with popular idioms like “Blue Monday” and “Thank God it’s Friday”. Considering this study, we will explore how the last day of contacting a client influences the client's decision on subscribing to a term deposit. We will investigate and compare the proportions of the clients that subscribed to a term deposit when the last day of contact is Monday vs Friday. Then we will measure the standard deviation of these proportions.

The question we will answer is: Does the last contact day of the week affect the term deposit subscription rate?

In order to answer our inferential question, we will explore two random variables: the last contact day of the week (day_of_week) and whether or not the client has subscribed to a term deposit (term_sub). The day_of_week variable consists of five categories detailing each work day which we will then filter to Monday and Friday, and the term_sub variable consists of binary categories, yes or no.
