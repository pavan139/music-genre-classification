# music-genre-classification

### Abstract
Music has a significant impact on people's lives. It brings people together who share similar interests, and it is the glue that bonds communities together. Music genres are labels created by humans that identifies the category of music. Music genre classification is one of the most popular machine learning applications. In this project, out of many algorithms we tested and analyzed, we found accurate results in these two following models: 1. XGBoost technique 2. Convolutional Neural Networks. Both the classifiers gave noteworthy results with great accuracy and least margin of error. Which suggests it can be used on real world data as well.

### Environment Setup
#### Anaconda Installation
1. Install Anaconda:
2. Please go to the Anaconda.com/downloads site.
3. Select the respective platform: Windows/Mac/Linux.
4. Download the .exe installer.
5. Open and execute the .exe installer.
6. Launch Anaconda Navigator.
7. Click on the Install Jupyter Notebook Button.
8. Beginning the Installation.
9.  Upon installation, open jupyter notebook.
#### Python Libraries
Open Anaconda console and install the following libraries
``` 
pip install scikit-learn
pip install tensorflow
pip install keras
conda install -c conda-forge xgboost
pip install librosa
pip install pydub 
pip install seaborn
```


### Quick Start
1. Clone the code into your local machine and extract it.
2. Download the dataset from [Link](https://drive.google.com/file/d/1IeGJl67KCsIawgnWex4PV05uM4aJxU5P/view?usp=sharing) and extract the dataset
3. Place the downloaded "Dataset" folder  into music-genre-classification-main folder
4. Open Jupiter Environment and open music-genre-classification.ipynb
5. Start and Run all chunks

### Results
XGboost outperforms CNN with an accuracy of 87% for XGBoost model and 72% for the CNN model.
![image](https://user-images.githubusercontent.com/30415399/146255544-3a5b3cf3-c0a4-4276-82c7-72c44f15a674.png)

### Additional resources
Librosa - https://librosa.org/doc/latest/index.html
Anaconds - https://docs.anaconda.com/
Dataset - https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification
