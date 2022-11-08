# Neural_Network_Charity_Analysis

## Overview
The purpose of this analysis is to help create a binary classifier that is capable of predicting whether organizations will be successful if funded by Alphabet Soup.


## Results
- What variable(s) are considered the target(s) for your model?

    IS_SUCCESSFUL was the target variable for our analysis
    
-	What variable(s) are considered to be the features for your model?

	  All the other available variables were considered features
    
- What variable(s) are neither targets nor features, and should be removed from the input data?

    EIN and NAME were the only two features that are neither
    
-	How many neurons, layers, and activation functions did you select for your neural network model, and why?

    For this model I used all the available features & two hidden layers. The first hidden layer has 80 neurons, the second has 30. The first and second hidden layers are using the activation function "relu" & the output layer is "sigmoid". I kept the amount of neurons the same as I didn’t see any improvement from adding more. Out of  all the activations I tried, “relu” produced the most accurate results. I also increased the number of epochs to 30. All of my decisions were based on trial and error to get the best accuracy.
    

![image](https://user-images.githubusercontent.com/108442512/200684245-3873abb1-22a9-481a-b5a8-fd07676c0cab.png)

![image](https://user-images.githubusercontent.com/108442512/200684551-8976eb50-753c-4e05-b4ae-e457963cc5a8.png)



-	Were you able to achieve the target model performance?

  	I was able to get to approx. 71% on my best try.
    
    
![image](https://user-images.githubusercontent.com/108442512/200684440-58e23579-6336-4620-b85e-5f0c13cb9d30.png)


-	What steps did you take to try and increase model performance?

    I changed the activation types several times, tried removing “STATUS” from the features, increased the number of epochs, added additional hidden layers, and             increased the number of neurons. After all the adjustments up and down I settled on my current model.
    

## Summary
I was able to get approx. 4% away from the targeted accuracy goal of 75%. Even though I wasn't able to match the goal I was able to significantly improve the accuracy from approx 50% to 71%. I believe the goal can be reached by removing unneccessary input features. Some features may be skewing the data in ways that aren't relevant to the results we are looking for. 

