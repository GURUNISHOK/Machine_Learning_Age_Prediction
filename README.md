# Machine_Learning_Age_Prediction
Machine Learning- Age Prediction from facial images:

The above python code helps in predicting the facial images of the facial images. The problem is solved by using the 
Principle component analysis(PCA) in order to perform the dimensional reduction of the acquired dataset. Once this is done the 
reduced dimension dataset uses the linear regression model in order to learn their age.
 I have seperated the problem into various step by step tasks for the easy understaning purposes. And also 
I have run the stochastic gradient descent multiple times in order to compute the average Root Mean Square Error and the standard 
deviation is being computed.

NOTE : PCA
Principal component analysis (PCA) simplifies the complexity in high-dimensional data while retaining trends and patterns. 
It does this by transforming the data into fewer dimensions, which act as summaries of features. High-dimensional data are 
very common in biology and arise when multiple features, such as expression of many genes, are measured for each sample. This 
type of data presents several challenges that PCA mitigates: computational expense and an increased error rate due to multiple
test correction when testing each feature for association with an outcome. PCA is an unsupervised learning method and is 
similar to clustering—it finds patterns without reference to prior knowledge about whether the samples come from different treatment
groups or have phenotypic differences. 

Stochastic gradient descent:
In Gradient Descent, there is a term called “batch” which denotes the total number of samples from a dataset that is used for 
calculating the gradient for each iteration. In typical Gradient Descent optimization, like Batch Gradient Descent, the batch 
is taken to be the whole dataset. Although, using the whole dataset is really useful for getting to the minima in a less noisy 
or less random manner, but the problem arises when our datasets get really huge.
Suppose, you have a million samples in your dataset, so if you use a typical Gradient Descent optimization technique, you will 
have to use all of the one million samples for completing one iteration while performing the Gradient Descent, and it has to be 
done for every iteration until the minima is reached. Hence, it becomes computationally very expensive to perform.

This problem is solved by Stochastic Gradient Descent. In SGD, it uses only a single sample, i.e., a batch size of
 one, to perform each iteration. The sample is randomly shuffled and selected for performing the iteration.



