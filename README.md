# Diabetes-Detection

Simple model involving Neural Network
I have just experimented with different types of neural networks to check where overfitting can occur. 
First, I tried out the model with 2 hidden layer with 20 neurons each. Then moved on to deeper ones with more hidden layers and greater number of neurons.
There was an immediate increase in the noise in accuracy. 

## Model 1

![](/assets/model1.PNG)

## Model 2 

![](/assets/model2.PNG)

## Model 3

![](/assets/model3.PNG)

<hr>

Turns out, model 1 is the best one to predict diabetes using the given data. 
Now, trying to increase the number of epochs to 5000 gives:

![](/assets/model1-2.PNG)

<hr>

So 500 epochs shall suffice

Model 2 was also showing less noise on a smaller number of epochs. 

<hr>
  
Training the model with 160 epochs gave:

![](/assets/model2-2.PNG)

# Conclusion 

Model 1 has highest accuracy: 78.57%

Model 2 also gives good accuracy in lesser epochs: 76.62%
