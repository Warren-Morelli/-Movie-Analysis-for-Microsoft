## My repository and its contents

├── README FIRST.md  <- The README for this repo branch explaining it's contents - you're reading it now

├── Draft Notebook.ipynb  <- First analysis of the data in Jupyter notebook

├── Final Notebook, Factors That Determine a Successful Film.ipynb  <- Presentable analysis of data in Jupyter notebook

├── PDF Slides - Factors That Determine Successful Film.pdf <- PDF version of project presentation

├── Recording - Factors That Determine Successful Film.mp4 <- Recording explaination of project presentation

├── zippedData & zippedData2 <- Both sourced externally and generated from code

└── images <- Both sourced externally and generated from code



Please review our full analysis in *Final Notebook, Factors That Determine a Successful Film.ipynb* or my presentation *Recording - Factors That Determine Successful Film.mp4*

For any additional questions, please contact Warren Morelli at warren@momo-mktg.com


- - -


# Title

**Authors**: Warren Morelli

## Overview

In this project, I analysed a wide range of film databases from various sources (Bom, IMDb, etc), to come up with an understanding of what factors make a film successful and I have translated that into an actionable plan to help the decision-makers at Microsoft decide what type of film to create. 

After analysing the data, I came to the conclusion that the 3 main factors that determine whether a movie is successful are genre, release month and film runtime. Here are a couple of main points from my findings below:

Adventure is the genre that produces the most revenue, followed by action and sci-fi. 
Movies released in June-July and November-December are more successful, most likely due to the school holidays. 
And movies with a runtime of 90 - 150 minutes have the greatest success.


## Business Problem

Microsoft wants to get the most out of their investment in the movie industry. In order for them to achieve this, I have been tasked with determining the three most recommendations on what type of films they should create. The following Questions were addressed:

1- What are the most crucial factors that determine whether a movie is most profitable?

2- Is there enough data to be able to anaylise these factors

3- What are the most successful genres?

4- What is the ideal runtime for a profitable film?

5- Which months are films the most successful?


## Data

My data was taken from Bom, IMDb movie datasets which included films dated from 2010 and later.

I first started by dropping all of the variables that I thought wouldn’t effect the end result, producing the most revenue. A couple of the rows in my dataset were missing values. Luckily, I had a very large data base so I could afford to drop those one where need be. 

I added the domestic gross and forign gross together to find the total gross so I could compare that to the months, genres and runtime. There were quite a few missing runtime data values, too many to delete, so I found if I changed those missing values to the median, it didn’t effect the outcome and I wouldn’t lose data.


## Results

My above analysis leads me to 3 clear reccommendations I can confidenly provide that will produce the most profitable film

1. Choose one of these 3 genres are the best performers. Adventure is the leader closely followed by Action and Sci-Fi.

2. The ideal runtime for a film is between 90 - 150 minutes.

3. The months that generate the most revenue are June-July and November-December. These dates seem to aligm with 2 biggest school holidays of the year which could explain the increase in revenue.

***

Further anaylsis to compare profit margins with revenue could uncover more factors to determine successful films.   