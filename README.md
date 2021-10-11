#Automated Screen Shots saver

This is mini python project is aimed  to reduce the time in  taking  individual screenshots.


It allows to take automated screenshots during an interval only when there is a difference between the previous and current image.The image is then saved to a user specified directory
.There is also an option for taking screenshots with reference to a time table in which screen shots are taken and stored in a directory having the subject name in a specified duration.

Modules used:

tkinter  for GUI elements
pyAutoGui is used for capturing screen shot
SSIM algorithm from skimage is used for diffrentiating two images
open CV  for processing the images
numpy  for converting image to a numpyarry for processing
os for creating and processing the  files 
