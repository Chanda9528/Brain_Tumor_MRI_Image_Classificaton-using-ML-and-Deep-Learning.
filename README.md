# Brain_Tumor_MRI_Image_Classificaton-using-ML-and-Deep-Learning.
This project detects brain tumors from MRI images using Python,Convolutional Neural Network(CNN),and machine learning concepts.It classifies images into categories on tumor presence,aiding early diagnosis.
The project includes:  
- **Data preprocessing** to prepare MRI images for model training  
- **CNN model training** for accurate tumor detection  
- **Evaluation** using metrics such as accuracy and confusion matrix  
- A **Streamlit web interface** for real-time predictions on uploaded MRI images  

## Technologies & Libraries Used
- **Python** – main programming language  
- **TensorFlow & Keras** – building and training CNN models  
- **OpenCV & PIL** – image preprocessing  
- **NumPy & Pandas** – dataset handling  
- **Matplotlib & Seaborn** – visualization of training and evaluation
-  **Sklearn** – performance metrics  
- **Streamlit** – web interface for live predictions  

## Project Structure
- **Dataset folders**:  
  - `train/` – training images categorized by tumor type  
  - `valid/` – validation images  
  - `test/` – testing images  
- **Scripts/Notebooks**:  
  - Data preprocessing and augmentation  
  - CNN model building and training  
  - Evaluation and confusion matrix visualization  
  - Streamlit app for live predictions  

## Key Features
- Preprocessing MRI images for better model performance  
- Training a CNN model to detect tumors accurately  
- Validation and test accuracy measurement  
- Confusion matrix for performance analysis  
- **Streamlit interface** for real-time image upload and prediction  

## Outcome
- Detects tumors with high accuracy on test images  
- Provides visual performance metrics like accuracy and confusion matrix  
- Allows users to test new MRI images via the **Streamlit app**  

## Future Enhancements
- Add more tumor types for **multiclass classification**  
- Implement **real-time detection** using webcam or live imaging software  
