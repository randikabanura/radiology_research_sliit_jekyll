---
title: "Lung Cancer Detection"
date: 2018-11-18T12:33:46+10:00
featured: true
weight: 3
layout: scope
---

<p style='text-align: justify;'>
This is the thesis  in the part of Lung Cancer detection of the  research project including research problem, literature review ,objectives and  research gap.
</p>

![Lung Cancer Detection](/images/scopes/lung_cancer_detection/lung.jpg "Lung Cancer Detection")	

<p style='text-align: justify;'>
Currently there are no viable solutions for the web based medical images viewing systems that also run computer aided systems that can diagnose or identify potential problems with the medical images. Even though I mainly focused on the detection using X-ray images this technique can be improved and updated for other techniques such as MRIs and ultrasound images. Current situation is that most of the work is done by a radiologist or a physician for the diagnosis part of the procedure. Picture archiving and communication systems (PACS) are the systems that are currently in use in countries like Sri lanka. They only provide a way to view the medical images by the radiologist and do not provide any helpful diagnosis prediction on behalf of the medical practitioner. And PACS solves the problem of having to manually transfer the medical images from the capturing device to the computer that has the viewing software. With the lack of human and technical resources it is vital to get most out of the resources available in hand. Due to this, there should be a mechanism for managing the available medical resources well so that every patient who does need the attention gets it whether they are in a city, town or rural village. Detection of bone abnormalities in humans using X-rays is the problem that I am focusing on. It is important because it is overlooked most of the time due to the rarity of a diagnosis event. Most of the time bone abnormalities detection has been diagnosed accidently. I could make every bone X-ray go through a model and automatically inform the radiologist if any irregularities were found about the X-ray. There are several ways for the detection of bone abnormalities such as SVM model and deep learning using CNN model. Most of the models give a relatively similar rate of a prediction of the abnormality. I have to incorporate these models with a view for the radiologist.
</p>

## Literature Survey

<p style='text-align: justify;'>
As reported by WHO, cancer caused approximately 9.6 million deaths in 2018 [1]. Almost 20% or 1.76 million of these deaths were due to lung cancer [1]. Cancer screening plays an important role in preventive care because it is most treatable when caught in the early stages. This study shows that the appearance of malignant lung nodules more commonly demonstrates a spiculated contour, lobulation, and inhomogeneous attenuation [2]. Presently, low dose computed tomography (LDCT) plays an important role in lung cancer screening [3]. LDCT screening has reduced lung cancer deaths and is recommended for high-risk demographic characteristics [3]. Results from LDCT screening may be further evaluated with standard dose computed tomography (CT) [4]. However, there are many barriers to implementing LDCT screening, such as providers’ anxiety concerning the access to LDCT equipment and the potential financial burden on rural populations [3]. Moreover, rural populations have limited access to both primary care physicians and specialists [3]. On the other hand, chest X-rays are readily available in rural areas. Nonetheless, chest X-rays produce lower quality images compared to LDCT or CT scans and, therefore, a lower quality diagnosis is generally expected. This study explores the use of chest x-rays with a computer-aided diagnosis (CADx) system to improve lung cancer diagnostic performance. The convolutional neural network (CNN) is proven to be very effective in image recognition and classification tasks. Lung cancer prediction with CNN faces the problem of small sample size. Indeed, CNN contains a large number of parameters for adjustment on a large image dataset. In practice, researchers often pre-train CNNs on ImageNet, a standard image dataset containing more than one million images. The trained CNNs are then adjusted on a specific target image dataset. Unfortunately, the available lung cancer image dataset is too small for this transfer learning to be effective, even with a data augmentation trick. To alleviate this problem, the idea of applying transfer learning was proposed several times to gradually improve the performance of the model. In this work, transfer learning is applied twice. Firstly, to 3 transfer the model from a general image into the chest x-ray domain, and secondly to transfer the model for lung cancer. Such multi-transfer learning can solve the problem of a small sample size and achieves a better task result compared to the traditional transfer learning technique. Though there are some literature available for detecting the lung cancers form X-ray images, but less number of researchers has been conducted with the combination of the above-mentioned area. In 2018, Worawate Ausawalaithong, Arjaree Thirach, Sanparith Marukatat and Theerawit Wilaiprasitporn presented an approach for Automatic Lung Cancer Prediction from Chest X-ray Images Using the Deep Learning Approach. For this they have used JSRT and ChestX-ray14 public datasets. Among the convolutional neural network’s architectures such as Inception [5] [6], ResNet [7], and DenseNet [8], the model used in this research is the 121-layer Densely Connected Convolutional Network (DenseNet-121). In 2017, Rajpurkar proposed a 121-layer convolutional neural network based on DenseNet and named as CheXNet [9]. They trained their network with 10.000 frontal view chest X-ray images with 14 different diseases. They have assessed the performance of their network with four expert radiologists in f1 score metric which is the harmonic average of the precision and recall metrics. CheXNet achieved a f1 score of 0.435. In 2017, Abhishek Sharma, Daniel Rajuetal, Sutapa Ranjan presented an approach for detecting the presence of pneumonia clouds in chest X-rays (CXR) by using only Image processing techniques [10]. For this, they have worked on 40 analog chest CXRs pertaining to Normal and Pneumonia infected patients. Indigenous algorithms have been deployed for cropping and for extraction of the lung region from the images. This reference used to go through the image processing and feature extraction technics, they were used.
</p>

