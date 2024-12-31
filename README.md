# COVID-19 Detection Using Chest X-ray Images  

## Project Overview  
This project uses machine learning to classify chest X-ray images as either "Normal" or "COVID-19". It preprocesses images, extracts features, and trains two models: a Neural Network and a Random Forest classifier. Performance metrics like accuracy, precision, and recall are used to evaluate the models.

## Features  
- **Image Preprocessing:** Resizes and reshapes images to prepare for model training.  
- **Machine Learning Models:**  
  - Artificial Neural Network (ANN)  
  - Random Forest Classifier  
- **Metrics:** Calculates accuracy, precision, and recall for performance evaluation.  

## Technologies Used  
- Python  
- OpenCV (for image processing)  
- NumPy (for numerical operations)  
- Scikit-learn (for model training and evaluation)  

## Dataset  
The dataset used in this project is the **COVID-19 Radiography Dataset**, which contains labeled X-ray images.  
- **Classes:** Normal and COVID-19  
- **Dataset Link:** [https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database]  

## Setup Instructions  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Nawafosaimi/COVID-19-Detection-Using-Chest-X-ray-Images.git
   cd COVID-19-Detection-Using-Chest-X-ray-Images
   ```
2. Install the required libraries:
   ```bash
   pip install numpy opencv-python scikit-learn
   ```

3. Update the dataset path in main.py
4. Run the program:
   ```bash
   python main.py
   ```

## Project Structure
- main.py: Main script for data preprocessing, model training, and evaluation.
- COVID-19_Radiography_Dataset/: Folder containing X-ray images.

## Results

### Artificial Neural Network (ANN):
- Accuracy: 0.74%
- Precision: 0.54%
- Recall: 0.74%
### Random Forest Classifier (RF):
- Accuracy: 0.93%
- Precision: 0.93%
- Recall: 0.93%

## Contact

For inquiries, feel free to contact me via:
**Email: Nalosaimi22@gmail.com**
**GitHub: Nawafosaimi**
