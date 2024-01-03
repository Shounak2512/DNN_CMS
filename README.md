This repository is a account of my project performed under the supervision of Dr. Jyothsna Rani Komaragiri. 
In this project I have used the sample code provided with the data in the CMS open data portal as a base template and built a code to compare the performance of a ordinary discriminator and a Deep Neural network discriminator.
This discrimiator distinguishes between QCD jets (background) and Quark jets (signal). In the initial stages I have only used a few input variables and 3 dense layers in the DNN.
The data to train the ML model is available in 122 chunks on the CMS open data website. The direct download channel only partially downloads files. To circumvent this issue we employ the xrdcp method to download the files and I with he help of my supervisor have writted a scipt to help download all the files in one click.
We test the performance of our models using the ROC curve.
