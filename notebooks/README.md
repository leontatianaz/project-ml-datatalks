# Dataset Guide – FER-2013

## Overview
This project uses the **FER-2013 (Facial Expression Recognition 2013)** dataset to train a deep learning model capable of recognizing human emotions from facial images.

The dataset contains grayscale facial images labeled with **7 emotion categories**:
> `Angry`, `Disgust`, `Fear`, `Happy`, `Sad`, `Surprise`, and `Neutral`.

## Source and License
- **Source:** [Kaggle – FER-2013 Dataset](https://www.kaggle.com/datasets/msambare/fer2013)  
- **License:** Open for research and educational purposes.  
- **Author / Curator:** Manish Sambare  

Please review the dataset license on Kaggle before using it for commercial projects.

## Download Instructions (Kaggle API)

1. Make sure you have a Kaggle account
2. Create a Kaggle API token
3. Place you `kaggle.json` in your current working directory, then run:

```python
!mkdir -p ~/.kaggle
!cp /workspaces/project-ml-datatalks/notebooks/kaggle.json ~/.kaggle/
!chmod 600 ~/.kaggle/kaggle.json
!ls -l ~/.kaggle
```

Then, to download it run:
```python
!kaggle datasets download -d msambare/fer2013 -p data/ --unzip
```
