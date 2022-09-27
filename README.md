# Credit_Risk_Analysis

## Overview of Analysis
The purpose of this analysis was to use different techniques to train and evaluate models with unbalanced classes in order to accurately determine the Credit Risk of loan applicants. 

## Results
Describe the balanced accuracy scores and the precision and recall scores of all six machine learning models (screenshots of your outputs to support results)
  #### Naive Random Over Sampling:
        Balanced Accuracy Score - 63.7%     
        Precision Score - 0.9%
        Recall Score - 62%
  ![Scores](/Resources/1_NaiveOS_Matrix_AccScore.png)
  ![Table](/Resources/1_NaiveOS_ClassificationReport.png)
  
  #### SMOTE Oversampling:        
        Balanced Accuracy Score - 63.0%
        Precision Score - 0.86%   
        Recall Score - 62% 
  ![Scores](/Resources/2_SMOTE_Matrix_AccScore.png)
  ![Table](/Resources/2_SMOTE_ClassificationReport.png)       
  
  #### UnderSampling:
        Balanced Accuracy Score - 51.6%
        Precision Score - 0.53%        
        Recall Score - 59.8% 
  ![Scores](/Resources/3_Undersampling_Matrix_Scores.png)
  ![Table](/Resources/3_Undersampling_ClReport.png)                  
  
  #### Combination Sampling:
        Balanced Accuracy Score - 65.3%
        Precision Score - 0.88%        
        Recall Score - 71.3%       
  ![Scores](/Resources/4_Combo_Matrix_Scores.png)
  ![Table](/Resources/4_Combo_Table.png)   
 
  #### Balanced Random Forest Classifier:
        Balanced Accuracy Score - 78.8%
        Precision Score - 3.5%        
        Recall Score - 66.7%           
  ![Scores](/Resources/5_BRFC_Scores.png)
  ![Table](/Resources/5_BRFC_Table.png)   
  
  #### Easy Ensemble AdaBoost Classifier:
        Balanced Accuracy Score - 92.5%
        Precision Score - 7.4%        
        Recall Score - 90.8%            
  ![Scores](/Resources/6_EEAC_Scores.png)
  ![Table](/Resources/6_EEAC_Table.png)           

## Summary
Summarize results & include recommendation on the model to use, if any. If none are recommended, justify reason. 
The Easy Ensemble AdaBoost Classifier is by far the best model to use. The accuracy score for this model was the highest, at 0.925 while the F1 score was also high at 0.97. 
