# thesis-masds

This repository contains code for my Master's thesis "Predicting New York Times Bestselling Fiction Books Using Text & Image-Based Machine Learning." My published thesis can be found [here.](https://escholarship.org/uc/item/87c0s4wf)

The folder containing the data (tabular dataset and book cover images) can be found [here.](https://drive.google.com/drive/folders/1wecYWbD47ycbEK8nYZGCQporMWePNGSv?usp=share_link)

This repository contains the following .ipynb files:
- **EDA.ipynb** - This file contains code for exploratory data analysis.
- **nlp_modeling.ipynb** - This file contains code for the following models:
  - Text Model 1: Logistic Regression (TF-IDF)
  - Text Model 3: Naive Bayes (TF-IDF)
  - Text Model 4: Random Forest (TF-IDF)
  - Text Model 6: XGBoost (TF-IDF)
- **bertmodeling_all.ipynb** - This file contains code for the following models:
  - Text Model 2: Logistic Regression (BERT)
  - Text Model 5: Random Forest (BERT)
  - Text Model 7: XGBoost (BERT)
- **image_modeling.ipynb** - This file contains code for the following models:
  - Image Model 3: ResNet50
  - Image Model 2: MobileNet
  - Image Model 1: EfficientNet
  - Image Model 4: VGG16
- **modeling_clip_multimodal.ipynb** - This file contains code for the following models:
  - Image Model 5: XGBoost (CLIP)
  - Multimodal Model 1: XGBoost (TF-IDF + CLIP)
  - Multimodal Model 2: XGBoost (TF-IDF + ResNet50)
  - Multimodal Model 3: Logistic Regression (BERT + CLIP)
  - Multimodal Model 4: Logistic Regression (BERT + ResNet50)
