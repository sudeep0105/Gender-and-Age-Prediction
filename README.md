# Gender-and-Age-Prediction
To detect the age and gender of a person in an image and also through the WebCam using ML and Computer Vision with Python and OpenCV to analyze photos and predict age and gender, overcoming challenges like cosmetics and lighting.


<b>libraries required:</b><br>
- OpenCV

      pip install opencv-python
  
- argparse

      pip install argparse

<b>files required:</b><br>
- opencv_face_detector.pbtxt<br>
- opencv_face_detector_uint8.pb
- age_deploy.prototxt
- age_net.caffemodel
- gender_deploy.prototxt
- gender_net.caffemodel
- few pictures
- detect.py

<b>How to run the code:</b><br>
1. Open Command Prompt or Terminal and change directory to the folder where all the files are present.
- Detecting Age and Gender of a face in an <b>image</b> by using the command:

      python detect.py --image <image_name>
<b>Note:</b> The Image should be present in same folder where all the files are present.
- Detecting Age and Gender with <b>WebCam</b> by using the command:

      python detect.py

Press 'q' to stop the execution.
