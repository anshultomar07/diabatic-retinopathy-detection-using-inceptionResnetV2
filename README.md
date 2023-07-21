# Diabetic Retinopathy Detection using Inception Resnet V2
# How to run the code?
1. Download the dataset from https://ieee-dataport.org/open-access/indian-diabetic-retinopathy-image-dataset-idrid (if this link shows "403 Forbidden" then copy the link and paste it in your browser and run.)
2. Create two folders "test" and "train".
3. Upload the training images in train folder and testing images in test folder.
4. Rename the training csv file as "Training_labels.csv" and testing csv file as "Testing_labels.csv".

![image](https://github.com/anshultomar07/diabatic-retinopathy-detection-using-inceptionResnetV2/assets/108689719/b56bfc89-fbe1-4228-be9d-a0e4f6590da1)
![image](https://github.com/anshultomar07/diabatic-retinopathy-detection-using-inceptionResnetV2/assets/108689719/1e920012-77ac-4a22-9c95-adc589d63cfb)

After doing this just run the code in your system.

# What Is Diabetic Retinopathy?
Diabetic retinopathy is a form of eye disease caused by chronically high or variable blood sugar that is associated with diabetes. When the small blood vessels of the retina become compromised due to several years of high blood sugars, diabetic retinopathy occurs. Retinopathy is the catch-all word that encompasses any sort of damage to the retina of the eyes, which is one of the deepest tissues of the eye.
If left untreated, diabetic retinopathy (DR) can lead to vision loss and blindness, so it’s important to get a comprehensive eye exam at least once a year if you have diabetes. Getting treatment as early as possible, as well as taking steps to manage diabetes, can help prevent or delay vision problems.

# What the project does?
This project is helpful in detecting whether the eye is infected with the disease. If infected then in which stage it is.
In the project the severity of Diabatic Retinopathy is also considered. The severity is classified into 5 classes.
'0' - Healthy Eye
'1' - Mild  NPDR (Non-Proliferative diabetic retinopathy)
'2' - Moderate NPDR
'3' - Severe NPDR
'4' - PDR (Proliferative diabetic retinopath)

Terms:
NPDR - Nonproliferative diabetic retinopathy (NPDR), commonly known as background retinopathy, is an early stage of diabetic retinopathy. In this stage, tiny blood vessels within the retina leak blood or fluid. The leaking fluid causes the retina to swell or to form deposits called exudates.
PDR - Proliferative diabetic retinopathy (PDR) is the advanced stage of diabetic retinopathy. It involves the development of abnormal retinal blood vessels. The vessels may leak blood and fluid into the retina and neighboring structures, leading to vision loss.

# Pre-Processing of Colour Fundus Images:
1. Reduced the size of the images.
2. Increased the number of the images using Data Augmentation. Initially there were 413 images in the dataset. After Data Augmentation the number of images increased to 2857.

# Classification:
1. Inception Resnet V2 is used as model for training.
2. 'Adam' is used as optimizer.

# Future Scope
1. Accuracy of this may further be increased if we use some feature detection techniques.
2. Blood Vessel Detection and Exudate Detection can be used to increase the accuracy.
3. In future, with increase in dataset, the model can be trained with much more accuracy.
