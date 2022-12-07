Vignette on anomaly detection with auto-encoders; created as a class project for PSTAT197A in Fall 2022. 

## Contributors:
Safiya Alavi, Eric Yoon, Mira Patel, Jai Uparkar, Eitan Rashkovan

## Vignette Abstract 
Autoencoders are a branch of artificial neural networks, specifically feed-forward neural networks, utilized for unsupervised learning - the branch of machine learning which analyzes and clusters unlabeled data. In our vignette, we utilized autoencoders to detect anomolies in a dataset. Our data set consists of information on Twitter accounts, which we used to classify which accounts are bots versus which are humans. The model is trained on human accounts, and will therefore not be familiar with bot data (in an ideal situation). Since the model will fail to accurately reconstruct anaomalies, high reconstruction loss indicates that an observation is an outlier. Our final model somewhat successfully differentiates the two types of accounts, although if given a wider timeframe, we anticipate being able to improve this model. 

## Repository
Our repository consists of the data sets, as well as a drafts folder. The final jupyter notebook is in the repository. 

## Reference List 
- https://www.kaggle.com/code/robinteuwens/anomaly-detection-with-auto-encoders/notebook#Training-the-auto-encoder 
- https://towardsdatascience.com/applied-deep-learning-part-3-autoencoders-1c083af4d798 
- https://blog.keras.io/building-autoencoders-in-keras.html
