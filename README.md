# Mood-Player
Mood Player is an Deep learning Object detection model used for playing a random song according to your mood. Song cant be shown in GIF :P


![Mein Video (1)](https://user-images.githubusercontent.com/51056214/118481123-6d3e6780-b713-11eb-9f83-2dd788201c8c.gif)



Have you ever Wondered, a music player that can automatically play song according to your mood. Then you are at right place.
The file has two Scripts. 
1. **Getting and Preprocessing dataset**: This file simply takes the image as webcam and manually requires annotation using the [Label Image annotator](https://github.com/tzutalin/labelImg) 
2. **Training and Validating**: Will load the Tensorflow Object Detection API,install all the protobuffers and then given our dataset from above,the model will be trained. For music player you need to manually put songs in different categories defined.

Network Used to train the Model: MobileNetwork for real time object detection.


Process to get started:

Step 1: Install basics like Python Interpreter and clone the repository.

Step 2: Create your Environment: Creating an environment will create a seperate room for your project and the libraries installed will be seperate from your installed one.

    python -m venv {NAME_OF_YOUR_ENVIRONMENT}
    
Step 3: Activation of Your Environment.
    
    .\ENVIRONMENTNAME\Scripts\activate

Step 4: Install IpyKernel so that you can attach the environment with Jupyter notebook

    python -m pip install --upgrade pip
    pip install ipykernel
    python -m ipykernel install --user --name=EnvironmentName

Step 5: Open the Jupyter notebook Click Your Environment in the Corner and Select it. My Environment name was Expression :)
![Environment](https://user-images.githubusercontent.com/51056214/118480998-48e28b00-b713-11eb-98fd-e90f4011301c.png)


Step 6: Execute the Preprocessing Library and Then Training and Validation Library.


Reference and Big Help From : [Nicholas Renotte](https://github.com/nicknochnack/)
