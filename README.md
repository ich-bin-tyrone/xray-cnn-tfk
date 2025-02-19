# 🩻 X-Ray Image Classification Web Application  

This web application allows users to upload X-ray images and classify them into one of the following categories:  

- **COVID-19**  
- **Pneumonia**  
- **Tuberculosis**  
- **Normal**  

## 🚀 Features  
✅ **User-friendly interface** for uploading X-ray images  
✅ **Automated classification** using a trained deep-learning model  
✅ **Quick and reliable results** for medical screening  

## 📦 Requirements  
Ensure you have the following installed:  

- Python **3.x**  
- Jupyter Notebook  
- Flask  
- TensorFlow  
- Other dependencies (will be installed automatically)  

## 🔧 How to Use the Web Application  

### **1️⃣ Download the Repository**  
Clone or download the repository to your local machine:  
```bash
git clone <repository_link>
cd <repository_directory>
```

### **2️⃣ Train the Model**  
Run `model.ipynb` using Jupyter Notebook or any IDE of your choice to train the model. This will create an `.h5` file (the trained model), which will be saved in your local **Desktop directory**.  

#### **Adjustable Training Parameters:**  
- `SIZE`: Number of training samples (**default = 2000**)  
- `batch_size`: Number of images per batch (**default = 8**)  
- `epochs`: Number of training iterations (**default = 100**)  

For a **quick test**, use:  
```python
SIZE = 256
batch_size = 8
epochs = 10
```

Run the notebook:  
```bash
jupyter notebook model.ipynb
```

### **3️⃣ Start the Web Application**  
After training is complete and the `.h5` model file is saved, run:  
```bash
python app.py
```

### **4️⃣ Access the Web App**  
Copy the local server address displayed in the terminal (e.g., `http://127.0.0.1:5000/`) and paste it into your browser. You can now upload X-ray images for classification.  

---

## 📂 Folder Structure  
```
├── app.py                  # Flask application  
├── model.ipynb             # Model training notebook  
├── static/                 # Static files (e.g., CSS, images)  
├── templates/              # HTML templates  
├── requirements.txt        # Dependencies  
└── README.md               # Project documentation  
```

---

## 💡 Contributing  
Feel free to contribute by submitting **issues** or **pull requests**! 😊  
