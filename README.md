# Empirical Study of Convolutional Neural Network Architectures
## Abstract
Convolutional neural networks is a class of deep
neural networks that is commonly applied to analyze visual
data. I will be studying the performance of different
architectures of convolutional neural networks (CNNs) to
gauge what tweaks and tuning brings about the best result for
our models. I will be constructing a custom designed CNN to
compare to the Alexnet and GoogLeNet architectures. All models will be trained on the CIFAR-10 dataset.

## Results
![Accuracies](/Accuracies.png)

This table shows the accuracies achieved by the different architectures. AlexNet performed the best with an accuracy of 85% over 10,000 images. 
Further breakdown of class by class accuracies can be found within the report. 

## Conclusion
In conclusion, the modifications made to the
architecture of a network play a significant role in
how well the network will perform. The type of
optimizer used, in this case between SGD and
Adam, made the biggest difference in terms of
performance. However, this performance boost was
dependent on which network the optimizer was
used on. On the advanced CNN, the SGD optimizer
worked best, while on AlexNet and GoogLeNet, the
Adam optimizer improved them significantly. The
second biggest factor was the type of activation
function used. Overall, ReLU performed best, with
tanh closely behind. Sigmoid, however, produced
abysmal results compared to the other two. Lastly,
the pooling layer did cause slight shifts in
performance, but nothing noteworthy in this
experiment. Overall, testing different settings and
modifications in creating an architecture is
immensely important and should not be overlooked.



