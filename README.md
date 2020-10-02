<h1 align="center">
	<img
		width="300"
		alt="coding duck MX"
		src="https://raw.githubusercontent.com/CodingDuckmx/hello-world/master/codingduckMX_logo.jpeg?sanitize=true">
</h1>

<h3 align="center">
	Data Scientist // Mathematician
</h3>

<p align="center">
	<strong>
    <a href="https://twitter.com/CodingDuckmx">Twitter</a>
		•
		<a href="https://medium.com/@CodingDuckMx">Blog</a>
		•
		<a href="https://www.linkedin.com/in/jesus-caballero-medrano/">LinkedIn</a>
	</strong>
</p>



# Predicting stars on Kindle books' Reviews.

For this project, I decided to predict how many stars a customer is more likely to give to a specific written review. 

## Procedure

I pull up a 2 million data set of Kindle reviews, but due to computational limitations I was forzed to use only a random 10% sample of this dataset to work on.

Even though this project was challenging for me, it helped me to push myself to untaught themes like Natural Language Processing NLP. So this job was done focusing more on the Statistical tool rather than on NLP tools. 

### Deployment

I deployed, as a stretch goal, an app on Heroku, where you can take a shot of how this works. You can see it <a href="https://kindle-books-reviews.herokuapp.com/predictions"> here</a>.

<p align="center">
	<img src="https://raw.githubusercontent.com/CodingDuckmx/AmazonKindleReviews/master/Screenshot%20from%20Kindles%20Reviews%20app.png" width="550">
</p>

### Result

Some highlights of the analysis of the data could be read in my <a href="https://medium.com/@CodingDuckMx/predicting-kindle-books-reviews-3be74232e5d7">blog post</a>.

## In this repository:

Here is the final notebooks and some pickles I had to make, due the size of the data set. 

## Built With

  * gzip
  * json
  * pandas as pd
  * numpy as np
  * matplotlib.pyplot as plt
  * urllib.request.urlopen
  * string
  * seaborn
  * pickle
  * Heroku

## Version

This is the very first version. Sometime I'd like to use more powerfool NLP tools to compare the new results.

## Sources

* The dataset could be found here: https://nijianmo.github.io/amazon/  
* <a href="https://youtu.be/xvqsFTUsOmc"> Natural Language Processing in Python - a introductorial talk by</a> <a href="https://github.com/adashofdata"> Alice Zhao</a>
* <a href="https://github.com/adashofdata/nlp-in-python-tutorial"> NLP in Python tutorial - repository by</a> <a href="https://github.com/adashofdata"> Alice Zhao</a>
