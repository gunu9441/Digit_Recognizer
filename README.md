# Digit_Recognizer

- Version_1  
  Performance: **0.99171**(402/1579)  
  Use CNN with **batchnorm**, **initilization**...
- Version_2  
  Performance: **0.99192**(390/1594)  
  **Preprocess the data** in range of `[-1,1]`
- Version_3  
  Performance: **0.99303**(310/1595)  
  Use **data augmentation** by using `albumentation`
- Version_4  
  Performance: **0.99428**(214/1592)  
  Use **10-fold cross validation** which has **100 epochs per one fold** by using `sklearn.model_selection.stratifiedKFold` to get more training datasets.  
  Performance: **0.99460**(189/1592)  
  Use Early stopped 10-fold cross validation model
