# Skin cancer Melanoma detection project
> multiclass classification model using a custom convolutional neural network in TensorFlow. 


## Table of Contents
* [General Info]: 
- To build a CNN based model which can accurately detect melanoma.
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here. 
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- What is the background of your project?
building a CNN based model which can accurately detect melanoma.

- What is the business problem that your project is trying to solve?
A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- What is the dataset that is being used?

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis: first model(after training the first model)
: seems like we have model overfitting as the validation loss curve is completely going upward after 8th or 9th epochs.

- Conclusion 2 from the analysis: second model(after training with the data augmentation)
: clearly we can see that the data augmentation has resolved the issue of overfitting in both the plots the accuracy is still needed to be improved. 

- Conclusion 3 from the analysis: Data imbalance
: seborrheic keratosis - has the least number of samples
: pigmented benign keratosis - has the most number of samples

- Conclusion 4 from the analysis: after using data augmentor(resolving data imbalance)
: may be, this overfitting be resloved using hyperparameter. 
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas     
- seaborn    
- matplotlib
- numpy     
- TensorFlow
- Keras

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...


## Contact
Created by [@gautamk2190] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->