# QR-Code-Detection-and-Extraction  

This is a project of Cours "Visual Scene Real Time Analysis" given by Prof. Fabien Moutrade from MINES ParisTech and by Prof. Hao Li from Shanghai Jiao Tong University.  
An algorithm based on traditional computer vision technics is developed to localize the QR code in the image and extract the binary informations.  

The general workflow is as following:    
- 1.Preprocessing: binarization  
- 2.Localize the four corners of QR code in the image  
- 1. Morphological opening operation  
- 2. Morphological gradient operation  
- 3. RANSAC to find four boundaries  
- 4. Compute the four corners based on boundaries  
- 3.Compute the Homography Transformation and transform the QR code into a square zone  
- 4.Rotate the QR code and Extract Informations  


![original image](https://github.com/JiadongWANG94/QR-Code-Detection-and-Extraction/blob/master/image_report/original_photo.png)
![morphological opening](https://github.com/JiadongWANG94/QR-Code-Detection-and-Extraction/blob/master/image_report/opening.png)
![homography transformation](https://github.com/JiadongWANG94/QR-Code-Detection-and-Extraction/blob/master/image_report/homography.png)
![data extracted](https://github.com/JiadongWANG94/QR-Code-Detection-and-Extraction/blob/master/image_report/data.png)
![reconstructed](https://github.com/JiadongWANG94/QR-Code-Detection-and-Extraction/blob/master/image_report/reconstructed.png)
