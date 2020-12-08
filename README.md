# Gesture-Recognition-project
In this project, you will build a model to recognise 5 hand gestures.
The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

Thumbs up:  Increase the volume
Thumbs down: Decrease the volume
Left swipe: 'Jump' backwards 10 seconds
Right swipe: 'Jump' forward 10 seconds  
Stop: Pause the movie
 

Each video is a sequence of 30 frames (or images). In the next couple of lectures, our subject matter expert Snehansu will walk you through the structure of the dataset.

Goals of this Project
In this project, you will build a model to recognise 5 hand gestures. The starter code has been shared with you above. Before you start working on the mode, let's see the suggestions Snehansu has to finish the project successfully.

Play Video
You need to accomplish the following in the project:

Generator:  The generator should be able to take a batch of videos as input without any error. Steps like cropping, resizing and normalization should be performed successfully.

Model: Develop a model that is able to train without any errors which will be judged on the total number of parameters (as the inference(prediction) time should be less) and the accuracy achieved. As suggested by Snehansu, start training on a small amount of data and then proceed further.

Write up: This should contain the detailed procedure followed in choosing the final model. The write up should start with the reason for choosing the base model, then highlight the reasons and metrics taken into consideration to modify and experiment to arrive at the final model. 

Sample Write-upfile_download	Download
You’ll be evaluated on the following submission:

Submit a zip folder containing the jupyter notebook having the final model, the final .h5 file and the write-up. The .h5 file will be used to calculate the accuracy on the test data.

 

There are certain things you should keep in mind before proceeding further:

Use the correct container: 'Tensorflow 1.5.0 GPU Py3' when you are using a GPU machine, else it'll throw an error similar to 'the kernel died'.
Use a C2/CPU machine to get the data on your persistent storage.
Whenever you modify your model, run the notebook from the beginning. This is to reset the initialisations and the generator.
To check the GPU usage, execute 'nvidia-smi' on the terminal.
