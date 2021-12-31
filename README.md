Introduction

Netflix is a popular media streaming platform that offers movies and tv shows for all people globally. In today's world, entertainment is vital to us all. It is even more so now with the avent of Covid-19 as we have to grapple with a few big questions with those being; how do we spend our free time and what show/movies should we watch in that time?
In this project, I am using clustering techniques to idenitfy movies and tv shows based on similar characteristics because this will help consumers to select the content that they want to watch while also not scanning and searching the listings for too much time. We can then use this information to emply the appropriate type of recommendation system that will best serve viewers interests.

Data

The data comes from Netflix. This dataset consists of movies and tvs shows with columns with details about cast, directors, ratings, country, release year, direction, etc Netflix has over 8000 movies or tv shows on their platform and as of mid-2021, they have over 200M Subsribers globally.
The columns of the data include things such as director, cast, title, year released, rating, show id, type, date added, epsiode, duration and country.
The data consists of over 8000 entries and 12 columns.

The Columns

Show_ID= Indictates the ID's of the differtent TV shows or Movies.

Type= Indicates whether the show is a TV show or Movie.

Title= Names of different TV Shows and Movies.

Director= Directors of respective TV Shows and Movies.

Cast= Actors Featured in respective TV shows and Movies.

Country= Country of Origin of Movie Make.

Date_added= The Date on which that particula Movie or TV Show was added.

Release_Year= The year in which repsective TV Show or Movie Released.

Rating= Based on the different Parental Guidelines.

Duration= the length of the TV show(measured in episodes) or Movie (in minutes).

Listed_In= Classification of TV show or movie based on genre.

Description= Summary of the TV show or movie.

Research Design

I wil be clustering the data using unsupervised machine learning techniques to answer this question:
How can you use clustering techniques to identify similar Netflix movies and shows based on content characteristics?

Audience

This resaerch will be valueable for entertainment companies trying to segement movies and tv shows by certain characteristics whether that be genre or by director or by country etc. Which in turn will make it easier to design recommendation systems to assist consumers when they are thinking about what they'd like to watch and therefore avoid the dreaded choice overload that comes with these streaming services.


Results:

Of the clustering techniques used the KMiniBatch performed the best.

Silhouette Scores
K-means: 0.4099982930726153
KMiniBatch: 0.41078985617189445
Agglomerative: 0.3661350374363302

How can you use clustering techniques to identify similar Netflix movies and shows based on content characteristics?

You can use the clustering techniques to help identify hidden patterns in the data that would give insghts into consumer habits and behavior while using the streaming service. With the clusters you can gain insight into things like what type of movie was selected by whom or looking at the time, data and location of the person that watched the content. This will allows us to gain a better understanding of consumer preferences and then allow us to build engines that help make the viewer experience better.

Discussion: How do clustering and modeling compare? What are the advantages of each? Why would you want to use one over the other?

Clustering allows us to separate the data points into a number of groups such that the data points in the same group are more similar to the other data points in the same group thna those of other groups. Which allows us to segement grpoups based on particular characteristics. For example, looking at this dataset we are able to segement the differnt data points into different groups based on their different features. As opposed to modeling used for supervised learning which uses already labeled data(inputs and outputs) to measure its accuracy and learn over time. With clustering you are able to discover hidden patterns using the clustered unlabeled data without human intervention.

Advantages of clustering:
Allows us to find hidden patterns.
We can separate groups with similar traits and assign them into clusters.
Does not require upfront human intervention.
Not as time consuming as using supervised learning models.

Advantages of modeling:
Is more accuarate than clustering.
Is a simple method for machine learning.
You'd want to use clustering for segementing customers based on purchasing habits, recommendation engines, and medical imagining.
You'd want to use modeling for things like spam detection, weather forecasting, and pricing prediction.
