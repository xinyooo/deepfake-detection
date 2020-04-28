# deepfake_detection


Detect the video is fake or not using InceptionResNetV2.


The dataset was downloaded from kaggle deepfake detection challenge: https://www.kaggle.com/c/deepfake-detection-challenge/data

Experimental steps

Step1.
run capture_img -> use the dlib face detecter to convert video to face img.

Step2.
run deepfake_detection_train -> training the dataset from capture_img and output the model file.

Step3.
run model_play -> load model then input video to detect the video is fake or not. [0]: fake, [1]: real
