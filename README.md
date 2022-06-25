# Cryptocurrencies
To use supervised learning to see how Bitcoin performs over time.

## Purpose
The purpose of this project is to analyze a database about cryptocurrencies using unsupervised machine learning. This information could be used by investment banks to analyze new cryptocurreny investments. 

## Summary 
We was able to reduce the data to only the necessary information which included: Coin Name, Algorithm, ProofType, Total Coin Supply, Total Coins Mined and class. 

The following are an example of tradeable cryptocurrency.
![tradeable cryptocurrencies](https://user-images.githubusercontent.com/96890065/175758049-e54ac377-daac-45ed-8a8e-b6050e15c9e9.JPG)

We were able narrow this information down by using an elbow curve which showed us the best k-value was 4. 

![elbow curve](https://user-images.githubusercontent.com/96890065/175758071-184e197e-54bd-4c60-9d69-3f3d244fabe6.JPG)

Once we had this information we could render a 3D Scatter plot with PCA data dn clusters. 

![3D scatter plot](https://user-images.githubusercontent.com/96890065/175758094-deac8654-2183-481f-8f5e-062d5c0e13be.JPG)

We could use an hvplot scatter plot to view Total Coins Mined vs Total Coin Supply, but the data is too clustered to be helpful. 

![hvplot](https://user-images.githubusercontent.com/96890065/175758114-bb514e04-01ab-4b9f-9d4e-38dbc25f15c4.JPG)

The 3D Scatter plot using PCA gives us a better picture.

## Conclusion
There are 532 tradable cryptocurrencies.  Further analysis would be needed to determine their performance over the long term and short term. 
