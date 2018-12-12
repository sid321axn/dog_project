# Project Overview :

Welcome to the Convolutional Neural Networks (CNN) project in Term 2 of Machine Learning Nanodegree Program. In this project, I have build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images. Given an image of a dog, our algorithm will identify an estimate of the dog’s breed. If supplied an image of a human, the code will identify the resembling dog breed.

## Sample Prediction
![Screenshot Dog](https://i.ibb.co/S3N3JPG/screenshot1.png)
![Screenshot Human](https://i.ibb.co/yfwRcPB/screenshot2.png)

# About Dataset :
This dataset contains 133 different categories of breeds of dogs and is already split into train, test, and validation sets. 

Download the ![dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). Unzip the folder and place the training, testing, and validation datasets in the ``dogImages folder``.

Download the ![human dataset]. Unzip the folder and place it in the ``lfw folder``. If you are using a Windows machine, you are encouraged to use ![7zip](http://www.7-zip.org/) to extract the folder.

# Project Instruction :

1. If you want to run this code on your local computer, you'll also need to download the bottleneck features. 
Donwload the ``VGG-16 bottleneck features`` for the dog dataset. Place it in the ``bottleneck_features folder``.I'll discuss what this is in the Jupyter Notebook, but it's a relatively large file so you may want to go ahead and start the download.

2. I recommend setting up an environment for this project to ensure you have the proper versions of the required libraries.

**Note:** You must navigate to the root folder of the project directory in order for the following commands to work properly.

For **Mac/OSX**:

```conda env create -f requirements/aind-dog-mac.yml
	source activate aind-dog
	KERAS_BACKEND=tensorflow python -c "from keras import backend"
  ```
For **Linux**:

	```conda env create -f requirements/aind-dog-linux.yml
	source activate aind-dog
	KERAS_BACKEND=tensorflow python -c "from keras import backend" ```
For **Windows**:

	```conda env create -f requirements/aind-dog-windows.yml
	activate aind-dog
	set KERAS_BACKEND=tensorflow
	python -c "from keras import backend"```
  
 3. (Optional) If you plan to install TensorFlow with GPU support on your local machine, follow the ![guide](https://www.tensorflow.org/install/) to install the necessary **NVIDIA** software on your system. If you are using an EC2 GPU instance, you can skip this step.

4. Lastly, fire up the Jupyter Notebook and let's get started.

	```jupyter notebook dog_app.ipynb```


