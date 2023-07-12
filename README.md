>The project is done under Rani Rasmoni Green University ,Tarakeswar - Hooghly

# Transfer Learning for DiabetesRisk Assessment: **"** **Retinal Biomarkers for Diabetes Detection:Applying Deep Learning to Retinography Analysis "**



Report Submitted By-

 Name: - Rajat Chakraborty
 Name: - Snehasish Sadhukhan
 Department of Computer Science,

**Guided by–**

 **Anupam Sen**

 **Assistant Professor**

 **Department of Computer Science,**

 **Government General Degree College, Singur**

 
                                                                              
                                                                              
---------------------------------------------------------------
> `#0969DA***Abstract***  ``#0969DA Abstract `

Diabetes is a chronic disease that affects millions of people worldwide
and is a significant cause of morbidity and mortality. Early detection
and risk assessment of diabetes are crucial for timely intervention and
management. Retinal biomarkers, extracted from retinal images obtained
through retinography, have shown promise in identifying individuals at
risk of diabetes. However, analyzing retinal images manually is
time-consuming and requires specialized expertise.

The proposed methodology involves fine-tuning the pre-trained model on a
dataset of labeled retinal images associated with diabetes risk factors.
The labeled dataset consists of retinal images from individuals with and
without diabetes, along with relevant clinical information. By
fine-tuning the pre-trained model, the deep neural network learns to
extract discriminative features specific to diabetes risk assessment. We
have used multiple transfer learning algorithms like **VGG16 , VGG19
,RESNET50 , RESNET152 , INCEPTION V3 , InceptionResnet v2 , mobileNetV2
etc.** in our diabetic retinography image set.

> ***Introduction***

Diabetes is a chronic, metabolic disease characterized by elevated
levels of blood glucose (or blood sugar), which leads over time to
serious damage to the heart, blood vessels, eyes, kidneys, and nerves.
The most common is type 2 diabetes, usually in adults, which occurs when
the body becomes resistant to insulin or doesn't make enough insulin. In
the past 3 decades the prevalence of type 2 diabetes has risen
dramatically in countries of all income levels. Type 1 diabetes, once
known as juvenile diabetes or insulin-dependent diabetes, is a chronic
condition in which the pancreas produces little or no insulin by itself.
For people living with diabetes, access to affordable treatment,
including insulin, is critical to their survival. There is a globally
agreed target to halt the rise in diabetes and obesity by 2025\[
W.H.O\]. 

-   About 422 million people worldwide have diabetes, the majority
    living in low-and middle-income countries, and **1.5 million
    deaths** are directly attributed to diabetes each year. Both the
    number of cases and the prevalence of diabetes have been steadily
    increasing over the past few decades. 

 The World Health Organization (WHO) approved five worldwide coverage
and treatment goals for diabetes in May 2022, which are to be met by
2030 . Diabetes affected 536.6 million people aged 20 to 79 worldwide in
2021, with a forecast rise to 783.2 million by 2045.

Diabetes mellitus is a chronic metabolic disorder that affects millions
of people worldwide, posing significant health challenges and economic
burdens. Early detection and accurate risk assessment play crucial roles
in effectively managing and preventing diabetes-related complications.
Ocular manifestations of diabetes, such as diabetic retinopathy, have
been identified as potential biomarkers for early diabetes risk
assessment. Retinography, a non-invasive imaging technique that captures
detailed retinal images, offers valuable insights into the microvascular
changes associated with diabetes.

In recent years, deep learning techniques have demonstrated remarkable
success in various medical image analysis tasks,

including diabetic retinopathy detection. The ability of deep neural
networks to learn complex patterns and features from vast amounts of
data makes them well-suited for handling the intricate characteristics
of retinography images. However, training deep learning models from
scratch for diabetes risk assessment may be hindered by the scarcity of
labeled data, computational resources, and time-intensive processes.

Transfer learning presents a compelling solution to address these
challenges. By leveraging knowledge from pre-trained deep neural
networks, specifically those trained on large-scale image datasets like
ImageNet, we can accelerate the training process and achieve better
performance even with limited labeled retinography data. Transfer
learning allows us to fine-tune the pre-trained models on our target
task, diabetes risk assessment, while retaining the ability to recognize
relevant features from the retinography images.

This university project aims to explore the effectiveness of transfer
learning in the context of diabetes risk assessment based on retinal
biomarkers derived from retinography analysis. The central objective is
to develop a robust and accurate deep learning model that can identify
early signs of diabetes risk using retinal images. By doing so, this
project seeks to contribute to the early diagnosis and management of
diabetes, potentially reducing the incidence of diabetes-related
complications and improving patients' quality of life.

