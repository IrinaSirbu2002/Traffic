# Traffic

For the first attempt of creating the model, I took the metrics and parameters from the model described in the course which gave me an accuracy of 0.9719 and I understood that there is room for improvment.

## Changing pooling method
I decided to add two layers of convolution + pooling. After adding the second layer, the accuracy raised to 0.9849. After that, I wanted to try a different kind of pooling, the average pooling. This method had an accuracy of 0.9643, understanding that for this kind of problem the max pooling is more otimal.

## Changing hidden layers
Firstly, I wanted to try to change the activation function from "relu" to "sigmoid" and that changed the accuracy from 0.9849 to 0.9803, the "relu" being more affective in this problem. Secondly, I added another hidden layer with a dropout also of 0.5 and that also lowered the accuracy to 0.9735. Then, I tried to change the number of neurons in the second layer to be 200 and that also lowered the accuracy.

## Conclusion
In conclusion the best berformance that I found was with two steps of convolution and pooling and one hidden layer with an accuracy of 0.9849.
