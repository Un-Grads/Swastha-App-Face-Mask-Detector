# Swastha-App-Face-Mask-Detector-with-Python-and-Machine-Learning-AI-Computer-Vision-Team-Un-Grads-Reva-University
# Team Un-Grads:
we are Group of 4 students studying Computer Science and Engineering at Reva University, Bangalore. known each other from past 2 years and have same intersts in learning programing and coding in Hackathon. we as a team have intersts in developing Applications in AI & ML and implement them to make betterment in  technology.

Team members:
Shashank K S email:shashankreddy0709@gmail.com ,  Siddesh B R email:siddesh2000br@gmail.com ,                  Shaik Sahil Ahmed email: sahilahmedshail63@gmail.com , Shashidhar Reddy email: reddyshashidhar74@gmail.com .

# About:
The corona virus COVID-19 pandemic is causing a global health crisis so the effective protection methods is wearing a face mask in public areas according to the World Health Organization (WHO). The COVID-19 pandemic forced governments acrossthe world to impose lockdowns to prevent virus transmissions. Reports indicate that wearing facemasks while at work clearly reduces the risk of transmission. An efficient and economic approach of using AI to create a safe environment in a manufacturing setup. A hybrid model using deep and classical machine learning for face mask detection will be presented. A face mask detection dataset consists of with mask and without mask images , we are going to use OpenCV to do real-time face detection from a live stream via our webcam. We will use the dataset to build a Swastha App face mask detector with computer vision using Python, OpenCV, and Tensor Flow and Keras. Our goal isto identify whether the person on image/video stream is wearing a face mask or not with the help of computer vision and Machine learning.
# TechStack/frameworks:
  1.Python 
  2. Machine Leaning 
  3. AI and Computer Vision
  4. OpenCV
  5. Keras
  6.TensorFlow
  7.MobileNetV2
  8.Web Camera
# Features:
Our face mask detector didn't use any morphed masked images dataset. The model is accurate, and since we used the MobileNetV2 architecture, it’s also computationally efficient and thus making it easier to deploy the model to embedded systems (Raspberry Pi, Google Coral, etc.).

This system can therefore be used in real-time applications which require face-mask detection for safety purposes due to the outbreak of Covid-19. This project can be integrated with embedded systems for application in airports, railway stations, offices, schools, and public places to ensure that public safety guidelines are followed.
# Dataset :
This dataset consists of 3835 images belonging to two classes:
with_mask: 1916 images
without_mask: 1919 images
we have collected all the images from google , Unsplash , Free Images , Burst , Canva and sperated them into two folders with_mask and without_mask in data set folder.
# Overview :
The corona virus COVID-19 pandemic is causing a global health crisis so the effective protection methods is wearing a face mask in public areas according to the World Health Organization (WHO). Reports indicate that wearing face masks while at work clearly reduces the risk of transmission. An efficient and economic approach of using AI to create a safe environment in a manufacturing setup. A hybrid model using deep and classical machine learning for face mask detection will be presented. A face mask detection dataset consists of with_mask and without_mask images , we are going to use Open CV to do real-time face detection from a live stream via our webcam. We will use the dataset to build a Swastha App face mask detector with computer vision using Python, Open CV, and Tensor Flow and Keras. 
# Goals :
•	Our goal is to identify whether the person on image/video stream is wearing a face mask or not with the help of computer vision and Machine learning. 
•	Following the outbreak of covid-19, everyone is aware of taking precautionary and protection measures about covid-19, so the identification of face masks would play a huge role in preventing corona virus.
# Working Methodology :
We have divided two Phases in Swastha App (Face Mask Detector):
Phase 1: Train the Face Mask Detector –-we load the face mask data set having images of with mask and without mask collected from google and other sources and Train the face mask classifier with keras / Tenser Flow. Later Serialize face mask classifier to disk.
Phase 2: Apply Face Mask Detector – Load face mask classifier from disk and detect faces in image / video stream. Extract each face ROI and apply face mask classifier to each face ROI to determine mask or no mask . results are shown using web Camera whether a person is wearing a face mask or not with percentage Accuracy. 
# Programing Language : Python 
# Results: 
As the technology are blooming with emerging trends the availability so we have novel face mask detector which can possibly contribute to public healthcare. The architecture
consists of MobileNet as the backbone it can be used for high and low computation scenarios. In order to extract more robust features, we utilize transfer learning to adopt weights from a similar task face detection, which is trained on a very large dataset.

We used OpenCV, tensor flow, keras , Pytorch and CNN to detect whether people were wearing face masks or not. The models were tested with images and real-time video
streams. The accuracy of the model is achieved and, the optimization ofthe model is a continuous process andwe are building a highly accurate solution by tuning the hyper
parameters. This specific model could be used as a use case for edge analytics. Furthermore, the proposed method achieves state-of-the-art results on a public face mask
dataset. By the development of face mask detection we can detect if the person is wearing a face mask and allow their entry would be of great help to the society.
 
 



