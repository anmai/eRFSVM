# eRFSVM
A tool for predicting enhancers
For details on the algorithm, please see 

eRFSVM: a hybrid classifier to predict enhancers-
integrating random forests with support vector machines


Fang Huang, Jiawei Shen, Qingli Guo, Yongyong Shi, Hereditas (2016) submitted


#############################################
##############  Installation ################
#############################################

Installation of eRFSVM only requires unpacking the files in the
eRFSVM.tgz file.  Prerequisites include:


I. Install python required packages.
The version of python should be >=2.7.9. Instal the numpy, scipy packages (http://www.scipy.org/), scikit-learn packages (http://scikits.appspot.com/),
To check whether the packages are properly installed, please run

$python
>>> import numpy
>>> import scipy
>>> import sklearn


If there is no error message, this step is done.


#############################################
##############  Running eRFSVM ###############
#############################################

The raw data needs to be in the BED or broadpeak format. 
The testing file name should name as "  "_testing.txt


for example:
step 1:
$python rffantom5.py # running eRFSVM-FANTOM5
input the file name for testing:"adipose"  
step 2:
$python rfsvmfantom5.py
the results is saving in the file "adiposetest.txt"

step 1:
python rfep300.py # running eRFSVM-ENCODE
input the file name for testing:"K562"  
step 2:
$python rfsvmep300.py
the results is saving in the file "K562test.txt"


