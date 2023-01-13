# Age-and-Gender-Classification
I use two famous facial dataset for this project, UTKFace and UAGD dataset. UTKFace give me more than 16.300 images that labeld and cropped which would reduce tons of time for preprocessing. Meanwhile, UAGD supply more stability proportion in age and gender which will become a good dataset for training. The only problems is UAGD also uses data from UTKFace, so after rename and remove all UTKFace image in UAGD dataset. Combine all together I have a dataset with 16.383 images from UTKFace for train, 4.342 images from UAGD for test, 2.235 images from UAGD for validation.

The train dataset includes images of people form 1 to 116 years old. Splitting dataset in 10 class of age:

![image](https://user-images.githubusercontent.com/100464098/212265497-26fab234-4cc9-4c0e-9f73-4d1cc4347935.png)

CNN architecture for classify age:

![image](https://user-images.githubusercontent.com/100464098/212265780-9b0389db-69c6-43e4-a6f3-960b3ffd7cf8.png)

Using the trained weigth from the architecture above to train for classify gender:

![image](https://user-images.githubusercontent.com/100464098/212266244-da0a6662-6764-4afc-9ac4-580bba34c2fc.png)

![image](https://user-images.githubusercontent.com/100464098/212266705-71dfe58f-3194-4d2f-907b-886a703e7370.png)

![image](https://user-images.githubusercontent.com/100464098/212266774-bf93b86f-f93b-4d88-b98c-26ae83301b40.png)
