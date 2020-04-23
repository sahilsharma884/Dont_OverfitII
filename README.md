# Dont_OverfitII
<ul>
  <li>
    <h3>Kaggle problem:</h3> 
    <strong>Don’t Overfit! II</strong> is a challenging problem where we must avoid models to be overfitted (or crooked way to learn) given very small amount of training samples. 
    
   As per Kaggle say,
    <i>"It was a competition that challenged mere mortals to model a 20,000x200 matrix of continuous variables using only 250 training samples… without overfitting."</i>
    
<strong>Dataset</strong> can be download here: https://www.kaggle.com/c/dont-overfit-ii/overview 

Dimension of train.csv – 250 samples and 300 features and 1 class label and 1 Id: (250,302)

Dimension of test.csv – 19750 samples and 300 features and 1 Id: (19750,301)

So, with the small amount of train data given, we must do to task carefully to avoid overfitting easily.
What do we need to predict? We are predicting the binary target value (binary classification) associated with each row which contains 300 continuous feature values. Also without overfitting with the minimal set of training samples given.</li>
<li><h3>Evaluation:</h3>
  As per Kaggle problem statement, the score will be evaluated based on <strong>AUROC</strong> between predicted target and actual target.
  </li>
  </ul>
