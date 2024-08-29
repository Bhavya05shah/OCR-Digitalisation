# OCR-Digitalisation
For processing_health_record file
<br>
I have inputted an image and extracted its horizonatl and vertical lines to form the table that was present in it
and finding the intersection points which are the points of intersection of the horizontal and vertical lines and hence adding new 
intersection points in the rows and columns if by chance they were missed during the processing 
<br>
<br>
The ML modle being used for the OCR detection in this initially was pytesseract but due to its low effeciency and accuracy i have
introduced Vision API but it needs a billing account to be worked on with 
<br>
<br>
Future Developments in this
<br>
Adding rotation and crop feature for the Opencv model 
<br>
Properly incorporatig the Vision API form google cloud
<br>
<br>
For easyOCR file
<br>
I have tried to incorporate the easyOCR to get some results
by using contours and manually trying to find the number of columns
<br>
<br>
For Image_processing file
<br>
Denoising and removing the borders of the image

