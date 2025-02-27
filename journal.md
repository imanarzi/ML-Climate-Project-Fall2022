9/16 - forking this reopository
<br>
9/23 - changing my research question to be about predicting wildfires. This new research question will incoporate many variables and most likely use deep learning to generate a probability of wildfire occurrence on a specific day and in a specific location.
<br>
9/30 - a lot of studies I found predicted the cause of wildfires. An estimated 85-90% of these causes are from humans (like arson or fireworks) and the remainder are natural (such as lightning).  I will change my research to consist of two parts: 
<br>
<ol>
<li> Training a model to predict the cause of a wildfire, and use this to fill in missing/miscellaneous values in the dataset. The prediction will most likely be binary (whether the cause was human or not).  </li>
<li> Show the presence and strength of the wildfire and climate change positive feedback loop.  Wildfires contribute to carbon dioxide emissions which lead to high temperatures, which makes land prone to more wildfires. </li>
</ol>
Data: https://www.kaggle.com/datasets/4735dcf84228370db9a551c153b520cc6d9166aaeadffaf6205745c31c3585ae or https://www.kaggle.com/datasets/rtatman/188-million-us-wildfires (the original larger dataset that this data is from)
<br>
10/7 - load data into a jupyter notebook and perform some data analysis. it apeears that the number of wildfires per year is not necessarily increasing, as well as the number of natual-wildfires. Will research some of the causes listed as 'miscellaneous' since these could also be natural (such as from a volcano). Also will begin to look into relevant literature.
<br>
10/14 - after looking at relevant literature, thinking of using regression to estimate area burned from a wildfire. will use the kaggle dataset in conjunction with the weather data set. did analysis to show that the area burned from wildfires has increased over time. did a simple linear regression with year, latitude, and longitude as the features. can also use a decision tree to determine which "category" the fire falls into (based on the area burnt).
<br>
10/21 - pivoting to study drought patterns with k-means and GMM clustering algorithms
<br>
10/29 - completed abstract and literature review, researching different algorithms and data
<br>
11/4 - import data and preprocessing, learning about best data format (went with PENTAD spi), begin writing methods section and researching different clustering algorithms
<br>
11/16 - ran k means and visualization, x-means and visualization, PCA. having issue with x=means converging at the maximum which must be defined by the user, so no real findings for k are made by x-means
<br>
11/23 - ran g-means and PCA w/ visualization (3 components, 1 map per component). ran and discovered that g-means results in 700+ clusters, so i increased clusters max for x-means to much higher. x means converges at ~130 clusters. also filtered data by rainy season.
<br>
12/1 - evaluating results by seeing how much variation is explained by PCA
<br>
12/8 - writing final paper methods and conclusion, ran final analysis of g-means and x-means vs. PCA as well as k vs. error
<br>
12/15 - wrote discussion section, polish final paper and code cleanup
