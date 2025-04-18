🧬 Blood Group Classification using Fingerprint Images with Deep Learning
This project implements a Convolutional Neural Network (CNN) to classify blood groups using fingerprint images. It aims to provide a non-invasive, accurate, and scalable solution for biometric-based blood typing — useful in healthcare, emergency diagnostics, and forensic science.

📁 Project Structure
plaintext
Copy
Edit
/dataset/        # Preprocessed fingerprint images (by blood group)
/models/         # Trained CNN models
/notebooks/      # Jupyter Notebooks (EDA, model training, evaluation)
/reports/        # Evaluation metrics, plots, documentation
README.md        # Project overview and setup instructions
🚀 Project Objectives
✅ Classify blood groups using fingerprint images

✅ Implement image preprocessing and augmentation

✅ Train a CNN model with optimized performance

✅ Evaluate using metrics like accuracy, precision, recall

✅ Document and visualize project outcomes

🛠️ Tech Stack
🐍 Python 3.x

📚 TensorFlow / Keras

🧠 OpenCV

📊 scikit-learn

📈 matplotlib / seaborn

🧪 Jupyter Notebook

🧠 Model Architecture
📥 Input Layer: (150x150 RGB fingerprint image)

🧱 Conv2D Layers: 3 layers with ReLU activation

🧹 MaxPooling2D after each Conv layer

🔄 Flatten → Dense → Dropout

🎯 Output: Softmax classifier for multi-class blood group prediction

🧪 Evaluation Metrics
✅ Accuracy

📉 Loss Curves (Train & Validation)

🔍 Confusion Matrix

🎯 Precision, Recall, F1-score

⚙️ Setup Instructions
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/bloodgroup-classifier.git
Navigate to the project directory:

bash
Copy
Edit
cd bloodgroup-classifier
Install the required packages:

bash
Copy
Edit
pip install -r requirements.txt
Launch the project notebook:

bash
Copy
Edit
jupyter notebook notebooks/Projectfile1.ipynb
