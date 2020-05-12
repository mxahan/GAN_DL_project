Well there are lots of code here.

I will go over the codes that needs to run the Semi-supervised learning code


The most important code is the sgan_train.py. 

Requirement: 
- Tensorflow 2.0 or higher
- Python 3.7, CV2
- Trained weights of inception v3 downloaded from keras application. Please Check the Transfer learning portion for the name.
- The monkey 10 data-set from kaggle. 

Please fix the location of the dataset in the code which is the work_path in the original code. 

After fixing them, run the "sga_train.py" in any suitable IDE. 

If having issues, Please let me know via email zhasan3@umbc.edu

Code Description: 

1. sgan_train.py  -  The main developed code for running sgan model
2. gen_dis_def.py - Generator and discriminator defined in this function
3. sgan_train_classification.py  -  Consists of classification only model
4. gan_train.py  - Vanilla gan model for the monkey 10 dataset.
5. GANmodels.py - Another Gan model with different loss function on MNIST dataset

The above mentioned 5 codes we developed for our project. 

The rest of the codes were colleceted from the kaggle website in the begging of the project for starter and baseline check. 
