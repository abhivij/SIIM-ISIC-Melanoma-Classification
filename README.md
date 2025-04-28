#  Melanoma Classification
Identify melanoma in images of skin lesion

![header](https://github.com/user-attachments/assets/9489d139-d990-4f93-aa77-ae21fbdd7bd6)

-------------------------------------------------------------------------------------------------------

**📝 Task** : Classify image and associated patient information into malignant or benign. i.e. predict the probablity that the image is malignant.

**📊 Evaluation metric** : Area Under the ROC curve between the predicted probability and the observed target.

ℹ️ Please refer to https://www.kaggle.com/competitions/siim-isic-melanoma-classification for more details

-------------------------------------------------------------------------------------------------------

📈 **Best Score**
- Private score : 0.9075 (calculated with approx 70% of test data)
- Public score : 0.9227  (calculated with approx 30% of test data)
- Validation split score : 0.918999 (validation data obtained using 80-20 split of train data ensuring equal proportion of target column values and non-overalapping sets of patient-ids)
- A multimodal architecture accepting image and tabular data as input was used. EfficientNetV2 was used as the base model 

  -------------------------------------------------------------------------------------------------------

**Main contents**
- [Melanoma Classification notebook](https://github.com/abhivij/SIIM-ISIC-Melanoma-Classification/blob/main/melanoma-classification.ipynb)
  (The ipython notebook contains images and other details, so please reload in case it does not render properly. Alternatively view the code on Kaggle in the link below)
- [Submission scores](https://github.com/abhivij/SIIM-ISIC-Melanoma-Classification/blob/main/submission_scores.png)
- [Scores of all runs](https://github.com/abhivij/SIIM-ISIC-Melanoma-Classification/blob/main/results.txt)

-------------------------------------------------------------------------------------------------------

The notebook provided here can be directly accessed and run from :
- [Kaggle - Melanoma Classification](https://www.kaggle.com/code/abhivij/melanoma-classification)
