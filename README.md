# Product-Based-Recommendation-Model-using-Collaborative-Filtering

In first part, we will implement an anomaly detection algorithm to detect anomalous behavior in server computers. We will use a Gaussian model to detect anomalous examples in our dataset. we will first start on a 2D dataset that will allow us to visualize what the algorithm is doing. On that dataset we will fit a Gaussian distribution and then find values that have very low probability and hence canbe considered anomalies


The function selectThreshold.m should return two values; the first is the selected threshold ε. If an example x has a low probability p(x) < ε,then it is considered to be an anomaly. The function should also return the F1 score, which tells us how well we’re doing on finding the ground truth anomalies given a certain threshold



In the second part, we will implement the collaborative filtering learning algorithm and apply it to a dataset of movie ratings.This dataset consists of ratings on a scale of 1 to 5. The dataset has nu = 943 users, and nm = 1682 movies. For this part of the exercise, we will be working with
the script ex8 cofi.m. In the last part, we will implement the function cofiCostFunc.m that computes the collaborative fitlering objective function and gradient. After implementing the cost function and gradient, we will use fmincg.m to learn the parameters for collaborative filtering.



![alt_text](https://github.com/SID2015/Product-Based-Recommendation-Model-using-Collaborative-Filtering/blob/master/img/Screenshot%20from%202020-08-18%2002-12-39.png)

![alt_text](https://github.com/SID2015/Product-Based-Recommendation-Model-using-Collaborative-Filtering/blob/master/img/Screenshot%20from%202020-08-18%2002-12-50.png)


![alt_text](https://github.com/SID2015/Product-Based-Recommendation-Model-using-Collaborative-Filtering/blob/master/img/Screenshot%20from%202020-08-18%2002-13-02.png)





The F 1 score is computed using precision (prec) and recall (rec):

                             F1 = 2(prec*rec)/(prec + rec),
                             
                             prec = tp/(tp + fp)
                             
                             rec = tp/ (tp + fn)
                             
                             


![alt_text](https://github.com/SID2015/Product-Based-Recommendation-Model-using-Collaborative-Filtering/blob/master/img/Screenshot%20from%202020-08-18%2002-13-09.png)


![alt_text](https://github.com/SID2015/Product-Based-Recommendation-Model-using-Collaborative-Filtering/blob/master/img/Screenshot%20from%202020-08-18%2002-13-15.png)


![alt_text](https://github.com/SID2015/Product-Based-Recommendation-Model-using-Collaborative-Filtering/blob/master/img/Screenshot%20from%202020-08-18%2002-14-01.png)


![alt_text](https://github.com/SID2015/Product-Based-Recommendation-Model-using-Collaborative-Filtering/blob/master/img/Screenshot%20from%202020-08-18%2002-14-12.png)


![alt_text](https://github.com/SID2015/Product-Based-Recommendation-Model-using-Collaborative-Filtering/blob/master/img/Screenshot%20from%202020-08-18%2002-14-17.png)


![alt_text](https://github.com/SID2015/Product-Based-Recommendation-Model-using-Collaborative-Filtering/blob/master/img/Screenshot%20from%202020-08-18%2002-14-35.png)




![alt_text](https://github.com/SID2015/Product-Based-Recommendation-Model-using-Collaborative-Filtering/blob/master/img/Screenshot%20from%202020-08-18%2002-14-46.png)



![alt_text](https://github.com/SID2015/Product-Based-Recommendation-Model-using-Collaborative-Filtering/blob/master/img/Screenshot%20from%202020-08-18%2002-14-53.png)


![alt_text](https://github.com/SID2015/Product-Based-Recommendation-Model-using-Collaborative-Filtering/blob/master/img/Screenshot%20from%202020-08-18%2002-15-06.png)



![alt_text](https://github.com/SID2015/Product-Based-Recommendation-Model-using-Collaborative-Filtering/blob/master/img/Screenshot%20from%202020-08-18%2002-15-23.png)


![alt_text](https://github.com/SID2015/Product-Based-Recommendation-Model-using-Collaborative-Filtering/blob/master/img/Screenshot%20from%202020-08-18%2002-15-34.png)


![alt_text](https://github.com/SID2015/Product-Based-Recommendation-Model-using-Collaborative-Filtering/blob/master/img/Screenshot%20from%202020-08-18%2002-15-38.png)



![alt_text](https://github.com/SID2015/Product-Based-Recommendation-Model-using-Collaborative-Filtering/blob/master/img/Screenshot%20from%202020-08-18%2002-16-00.png)




