# Music-Genre-Classifier


Methodology :

(Standard Data) --> (Data Pre-processing) --> (Training,testing and saving five models) --> (Taking the location of the song as an input,extracting it's features using librosa library and predicting it's genre using all five models) --> (predicting the output from all 5 models and voting among all of them) --> (Computing the final results and showing it on the console).

Description :

Music genre classifier is a machine learning and deep learning based music genre classification system.
Here is how it is made:
We trained three deep learning models and two machine learning models on the GTZAN dataset which is a dataset for different music geners. We applied three neural networks and two machine learning models which are Light Gradient boosting machine and Extra Tree Classifier. Then all the models vote to get the finbal fresult. Now, when we have a new song to classify then, we use librosa libraray to extract its features and give them to the model to give us the final result i.e. the genre of that music.
Models :
Three deep learning models.
Two machine learning models : Extra Tree classifier, Light Gradient Boosting Machine.
Final Accuracy : 94.29 %


Input/Output :

Input : Song

Output : Genre ('blues', 'classical', 'country', 'disco', 'hiphop', 'jazz','metal', 'pop', 'reggae', 'rock')

For ex :

Input : Badfella by Sidhu Moosewala

Output : HipHop






