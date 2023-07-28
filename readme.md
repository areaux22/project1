Color Identifier Model

The theory of this model was for it to be used to identify the color of yarn that is shown, and then give suggestions on what to make based on the color available.


## The Algorithm
The algorithim in theory was it being used by detecting a color in an image, based on the training it went through. It then identifies a color, and then uses 'if' statements to give a suggestion based on the color it detected.

## Running this project

1. Connect to your Jetson Nano via VSCODE. 
2. Download the dataset into VSCODE.
3. Go into the docker container, and run the training script to train the images.
   
This is as far as I was able to get, but in theory the rest of the steps would be to:
4. Select the amount of epochs for it to run
5. Export it, and select the dataset variables
6. And then open VSCODE and run an image from the test section!

Some of the errors I had:
nano wouldn't connect to wifi --> got a new wifi adapter,
nano wouldn't connect to computer --> got a new nano,
new nano wouldn't connect to computer --> got a new computer,
new nano still wouldn't connect to new computer --> got a usb cord,
new nano with new cord still wouldn't connect to new computer --> got a new memory card,
-- which enabled it to finally connect back --
wouldn't run the tarining script --> found broken packages
broken packages were caused by dependency hell
tried to fix dependency hell --> by trying to install correct version of jetpack
correct version of jetpack still won't install 

[View a video explanation here](video link)
