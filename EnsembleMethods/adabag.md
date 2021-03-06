Boosting and bagging are two widely used ensemble methods for classiﬁcation. Their
common goal is to improve the accuracy of a classiﬁer combining single classiﬁers which are
slightly better than random guessing. Among the family of boosting algorithms, AdaBoost
(adaptive boosting) is the best known, although it is suitable only for dichotomous tasks.
AdaBoost.M1 and SAMME (stagewise additive modeling using a multi-class exponential
loss function) are two easy and natural extensions to the general case of two or more
classes. In this paper, the adabag R package is introduced. This version implements
AdaBoost.M1, SAMME and bagging algorithms with classiﬁcation trees as base classiﬁers.
Once the ensembles have been trained, they can be used to predict the class of new
samples. The accuracy of these classiﬁers can be estimated in a separated data set or
through cross validation. Moreover, the evolution of the error as the ensemble grows
can be analysed and the ensemble can be pruned. In addition, the margin in the class
prediction and the probability of each class for the observations can be calculated. Finally,
several classic examples in classiﬁcation literature are shown to illustrate the use of this
package.