## Rsearch Gap

<p style='text-align: justify;'>
Lusted L.B proposed for the first time by analyzing and recognizing the abnormal and normal photography images [11]. Hence, an analysis of medical images by computer was introduced and it includes some steps such as Image Enhancement, Segmentation and feature extraction. There are several types of research have been done for the past few years about the systems that can detect the presence of lung cancers. When considering the previous researchers, we found certain limitations and future works. Therefore, we propose a system in order to overcome above-mentioned limitations and come up with a new product with strong feature extraction method, compare to other existing system and achieve better performance for Lung Cancer Detection (LCD) system. The proposed system expects to provide more accurate result compare than other existing systems.
</p>

## Research Problem

<p style='text-align: justify;'>
Lung cancer is one kind of dangerous diseases of the world. The mortality rate of lung cancer is the highest among all other types of cancer. In every year more people die because of lung cancer than any other types of cancer such as: breast, brain, and prostate cancers. Lung cancer is leading cause of death from cancer among people of ages between 45 and 70. Lung cancer is responsible for more than 25% of all cancer related deaths every year and lung cancer kill more people than breast, colon and prostate cancers combined. Lung cancer is one of the most serious cancers in the world, with the smallest survival rate after the diagnosis, with a gradual increase in the number of deaths every year. Survival from lung cancer is directly related to its growth at its detection time. But people do have a higher chance of survival if the cancer can be detected in the early stages. 5 There are many existing techniques (most of these are expensive and time consuming and also can be unclear or can be confused with other diseases) that are used to detect lung cancer in advanced stages, such as Computed Tomography (CT), Chest Radiography (x-ray), Magnetic Resonance Imaging (MRI scan) and Sputum Cytology. (The manual process of reading X-ray, CT, and MRI) So, it is a great needed for a new technology to detect lung cancer in its early stages.
</p>

## Rsearch Objectives

<p style='text-align: justify;'>
The main objectives of the proposed system are to support to radiologists to make his/her decisions more accurately and with more efficiency. And make radiologists life easier by saving much needed time and money in order to already experiencing radiologist’s poverty by producing a web viewer to detect presence of lung cancers using image processing and deep learning approaches.
</p>

### Increasing the accuracy of the reading X-ray to detect the presence of lung cancers

 <p style='text-align: justify;'>
Several data augmentation methods are deployed to artificially increase the size and quality of the dataset. This process helps in enhances the model’s generalization ability during training. the process of lung cancer detection by reading X-ray images manually can be time consuming and less accurate. The reason is that several other medical conditions i.e. pneumonia, excess fluid etc. can also show similar opacities in images. Therefore, accurate reading of images is highly desirable. Simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard .
 </p>

### Increasing the efficiency of the radiologist

 <p style='text-align: justify;'>
Unlike other methods that rely solely on transfer learning approaches or traditional handcrafted techniques to achieve a remarkable classification performance, a convolutional neural network model is constructed from scratch to extract features from a given chest X-ray image and classify it to determine if a person is infected with pneumonia. These approaches save the time of radiologist.
 </p>

