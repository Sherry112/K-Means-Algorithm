<h1>K - Means Algorithm</h1>
<p>This code demonstrates how to perform K-means clustering using the sklearn library in Python. K-means is an unsupervised learning algorithm used to identify clusters of data points in a dataset. Here are the steps involved:</p>
<ol>
    <li>Pick K points as the initial centroids from the data set, either randomly or the first K.</li>
    <li>Find the Euclidean distance of each point in the data set with the identified K points — cluster centroids.</li>
    <li>Assign each data point to the closest centroid using the distance found in the previous step.</li>
    <li>Find the new centroid by taking the average of the points in each cluster group.</li>
    <li>Repeat 2 to 4 for a fixed number of iterations or until the centroids don't change.</li>
</ol>
<p>The code imports the required libraries and reads in a dataset of income and age data. It then performs K-means clustering on the data, and plots the resulting clusters. It also shows an elbow plot to help determine the optimal number of clusters.</p>
<h2>Libraries Used</h2>
<ul>
    <li>sklearn.cluster for performing K-means clustering</li>
    <li>pandas for reading in and manipulating data</li>
    <li>sklearn.preprocessing for scaling the data using MinMaxScaler</li>
    <li>matplotlib.pyplot for creating plots</li>
    <li>warnings for ignoring FutureWarnings</li>
</ul>
<h2>Steps</h2>
<ol>
    <li>Import the required libraries</li>
    <li>Read in the dataset</li>
    <li>Plot the original data</li>
    <li>Perform K-means clustering on the data</li>
    <li>Plot the resulting clusters</li>
    <li>Scale the data using MinMaxScaler</li>
    <li>Perform K-means clustering on the scaled data</li>
    <li>Plot the resulting clusters</li>
    <li>Create an elbow plot to determine the optimal number of clusters.</li>
</ol>
<h2>Usage</h2>
<p>To run this code, you need to have the required libraries installed. You can install them using pip or any other package manager. Once the libraries are installed, you can run the code in a Python environment of your choice.</p>
<p>The income.csv file contains the data used in this code, and you can replace it with your own data to perform K-means clustering on your dataset.</p>
<h2>Example Output</h2>
<a href="https://imgur.com/tKCL7z8"><img src="https://i.imgur.com/tKCL7z8.png" width="300" height="300" title="K-Means Algo" /></a>

