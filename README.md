#  DEEP CNN IMAGE CLASSIFIER

A Deep Learning project built using **Convolutional Neural Networks (CNNs)** to classify images into emotional categories such as *happy*, *sad*, *angry*, etc. Designed and trained using **TensorFlow** and **Keras**, this project demonstrates practical image classification with real-world data.

---

## 📌 Project Highlights

- 🧠 Built a custom CNN model for multi-class emotion classification  
- 📈 Achieved high accuracy using data augmentation and fine-tuning  
- 📊 Trained on a balanced dataset of labeled images  
- 🛠️ Implemented with TensorFlow 2.x, Keras, and OpenCV  
- 📁 Organized with modular scripts for training, data loading, and evaluation  

---

## 🧪 Sample Results

| Input Image | Predicted Label |
|-------------|------------------|
| ![Happy](./data/happy/example1.jpg) | Happy |
| ![Sad](./data/sad/example2.jpg) | Sad |
| ![Angry](./data/angry/example3.jpg) | Angry |

> *(Replace image links with actual examples if possible)*

---

## 🗂️ Project Structure

ImageClassification_Project/
├── data/ # Organized image dataset (happy, sad, angry, etc.)
├── models/ # Saved model weights (.h5)
├── scripts/ # Custom training, evaluation scripts
├── main.ipynb # Jupyter notebook for quick prototyping
├── requirements.txt # Python dependencies
├── .gitignore
└── README.md


---

🚀 How to Run
1. Clone the Repository
git clone https://github.com/Vasper16/Deep_Vision_Image_Classifier.git
cd Deep_Vision_Image_Classifier

2. Create a Virtual Environment (Optional)
python -m venv venv

Activate it:
On Windows:
venv\Scripts\activate

On macOS/Linux:
source venv/bin/activate

3. Install Dependencies
pip install -r requirements.txt

4. Run the Training Script
python scripts/train.py

5. Evaluate the Model
python scripts/evaluate.py

🧰 Technologies Used
Python 3.x

TensorFlow & Keras

NumPy, OpenCV, Matplotlib

Jupyter Notebook

CNN (Convolutional Neural Networks)

📊 Accuracy
Training Accuracy: 95%
Validation Accuracy: 91%

Loss curves were visualized using TensorBoard and Matplotlib.
(Adjust values above based on your actual results)

📁 Dataset
Custom dataset of emotion-based facial expression images

Labeled categories like: happy, sad, angry, neutral

Collected from public sources and organized manually

Preprocessing included resizing, normalization, and data augmentation

⭐️ Show Your Support
If you found this project helpful or interesting:

⭐ Star the repository

📢 Share it with your peers

✅ Fork and extend it if you’d like to build on top of itI hope it's good.



