# Personalized_cancer_diagnosis
## Introdoction:
This is not a trivial task since interpreting clinical evidence is very challenging even for human specialists. Therefore, modeling the clinical evidence (text) will be critical for the success of your approach.
Both, training and test, data sets are provided via two different files. One (training/test_variants) provides the information about the genetic mutations, whereas the other (training/test_text) provides the clinical evidence (text) that our human experts used to classify the genetic mutations. Both are linked via the ID field.
We have two data files: one conatins the information about the genetic mutations and the other contains the clinical evidence (text) that human experts/pathologists use to classify the genetic mutations.
Both these data files are have a common column called ID.
* A lot has been said during the past several years about how precision medicine and, more concretely, how genetic testing is going to disrupt the way diseases like cancer are treated.
But this is only partially happening due to the huge amount of manual work still required. Memorial Sloan Kettering Cancer Center (MSKCC) launched this competition, accepted by the NIPS 2017 Competition Track,  because we need your help to take personalized medicine to its full potential.
Once sequenced, a cancer tumor can have thousands of genetic mutations. But the challenge is distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers). 

* Currently this interpretation of genetic mutations is being done manually. This is a very time-consuming task where a clinical pathologist has to manually review and classify every single genetic mutation based on evidence from text-based clinical literature.
### Data file's information: 
1. training_variants (ID , Gene, Variations, Class)   2. training_text (ID, Text)

## Problem Statement and build ML model:
#### we have two data sets 1 training_text.zip  and 2nd training_variants.zip
#### training _text contains text data wich is provided by Pathologist, it contains lot of text data  for each type of cancer tumor
traing variants.zip file contains two features zene and variation data and we have 9 class labels wich are 9 types of cancers(so we can say it is multi class classifiacation
#### now we have to combine two files based on IDs  text data(wich is provided by pathologist) and train data with 2 features.
#### after performing data analysis EDA and feature engineering we could build classical ML models(multi class classification) to predict cancer.
#### then our model prediction result could be helpfull for Pathologist doctors to reduce read text information

### Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/

### Tools we have used:
* Python3
* Jupyter Notebook
### Required libraries:
*  Pandas: using for construct dataframes
*  Numpy : using for some Numerical mathematical operations
*  matplotlib&seaborn: using for visual tools 
*  Sklearn: this most useful for basing ml models 
#### Acknowledgement:  
* Applied AI course
