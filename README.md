# SPINE-X-RAY-IMAGE-CLASSIFICATION
SPINE X-RAY IMAGE CLASSIFICATION

In this project I explored the classification of Spine X-ray images into 03 (Three) categories –
(1)	Normal; (2) Scoliosis; (3) Spondylolisthesis
Leveraging the power of Deep Leaning, I utilized pretrained models – Xception, InceptionV3 and DenseNet – enhance with an attention mechanism to improve classification Accuracy.

Project Highlights: -
1)	Data Preparation:
I worked with a dataset consisting of 338 Spine X-ray images, ensuring balanced class representation through oversampling techniques. The distribution was crucial for training robust models.
2)	Model Selection: -
Implemented and Fine-Tuned three state-of-the-art architectures:

2.1) Xception: Achieved an Accuracy of 95%, with precision and Recall values showcasing strong performance in different categories (Precision = 0.90; Recall = 1.00 for Normal; Precision = 0.83; Recall = 1.00 for Spondylolisthesis).
2.2) InceptionV3: Delivered outstanding results with a perfect Accuracy of 100%, demonstrating flawless classification across all categories
2.3) DenseNet: Reached an overall Accuracy of 88%, highlights potential areas for improvement, especially in distinguishing between certain conditions (Precision = 1.00; Recall = 0.89 for Normal; Precision = 0.59; Recall = 0.42 for Spondylolisthesis).
3)	Attention Mechanism: -
Integrated an attention layer to enhance the models’ focus on important features in the images, resulting in better interpretability and performance.
4)	Training & Evaluation: -
Employed techniques like early stopping to prevent overfitting and used validation data to ensure the models generalized well. Achieved promising Accuracy rates, demonstrating the effectiveness of combining pretrained networks with attention mechanisms.
5)	Visual Insights: -
Generated visualizations to understand model predictions and to showcase the distribution of image clasess.

Conclusion: -
This project not only solidified my understanding of image classification using Deep Learning but also emphasized the importance of attention mechanisms in enhancing model performance. I am looking forward to applying these insights in real-world medical applications.
