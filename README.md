


# Jafar Abdollahi

<h2> Discription </h2>
# An-artificial-intelligence-system-for-detecting-the-types-of-the-epidemic-from-X-rays-
Since the beginning of the COVID-19 pandemic, many lives have been in danger. The visual geometry group network (VGGNet) is used in this research as a model to identify epidemic types. The dataset consisted of 1206S chest X-ray images extracted from the Kaggle website and evaluated in 4 classes: Pulmonary tuberculosis, normal lung, pneumonia, and Covid 19. We have used the VGGNet architecture to diagnose and classify the mentioned disease using the chest X-ray images. To assess the performance of these classes, the parameters such as accuracy, specificity, and sensitivity are measured. Regarding the measured parameters, the accuracy, specificity, and sensitivity values were 0.97, 0.96, and 0.98, respectively. This system can differentiate among these diseases by accurately diagnosing differences in patients’ X-ray images. The results showed that the VGG16 model could be more effective than VGG19 in diagnosing epidemics. The VGG16 based technique can facilitate the rapid diagnosis of patients and increase their chances of recovery. The findings also showed that the proposed model based on chest X-ray images is more accurate, simpler, and less expensive than computed tomography (CT) images.


<h2> Dataset </h2>
This section describes the three datasets considered during this work. These are the three most enormous public datasets to the most effective of our knowledge.

• Tuberculosis (TB) Chest X-ray Database

A team of academics from Qatar University in Doha, Qatar, and the University of Dhaka in Bangladesh has created a database of chest X-ray photos for Tuberculosis (TB) positive cases and normal shots. The database for this paper contains 3047 (TB) photographs and 3047 representative images. The TB database is collected from the source:https://www.kaggle.com/tawsifurrahman/tuberculosis-tb-chest-x-ray-dataset

• Covid-19 Chest X-ray Database

RADIOGRAPHY DATABASE FOR COVID-19 (Winner of the COVID-19 Dataset Award by Kaggle Community) Researchers from Qatar University in Doha, Qatar, and the University of Dhaka in Bangladesh, in partnership with collaborators from Pakistan and Malaysia and medical practitioners, have established a database of COVID-19 positive cases, as well as normal and virus infection images. 3006 Covid-19 photos were used to generate the database for this paper. The database is collected from https://www.kaggle.com/tawsifurrahman/covid19radiography-database.

• Pneumonia Chest X-ray Database

The pneumonia database used 3060 validated Chest X-Ray images as our dataset to identify this lung infection. The database is collected from source:https://www.kaggle.com/paultimothymooney/chest-x-raypneumonia.

• Final regards

The detailed information about the collected dataset and the identified issues are summarized in Table I. This section presents the relation between the number of images and patients for each class.
<img src="https://github.com/Jafar-Abdollahi/An-artificial-intelligence-system-for-detecting-the-types-of-the-epidemic-from-X-rays-/blob/main/1.jpg"> 
<img src="https://github.com/Jafar-Abdollahi/An-artificial-intelligence-system-for-detecting-the-types-of-the-epidemic-from-X-rays-/blob/main/2.png"> 
<img src="https://github.com/Jafar-Abdollahi/An-artificial-intelligence-system-for-detecting-the-types-of-the-epidemic-from-X-rays-/blob/main/3.jpg"> 
<img src="https://github.com/Jafar-Abdollahi/An-artificial-intelligence-system-for-detecting-the-types-of-the-epidemic-from-X-rays-/blob/main/abdol3-CSICC202220-small.gif"> 



<h2> Methods </h2>
This paper uses the transfer learning method to train a convolutional neural network (CNN). This paper offers an upgraded convolutional neural network VGG-16 and VGG19 that uses deep learning to achieve this purpose.

The proposed x-ray-based epidemic screening methodology is described. We modified the VGGNet architecture and used X-ray images from healthy and SARCoV-2 and pneumonia-infected patients to train the models. The x-ray pictures are derived from the datasets mentioned in the preceding section and are subjected to the preprocessing steps outlined below. The proposed method is intended to determine if chest x-rays are normal or show signs of lung illness.

