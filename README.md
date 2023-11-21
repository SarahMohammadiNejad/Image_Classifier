# Image_Classifier

In this program, first you gather a bunch of images for each object you want to classify. For this you first choose several objects and capture several iage fro each object. The codes for capturing the images are located in folder "image_capture" and can be ran using the following command:
cd image_capture
python3.9 capture.py data/pen



Then after capturing and saving images in separate folders you can run the jupyter notebook to learn your classifier. Just first you need to provide the nae of objects to the code by changing this line:

objects = ['suncream','adapter','thermometer','onion','lime','teabag','almonds','fork','apple','banana']


