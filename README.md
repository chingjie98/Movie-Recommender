# Movie-Recommender
Build a machine learning algorithm to recommend movie to new and existing users.<br><br>
The main technique used will be collaborative filtering assuming there are already existing users in the database.
How this works is that users with similar interests as each other, will recommend movie that they rate highly where the other party has not watched the movie. 

The algorithm used for this technique would be <strong>Euclidean distance</strong> which is basically sq root of the summation of differences in ratings of common movie squared.

![Capture3](https://github.com/chingjie98/Movie-Recommender/assets/35895182/4ff18a2b-5f10-4cc7-b60e-9178cefb6b08)


For example, even just at a glance, <strong>Jessica</strong> and <strong>Stuart</strong> have very similar tastes as observed in the 3 common movies they have both watched:
<strong>'The Lord of the Ring'</strong>, <strong>'The Terminator'</strong> and <strong>'Star Wars'</strong>. 

![Capture4](https://github.com/chingjie98/Movie-Recommender/assets/35895182/23e12940-2943-4f4d-97ef-b71bf3157731)

Their euclidean distance can be computed as 
![Capture5](https://github.com/chingjie98/Movie-Recommender/assets/35895182/16aed434-9d33-4387-93b3-f8f9afe113c7)
