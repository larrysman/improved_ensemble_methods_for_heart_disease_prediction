## `improved_ensemble_methods_for_heart_disease_prediction`
This is project aimed at predicting the heart diseases. It is a typical classification problems. The unique approach to this work is to develop an improved algorithms that behaves well to an external dataset. To achieve this objective, I leveraged on an improved multi-feature selection architecture where multiple algorithms are used to select the top performing features in the dataset and also developed a multi-agent ensemble techniques with voting techniques to develop a robust stochastic model for predicting if an individual suffers from heart diseases leveraging on the contributive effect of all performing algorithms.

#### Multi-Ensemble Techniques
![voting](https://github.com/user-attachments/assets/af5f510a-1630-44b3-9e5c-8bf2337ca426)
Leveraged on the improved performance of high performing algorithms. Multiple algorithms were trained on the dataset and evaluating each metrics to determine which of the algorithms is best in terms of performance metrics - `[accuracy, precision, recall, f1_score]`.
After a comprehensive hyperparameter tunning on all models, a voting classifier is used to vote the best algorithms and the architecture designed.

#### Metrics Evaluation for best model and voting classifier
![class_report](https://github.com/user-attachments/assets/b0c2f33a-cb10-4c01-9aab-9f49d819fec5)

![img](https://github.com/user-attachments/assets/60b446f3-4210-4e21-97fc-e9359aa23ef2)

Clearly, the model makes prediction and identify each labels correctly as measured by the performance metrics using the combine effects of multi-agent performing algorithms.
