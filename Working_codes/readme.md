# Code instruction
Well there are lots of code here.

I will go over the codes that needs to run the Semi-supervised learning code


The most important code is the sgan_train.py. 

Requirement: 
- Tensorflow 2.0 or higher
- Python 3.7, CV2
- Trained weights of inception v3 downloaded from keras application. Please Check the Transfer learning portion for the name.
- The monkey 10 data-set from kaggle. 

Please fix the location of the dataset in the code which is the work_path in the original code. 

After fixing them, run the "sgan_train.py" in any suitable IDE. 

If having issues, Please let me know via email zhasan3@umbc.edu

For SGAN experiments, we have developed five codes to successfully run the SGAN implementation. 
Developed Code Description: 

1. sgan_train.py  -  The main developed code for running sgan model
2. gen_dis_def.py - Generator and discriminator defined in this function
3. sgan_train_classification.py  -  Consists of classification only model
4. gan_train.py  - Vanilla gan model for the monkey 10 dataset.
5. GANmodels.py - Another Gan model with different loss function on MNIST dataset

The above mentioned 5 codes we developed for our project. 
## Extras

The rest of the codes were colleceted from the kaggle website in the begging of the project for starter and baseline check. Kudos to them for their works. 


# Additional Option

In the sgan_train.py we enables the option for experimenting with different loss function. Please open the code and find the discriminator_loss and generator_loss function in the code. There just comment in and out the corresponding sections together in the function to change the loss function accordinging. For the WGAN please activate the commented weighted clipping in the discriminator. 
