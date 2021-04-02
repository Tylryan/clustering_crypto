# clustering_crypto

# Purpose
The script was designed to be able to analyze the various types of cryptocurrencies by grouping them by classification using unsupervised machine learning techniques.

# Steps involved
After the data was aqcuired, it then had to be preprocessed. This invovled slicing and dicing and standardization of the dataset. After the preprocess, it was then time to process the data. The first step was to essentially boil down the data leaving only the most important bits. This was accomplished using Principal Component Analysis (PCA). Then the data had to be clustered in a meaningful way. In order to do this, the optimal K value for the K Means analysis had to be found. To do this, I looped through various K values and plotted the results. This is known as an "Elbow Curve". This elbow curve helped me identify the most critical K value, which in my case happened to be 4. After this was discovered, this K value was then used to predict which class a particular cryptocurrency belonged to. All that was left to do after this was to simply (or in this instance, not so simply) plot the results. A 3D scatter plot was used to visualize the results as it has the ability to describe in greater detail the various classes/categories that were discovered while processing the data. 
