# MultiModal_Classification( Auto + Text)

Problem_statement :

  In this project we address the MultiModal Sentiment Anlaysis (Classification) to Archive Maximum Accuracy On Different Trannsformer Architecture. To Architecture Accuracy 98 % for MultiModal Classification (better than Many models).

Method:
  Deep Learning :
    Model 1 : MultiModal fusion Transformer(MFT)
    Model 2 : Self-Modulating Fusion Former(SMFF)
    Model 3 : Dual-Modal Attention Fusion Network (DMAFNet)
    
Evaluation:
 classification Report :
 ```
   Model 1:
     Classification_Report : 
               precision    recall  f1-score   support

           0       0.96      0.98      0.97       314
           1       0.97      0.96      0.96       162
           2       0.97      0.93      0.95        84

    accuracy                           0.96       560
   macro avg       0.97      0.95      0.96       560
weighted avg       0.96      0.96      0.96       560
```
```
Model 2:
  Classification_Report : 
               precision    recall  f1-score   support

           0       0.98      0.99      0.99       317
           1       0.99      0.97      0.98       163
           2       1.00      1.00      1.00        80

    accuracy                           0.99       560
   macro avg       0.99      0.99      0.99       560
weighted avg       0.99      0.99      0.99       560
```
```
Model 3:
  Classification_Report : 
               precision    recall  f1-score   support

           0       0.98      0.99      0.99       317
           1       0.99      0.97      0.98       163
           2       1.00      1.00      1.00        80

    accuracy                           0.99       560
   macro avg       0.99      0.99      0.99       560
weighted avg       0.99      0.99      0.99       560

```


Conclusion :
  I got this performance from my dataset. working with other dataset maybe change so please tune based your requirements.
