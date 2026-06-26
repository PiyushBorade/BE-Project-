RareDetect – Brain Tumor Detection Using Deep Learning
About the Project

RareDetect is a final year engineering project developed to assist in the detection of brain tumors from MRI images using deep learning. The main idea behind this project is to compare different deep learning models and provide a simple web application where users can upload an MRI scan and receive a prediction.

The project uses three different models:

VGG16
ResNet50
RareDetect (Custom CNN)

The final prediction is displayed through a Streamlit-based web interface along with the confidence score and confusion matrix.

Features
Upload MRI images
Detect whether the scan contains a tumor or not
Compare predictions from multiple deep learning models
Display confidence score
View confusion matrix
Download the prediction report
Simple and easy-to-use interface
Tools and Technologies
Python
TensorFlow & Keras
Streamlit
NumPy
Matplotlib
Pillow
How the Project Works
Upload an MRI image.
The image is resized and preprocessed.
The trained model analyzes the image.
The application predicts whether a tumor is present.
The result is displayed along with the confidence score.
Users can also download the generated report.
Project Structure


RareDetect/
│── app.py
│── vgg16_model.h5
│── resnet50_model.h5
│── raredetect_model.h5
│── README.md
│── requirements.txt
│── sample_images/
Running the Project

Install the required libraries:

pip install -r requirements.txt

Run the application:

streamlit run app.py
Future Improvements

Some improvements that can be added in the future are:

Training on a larger MRI dataset
Better model optimization
Multi-class tumor detection
Deployment on cloud platforms
Integration with hospital management systems
