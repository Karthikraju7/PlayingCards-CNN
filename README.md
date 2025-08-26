# Playing Cards Classifier

This is a **PyTorch-based CNN project** to classify playing card images. (For Learning Purpose)  

---

## Dataset

We use the **Playing Cards Image Dataset** from Kaggle:

[https://www.kaggle.com/datasets/gpiosenka/cards-image-datasetclassification](https://www.kaggle.com/datasets/gpiosenka/cards-image-datasetclassification)

- The dataset contains images of **52 standard cards + Joker**, totaling **53 classes**.  
- Dataset is split into **train, validation, and test** folders.  

---

## Features

- Uses **EfficientNet-B0** as a base model from [timm](https://github.com/rwightman/pytorch-image-models)  
- Replaces the final layer to output **53 classes** for this dataset  
- Trains using **CrossEntropyLoss** and **Adam optimizer**  
- Uses **PyTorch DataLoader** with batch size of 32  
- Includes **training and validation loops** with loss tracking  
