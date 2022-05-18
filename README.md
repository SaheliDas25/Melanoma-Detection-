# Melanoma-Detection-

# Problem statement: 

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion


# Project Pipeline

1.Data Reading/Data Understanding → Defining the path for train and test images 
2. Dataset Creation→ Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180.
3. Dataset visualisation → Create a code to visualize one instance of all the nine classes present in the dataset 
4. Model Building & training : 

            1. Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values                    between (0,1).
            2. Choose an appropriate optimiser and loss function for model training
            3. Train the model for ~20 epochs
            4. Write your findings after the model fit. You must check if there is any evidence of model overfit or underfit.
            5. Chose an appropriate data augmentation strategy to resolve underfitting/overfitting 
            6. Model Building & training on the augmented data :
            7. Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values                    between (0,1).
            8. Choose an appropriate optimiser and loss function for model training
            9. Train the model for ~20 epochs
            10. Write your findings after the model fit, see if the earlier issue is resolved or not?
            11. Class distribution: Examine the current class distribution in the training dataset 
                      - Which class has the least number of samples?
                      - Which classes dominate the data in terms of the proportionate number of samples?
            12. Handling class imbalances: Rectify class imbalances present in the training dataset with Augmentor library.
            13. Model Building & training on the rectified class imbalance data :
            14. Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values                    between (0,1).
            15. Choose an appropriate optimiser and loss function for model training
            16. Train the model for ~30 epochs
            17. Write your findings after the model fit, see if the issues are resolved or not?
 

