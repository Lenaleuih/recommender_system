# Recommender Systems

* Recommender systems as a way to deal with the "paradox of choice", the dilemma of determining what information to feed back to learners about their learning. 
* An idealized recommender system provides a limited number of suggested metrics or new content based on the learner's past behavior and the patterns of all other learners in the sample.

*Recommender systems may provide behavioral cues, new content, insights or suggested behavioral changes based on a comparison of the learner to all other learners in the system.

## use cases & applications

* discuss different uses for recommender systems in learning applications
* discuss the theory behind item-based and user-based collaborative filtering methods and the role of cosine similarity 
* build a basic recommender system using an item-based collaborative filter and cosine similarity in R

## how does it work

*This project creats a recommender system for the couse HUDK4051. 
*In HUDK4051 there are six units, we will use students' ratings of these units in terms of both interest and difficulty to produce individual suggestions about what unit to attempt next.
* we can generate a user-based similarity matrix based on cosine similarity using the ratings the class gave each unit. 
* we then completed the collaborative filter
*At last we generate a suggestion for a student


### references

[Drachsler, H., Verbert, K., Santos, O. C., & Manouselis, N. (2015). Panorama of recommender systems to support learning. In *Recommender Systems Handbook* (pp. 421-451). Springer: New York, NY.](https://lirias.kuleuven.be/bitstream/123456789/476545/1/TEL_RecSys.pdf)

[Schafer, J. B., Frankowski, D., Herlocker, J., & Sen, S. (2007). Collaborative filtering recommender systems. In *The Adaptive Web* (pp. 291-324). Springer: Berlin, Heidelberg.](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.130.4520&rep=rep1&type=pdf)

### Videos

[Leskovec, J., Rajaraman, A. & Ullman, J. (2017). Recommender systems: Collaborative filtering. In *Mining of Massive Data Sets*. Coursera: Stanford, CA](https://www.youtube.com/watch?v=h9gpufJFF-0)

Brinton, C. & Chiang, M. (2013). Cosine similarity. In *Networks Illustrated: Principals without Calculus*  
[Part A](https://www.youtube.com/watch?v=C-JauEnlSlM)  
[Part B](https://www.youtube.com/watch?v=-gz1qdsM0tk)  
