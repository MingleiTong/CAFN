# CAFN: The Combination of Atrous and Fractionally Strided Convolutional Neural Networks for Understanding the Densely Crowded Scenes

This is main code of the paper CAFN: The Combination of Atrous and Fractionally Strided Convolutional Neural Networks for Understanding the Densely Crowded Scenes which is accepted at PRCV 2018.

Data Setup
1. Download ShanghaiTech Dataset from

   Dropbox: https://www.dropbox.com/s/fipgjqxl7uj8hd5/ShanghaiTech.zip?dl=0

   or
   
   Baidu Disk: http://pan.baidu.com/s/1nuAYslz

2. Download UCF_CC_50 Dataset from

   http://crcv.ucf.edu/projects/crowdCounting/index.php

3. WorldExpo'10 obtained from

   http://www.ee.cuhk.edu.hk/~xgwang/expo.html

   The dataset is available, Shanghai Jiao Tong University has the copyright of the dataset. 
   So we contacted Prof. Xie (xierong@sjtu.edu.cn) to get the download link.

The proposed models are trained in a DELL PC station with a GPU Titan XP using Pytorch0.4.0

Here we supply our model.py as a comparasion to MCNN(CVPR2016). I suggest you can read the detailed steps at https://github.com/svishwa/crowdcount-mcnn, a pretty good unofficial implementation of MCNN. 

Following are the results of CAFN on Shanghai Tech A and B dataset:
    
     |     |  MAE    |   MSE    |
     ----------------------------
     | A   |  100.8  |   152.3  |
     ----------------------------
     | B   |   21.5  |   33.4   |
