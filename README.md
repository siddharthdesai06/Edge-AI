# Edge-AI

Here we have trained 2 model to detect emotions of the person. 

We have created a dataset for video emotion recognition.

## Hardware used:-
1) Intel Realsense depth sensing camera
2) USB Microphone
3) Raspberry pi

## Structure of the Dataset   
The dataset is organized into training and validation sets, each containing four categories of emotions:

- **Train**
  - Happy
  - Sad
  - Neutral
  - Excited

- **Val**
  - Happy
  - Sad
  - Neutral
  - Excited


## Running the code:

1) Run the Video_dataset_creation file and give the number of images you need.
2) Run the emotion.py file to create the model, train it and saave the .pt file
3) Connect the raspberry pi, camera module and USB microphone to the pi 4
4) Upload the .pt file in your raspberry pi 4 along with the inference_video.py and inference_audio.py
5) On the terminal go in the particular directory and to run both the files use python inference_video.py for running the video model. (Also give the .pt file path)
6) Also in the same directory run python inference_audio.py for running the audio file. (You can open another terminal for the same)
