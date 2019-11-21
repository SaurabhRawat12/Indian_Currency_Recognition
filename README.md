##  🇮🇳Indian Currency💱$ Detection System

### Sourcerer
<a href="https://sourcerer.io/spidy20"><img src="https://avatars2.githubusercontent.com/u/42056100?v=4" height="50px" width="50px" alt=""/></a>

### Code Requirements
- Opencv(`pip install opencv-python`)
- Tensorflow GPU(Preferred)(`pip install tensorflow-gpu`)
- Numpy (`pip install numpy`)

### What steps you have to follow??
- Download my Repository 
- Extract a `Model.zip` , In this zip you will find `frozen_inference_graph.pb` a model file and `labelmap.pbtxt` a label file, Put this files in working directory.
- Run a `currency_det_im.py`, if you want to detect from an image otherwise for video use `currency_detection_webcam.py`

### Project Structure

- I given my prepared model to you so you don't need to train it, just follow me:)
- It can detect (10,20,50,100 Rupees) old notes, because of i am just testing & learning abou this that's why i choosen less classes,but now i am working a system which can detect all indian currency with old & new notes and even coins also,but it will take time, i am gathering a dataset for it. 
- I used own image dataset for this model, Images captured with mobile.
- I used Tensorflow API of object detection but used own images.
- I used `faster_rcnn_inception_v2_coco` model for training ,you can use any other model for training.

### Screenshots

### 10 Rupees detection from live video
<img src="https://github.com/Spidy20/Indian_Currency_Recognition/blob/master/Screenshot%20(49).png">

### 100 Rupees detection from live video
<img src="https://github.com/Spidy20/Indian_Currency_Recognition/blob/master/Screenshot%20(51).png">

### 50 Rupees detection from live video
<img src="https://github.com/Spidy20/Indian_Currency_Recognition/blob/master/Screenshot%20(53).png">

### 100 Rupees detection from image
<img src="https://github.com/Spidy20/Indian_Currency_Recognition/blob/master/Screenshot%20(54).png">



### Notes
- It will require high processing power(I have 8 GB RAM & 2 GB GC)
- If you think it will recognise notes like human then please leave it ,it's have many bugs ,but currently i am solving it.
- Quality of images matters which you are giving as input for a prediction ,please use clear images.

## Just follow☝️ me and Star⭐ my repository 

