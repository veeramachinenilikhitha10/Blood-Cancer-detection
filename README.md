🩸 **Blood Cancer Detection using Deep Learning**
📌 **Project Overview**

This project focuses on detecting blood cancer from microscopic blood cell images using deep learning techniques. The system leverages pretrained models such as EfficientNet-B3, DenseNet-201, and Vision Transformer (ViT) to classify images as cancerous or healthy. The goal is to assist in early diagnosis by providing accurate and automated predictions.

🚀**Features**
Image-based blood cancer detection
Multiple deep learning models for comparison
Image preprocessing and augmentation
Model training and evaluation pipeline
Performance metrics (Accuracy, Precision, Recall, F1-score, ROC-AUC)
Confusion matrix and visualization graphs
Single image prediction support
Model saving and loading functionality
**🧠 Models Used**
EfficientNet-B3
DenseNet-201
Vision Transformer (ViT-Base Patch16-224)
**🛠️ Tech Stack**
Python 3.x
PyTorch
Torchvision
Transformers (Hugging Face)
Scikit-learn
Matplotlib
NumPy
**📂 Project Structure**
Blood_Cancer_Detection/
│── train/
│   ├── cancer/
│   ├── healthy/
│
│── val/
│   ├── cancer/
│   ├── healthy/
│
│── test_images/
│
│── models/
│   ├── efficientnet.pth
│   ├── densenet.pth
│   ├── vit.pth
│
│── results/
│
│── main.py / notebook.ipynb
│── README.md
**⚙️ Installation**
Clone the repository:
git clone https://github.com/your-username/blood-cancer-detection.git
cd blood-cancer-detection
Install dependencies:
pip install -r requirements.txt
**▶️ Usage**
Train the model
python main.py
Predict on a single image
python predict.py --image path_to_image
**📊 Evaluation Metrics**

The model performance is evaluated using:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
ROC-AUC Curve
**💡 Results**

The models demonstrated strong performance in classifying blood cell images. Among the tested models, deep learning architectures showed high accuracy and reliable predictions, making them suitable for medical image classification tasks.

**🔮 Future Scope**
Use larger and more diverse datasets
Multi-class classification for different cancer types
Deploy as a web or desktop application
Integrate explainable AI techniques
