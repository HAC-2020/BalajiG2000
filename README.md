# BalajiG2000

This project was prepared during the Hack Against Covid 2020 .

# AUTOMATED COVID 19 PREDICTOR

## ABOUT

A neural network binary classifier which can predict the presence of COVID 19 using X-Ray image of chest. The proposed model is developed to provide accurate diagnostics for binary classification (COVID vs. No-Findings).

## ABSTRACT

The novel coronavirus 2019 (COVID-2019), which first appeared in Wuhan city of China in December 2019, spread rapidly around the world and became a pandemic. It has caused a devastating effect on both daily lives, public health, and the global economy. It is critical to detect the positive cases as early as possible so as to prevent the further spread of this epidemic and to quickly treat affected patients. The need for auxiliary diagnostic tools has increased as there are no accurate automated toolkits available.

Recent findings obtained using radiology imaging techniques suggest that such images contain salient information about the COVID-19 virus. Application of advanced artificial intelligence (AI) techniques coupled with radiological imaging can be helpful for the accurate detection of this disease, and can also be assistive to overcome the problem of a lack of specialized physicians in remote villages.

In this project, a new model for automatic COVID-19 detection using raw chest X-ray images is presented. The proposed model is developed to provide accurate diagnostics for binary classification (COVID vs. No-Findings). This model produced a classification accuracy of 98.08% for binary classes.I implemented 17 convolutional layers and introduced different filtering on each layer.

## VALIDITY

The most common test technique currently used for COVID-19 diagnosis is a real-time reverse transcription-polymerase chain reaction (RT-PCR). Chest radiological imaging such as computed tomography (CT) and X-ray have vital roles in early diagnosis and treatment of this disease . Due to the low RT-PCR sensitivity of 60%–70%, even if negative results are obtained, symptoms can be detected by examining radiological images of patients . It is stated that CT is a sensitive method to detect COVID-19 pneumonia, and can be considered as a screening tool with RT-PRC . CT findings are observed over a long interval after the onset of symptoms, and patients usually have a normal CT in the first 0–2 days . In a study on lung CT of patients who  survived COVID-19 pneumonia, the most significant lung disease is observed ten days after the onset of symptoms .

## HISTORY 

At the beginning of the pandemic, Chinese clinical centers had insufficient test kits, which are also producing a high rate of falsenegative results, so doctors are encouraged to make a diagnosis only based on clinical and chest CT results . CT is widely used for COVID-19 detection in countries such as Turkey, where a low number of test kits at onset of the pandemic were available.

Researchers state that combining clinical image features with laboratory results may help in early detection of COVID-19 . Radiologic images obtained from COVID-19 cases contain useful information for diagnostics. Some studies have encountered changes in chest X-ray and CT images before the beginning of COVID-19 symptoms. Significant discoveries have been realized by investigators in imaging studies of COVID-19.

## Technology Stack
* Python
* Deep Learning
* Neural Networks
* Web Scraping
* Data Visualization
* Pandas and Numpy
* Fastai

## Challenges Faced

The typical clinical features of COVID-19 include fever, cough, sore throat, headache, fatigue, muscle pain, and shortness of breath which is similar to pneumonia . So it was hard to distinguish data sets between Covid and the latter. And I faced difficulties during feature extraction . Also it was bit harder to increase efficiency of the model.
