# 🩻 X-Ray Image Classification Web Application

This web application allows users to upload X-ray images and classify them into one of the following categories:

- **COVID-19**  
- **Pneumonia**  
- **Tuberculosis**  
- **Normal**

## Features
- User-friendly interface for uploading X-ray images
- Automated classification using a trained deep-learning model
- Quick and reliable results for medical screening

## Requirements
- Python 3.x
- Jupyter Notebook
- Flask
- TensorFlow
- Other dependencies will be automatically installed 

## How to Use the Web Application

1. **Download the Repository**  
   Clone or download the entire repository to your local machine.

   ```bash
   git clone <repository_link>
   cd <repository_directory>
   ```

2. **Run the Model Notebook**  
   Open and run `model.ipynb` using Jupyter Notebook or any IDE of your choice. This will train the model and create an `.h5` file (the trained model) that will be saved in your local Desktop directory.

   ```bash
   jupyter notebook model.ipynb
   ```

3. **Run the Web Application**  
   After the `.h5` file is created:

   ```bash
   python app.py
   ```

4. **Access the Web App**  
   Copy the local server address displayed in the terminal (e.g., `http://127.0.0.1:5000/`) and paste it into your browser. The web application will load, and you can start uploading X-ray images for classification.

## Folder Structure
```
├── app.py
├── model.ipynb
├── static/
├── templates/
├── requirements.txt
└── README.md
```

---
Feel free to contribute to this project by submitting issues or pull requests!
