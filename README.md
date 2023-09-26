# Open-CV-Sessions
Open CV Live session Optimization's and Real time working Samples
Open CV- Computer Vision 

gathering data
data processing
model training
model evaluation

Libraries:
Numpy 
Pandas

Installation:
pip install opencv-python

Steps:
inputting the image to make it accessible to the computer
Extracting RGB Values of each pixel
Resizing the image for Operation 
image Recogonitation/ detection algorithms
Adding artifacts that help with the above step
displaying the result


Functions:
cv2.imread() -used to input an image to work with
cv2.imshow() -Displays the image in the working environment
cv2.imwrite() -Write any change to the actual image


Syntax:
cv2.imread(file path,flag)
File path - Denotes the location of the image to be read
flag - specifies the way in which to read the image
return  -return an image that is loaded  from the specified location


grey scale image contain only one color like black and white


cv2.imread(windowname ,image to be displayed)

Syntax:

windowname--> Nameof the window in which to display the file in
return--> no return values but display the image on screen


cv2.imwrite(filename,image to be saved) 
file name-->name of the file that will be saved 
Return-->return a boolean if the image saved sucessfully 


Face Detection:

1. Face Detection -Convert Datas to vectors 
2. Deature Extraction

Face embedding is used with each face to convert it into a vector and this technique is called as Deep Metric Learning 
3.Training a neural network
4.Feature map across the face
5.Face embeddings for images are obtained after training
