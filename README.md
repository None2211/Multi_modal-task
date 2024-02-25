# multitask-modal-enhancement method
## Overview

### Image Data
The original dataset is from [Kaggle The Chinese Mammography Database (CMMD) 2022](https://www.kaggle.com/datasets/tommyngx/cmmd2022), which includes the pathological classification label and mammography classification label. 
We revised this dataset, and it now has corresponding lesion masks for segmentation.

### Alignment

```sample of caption.txt``` is sample of caption for pretrained alignment task.

The training of alignment referred to [Simple CLIP](https://github.com/moein-shariatnia/OpenAI-CLIP?tab=readme-ov-file)

```alignment```folder contains hyperparameters and model selection.
Here, we used the ResNet 50 and Distilbert as image encoder and text encoder respectively.

