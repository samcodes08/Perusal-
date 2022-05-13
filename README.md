# Perusal-
Identifying Figures and Figure Captions in Image-Based Documents

**Prerequisites**
1.Installation paths must be set as required
2.Creation of folders manually if the environment used is google colab. This means the folders that are used for saving extracted text and images from the input documents .

**Problem statement**
There is currently no system which can detect and understand figures in documents. This causes inconvenience to visually challenged individuals , people who cannot see the screen at that particular instance . This puts the above two domains in backseat in day to day functions. Also, to recognize huge dataset of image-based documents, there is no automated  system that can detect and analyze images, to work on this a lot of individual’s time is wasted.

**Approach** 
1. Extract the text and images from the document and save them in a folder
2. Perform Pre-processing steps
2a. Converting Image to gray 
2b. Blurring the image
2c. Thresholding the image
2d. Creating kernel 
2e. Dilating the image
3. Find Contours
4. Find contours with region of interest
5. Find captions 


**References**
Dataset(s) used : SROIE, Docbank 
[1]Huang, Z., Chen, K., He, J., Bai, X., Karatzas, D., Lu, S., & Jawahar, C. (n.d.). ICDAR2019 Competition on Scanned Receipt OCR and Information Extraction. https://arxiv.org/pdf/2103.10213v1.pdf

[2]DocBank: A Benchmark Dataset for Document Layout Analysis
Minghao Li, Yiheng Xu, Lei Cui, Shaohan Huang, Furu Wei, Zhoujun Li, Ming Zhou
https://arxiv.org/abs/2006.01038

![image](https://user-images.githubusercontent.com/96153900/166857815-c3115e05-7743-4185-b531-787785049618.png)




