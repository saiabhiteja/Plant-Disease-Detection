**PrecisionLeaf: Plant Disease Detection**

**INTRODUCTION**

➢ Late and wrong identification of leaf disease leads to huge loss of yield, time,
money and quality of plants.

➢ After detection, farmers could apply appropriate pesticides and herbicides.to
stop the infection.

➢ Leaf diseases are recognised and researched using visual patterns of leaves.

MOTIVATION

➢ Most of the time, leaf disease detection is done by naked eyes by farmers or
expert.

➢ Physical properties like leaf color, texture, etc are analyzed.

➢ Detection by physical method is quite expensive and time consuming.

➢ The best solution is to introduce an automated system which could achieve
the same task.

➢ This motivated us to design an automated system to track and identify leaf
disease.

PROBLEM STATEMENT

➢ Agriculture is a vital source of income for many countries. However, the
quality of crops can be affected by various factors, including disease, pests,
and environmental conditions. The early detection and diagnosis of these
issues are crucial to prevent the spread of diseases and ensure high-quality
crop production.

➢ Currently, the detection of leaf diseases is done manually which is
time-consuming and very much prone to errors.

➢ To address these issues, an efficient and automated system that uses
machine learning and deep learning can be developed to detect plant
diseases at an early stage.

OBJECTIVE

➢ Create dataset of images of respective tea leaves

➢ Classification of leaf disease using Machine Learning and Deep
Learning Classifiers.

➢ Once a leaf is detected with disease, we should give which type of
disease it is.

➢ Improve the accuracy of the already existing method


PROPOSED METHODOLOGY

![image](https://github.com/Saketh1702/PrecisionLeaf-Advanced-Disease-Detection/assets/62469950/2fd6cf1a-4b99-4b2c-9977-afc4f66965f0)


The algorithm which we are going to use in this
classification of infected plant leaves consists of 5
phases, viz: -

➢ Dataset Collection

➢ Image Preprocessing

➢ Feature Extraction

➢ Selection of Classifier

➢ Analyzing the Results

ALGORITHM

● Multiple models, including
VGG16, VGG19, CNN, and
LSTM, are trained to predict
diseases.

● A voting algorithm is
employed to combine the
predictions of these models.

![image](https://github.com/Saketh1702/PrecisionLeaf-Advanced-Disease-Detection/assets/62469950/de8b95bc-248f-491b-bedb-e583a3e4829a)

● This ensemble approach helps
improve the accuracy of disease
predictions.

● If a disease is detected, the
algorithm moves to the next
step for disease type detection.

● The combination of multiple
models and the use of voting
algorithm aim to improve the
accuracy of disease predictions.

● By accurately classifying
diseases, the algorithm
enhances the overall accuracy
and efficiency of disease
diagnosis.

● Once a disease is predicted, a
second algorithm is used for
more detailed disease
classification.

● This step involves further
analysis of images or other
diagnostic tests.
