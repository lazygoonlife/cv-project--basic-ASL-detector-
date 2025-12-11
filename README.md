# cv-project--basic-ASL-detector-
![Demo Screenshot or GIF](results/demo.gif)
my ASL detector identifis ASL hand sign images from the internet
10/11/25, 12:00 pm Final Project Guide - Colab

## Team Members
-Justin Davis

## Project Tier
---Tier 1- this project creates the environment ready for YOLO training and prepares the raw data into a format suitable for the model
by downloading datasets, indexing images, and splitting the dataset into train, validation, and test sets.
## 🎯 Problem & Solution
### The Problem
[2-3 sentences: What real-world problem does this solve?] People who rely on ASL ussaly have a harder time communication with people who can speak.
every time someone trys to interact with a deph person without someone to translate it ends up tuning a basic intraction into a guessing game.
### Our Solution
[2-3 sentences: How does your system solve it?] this porject allows for people who rely on ASL to communicate to interact with people who dont know any ASL.
this creates more chnaces for people to make more meaningful relationship and allows for more people to efftively share ideas.
### Impact
[Who benefits? How much time/money saved? What's the value?]
---this project benifits both deph and normal people as now we are able to intract efftively.
## 🔧 Technical Details
### Approach
- **Task**: Image Classification
- **Model**:  YOLOv8n-cls (YOLOv8 nano for classification)

- **Framework**: Ultralytics 
- **Key Libraries**:
shutil
sklearn.model_selection (train_test_split)
numpy
tqdm.notebook (tqdm)
PIL (Image, ImageFile)
kagglehub
ultralytics (YOLO)
sklearn.metrics (accuracy_score, classification_report, confusion_matrix)
matplotlib.pyplot
seaborn
pandas
### System Architecture
[Include your system diagram - image or flowchart]
