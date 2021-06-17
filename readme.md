Machine learning project. Made by Priyansh.

This project deals with Hand Gesture Recognition from the wide field of Human Machine Interaction.
In this project I am doing hand gesture digits classification.
The dataset used is the Sign Language Digits Dataset. The link for the same is https://www.kaggle.com/ardamavi/sign-language-digits-dataset.

In this I am simply using a Multilayer Perceptron for the classification with 4 hidden layers and the activation function for the same being relu and for the output layer I have used the activation function softmax and the optimiser being adam i.e basically a better version of gradient descent. I have used keras for mlp.

The testing accuracy that we get from this is 82%.

We can easily see that this accuracy can be drastically increased by using a CNN as we all know its dominance in recognising patterns.

This code also allows user to caputre a live gesture from webcam and classify the same. I have used openCV library for the same.


