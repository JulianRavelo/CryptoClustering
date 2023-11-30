# CryptoClustering
## Scope
In this challenge, we used Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.  
To do so, we standardised the cryptocurrency data and then plotted an elbow curve to determine the optimal value for k. Having that, we predicted the clusters to group the cryptocurrencies and then plotted them to visualise them on a scatter plot.  
To compare our results with a different approach, we used the Principal Component Analysis. Using the standardised data and defining a set of 3 components, we plot a new elbow curve and scatter plot.  
Finally, we compared the elbow curves and scatter plots by using both methods to compare the results.   
## Results
As shown in the graphs below, we got different results for the elbow curves, but both methods suggested a k value of 4.   
![image](https://github.com/JulianRavelo/CryptoClustering/assets/132871396/c60e0355-b514-4ea0-8842-178b71198bd7)  

When plotting the scatter plots using the original data and the PCA method, we can conclude that we can use fewer features and get similar performance to the original model since we can identify four clusters.  
![image](https://github.com/JulianRavelo/CryptoClustering/assets/132871396/be951ada-4814-4872-9e27-31258fbcc4aa)  

## Resources
https://holoviz.org/tutorial/Composing_Plots.html  
