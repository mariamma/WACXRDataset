## WA CXR Dataset

WhatsApp became a common media for radiologists to share and discuss the interpretation of radiological images. During COVID-19, many AI systems emerged to provide radiological interpretation services through WhatsApp. One main challenge with the messgaing application is their compression of images. For example, WhatsApp compresses the images as much by >90%. When we tested the SoTA with the Whatsapp compressed images, they resulted in flipping of predicted labels from normal to covid-19 or viceversa and also in spurious features. It is important to make the architectures robust to these image perturbations. Currently, there are no publicly available Whatsapp compressed COVID-19 Data. Whatsapp ChestXRay (WA CXR) dataset is a first ever opesoure whatspp dataset consiting COVIDX-Ray images obtained through messaging application such as WhatApp. 


To generate this WA CXR Dataset, we considred COVID-NET Dataset (Wang et al) and passed it through WhatsApp messaging application

covid_binary_test folder contains test images collected from [COVIDNet dataset](https://github.com/lindawangg/COVID-Net), which has ethics committee approval and informed consent. covid_binary_test_whatsapp folder contains images in covid_binary_test passed through WhatasApp. COVID-19 images are present in 1_COVID-19 folder and non-COVID images are present in 0_NON_COVID folder.


### Acknowlegements

We would to acknowledge XraySetu, IISC Bengaluru, Niramai Health Analytix for their support in conducting this research

### Contact
If you want to use our dataset or for any queries/colloborations, please contact:

mariammaa@iisc.ac.in



