1. Data Preprocessing
Implement CLAHE (Contrast Limited Adaptive Histogram Equalization) preprocessing on the MRI images to enhance metastasis visibility.
Ensure proper normalization and augmentation of the dataset, considering the specific challenges of metastasis segmentation.
2. Model Implementation
Implement the following two architectures for metastasis segmentation:
a. Nested U-Net (U-Net++)
b. Attention U-Net
3. Model Training and Evaluation
Train both models on the preprocessed metastasis dataset.
Use the DICE Score as the primary evaluation metric for metastasis segmentation accuracy.
Compare the performance of both models in identifying and segmenting brain metastases.
4. Web Application Development
Create a FAST API backend to serve your best performing metastasis segmentation model.
Develop a Streamlit UI that allows users to upload brain MRI images and view the metastasis segmentation results.
