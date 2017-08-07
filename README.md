# CozmoSelfDriveToyUsingCNN
## Note
This toy proj needs Tensorflow and Cozmo SDK provided by Anki [source codes](https://github.com/anki/cozmo-python-sdk/tree/master/examples/apps) 

### using CNN
1. base modle is provided in Tensorflow Dir.

###  Training Pics
1. Using py code capture_imgs_remote_driving_cozmo.py in DriveTool dir to get training pics
2. Training CNN module by using py code cozemo_cnn.py in Tensorflow dir to get the module
3. Using drive_by_cnn.py in DriveTool dir to run Cozmo

### Result Video in Youtube
1. Since I had trained the model in this simple toy track which is drawn by chalk, so the result is displayed at the same place.
2. After capturing 5034 pics and training the version 1 model, I get 60% accuracy at last.  
3. [Result Video](https://www.youtube.com/watch?v=klVTxu8CQI4)
