# CryptoClustering
I began my analysis by considering the concept of Machine Learning, which involvesa process of using algorithm and statistics to create models that can learn from past data and create predictions and decisions about future data.


With this foundation, we proceeded to preprocess our initial data frame using StandardScaler. Our objective was to normalize the data so that it had a mean of 0 and a standard deviation of 1, ensuring consistent scaling.

Next, we identified the optimal value for 𝑘: k in our original data using the KMeans algorithm and visualized it with an Elbow Curve. This helped us determine that the best initial value for 𝑘=4

After determining 𝑘, we performed clustering and incorporated our prediction data, visualizing the results with HVPlot.

The next three steps were centered on optimizing our data and creating an additional KMeans model, Elbow Curve, and clustering analysis.

Finally, we visualized that the optimal value for 𝑘 remained unchanged at 4, even though our clusters indicated greater accuracy in clustering.