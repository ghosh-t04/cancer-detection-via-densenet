# cancer-detection-via-densenet - categorical classification

 Model Architecture
Backbone: DenseNet121

Classifier Head: Fully connected layers with softmax for categorical output

Dataset
Input: Medical images (e.g., histopathology, radiology, or dermatoscopic scans)

Output Labels: Multiple classes (e.g., melanoma, carcinoma, benign, etc.)

Images are resized, normalized, and augmented for training.

Requirements
Python ≥ 3.7

TensorFlow ≥ 2.x / Keras

OpenCV, NumPy, Pandas, scikit-learn

Matplotlib, Seaborn (for visualization)


Evaluation Metrics
Accuracy

Precision / Recall

F1 Score

Confusion Matrix

ROC-AUC (per class)

Results
Model achieves >85% accuracy on the validation set.

Training and validation curves show strong generalization.

Outputs
Trained model saved as .h5

Classification reports and visualizations


Future Work
Integration with real-time diagnostic tools

Expansion to more cancer types or modalities

Deployment via web or mobile interface
