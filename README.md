# Captcha-Solver - Mosaic 2k20 - Round 1 
This captcha solver has been developed using deep learning and convolutional neural networks along with the help of OpenCv for letter segmentation. It can be used to recognize captchas consisting of different letters as well as numbers. The model was trained on Google Colab using the EMINST by_class dataset in the form of a csv file. The dataset was modified to remove similar characters such as X and x. The model was trained to achieve a validation accuracy of 97% and a test accuracy of 92%.

## Special features of this model - 
The special features of this model include :-  
  1. This model can recognize captchas consisting of letters and numbers rotated at a max. angle of 45 deg.
  2. It can be also used for captchas consisting of lots of noise in the form of lines and dots.
  3. Can detect captchas having letters of variable thickness and size
  
## Characters - 
The characters on which the model was trained are given in the file characters.txt.


To decode captchas you need to input the image paths in the decode_captchas.py file and run the file. The python libraries required for this are mentioned in the requirements.txt file. The csv file on which the model was trained is also available. A few sample captchas have also been provided in the sample captchas folder. This is the code that helped us win Mosaic 2k20 (Machine Learning event of the departmental fest of Electronics Engineering Society of IIT-BHU, Varanasi).