## Methodology

<p style='text-align: justify;'>
Proposed system focus on detection of Lung cancer from X-ray image which is automatically detects Lung cancer. Overall, there are three main processes used throughout the report; Preprocessing, feature extraction and finally the classification process. All the tasks in between the dataset to classification (preprocess, feature extraction, classification) will be discussed with the corresponding components.
</p>

### Dataset

1. <p style='text-align: justify;'>JSRT Dataset [20]: This public dataset from JSRT (Japanese Society of Radiological Technology) consists of 247 frontal chest x-ray images; 154 of which have lung nodules (100 malignant cases, 54 benign cases) and 93 are images without lung nodules. All images have a pixel size of 2048 2048. Since this dataset is very small, 10-fold cross-validation was performed to increase performance reliability. Malignant cases were considered as positive, while both benign and non-nodule cases were considered as negative. Data were randomly split into the training, validation, and test set.</p>

2. <p style='text-align: justify;'>ChestX-ray14 Dataset [17]: This public dataset released by Wang et al. [17] contains 112,120 frontal chest x-ray images, currently the largest of its kind. Each image is individually tagged with up to 14 different thoracic pathology labels. All images have a pixel size of 1024 × 1024 pixels. However, this dataset does not contain any lung cancer images. The fourteen thoracic pathology labels consist of Atelectasis, Consolidation, Infiltration, Pneumothorax, Edema, Emphysema, Fibrosis, Effusion, Pneumonia, Pleural Thickening, Cardiomegaly, Nodule, Mass, and Hernia. It was decided to use this dataset to compensate for there being only 100 cases of lung cancer data, firstly by training for the recognition of nodules, considering nodule cases as positive and all remaining cases (non-nodule) as negative. Data were randomly split into the training, validation, and test set, without having any overlap of patients between data sets.</p>

### Data preparation

<p style='text-align: justify;'>
Data preparation was applied to all images, consisting of the following four steps:
</p>

* Step 1: increasing the contrast of all images using histogram equalization. This allows the intensity of images to be normalized from different datasets.

* Step 2: removing the noise from all images using median filtering with a window size of 3×3.

* Step 3: resizing images to 224×224 pixels to match the input of the model used in this study.

* Step 4: normalizing image color based on the mean and standard deviation of the ImageNet training set [21].


### Feature extraction

<p style='text-align: justify;'>
The Image features Extraction stage is very important in our working in image processing techniques which using algorithms and techniques to detect and isolate various desired portions or shapes (features) of an image. Feature extraction is an essential stage that represents the final results to determine the normality or abnormality of an image [7].
</p>

<p style='text-align: justify;'>
These features act as the basis for classification process. Only these features were considered to be extracted; average intensity, area, perimeter and eccentricity. The features are defined as follows:
</p>

1. Area: it is a scalar value that gives the actual number of overall nodule pixel. It is obtained by the summation of areas of pixel in the image that is registered as 1 in the binary image obtained.

2. Perimeter: It is a scalar value that gives the actual number of the outline of the nodule pixel. It is obtained by the summation of the interconnected outline of the registered pixel in the binary image.

3. Roundness: Eccentricity: This matric value or roundness or circularity or irregularity index (I) is to 1 only for circular and it is <1 for any other shape. Here it is assumed that, more circularity of the object [5].


### Classification

<p style='text-align: justify;'>
After the Thresholding method, rest of the Lung Cancer Detection System uses neural network which is very efficient and reliable. After the feature extraction process, these features are passed through the neural network to train up the system for classification purpose or detection purpose. The whole proposed training system of lung cancer detection consist of the following steps- Image Acquisition, Image Preprocessing, Segmentation, Feature Extraction, Neural Network Classification. A neural network is employed for lung cancer detection. A multilayer feed forward neural network with supervised learning method is more reliable and efficient for this purpose.
</p>

## Technologies Used


### Python

 <p style='text-align: justify;'>
