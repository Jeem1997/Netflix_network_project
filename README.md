# Netflix_network_project
This file has the code I used to solve the problems listed here:
1. Draw a histogram of movie duration in the database and identify any particular trend.
(should use any curve fitting to justify the trend). You may inspire from the related
programs available in Kaggle for this particular dataset.
2. We want to test the hypothesis whether the duration of the movie is linked to the rating of
the movie. Write a script that calculates Person correlation and p-value between the movie
ranking and its duration (movie ranking should be in full numerical scale prior to this
operation).
3. We want to construct a social network between the various movies. First use a simple
labelling of the movies to ease graphical illustration. Write a script that constructs a social
network of the movies in the following way. First, for each actor full name (pay attention
that the name is composed word of two or more terms) in the cast category, identify the list
of movies that this actor played in. You may represent each actor in cast as an index file,
pointing towards the movie ID he played with (You may introduce a simple IDs for movies
to avoid lengthy movie title). Second, consider the network constituted of movie IDs as
nodes, and where an edge between two nodes is established if there if there is at least one
actor who played in both movies. Third, assume the above network is weighted graph where
the weight is evaluated by the number of actors that played in both movies. Fourth, use
appropriate visualization tools to provide a dense graphical representation of this network.
You may show the IDs of some interesting nodes of the network.
4. Write a program that outputs some statistical properties of the generated network, which
include: number of singletons, size of largest component, number of components and their
sizes, diameter of the network, average path length, average clustering coefficient. Provide
the result in a table.
5. Use NetworkX to determine the k-cliques communities and Louvain communities. Use also
NetworkX to evaluate the quality of these communities using function performance.
6. Now we want to test the partition using the rating mechanism. For this purpose, write a
script that calculates the rating of each community in terms of average rating of the movies
forming the community and its standard deviation. The smaller the standard deviation value,
the better the fitting of the community with the rating criterion.
7. Now we want to test the partition using the movie textual description attribute. Write a
script that calculates the number of overlapping words among textual description of each
movie in the community, the higher this number, the better the fitting of the community
with this metric.
8. We want to approximate the underlined network by a random graph G(n,p). Determine the
probability value p of this random graph that best approximates the number of singletons,
diameter and average path length of the original network.
9. Use approximate literature from movie, leisure literature to comment on the findings and
results of each specification.


---------------------------------------------------------
REMINDER
---------------------------------------------------------
If you plan to use this code you need to import the data set into google colab for every runtime if you don't want to keep it there through google drive.
