# ✋ Hand Gesture Recognition using SVM 

This project is part of Task 04 of the SkillCraft Technology internship program. It includes two components:
- Image-based gesture classification using SVM, trained on the Sign Language Digits Dataset
 (digits 0–9).
- Real-time hand gesture recognition using OpenCV + MediaPipe, with rule-based logic to detect gestures like Fist, Peace, Thumbs Up, and OK based on hand landmarks.

The image classification pipeline includes preprocessing, training, and evaluation with confusion matrix and report. 

## 📌 Technologies Used

- Python  
- OpenCV  
- MediaPipe  
- Scikit-learn  
- NumPy  
- Matplotlib  
- Seaborn

## Installation

This project was developed using Google Colab. To run it:
1. Open the notebook in Google Colab
- Go to: https://github.com/Agent-A345/SCT_ML_04
- Open task4.ipynb
- Click “Open in Colab” (or open manually in Google Colab)
2. Run all cells in order

## 🧠 How It Works

1. Load the Sign Language Digits Dataset (0–9) from GitHub using git clone.
2. Convert images to grayscale, resize to 64×64, flatten them, and assign numeric labels.
3. Shuffle and split the dataset into training and testing sets (80:20).
4. Train an SVM classifier (rbf kernel, C=10) on the preprocessed image data.
5. Evaluate performance using accuracy, classification report, and confusion matrix.
6. Visualize test samples, predictions, and the confusion matrix using matplotlib and seaborn.

## 🙌 Acknowledgements

- The dataset used in this project is the **Sign Language Digits Dataset**, created and maintained by students at **Turkey Ankara Ayrancı Anadolu High School**.  
  Special thanks to **@ardamavi** for making this dataset publicly available under the Apache-2.0 License.  
  GitHub Repository: `https://github.com/ardamavi/Sign-Language-Digits-Dataset`

- Thanks to **SkillCraft Technology** for the opportunity to work on this internship project.

## License
This project is licensed under the MIT License.
