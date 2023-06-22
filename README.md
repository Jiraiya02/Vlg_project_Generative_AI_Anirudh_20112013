# Vlg_project_Generative_AI_Anirudh_20112013
Vlg project on generative AI by anirudh 20112013

Generative AI binary  image classification project

the main objective of this project is the create a model which has the highest accuracy to predict whter a image is real or Ai generated

I used lenet similar  cnn model which is good for small input images like 20*20*3 and it gave a validation accuracy of 83 percnet and f1 score of 0.7,the accuracy was relatively low due to the input data already being pre-processed and not in the form of pixels

the next model used was a artificial neural network where I used 2 hidden layers of 50 and 60 neurons and a dropout rate of 0.7  and to reduce overfitting i also used early stopping and l2 regularization and with this I was able to get 86 percent validation acuracy and a f1 score of 78.9 on the bitgrit website

Then I used machine leaning models on the dataset like random forest and knn,I scaled and processed the data usning standard-scalar,from the ranodm forest model I was able to get a f1 score of 0.89 and with the knn i was able to get a f1 score of 0.91 and then by tuning the hyper-parameters and using feature selection I was able to get a f1 score 0.942


from all these models KNN model gave the highest acuuracy and f1 score of 0.942 on the bitgrit website


