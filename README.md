# Machine Learning project: emotion recognition

### Introduction ###

Emotion recognition is a crucial domain within human-computer interaction research, focusing on understanding and classifying human emotions. Past studies on the matter have classified emotions into seven groups: anger, fear, happiness, sadness, contempt, disgust, and surprise. All emotions could be expressed in terms of valence (positive or negative) and arousal (intensity). In the present study, we only focus on valence, deeming emotions as either positive or negative, based on the valence coefficient provided for each image. This goal is achieved through a classification method, where the aim is to assign input data to specific categories or classes. 
Furthermore, transfer learning is a significant component of the project. In the latter stages, a key strategy is to leverage transfer learning by using pretrained models. These models, initially trained on extensive datasets for general tasks, are fine-tuned to perform specific tasks relevant to the project. This approach accelerates training and enhances model performance, particularly in cases where data is limited or specialized.
In the current study, transfer learning is applied to both mask detection and emotion recognition tasks. For mask detection, a pretrained model is fine-tuned on RealLifeMask, a mask-related dataset, enhancing its ability to classify mask presence. Similarly, for emotion recognition, the pretrained model is adapted to work with images where the masks are generated artificially, improving its ability to recognize emotions despite the presence of masks.
Therefore, the presence of facial masks in the current project creates a dual challenge: first, training a model to discern whether a person in an image is wearing a mask; and second, leveraging the previously trained models to categorize emotions as positive or negative.

---

### Requirements to run the project ###

An environment with:
- Python 3.8 or later versions
- scikit-learn 1.2 or later versions
- tensorflow 2.0 or later versions
- numpy 1.19 or later versions
- seaborn 0.8 or later versions
- matplotlib 3.8.1

---

### How to run the project ###

Download the zip folder containing the .ipynb file and the dataset. Modify the path to the directory in the .ipynb file to your actual directory. I advise you to run the project on Google Colab, due to the specifics in mounting content. If you decide to, grant access to your Google Drive profile, where the dataset has to be present, to Google Colab.
Otherwise, with minor adjustments to the directory path, the file can be run on other IDEs.
  

