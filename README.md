# Heart-attacks
## Installation
In order to run the code, you need to have the following library:
 - pandas
 - matplotlib
 - sklearn
 - seaborn
 - numpy
If you miss any library, you can install it using pip. For example if you want to install pandas: `pip install pandas`

## Motivation
This project is initiated by Udacity on the data scientist nanodegree. I have chosen the hear attack dataset you can find on Kaggle. The questions I wanted to answer are the following:
  1. Is the cholestherol really increase the risk of doing a heart attack ?
  2. Are the age and the sex determinant factors of risks ?
  3. Can we predict chances to do heart attacks ?
 
 I answered those 3 questions in the same file. You can open it with Jupyter Notebook.
 
 ## Description of the repository
 You will find in this repository:
  - The README your are reading right now (thanks !)
  - The images folder to store the image I get (and the ones you can find here)
  - The jupyter notebook file containing all the code
  - The dataset in csv format I used for the analysis. The dataset looks like this:
  
 ![Image of the dataframe](https://github.com/ClemHuriaux/Heart-attacks/blob/main/images/df.PNG)
 
 The dataset try to diverse entry such as the following picture showing the age density:
 ![Image of the age density](https://github.com/ClemHuriaux/Heart-attacks/blob/main/images/density.PNG)
 
 It still is a small dataset so it doesn't have many entry. But is enough to have fun with it !
 
 ## Results
 With this dataset, I found that:
  1. The cholesterol is not a key indicator of heart attacks
  2. The sex a strong indicator but the age is not
  3. I can predict the likelyhood of doing a heart attack with a precision of 90%

But I insist on the fact that those results should not be taken too seriously as the dataset is small and not very well distributed.

## Sources
You can find the dataset here: https://www.kaggle.com/rashikrahmanpritom/heart-attack-analysis-prediction-dataset
