# v3.1.1 (reference model)
___________________________________________________
- pretrained_model = "microsoft/deberta-v3-base"
- When to stop the training? 
  - train with all epoch and replace original model if Pearson correlation is better
- What is the original ensemble method? 
  - use 4 cross validation model to predict 4 score then average 4 score
- cv score in kaggle: <mark>0.8101</mark>