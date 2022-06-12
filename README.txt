To make the program work without any modifications, you should follow these steps:
1. extract the file downlaoded from https://www.kaggle.com/datasets/tourist55/alzheimers-dataset-4-class-of-images?resource=download and upload the Alzheimer_s Dataset folder to your MyDrive

2. Also upload the ipynb file to MyDrive, but do NOT put the file inside any folders

3. Extract the models.zip folder into the Alzhimer_s Dataset folder

4. Download the Google colab extension to open up the ipynb file, and you're all set!

To make additions such as altering the code or the models, make changes to the model_list.txt
file located in the models folder inside the dataset.

List of models which are currently supported:
- resnet18, resnet34, resnet50, resnet101, resnet152
- squeezenet1_0, squeezenet1_1
- densenet121, densenet169, densenet201, densenet161
- vgg16_bn, vgg19_bn
- alexnet

*** keep in mind that some of these models will take different sized images as inputs
and so they may have to be scaled to fit when creating the data. So far, the ones personally
tested are: resnet18, vgg16_bn, and alexnet.

The checkpoints_test folder is simply there if you wish to load in model weights which
I have trained. Simply change the MODEL_PATH to checkpoints_test and the program will work
as intended for the corresponding models.

*** Currently, the checkpoints and the checkpoints_test folders are not uploaded to the Github 
repository as the files are too large to support the upload limit. If you would like to specifically
obtain these folders, then email me at jayshim0725@gmail.com
