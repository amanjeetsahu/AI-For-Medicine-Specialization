# AI-For-Medicine-Specialization

AI is transforming the practice of medicine. It’s helping doctors diagnose patients more accurately, make predictions about patients’ future health, and recommend better treatments. In this Specialization, you’ll gain practical experience applying machine learning to concrete problems in medicine. You’ll learn how to:

- Diagnose diseases from x-rays and 3D MRI brain images
- Predict patient survival rates more accurately using tree-based models
- Estimate treatment effects on patients using data from randomized trials
- Automate the task of labeling medical datasets using natural language processing

---

## Course 1: AI For Medical Diagnosis

How can AI be applied to medical imaging to diagnose diseases? In this first course, you’ll learn about the nuances of working with both 2D and 3D medical image data, for multi-class classification and image segmentation. You’ll then apply what you’ve learned to classify diseases in x-ray images and segment tumors in 3D MRI brain images. Finally, you’ll learn how to properly evaluate the performance of your models.

### Week 1:
- Introduction: A conversation with Andrew Ng
- Diagnosis examples
- Model training on chest x-rays
- Training, prediction, and loss
- Class imbalance
- Binary cross entropy loss function
- Resampling methods
- Multi-task loss
- Transfer learning and data augmentation
- Model testing

### Week 2:
- Introduction: A conversation with Andrew Ng
- Evaluation metrics
- Accuracy in terms of conditional probability
- Sensitivity, specificity, and prevalence
- Confusion matrix
- ROC curve
- Threshold (operating point)
- Confidence intervals
- Width of confidence intervals and sample size
- Using a sample to estimate the population 

### Week 3:
- Introduction: A conversation with Andrew Ng
- Representing MRI data
- Image registration
- 2D and 3D segmentation
- 3D U-Net
- Data augmentation for segmentation
- Loss function for image segmentation
- Soft dice loss
- External validation
- Retrospective vs. prospective data
- Working with cleaned vs. raw data
- Measuring patient outcomes
- Algorithmic bias
- Model influence on medical decision-making

---

## Course 2: AI For Medical Prognosis

Machine learning is a powerful tool for prognosis, a branch of medicine that specializes in predicting the future health of patients. First, you’ll walk through multiple examples of prognostic tasks. You’ll then use decision trees to model non-linear relationships, which are commonly observed in medical data, and apply them to predicting mortality rates more accurately. Finally, you’ll learn how to handle missing data, a key real-world challenge.

### Week 1:
- Introduction: A conversation with Andrew Ng
- Examples of prognostic tasks
- Patient profile to risk score
- Risk score for atrial fibrillation
- Liver disease mortality
- Calculate 10-year risk of heart disease
- Risk score computation
- Evaluating prognostic models
- Concordant pairs
- Risk ties
- Permissible pairs
- C-index interpretation

### Week 2:
- Decision trees for prognosis
- Predicting mortality risk
- Dividing the input space
- Non-linear associations
- Class boundaries of a decision tree
- Random forest
- Ensemble methods
- Survival data
- Problems with dropping incomplete rows
- Dropping incomplete case changes the distribution
- Imputation
- Mean imputation
- Regression imputation

### Week 3:
- Survival function
- Censoring
- Collecting time data
- Heart attack data
- Estimating the survival function
- Using censored data
- Chain rule of conditional probability
- Derivation
- Calculating probabilities from the data
- Comparing estimates
- Kaplan Meier Estimate
 
### Week 4:
- Hazard functions
- Survival to hazard
- Cumulative hazard
- Individualized predictions
- Individual vs. baseline hazard
- Smoker vs. non-smoker
- Effect of age on hazard
- Factor risk increase or decrease
- Survival trees
- Nelson Aelen estimator
- Mortality score
- Evaluating survival models
- Permissible pair examples
- Harrell’s concordance index

---

## Course 3: AI For Medical Treatment

Medical treatment may impact patients differently based on their existing health conditions. In this final course, you’ll estimate treatment effects using data from randomized control trials and applying tree-based models. In the second week, you’ll apply machine learning interpretation methods to explain the decision-making of complex machine learning models. In the final week of this course, you’ll use natural language entity extraction and question-answering methods to automate the task of labeling medical datasets.

### Week 1:
- Treatment effect estimation
- Randomized control trials
- Average risk reductio
- Individualized treatment effect
- T-Learner and S-Learner
- C-for-benefit

### Week 2:
- Information extraction from medical reports
- Rules-based label extraction
- Text matching
- Negation detection
- Dependency parsing
- Question-Answering with BERT
 
### Week 3:
- Machine Learning Interpretation
- Interpret CNN models with GradCAM
- Aggregate and Individual feature importance
- Permutation Importance
- Shapley Values
- Interpret random forest models

---
