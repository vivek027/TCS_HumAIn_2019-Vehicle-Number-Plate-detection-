# TCS_HumAIn_2019-Vehicle-Number-Plate-detection
Problem statement: Identify the license place in the image and do an OCR to extract the characters from the detected license plate.
Category: Object detection & OCR.

Steps to run this code:-

1. Install Tesseract OCR in your machine from the given url https://github.com/tesseract-ocr/tesseract/wiki/Downloads and restart system if it is not working after installing this.

2. Import 
    -numpy            : Numpy library to generate the coordinates of the image.    
    -pandas           : Panda library to read JSON.
    -PIL              : To make the changes in the images.
    -pytesseract      : To extract the characters from the number plate.
    -urllib           : To visit the url available in the JSON.
    -cv2              : To read images and make changes.
    -json             : To read JSON.

3. Download the code and put both the files(code and data set) in the same directory, after importing all the libraries.

4. The code will generate the result for the given data set.

5. exit.

NOTE:- As data-set contain urls the result will take some time to evaluate each query depending upon the internet speed.