**This project will involve the following key components:**

-   **Data Collection and Preprocessing**: A comprehensive dataset of
    retinography images will be collected, including both diabetic and
    non-diabetic individuals. Preprocessing steps will be performed to
    standardize the images, correct for potential artifacts, and ensure
    data quality.

-   **Deep Learning Model Selection**: Several state-of-the-art deep
    learning architectures will be considered for transfer learning,
    including ResNet , mobileNet , Inception, and VGG models. The most
    suitable model will be selected based on its performance and
    computational efficiency.

-   **Transfer Learning:** The chosen pre-trained model will be adapted
    to the diabetes risk assessment task using transfer learning. The
    model will be fine-tuned on the retinography dataset to learn
    relevant features specific to diabetes detection.

-   **Comparison and Analysis:** The performance of the developed deep
    learning model will be evaluated using standard evaluation metrics,
    such as accuracy, validation loss ,training loss , validation
    accuracy , test loss and test accuracy.

**The outcome of this university project is expected to provide valuable
insights into the potential of transfer learning in diabetes risk
assessment and contribute to advancements in early diabetes detection
using retinography analysis. Ultimately, the findings may have
implications for future medical practices, guiding the development of
efficient and accurate diagnostic tools to combat the global diabetes
epidemic.**\
>***Related WorK***

 “Transfer Learning for Diabetic Retinopathy Detection: A Study of
 Dataset Combination and Model Performance” this research was done at
 *Kuwait university*. They have used some Transfer Learning models like
 VGG16, InceptionV3, MobilenetV2, and DenseNet12.
 **[\[1\]](https://www.mdpi.com/2076-3417/13/9/5685) 

  *Hagos and Kant*
\[[2](https://doi.org/10.48550/arXiv.1905.07203)\] showed an
 accuracy of 90.9% with a binary classification of DR with the
 InceptionV3 model .

 Bagadi et al.
 [\[3\]](https://link.springer.com/chapter/10.1007/978-981-16-8512-5_28)
 achieved an accuracy of 95% with the DenseNet121 model for the APTOS
 dataset in classifying the DR images .
“The effect of model size on accuracy”. This project also achieves great parameters of accuracy: 0.8515 - precision: 0.8517 - recall: 0.8526. [**\[4\]**](https://www.kaggle.com/code/the314arham/the-effect-of-model-size-on-accuracy/notebook#ABSTRACT)
“DL-Diabetic RetinopathycDetection-95%Acc-CN”[**\[5\]**.](https://www.kaggle.com/code/parisanahmadi/dl-diabetic-retinopathycdetection-95-acc-cnn#Deep-Computer-Vision) The research did built a custom CNN model and got approximately 93% of test accuracy.
“Diabetic Retinopathy Detection and Classification**”**[**\[6\]**](https://www.kaggle.com/code/akshat0007/diabetic-retinopathy-detection-and-classification) .project uses EfficientNet as a pretrained model . It has training loss of 0.0728 accuracy of 0.9758 validation accuracy of 0.7866 .
“Deep Transfer Learning Models for Medical Diabetic Retinopathy Detection”[**\[7\].**](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7085308/) This research has researched extensively on AlexNet, ResNet18, SqueezeNet, GoogleNet, VGG16, and VGG19 and found AlexNet with 97% accuracy.


| ***Deep Learning***

***(In diabetic retinopathy)***

> Deep learning and transfer learning are powerful techniques used in
> the detection of diabetic retinopathy, a common complication of
> diabetes that affects the retina of the eye.

Deep learning models, particularly convolutional neural networks (CNNs),
have shown great promise in detecting diabetic retinopathy from retinal
images. These models can automatically learn complex patterns and
features from the images, enabling accurate detection.

Transfer learning is employed in diabetic retinopathy detection to
leverage pre-trained models that have been trained on large-scale
datasets, such as **ImageNet**. These models have learned generic
features that can be useful for various vision tasks, including diabetic
retinopathy detection.

Pre-trained models like **InceptionV3, ResNet, and VGG** are commonly
used in transfer learning for diabetic retinopathy detection. These
models offer a good starting point as they have already learned a wide
range of features from diverse images.

Data augmentation techniques, such as rotation, scaling, and flipping,
are employed to increase the diversity and quantity of the training
data. Data augmentation helps prevent overfitting and improves the
generalization capability of the model.

Evaluation of the diabetic retinopathy detection model involves various
metrics, including **accuracy, precision, recall, and F1 score**. These
metrics provide insights into the performance of the model in correctly
classifying diabetic retinopathy cases. **\
**

>**| Convolution Neural Networks**

**A** Convolutional Neural Network (CNN) is a type of deep learning
algorithm that is particularly well-suited for image recognition and
processing tasks. It is made up of multiple layers, including
convolutional layers, pooling layers, and fully connected layers.

-   The construction of a convolutional neural network is a
    > multi-layered feed-forward neural network, made by assembling many
    > unseen layers on top of each other in a particular order.

-   It is the sequential design that give permission to CNN to learn
    > hierarchical attributes.

-   In CNN, some of them followed by grouping layers and hidden layers
    > are typically convolutional layers followed by activation layers.

-   ![](media/image2.png){width="7.775in" height="4.025in"}The
    > pre-processing needed in a ConvNet is kindred to that of the
    > related pattern of neurons in the human brain and was motivated by
    > the organization of the Visual Cortex.

> **| *Transfer Learning* *Algorithms***

We have used several Transfer Learning models.

This study proposes a transfer learning approach for diabetes risk
assessment by leveraging deep learning techniques for retinography
analysis. Transfer learning allows the transfer of knowledge and
features learned from one task to another related task, reducing the
need for large, labeled datasets. In this research, a pre-trained deep
learning model is used as a feature extractor to capture meaningful
features from retinal images. Transfer Learning algorithms make it
possible for researchers to get needed outcome very fast and efficient
way . It figure out its own method for retaining the best outcome. It is
like a pretrained CNN model where the CNN layers are already written on
the pretrained model.

***Names of used Transfer Learning models ***

1.  **Vgg 16 (** oxford **)**

2.  **Vgg 19 (**oxford)

3.  **Resnet 50 (** Microsoft**)**

4.  **Resnet 152 (** Microsoft **)**

5.  **Resnet 152v2 (** Microsoft **)**

6.  **Inception v3** ( Google**)**

7.  **InceptionResnetv2 (** Google**)**

8.  **MobileNet v2 (** Google **)**

9.  **EfficientNetB0 (** Google Brain **)**

10. **DenseNet121 (** Cornell University **)**

***\
* | *Data Set* **

large set of retina images taken using [fundus
photography](https://en.wikipedia.org/wiki/Fundus_photography) under a
variety of imaging conditions. We took the dataset from Kaggle
[**\[8\]**](https://www.kaggle.com/datasets/sovitrath/diabetic-retinopathy-224x224-2019-data?select=colored_images).

0 - No DR 1 – Mild 2 – Moderate 3 – <span id="_Hlk139546352"
class="anchor"></span>Severe 4 - Proliferative DR

***Fundus Example images with each condition* :**

![](media/image4.png){width="8.150694444444444in"
height="4.65467738407699in"}

Our dataset contains a total of 3663 images. These images are contained
in 5 different directories as the disease No DR Mild Moderate Severe
Proliferative DR

***Dataset details :***

**No\_DR**: This category indicates the absence of diabetic retinopathy,
meaning there are no signs of the condition in the patient's retina.

**Mild DR**: This category represents the early stages of diabetic
retinopathy, characterized by the presence of mild abnormalities in the
blood vessels of the retina.

**Moderate DR**: This category signifies a progression of the condition,
where there are more pronounced abnormalities in the blood vessels of
the retina.

**Severe DR**: This category indicates a significant advancement of
diabetic retinopathy, with severe abnormalities in the blood vessels of
the retina. At this stage, the risk of vision loss increases.

**Proliferative DR**: This category represents the most severe and
advanced stage of diabetic retinopathy. It involves the growth of
abnormal blood vessels in the retina, which can lead to vision loss and
other complications.

**\
**

> ***Proposed Methodology***

![](media/image14.jpeg){width="7.45in" height="7.406592300962379in"}

**|**As the above image tells, we have preprocessed our datasets and
transforms into two category, **DR** and **No\_DR** for accurate results
.Then **augmented** the images to overcome overfitting and for our
**Ann** we have initialized weights with **Imgenet** and feed these
images into the pretrained Cnn Transfer Learning models .We have used
**Relu** Activation function for Hidden Layers and **sigmoid** for final
layer. We have used BinaryCrossEntrophy for calculating loss and
**ADAM** Optimizer for updating and optimizing Gradients. At last, we
compared all the model’s outcome by the evaluation metrices and reached
our conclusion.

> ***Evaluation Metrices***

***Training Loss vs Validation Loss:***

Loss measures model performance on training data, while validation loss
evaluates performance on unseen data. Decreasing loss and validation
loss simultaneously indicates good model learning. Increasing validation
loss while decreasing loss suggests overfitting, requiring adjustments.

***Training Accuracy:*** ***Validation Accuracy:***

***Test Accuracy:*** ***Test Loss:* *Precision***:

***Recall:*** ***F1 Score:***

![](media/image34.png){width="7.552403762029746in"
height="10.355555555555556in"}

***Result and Analysis Table(After 25 Epochs):***

  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Model Name**      **Training Loss**   **Training Accuracy**   **Validation**   **Validation**   **Test Loss**   **Test Accuracy**   **precision**   **Recall**   **F1 Score**
                                                                                                                                                                     
                                                                  **Loss**         **Accuracy**                                                                      
  ------------------- ------------------- ----------------------- ---------------- ---------------- --------------- ------------------- --------------- ------------ --------------
  Vgg16               **0.1033**          **96.64%**              **0.1088**       **95.86%**       **0.1115**      95.73%              95.82%          95.68%       **95.74%**

  Vgg19               **0.1222**          **95.82%**              **0.1201**       **95.51%**       **0.1218**      95.82%              95.91%          95.73%       **95.81%**

  Resnet 50           **0.2445**          **91.27%**              **0.2340**       **91.37%**       **0.2662**      90.88%              90.97%          90.93%       **90.94%**

  Resnet 152          **0.3246**          **87.47%**              **0.2738**       **88.99%**       **0.2743**      88.92%              88.92%          88.92%       **88.92%**

  Resnet 152V2        **0.0817**          **98.60%**              **0.1321**       **97.41%**       **0.0965**      98.34%              98.74%          97.67%       **98.20%**

  InceptionV3         **0.1156**          **96.85%**              **0.1532**       **96.35%**       **0.1246**      96.68%              96.01%          97.60        **96.79%**

  InceptionResnetV2   **0.1754**          **95.91%**              **0.1173**       **96.77%**       **0.1149**      96.58%              96.58%          96.53%       **96.55%**

  mobilenetV2         **0.1683**          **97.25%**              **0.2046**       **96.98%**       **0.2318**      96.53%              95.78%          97.06%       **96.41%**

  Efficient           **0.7384**          **54.32%**              **0.9335**       **48.60%**       **0.9279**      48.96%              48.96%          48.96%       **48.96%**
                                                                                                                                                                     
  NetB0                                                                                                                                                              

  Dense Net121        **0.1031**          **97.43%**              **0.0733**       **97.55%**       **0.0771**      97.39%              97.43%          97.29%       **97.35%**
  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

The python libraries such as TensorFlow
[**\[9\]**](https://www.tensorflow.org/guide) and keras Tuner
**[\[10\]](https://keras.io/api/applications/%5d)** are used to
implement the models in this study. In the code we have imported the
datasets of fundus images and augmented them. To overcome Overfitting,
We have used some regularization methods for augmentation we have used
zoomed scale and rotated the images. When we feed the images to the
transfer learning models and fit the model with our data set. Then find
validation accuracy validation loss along with training accuracy
training loss. From the confusion matrix we have found precision recall
then by calculation f1 score

We had 5 different fundus image classes, we have separated them or
partitioned then into 2 classes for binary classification.

By augmentation the Number of images increased above 5000 from 3663. We
have selected 64 as the batch size. And the number of epochs is fixed to
25. Our main goal was To have higher test accuracy, training accuracy,
and validation accuracy. Although in the medical field image
classification. The recall is more important than anything else. Almost
Maximum of models have minimum of 90% of recall.

Almost maximum of our models predicted 95 out of 100 images correctly.
our goal was to achieve lower validation loss and higher recall value.
vgg 16, vgg 19 models Got 95% of validation accuracy .Resnet models have
identified diabetic retinopathy very well. Resnet models have good test
accuracy, recall, precision, and f1 score. Dense net models with 121
layers r also very effective eat has second Louis training loss and the
lowest validation laws with highest validation accuracy along with
lowest test loss. Dense net models worked very well in diabetic
retinopathy fundus image classification. It also has 97.39% of test
accuracy 97.43% of precision 97.29% of recall and 97.35% of F1 score.

> ***Conclusion***

For our project we take the help of Google Colaboratory . We use the
**Tesla T4** GPU , . 24 GB of DDR5 Ram and 110 GB of storage to run our
codes.

This study investigated the performance of Ten distinct transfer
learning models . with preprocessing and data augmentation approaches,
In this study we got encouraging findings on our DR classification .

-   Overall ,among the 9 metrics **Resnet** **152** **V2** has higher
    performance in 6 of them.

    It has a training accuracy of **98.60 %** , lowest training loss of
    0.0817 ,highest test accuracy of **98.34%,** precision of **98.74%**
    , Recall of **97.67%** , F1 score of **98.20%** . So as of now
    **Resnet 152 v2** model is on top. In the second we found the model
    **DenseNet121.**It has got **97.43%** Training accuracy ,and lowest
    validation loss **0.0733.** , High Test accuracy of **97.39%** and
    great f1 score of **97.35% .**

Other Inception Models and ResNet Models also performed well.
**EfficientNetB0** was the lowest scorer. InceptionV3 has scored
**96.68%** of test accuracy,

I**nceptionResnetV2** scored **96.58%** **, mobilenetV2** scored
**96.53%** of test accuracy.

**So overall Resnet 152 V2 worked best for our dataset.**

In conclusion, diabetic retinopathy is a serious complication of
diabetes that affects the retina and can lead to vision loss if left
untreated. Early detection and timely intervention are crucial in
managing the condition effectively. Regular eye examinations, adherence
to diabetes management strategies, and lifestyle modifications play a
pivotal role in preventing and minimizing the impact of diabetic
retinopathy. Close collaboration between patients, healthcare providers,
and eye specialists is essential to ensure comprehensive care and
optimize visual outcomes for individuals with diabetic retinopathy.

***Future Work***

In future work for transfer learning in diabetes risk assessment and
retinal biomarker detection, researchers can focus on exploring advanced
deep learning architectures specifically designed for retinography
analysis. Integrating multi-modal data, such as patient demographics and
clinical information, alongside retinal images, can improve prediction
models.

The availability of large-scale, diverse datasets will be crucial for
training and evaluating these models, ensuring generalizability across
different populations. Additionally, developing methods for explaining
ability and interpretability of the models' decisions can enhance trust
and acceptance in clinical settings.

The translation of transfer learning models into real-world clinical
practice, validation studies in diverse patient populations, and
assessing their impact on healthcare outcomes are vital for their
practical utility.

> **| References**

1.  Department of Computer Engineering, College of Engineering and
    Petroleum, Kuwait University, P.O. Box 5969, Safat 13060, Kuwait

    *Appl. Sci.* **2023**, *13*(9),
    5685; [**https://doi.org/10.3390/app13095685**](https://doi.org/10.3390/app13095685)

2.  [**https://arxiv.org/abs/1905.07203**](https://arxiv.org/abs/1905.07203)

3.  Comparative Analysis of Different Models for Diabetic Retinopathy Classification. Lavanya Bagadi, E. Pavankumar, A. Likitha, K. Niranjan & B. Nani . **\[[Reference](https://link.springer.com/chapter/10.1007/978-981-16-8512-5_28)\]**
    ========================================================================================================================================================================================================================================

4.  “The effect of model size on accuracy”.Parhaam Honolulu, Hawaii,
    United States
    **\[[Reference](https://www.kaggle.com/code/the314arham/the-effect-of-model-size-on-accuracy/notebook#ABSTRACT)\]**

5.  DL-Diabetic RetinopathycDetection-95%Acc-CN. Data Scientist | AI
    Researcher at freelanceAbadan, Khuzestan Province, Iran
    [**\[Reference\]**](https://www.kaggle.com/code/parisanahmadi/dl-diabetic-retinopathycdetection-95-acc-cnn#Diabet-Retinopathy-Detection-Section)

6.  “Diabetic Retinopathy Detection and Classification” Student at Birla
    Institute of Technology Ranchi, Jharkhand, India
    **\[<https://www.kaggle.com/code/akshat0007/diabetic-retinopathy-detection-and-classification>
    \]**

7.  “Deep Transfer Learning Models for Medical Diabetic Detection” Nour
    Eldeen M. Khalifa, Mohamed Loey, Mohamed Hamed N. Taha, and Hamed
    Nasr Eldin T. Mohamed
    [**\[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7085308/\]**](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7085308/)

8.  Diabetic Retinopathy 224x224 (2019 Data)
    Reference[**:\[https://www.kaggle.com/datasets/sovitrath/diabetic-retinopathy-224x224-2019-data?select=colored\_images\]**](https://www.kaggle.com/datasets/sovitrath/diabetic-retinopathy-224x224-2019-data?select=colored_images)

9.  TensorFlow Reference \[<https://www.tensorflow.org/guide>\]

10. Keras Tuner Reference
    **\[[https://keras.io/api/applications/\]](https://keras.io/api/applications/%5d)**

