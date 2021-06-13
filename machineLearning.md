MACHINE LEARNING-

A good start at a Machine Learning definition is that it is a core sub-area of Artificial Intelligence (AI). ML applications learn from experience (well data) like humans without direct programming. When exposed to new data, these applications learn, grow, change, and develop by themselves. In other words, with Machine Learning, computers find insightful information without being told where to look. Instead, they do this by leveraging algorithms that learn from data in an iterative process.

At a high-level, machine learning is simply the study of teaching a computer program or algorithm how to progressively improve upon a set task that it is given.


Types of Machine Learning-
There are so many different types of Machine Learning systems that it is useful to
classify them in broad categories based on:

• Whether or not they are trained with human supervision (supervised, unsuper‐
vised, semisupervised, and Reinforcement Learning)

• Whether or not they can learn incrementally on the fly (online versus batch
learning)

• Whether they work by simply comparing new data points to known data points,
or instead detect patterns in the training data and build a predictive model, much
like scientists do (instance-based versus model-based learning)


1 Supervised learning-
In supervised learning, the training data you feed to the algorithm includes the desired solutions, called labels.

Here are some of the most important supervised learning algorithms-
• k-Nearest Neighbors
• Linear Regression
• Logistic Regression
• Support Vector Machines (SVMs)
• Decision Trees and Random Forests
• Neural networks


2 Unsupervised learning
In unsupervised learning, as you might guess, the training data is unlabeled.The system tries to learn without a teacher.

Here are some of the most important unsupervised learning algorithms-
• Clustering
— K-Means
— DBSCAN
— Hierarchical Cluster Analysis (HCA)

• Anomaly detection and novelty detection
— One-class SVM
— Isolation Fores

• Visualization and dimensionality reduction
— Principal Component Analysis (PCA)
— Kernel PCA
— Locally-Linear Embedding (LLE)
— t-distributed Stochastic Neighbor Embedding (t-SNE)

• Association rule learning
— Apriori
— Eclat

3 Semisupervised learning-
Some algorithms can deal with partially labeled training data, usually a lot of unla‐
beled data and a little bit of labeled data. This is called semisupervised learning.

4 Reinforcement Learning-
Reinforcement Learning is a very different beast. The learning system, called an agent
in this context, can observe the environment, select and perform actions, and get
rewards in return (or penalties in the form of negative rewards, as in Figure 1-12). It must then learn by itself what is the best strategy, called a policy, to get the most reward over time. A policy defines what action the agent should choose when it is in a given situation.

for ex-
many robots implement Reinforcement Learning algorithms to learn
how to walk. DeepMind’s AlphaGo program is also a good example of Reinforcement
Learning: it made the headlines in May 2017 when it beat the world champion Ke Jie
at the game of Go. It learned its winning policy by analyzing millions of games, and
then playing many games against itself. Note that learning was turned off during the
games against the champion; AlphaGo was just applying the policy it had learned.



Training Testing and Validating-

Training set (60% of the original data set): This is used to build up our prediction algorithm. Our algorithm tries to tune itself to the quirks of the training data sets. In this phase we usually create multiple algorithms in order to compare their performances during the Cross-Validation Phase.

Cross-Validation set (20% of the original data set): This data set is used to compare the performances of the prediction algorithms that were created based on the training set. We choose the algorithm that has the best performance.

Test set (20% of the original data set): Now we have chosen our preferred prediction algorithm but we don't know yet how it's going to perform on completely unseen real-world data. So, we apply our chosen prediction algorithm on our test set in order to see how it's going to perform so we can have an idea about our algorithm's performance on unseen data.

