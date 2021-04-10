# Handwritten-Digit-Classification :
In this project we will classify that the handwritten digit is really a digit or not with the help of MNIST dataset.
after training and testing the classifier we checks accuracy .
after getting mean of accuracy we will create confusion metrix to evaluate the classifier
then check the precision and recall 
and then f1 score
# Why confusion metrics :
 because we are not assure that the accuracy predicted by classifier is 100% accurate so we created the confusion matrix to check how effective the accuracy of classifier.
 # Precision :
 It denotes that what percent of positive predictions made were correct with the help of confusion metrix.
 # Recall :
  It denotes the percentage of actual positive values classified by the classifier.
  # f1 score : 
   It is harmonic mean of precision and recall . It is convinient to combine the preformance of classifier (precision,recall) into a single matrix call f1 score.
# MNIST Dataset : 
 We have used mnist dataset for training and testing 
 It has 70000 handwritten digit images and 784 features
  # Steps :
  1. Importing Libraries
  2. Importing Datasets
  3. converting the imgage data in 28x28 resolution for visualisation
  4. Separating training and testing data
  5. Shuffling : Maybe each values are not equally divided so we do shuffle
  6. Creating digit detector 
  7. Creating classifier 
  8. Cross validation
  9. Mean : To check accuracy
  10. Creating Confusion matrix : We create confusion matrix to determine the precision recall and f1 score.
  11. Calculating Precision
  12. Calclating recall
  13. Calculating f1 score
  14. Plotting Precison Recall curve .
  
    
