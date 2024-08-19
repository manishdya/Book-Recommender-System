# Book-Recommender-system
Book Recommender system
This project aims to design and evaluate different approaches for computing recommendations within the book domain to provide personalised recommendations to the users.

SCOPE AND OBJECTIVES
An effective solution to the issue of information overload in e-commerce websites is the recommender system.
> This method offers users accurate recommendations.
> most reliable book-related suggestion technology.

OBJECTIVES
> Look into and assess the profiling and recommender systems that are already in use.
> By observing dynamic user behaviours, you can create a user's profile for a recommender system. The user profile needs to change to reflect the user's shifting interests.
> Create a recommender system that uses a variety of computation methods.
> Utilize the right methods to assess the system's recommendations accuracy.

DESCRIPTION OF PROPOSED SYSTEM
The application will be developed using the incremental development methodology and will be made up of four increments: Front End, Learning module, Recommendation module and Database increment. The requirements outlined in the Requirements Document will be mapped to manageable increments.

DATA SET
Books are identified by their respective ISBN. Invalid ISBNs have already been removed from the dataset. Moreover, some content-based information is given (Book-Title, Book-Author, Year-Of-Publication, Publisher), obtained from Amazon Web Services. Note that in case of several authors, only the first is provided.URLs linking to cover images are also given, appearing in three different flavours (ImageURL-S, Image-URL-M, Image-URL-L), i.e., small, medium, large. These URLs point to the Amazon web site.

Dataset description
we have 3 files in our dataset which is extracted from some books selling websites.
> Books – first are about books which contain all the information related to books like an author, title, publication year, etc.
> Users – The second file contains registered user’s information like user id,location.
> ratings – Ratings contain information like which user has given how much rating to which book.

RECOMMENDER SYSTEM
> Content based filtering approach
> Collaborative Filtering approach
> Hybrid Approach
> User - Based collaborative Filtering
> Item Based collaborative Filtering

CONCLUSION
All of our systems– purely content-based, purely collaborative-filtering, and hybrid– performed quite well. Looking back on the project, one thing that we might have chosen to do differently in retrospect would have been to spend more time searching for a dataset of ratings with a higher rating variance per user. Had we been able to find such a dataset, our implementations of algorithms would have been tested on data that would have been more representative of what a typical commercial recommendation system could access in creating its predictions. However, given the data that was available to us, as well as the results our various approaches produced, our systems were largely successful, providing insight into how the different systems we regularly use work and the varying algorithms that make that possible.

FUTURE WORK
Given more information regarding the books dataset, namely features like Genre, Description etc., we could implement a content-filtering based recommendation
system and compare the results with the existing collaborative-filtering based system.We would like to explore various clustering approaches for clustering the users based on Age, Location etc., and then implement voting algorithms to recommend items to the user depending on the cluster into which it belongs.
