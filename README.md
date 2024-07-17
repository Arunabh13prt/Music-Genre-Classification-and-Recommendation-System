# Music Genre Classification and Recommendation System

A Music Genre Classification System and Recommendation System using the [GTZAN dataset](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification) available on Kaggle.

Preprocess.ipynb preprocesses the GTZAN 30s audio data, by applying data augmentation techniques such as Time stretch, addition of noise, and Pitch shift for artificially increasing the size and the diversity of the training dataset. The 30s audio data has also been segmented in 10 parts each of 3s long, for added reliability and more accurate prediction. Finaly, this augmented data is converted to MFCC features and stored in a JSON file, which can be used by the model.

Deep Learning techniques such as Convulutional Neural Networks has been used to achive the Music Genre classification.
Cosine similarity technique has been applied for the Recommendation system.

This model has a consistent accuracy of above 90%, with a maximum accuracy of 93.3%.
![image](https://github.com/user-attachments/assets/47e5055a-c175-4c7e-b717-823c3cb7259a)



This is a project done as part of my research at PESU C3I internship 2024.
