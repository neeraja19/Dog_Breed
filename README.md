# Dog_Breed
Welcome to the Convolutional Neural Networks (CNN) project in the AI Nanodegree! In this project, you will learn how to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images. Given an image of a dog, your algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.

Along with exploring state-of-the-art CNN models for classification, you will make important design decisions about the user experience for your app. Our goal is that by completing this lab, you understand the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline. Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer. Your imperfect solution will nonetheless create a fun user experience!

Project Instructions

    Clone the repository and navigate to the downloaded folder.

    Download the dog dataset. Unzip the folder and place it in the repo, at location path/to/dog-project/dogImages.

    Download the human dataset. Unzip the folder and place it in the repo, at location path/to/dog-project/lfw. If you are using a Windows machine, you are encouraged to use 7zip to extract the folder.

    Donwload the VGG-16 bottleneck features for the dog dataset. Place it in the repo, at location path/to/dog-project/bottleneck_features.

    Obtain the necessary Python packages, and switch Keras backend to Tensorflow.

    For Mac/OSX:

    	conda env create -f requirements/aind-dog-mac.yml
    	source activate aind-dog
    	KERAS_BACKEND=tensorflow python -c "from keras import backend"

    For Linux:

    	conda env create -f requirements/aind-dog-linux.yml
    	source activate aind-dog
    	KERAS_BACKEND=tensorflow python -c "from keras import backend"

    For Windows:

    	conda env create -f requirements/aind-dog-windows.yml
    	activate aind-dog
    	set KERAS_BACKEND=tensorflow
    	python -c "from keras import backend"

   
Amazon Web Services

Instead of training your model on a local CPU (or GPU), you could use Amazon Web Services to launch an EC2 GPU instance. Please refer to the Udacity instructions for setting up a GPU instance for this project. (link for AIND students, link for MLND students)

    