Python was used as the main programming language mainly due to its extensive
selection of libraries and frameworks focusing on machine learning , the simple syntax
helps to collaborate with the rest of the team members, concise readable code,
extensive support from high quality documentation and active community of
developers that offer assistance. CNN was constructed using python and deployed
using python flask in the backend. Few main libraries were used.
to implement and it’s explained in next sub section
</p>
* Tensorflow

> <p style='text-align: justify;'>One of the most famous and widely used deep learning libraries is the Google tensorflow. Google uses deep learning techniques to improve their own products, as an example google search recommendation system is a direct result of machine learning and deep learning techniques. Tensorflow architecture has three parts which are processing the data, building the model and training and estimating the outcome. This architecture is really helpful to our research as I wanted to train the X-ray images and get an outcome of whether the image contains any abnormalities or diseases. This library does contain a lot of options to image preprocessing which is a very important part of deep learning research.
> Tensorflow also supports a large variety of algorithms including linear regression, classification, deep learning classification and much more. This has also contributed to the fact that this library is becoming more famous day by day. As C++ the main programming language used in the library it is very fast in large scale computational tasks such as image preprocessing and training using matrices. After the model creation it also helps the developers to use those models in platforms such as web, mobile and desktop. After training the possibilities are limitless as tensorflow supports every major platform including linux.</p>

* Keras

> <p style='text-align: justify;'>
Keras is a powerful and easy-to-use free open source Python library for developing and
evaluating deep learning models. It wraps the efficient numerical computation libraries
Theano and TensorFlow and allowed us to define and train neural network models in
just a few lines of code. So that keras was used us to train the CNN and preprocess
the image dataset.
> </p>

* OpenCv

> <p style='text-align: justify;'>
OpenCv was used to resize images for a same size as, as training
datasets,testind and inserting image in the real world can be different sizes.
> </p>

###  Orthanc

<p style='text-align: justify;'>
Orthanc is a dicom server which can be stored dicom images and meta data
with patient, physician details. We used it for storing dicom images and
metadata.
</p>

### Flask Framework

<p style='text-align: justify;'>
Flask is a lightweight WSGI web application framework. It is designed to make getting
started quick and easy, with the ability to scale up to complex applications. Also there
are many extensions provided by the community that make adding new functionality
easy. So that python flask was used to return the details of the result to the frontend.
</p>

###  DICOM Viewer with AI prediction - React JS

<p style='text-align: justify;'>
React js was selected to implement the front end as it is Easy to Learn ,Use and  creating Dynamic Web Applications Becomes Easier.And the react JS has  reusable components.So that it makes more easier to extend the application with new features for future developments.So that react JS was used to implement the viewer with 
AI prediction feature for X-ray Images
</p>        

## Commercialization

<p style='text-align: justify;'>
There is no current system in Sri Lankan hospitals to address the issues within the radiology field. Currently when a patient gets an X-ray it directly goes to the physician for a special doctor who prescribes it without going through the radiologist. It goes to the radiologist if the doctor asks for a report regarding the X-ray. Which makes potential issues with the X-ray that could have been detected through radiologist goes with any detection. And for the radiologists there needs to be a fully fledged PACS system and a Viewer that can create a report regarding the X-ray. Which makes radiologist working time less as he/she needs to in person. Main customers of the product will be hospitals in Sri Lanka. Especially private hospitals will be attracted to products rather than their government counterparts. Detection of bone abnormalities are proposed by this system that can be sold as a feature that no other system has. That also makes the current PACS more work with less productivity. This product gives hassle free internet solutions to bulky PACS in hospitals. As the system must connect to the internet it would not be possible to host the system by the hospitals themselves. Because it has to work with standards of internet 41security regarding medical data it should be on a centralized server. So the system can be sold as two separate stages. The access to the web application as well as admin panel for image uploading as a one time cost and monthly I can charge the hospitals for hosting the application and medical images and data. So, the proposed system will solve a lot of the current issues facing radiology in Sri Lanka. As the proposed system is a web based system, it can be accessed through the internet there would be direct access to radiologists medical images. This type of system can be commercially viable and can be deployed in private hospitals because that could increase the productivity of their hospital while the system could also bring down time that patient has to wait. Because private hospitals are always looking for the quickest and efficient way of working this product would make sense for them to have rather than not.
</p>