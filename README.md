# Target-Person-Identification
Integrating Object Detection (EfficientDet) and Facial Recognition (FaceNet) for Person Identification

Object detection, facial recognition, and person identification are important tasks in computer vision with numerous real-life applications. 

The major goal of the proposed model is to identify people and recognize them in the images. We propose a solution that combines power of both  EfficientDet model for object detection and the FaceNet model for facial recognition to detect persons in an input image, recognize their faces, and label them with their corresponding names. The experimental study of the model takes place on COCO dataset and a custom dataset of images of students. 

This solution can be applied to various scenarios beyond education, such as in security and surveillance, healthcare, transportation, retail, and entertainment etc. The importance of the model lies in its ability to efficiently and accurately perform person identification and recognition in real-time scenarios, which can save time and resources and improve overall efficiency.

TPI.ipynb - Actaul Code with EfficientDet and FaceNet Models (Preferebly use Google Colab)
photos.zip - Custom student images dataset.
vis_utils.py - Modified with updated methods to crop the persons.


Steps To Run:
1. Colne the github model of automl in the TPI.ipynb
2. Replace the vis_utils.py which is in autmol/efficientdet/Visualize folder with the one provided
3. Upload an input image in the autmol/efficientdet/testdata folder
4. Persons and Faces will be in the respected folder named - persons and faces
5. The output will be the recognized faces from the input image
