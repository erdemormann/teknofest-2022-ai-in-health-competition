<p align="center">
  <a href="https://www.teknofest.org/en/competitions/competition/34">
    <img src="https://cdn.teknofest.org/media/uploads/2023/02/22/saglkta-yz.png" alt="Teknofest" width="270">
  </a>
</p>

# Teknofest 2022 Ai in Health Competition

## Teknofest 2022 - Data Preprocessing Project 

**Preparing Mammography Images for the ResNet Algorithm and Performing Preprocessing of Mammography Images for the Teknofest 2022 Health Artificial Intelligence Competition.**

Read this in other languages: [Turkish](https://github.com/erdemormann/teknofest-2022-ai-in-health-competition/blob/main/README.tr.md)

I would like to share with you the data preprocessing project I developed as part of the Health Artificial Intelligence Competition at the previous Teknofest event. Within the scope of the project, I have developed specialized preprocessing codes for the processing and analysis of .dcm extension medical image data. I am excited to share these codes with you.

In my project, I developed image preprocessing steps to better process and analyze healthcare data. With these codes, I converted .dcm extension files to .png format, cropped out unwanted text details such as undesirable annotations on the image for deep learning algorithms, resized the images for the ResNet algorithm, and reduced differences between color channels. Additionally, to maintain data integrity, I conducted image naming processes and file arrangements.

During the algorithm development phase, I worked with a smaller dataset, and subsequently, the algorithm was applied to the entire dataset. The complete dataset consists of 16,000 .dcm files.

**Key Features:**

+ .dcm files were converted to .png format.
+ The angle information of the written photograph on the images was cropped from the image
+ Outlier images were removed to enhance the algorithm's training and learning processes.
+ The dimensions of the images were normalized to ensure data integrity.
+ The equalization of different color channels and enhancement of image quality were aimed.
+ Data management was facilitated through customized naming and file organization.
+ The developed codes automated the data preprocessing steps and made them more suitable for analysis.


📁 teknofest_data_preprocessing
├── 📁 test ➜ Raw data folder
├── 📁 Data ➜ Target folder for classified data
└── 📄 siralama.xlsx ➜ Excel table information

  

**Through this project, we have taken a step towards better management and processing of healthcare data.**

I have shared my code on GitHub, aiming to create a resource that other colleagues working in this field can benefit from. I hope it will be useful for those who are undertaking similar work.

