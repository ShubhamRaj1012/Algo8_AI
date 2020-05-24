# Algo8_AI
Human Activity Detection using neural network

Since the datasets contain rows large than permitted by the .csv format the train and test sets are divided into 2 for each cases, so in the load dataset function you have to enter the 4 filenames.

The whole dataset consisting of both train and test sets are at this link:- https://drive.google.com/open?id=17IkIw8b0TeUQBpTAPjU-ek3EjuX4fO9S

The first model is a deep neural network , the second model is also a deep neural network but with mini batch gradient descent with adam for more advanced optimization purpose . 
Since the dataset was so huge that I was only able to train the model and test it in on few individual test set (not the whole test set which included all the rows stacked over one another) . There was not much time left for the accurate hyperparameter tuning (the values of alpha(the training rate), number of iterations, number of layers for the neural network , number of nodes in each layers and some of the other parameters as well). 
I was running the whole dataset of training which containg about 2 million row in google collab and due to the large size and not very good internet connectivity I was not able to train the model for larger number of times(not more than just 100 iterations as the google colab notebook kept on hanging for larger number of iterations).
But due to not so well parameter tuning and very less number of iterations(because of hanging of google collab on the internet I had) I was not able to test on the entire dataset for test that was given hence there is no image for accuracy of test set. 
I have tried to explain everything respectively by using good number of commments . You will not face any difficulty while seeing the code of the neural network. The only flaw I think that is left is the hyperparameter tuning .
You can find all the .csv file in the google drive link (for train and test data)
