The goal of this project is to make use of the Egohands dataset fot training the 
tensorflow object detection api.

The folders in this directory are as follows :
1) Annotations : collection of all the .csv & .record files that will be generated
   by certain python scripts for our images and their respective labels.

2) Images :  main collection of train & test images. Inside both the subfolders we
   will keep the image and its respective annotation file in .xml format.

3)Pre-trained model : In this we will download the target model to train & the 
  target will also provide us with ckpt & weights to start the train.

4)training : collection of all the further ckpts and .config file along with a
  .pbtxt label map file generated during model train.
