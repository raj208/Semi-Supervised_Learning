# Semi-Supervised_Learning

**Note:** Semi-Supervised Learning has not yet been applied to the model. I'm currently working on it and will update the project as I make progress.

## Models

### Model-1: Fully Supervised Learning (without Augmentation)
- **Description**: This model is trained using the **entire Brain Tumor dataset** (100% of the data).
- **Accuracy**: 96%

### Model-2: Supervised Learning (50% Data) (without Augmentation)
- **Description**: This model is trained using **50% of the Brain Tumor dataset**.
- **Accuracy**: 84%
- **Goal**: The current accuracy is 84%, but I aim to improve it to exceed **93%** by experimenting with model adjustments and optimization techniques.

### Model-3: Supervised Learning (50% Data) 
- **Description** : This model is trained using **50% of the Brain Tumor dataset** with **data augmentation**, effectively increasing the dataset size to **twice its original length**.
- **Accuracy**: 94%

### Model-4: Supervised Learning (50% Data) (without Augmentation)
- **Description** : This model is trained using **50% of the Brain Tumor dataset** with pre-trained Model **EfficientNetB0**.
- **Accuracy**: 93%

### Model-5: Supervised Learning (50% Data)
- **Description** : This model is trained using **50% of the Brain Tumor dataset** with pre-trained Model **EfficientNetB0**.
- Data has been **Augmentation**,effectively increasing the dataset size to **twice its original length**.
- **Accuracy**: 94%



## Dataset
- The dataset used for training is a **Brain Tumor Dataset**,
- There are total **7022 files** in the dataset,
- [Dataset Link](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)



