# Car-and-lisence-plate-detection and deployment
## **I have used yolov3 for the project**<br>
# -----------------------
## Structure
 -- **image_and_annotations_zip_file** folder contains the zip file which contains the images and annotations txt files<br>
 -- **weights_and_config_files** folder contains my trained weights and config file<br>
 -- **Copy_of_liscence_yolov3.ipynb** is the file which contains the entire code<br>
 -- **prediction** folder contains my predicted images by the model<br>
 -- **deployment** folder conatains all the files neccessary to deploy model using flask<br>
# -----------------------

## Step 1
Firstly annotate images<br>
I have used LabelImg tool for annotating<br>
Link for LabelImg: https://github.com/tzutalin/labelImg<br>

## Step 2
compress(zip) the images and annotations txt file and upload it to google drive<br>

## Step 3
Follow the codes of **Copy_of_liscence_yolov3.ipynb**<br>

# **DEPLOYMENT**<br>
I have used flask to deploy the model.
The yolov3_deployment.ipynb file contains the deployment code.


