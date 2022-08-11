## Supervised Learning
**In Short**, Supervised learning used the label data to train the model. Then Machine know the feature's of the object and labels associated with them. 

The computer is presented with example inputs and their desired outputs, given by a “teacher”, and the goal is to learn a general rule that maps inputs to outputs. The training process continues until the model achieves the desired level of accuracy on the training data. 

Some real-life examples are:

-   **Image Classification:** You train with images/labels. Then in the future you give a new image expecting that the computer will recognize the new object.
-   **Market Prediction/Regression:** You train the computer with historical market data and ask the computer to predict the new price in the future.

## Unsupervised Learning
-   **Unsupervised learning**: No labels are given to the learning algorithm, leaving it on its own to find structure in its input. It is used for clustering population in different groups. Unsupervised learning can be a goal in itself (discovering hidden patterns in data).
    -   **Clustering:** You ask the computer to separate similar data into clusters, this is essential in research and science.
    -   **High Dimension Visualization:** Use the computer to help us visualize high dimension data.
    -   **Generative Models:** After a model captures the probability distribution of your input data, it will be able to generate more data. This can be very useful to make your classifier more robust.

A simple diagram which clears the concept of supervised and unsupervised learning is shown below:  
![](https://media.geeksforgeeks.org/wp-content/uploads/supervised_learning-.png)![](https://media.geeksforgeeks.org/wp-content/uploads/unsupervised_learning-.png)  
  
As you can see clearly, the data in supervised learning is labelled, where as data in unsupervised learning is unlabelled.

## Semi-supervised learning
Problems where you have a large amount of input data and only some of the data is labeled, are called semi-supervised learning problems. These problems sit in between both supervised and unsupervised learning. For example, a photo archive where only some of the images are labeled, (e.g. dog, cat, person) and the majority are unlabeled.

## Reinforcement Learning
A computer program interacts with a dynamic environment in which it must perform a certain goal (such as driving a vehicle or playing a game against an opponent). The program is provided feedback in terms of rewards and punishments as it navigates its problem space.