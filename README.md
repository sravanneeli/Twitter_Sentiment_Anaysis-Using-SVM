# Twitter_Sentiment_Anaysis-Using-SVM
Based on US airlines based twitter data we classify the given tweet as positive or negative

Here we are going to use Soft margin based classfier based SVM(support vector machine) from scratch.

Loss function
We'll use the Hinge loss. This is a loss function used for training classifiers. The hinge loss is used for "maximum-margin" classification, most notably for support vector machines (SVMs).

                         Total cost = ||w²||/2 + C*(Sum of all losses for each observation)
                         
here the first term is regularizer term itself and second term is like penality term or the loss term.

Now this whole function become unconstrained optimization,so now we can use the basic gradient descent algorithm for the optimization.

SVM uses “hinge” loss an approximation to the 0-1 loss ymax (0, 1 − yif(xi))