We use a deep learning network based on the VGG-19 and VGG16 (i.e., Visual Geometry Group) model [2] and transfer learning to develop the (first and second) model.

In-network depth has been improved as compared to typical convolutional neural networks. It has a better structure than one since it alternates between many convolutions and nonlinear activation layers. The layer structure can better extract image features, apply Maxpooling for low sampling, and use the linear unit (ReLU) as the activation function, selecting the most significant value in the image area as the site’s pooled value.
<img src="https://github.com/Jafar-Abdollahi/An-artificial-intelligence-system-for-detecting-the-types-of-the-epidemic-from-X-rays-/blob/main/abdol1-CSICC202220-small.gif"> 
<img src="https://github.com/Jafar-Abdollahi/An-artificial-intelligence-system-for-detecting-the-types-of-the-epidemic-from-X-rays-/blob/main/abdol2-CSICC202220-small.gif">



<h2> Conlusion </h2>
Due to the disease’s early stage, the number of labeled data points gathered was limited. As a result, the dataset’s scale was lowered, as was the number of data points utilized. There is a chance you will end up overfitting. When the dataset size is increased, greater results are often obtained. Our current proposal comprises two separate models capable of handling the categorization mentioned above tasks. In the future, an architecture might be built to group the chest X-rays within the indicated classes successfully. For the classification tasks, we used the VGG-16 and VGG-19 models.

As indicated in Table IV, we tried a variety of models and got varying degrees of accuracy. In summary, the upgraded network model’s precision for detecting epidemic categories has increased by 97.99 percent, and its sensitivity rate has increased by 98.26 percent. This improvement impact is well acknowledged to be quite strong. Furthermore, the parameters have been substantially lowered, and the upgraded VGG-16 for finding epidemic detection categories has much promise and provides a positive guarantee prior to admission to the hospital. We hope that our well-trained network can assist with medical diagnostics. The study also has a disadvantage because it only used a small number of COVID-19 X-ray pictures. I hope that larger datasets from COVID-19 from our local hospitals become available in the future, and using them increases the accuracy of our proposed network.

Available Code: All computational tools developed during this work can be found in a repository available at https://github.com/Jafar-Abdollahi/An-artificial-intelligence-system-for-detecting-the-types-of-the-epidemicfrom-X-rays- which, includes a tutorial for the usage of the proposed tools.
<img src="https://github.com/Jafar-Abdollahi/An-artificial-intelligence-system-for-detecting-the-types-of-the-epidemic-from-X-rays-/blob/main/abdol.t4-CSICC202220-small.gif"> 
<img src="https://github.com/Jafar-Abdollahi/An-artificial-intelligence-system-for-detecting-the-types-of-the-epidemic-from-X-rays-/blob/main/abdol4-CSICC202220-small.gif"> 
<img src="https://github.com/Jafar-Abdollahi/An-artificial-intelligence-system-for-detecting-the-types-of-the-epidemic-from-X-rays-/blob/main/abdol5-CSICC202220-small.gif"> 
<img src=" "> 


<h2> Paper </h2>
https://ieeexplore.ieee.org/abstract/document/9780523


<h2> Contact me </h2>
You can reach me at:

Email: ja.abdollahi77@gmail.com
<br>
LinkedIn: https://www.linkedin.com/in/jafar-abdollahi-7647971b3/
<br>
Google Scholar: https://scholar.google.com/citations?user=2dK8kPwAAAAJ&hl=en
<br>
researchgate: https://www.researchgate.net/profile/Jafar-Abdollahi?ev=hdr_xprf&_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6ImxvZ2luIiwicGFnZSI6ImhvbWUiLCJwcmV2aW91c1BhZ2UiOiJsb2dpbiIsInBvc2l0aW9uIjoiZ2xvYmFsSGVhZGVyIn19
<br>
youtube: https://www.youtube.com/@jafarabdollahi/featured
<br>
<img src="https://github.com/Jafar-Abdollahi/cuffless-bp-master-in-python-jupyter-/blob/main/2024-07-07_19-45-22.png"> 
