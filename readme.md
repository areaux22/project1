Color Identifier Model

This model is used to identify the color of yarn that is shown, and then give suggestions on what to make based on the color available.


## The Algorithm
The algorithim is used by detecting a color in an image, based on the training it went through. It identifies a color, and then uses 'if' statements to give a suggestion based on the color it detected.
Note: I ran this model on a realivly low epoch with information that was askew. The pretrained model is quite inacurrate.
## Running this project

1. Connect to your Jetson Nano via VSCODE. 
2. Confirm that you have downloaded and uploaded a color dataset to VSCODE
3. Ensure that the Renet18.onnx is downloaded as well.
4. Go into the docker container, and run the code
5. Upload an image from either the test file or from your own files.
6. Watch at it determines the color and gives you suggestions on what to create!

[View a video explanation here](video link)
