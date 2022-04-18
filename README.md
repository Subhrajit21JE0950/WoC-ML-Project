<strong>ML Project IIT(ISM) DHANBAD

Report  :  

This is the report about my findings regarding the project:
</strong>
•	Linear Regression uses gradient descent method to continuously update parameters. The hyperparameters are learning rate and number of iterations. I have found that
increasing learning rate makes the cost function minimise rapidly but after a certain point it oscillates. Whereas lower learning rate makes the cost function minimise
very slowly. The correct combination is found by hit and trial method. I have also used standardization on the training data. The cost function is 2522.
<p align="center">
<img src= "https://user-images.githubusercontent.com/103888763/163831801-cf83323f-d233-43ba-a1a2-7884da5659f4.png" width="250" height="250" align="center" />
<br>Cost function VS Number of iterations
</p>


•	Polynomial Regression also uses gradient descent method to continuously update parameters. The hyperparameters are learning rate and number of iterations. The same happens to learning rate like linear regression. The correct combination is found by hit and trial method. By hit and trial I has been found that the polynomial is a
two degree polynomial for which the cost function is the least. I have also used standardization on the training data. The final cost function is 26.
<p align="center">
<img src= "https://user-images.githubusercontent.com/103888763/163833522-f634aea8-9c5f-4606-825b-6bd1159a9fea.png" width="250" height="250" align="center" />
<br>Cost function VS Number of iterations
</p>


•	In logistic regression , we have a found a way to tackle classification problems like the emnist dataset. The hypothesis is a sigmoid function and gives a probability of the hypothesis being true . Since it is a multiclass classification problem we have used one vs all strategy. The updation of parameters is same as gradient descent. The accuracy is 80 percent for 1000 entries(as it is taking very long time).


•	In K-nearest neighbours algorithm, we have found the Euclidean distance between the test data and all the train data and found the minimum number of neighbors of them. Then I calculated the mode of the label values of the neighbors and the one with the highest mode was my prediction. The accuracy is 84.8 percent for 1000 entries.(Takes very long time to run)


•	In K-means clustering algorithm, we have first made random centroids. Then we made clusters and added them to a dictionary on the basis of minimum Euclidean distance between train data and centroids. Then we continuously changed the centroids by making the mean of the clusters as the new centroids. Next we calculated the minimum Euclidean distance between test data and the final centroids . Then I calculated the mode of the labels of the data of the cluster and made them my prediction. The accuracy is 84.6 percent for 5000 entries(Long time to run).


•	In two layer neural network , first we did forward propagation or activation of the input and hidden layers. Then we calculated mean squared error. Then we implemented backward propagation which is a mathematical use of weights of one layer to calculate weights of previous layer. Since this is a multiclass problem I have used softmax activation function which is used to normalize them. The accuracy is 86 percent.

<strong>
By Subhrajit Mukherjee
Admission number- 21JE0950
Section -H
Ml group-7
</strong>

