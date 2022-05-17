# Dacon-AI-Challenge-Anomaly-Detection
데이콘에서 진행된 [이상치 탐지 알고리즘 경진대회](https://dacon.io/competitions/official/235894/overview/description)에 대한 코드입니다.
## Preprocessing(image)
* Resize(384x384)
* Augmentation(RandomAffine, RandomHorizontalFlip, RandomVerticalFlip)
* Normalization
## Model
* Efficientnet_b4
## Training
* Stratified K-fold cross validation(k=5)
* Save model's best weight when score is highest
## Inference
* K-fold Model Ensemble(Soft Voting)
## Improvement
* tta appliance(Test Time Augmentation)
* model search
* GPU upgrade
* varius augmentation
