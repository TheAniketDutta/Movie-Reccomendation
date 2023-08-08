## Movie-Reccomendation System using Cosine Similarity

Content based movie recommendation system using cosine similarity 

Here is the working video uploaded on [**Youtube**](https://youtu.be/nMZ4zkyvYfs).

[![Watch the video](https://img.youtube.com/vi/nMZ4zkyvYfs/maxresdefault.jpg)](https://www.youtube.com/embed/nMZ4zkyvYfs)

## Types of recommendation System

  
- **Popularity Based:** It keeps a track of view counts for each movie/video and then lists movies based on views in descending order.

- **Content Based:** This type of recommendation system, takes in a movie that a user currently likes as input. Then it analyzes the contents of the movie to find out other movies which have similar content. Then it ranks similar movies according to their similarity scores and recommends the most relevant movies to the user.

- **Collaborative filtering:** In this category, the recommendations get filtered based on the collaboration between similar user’s preferences.

![](https://i0.wp.com/thecleverprogrammer.com/wp-content/uploads/2020/11/1-recommendation.png?resize=1024%2C627&ssl=1)


## Table of Content
- [Introduction to Recommendation System](#introduction-to-recommendation-system)
- [Cosine Similarity](#cosine-similarity)

#### Introduction to Recommendation System
Recommendation systems are the systems that are designed to recommend things to user based on many different factors. These system predict things that users are more likely to purchase or interested in it. Giant companies Google, Amazon, Netflix use recommendation system to help their users to purchase products or movies for them. Recommendation system recommends you the items based on past activities this is known as __Content Based Filtering__ or the preference of the other user's that are to similar to you this is known as __Collaborative Based Filtering__ .

#### Cosine Similarity 
Cosine similarity is a metric used to measure how similar two items are. Mathematically it calculates the cosine of the angle between two vectors projected in a multidimensional space. Cosine similarity is advantageous when two similar documents are far apart by Euclidean distance(size of documents) chances are they may be oriented closed together. The smaller the angle, higher the cosine similarity.
```
1 - cosine-similarity = cosine-distance
```

![cosine-sim](https://github.com/garooda/Movie-Recommendation-Sysetm/blob/main/images/cosine%20sim%20%201.PNG)

![cos-form](https://bit.ly/33baNhZ)
