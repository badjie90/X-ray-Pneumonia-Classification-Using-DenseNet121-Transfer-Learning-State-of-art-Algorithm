# X-ray-Pneumonia-Classification-Using-DenseNet121-Transfer-Learning-State-of-art-Algorithm

This reositoiry contains a notebook containing a deep neural network project for detecting and classifying pneumonia in human chest x-ray images. This project is built using DenseNet121 transfer learning model.

The primary objective of this project is to develop a powerful deep learning model, such as the DenseNet 121 transfer learning convolutional neural network model, that can accurately detect and classify pneumonia in X-ray images of the human chest. The dataset used for training, testing, and validation comprises 4,733, 539, and 624 images, respectively. It is worth noting that the dataset is imbalanced, which means that some classes have significantly fewer examples than others.

In medical diagnosis, it is crucial to choose appropriate metrics for model evaluation. In the case of imbalanced datasets, accuracy alone may not be the best performance metric, as it can give misleading results. Therefore, it is necessary to prioritize other measures such as precision, F1-score, recall, and the confusion matrix. While precision refers to the ratio of true positive observations to all positive observations, recall measures the proportion of actual positive cases that are correctly identified by the model. In this context, recall is especially important as it directly measures the success rate of the model in detecting pneumonia.

Furthermore, it is essential to examine the true positive rate and the true negative rate to gain deeper insights into the performance of the model. The true positive rate is the proportion of positive cases that are correctly identified by the model, while the true negative rate is the proportion of negative cases that are correctly identified. By analyzing these metrics, we can obtain a comprehensive understanding of the model's performance and identify areas for improvement.

To ensure the robustness of the trained model, it is necessary to evaluate it under different conditions. One way to test the model's resilience is to subject it to adversarial perturbations, outliers, or backdoor attacks. By doing so, we can determine whether the model's predictions are accurate and not influenced by external factors. Evaluating the robustness of the model is a critical step in ensuring that it is effective in real-world scenarios, where external factors may affect its performance. Therefore, it is crucial to consider this aspect of model evaluation in future work.

The dataset can be found here [Link](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
