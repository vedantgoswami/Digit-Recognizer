# Digit-Recognizer
This is a combo of Android app and the tensorflow model for image recognition.
It is a simple model for recognising the MNIST images <b>(28 x 28)</b> pixels. 

## Here is the look of the app:
<kbd>
<img width="250" height="330" src="https://raw.githubusercontent.com/vedantgoswami/Digit-Recognizer/main/images2/0.PNG">
<img width="250" height="330" src="https://raw.githubusercontent.com/vedantgoswami/Digit-Recognizer/main/images2/1.PNG">
<img width="250" height="330" src="https://raw.githubusercontent.com/vedantgoswami/Digit-Recognizer/main/images2/2.PNG">
<img width="250" height="330" src="https://raw.githubusercontent.com/vedantgoswami/Digit-Recognizer/main/images2/3.PNG">
<img width="250" height="330" src="https://raw.githubusercontent.com/vedantgoswami/Digit-Recognizer/main/images2/4.PNG">
<img width="250" height="330" src="https://raw.githubusercontent.com/vedantgoswami/Digit-Recognizer/main/images2/5.PNG">
<img width="250" height="330" src="https://raw.githubusercontent.com/vedantgoswami/Digit-Recognizer/main/images2/6.PNG">
<img width="250" height="330" src="https://raw.githubusercontent.com/vedantgoswami/Digit-Recognizer/main/images2/7.PNG">
<img width="250" height="330" src="https://raw.githubusercontent.com/vedantgoswami/Digit-Recognizer/main/images2/8.PNG">
  <p style="padding: 5px">
    <img width="250" height="330" src="https://raw.githubusercontent.com/vedantgoswami/Digit-Recognizer/main/images2/9.PNG">
  </p>
</kbd>
<h3><u>Android TensorFlow App Structure</u></h3> 
<b> THIS IS HOW MY MODEL WORKS IN FOUR STEPS </b><br>
  1. Image BitMap to the NDK.<br>
  2. Input Tensor to the Tensorflow PreTrained Model.<br>
  3. Predicting the Top result.<br>
  4. Returning classification and Confidence to the SDK.<br>
<p align="center">
  <img src="https://github.com/vedantgoswami/Digit-Recognizer/blob/main/images2/android-tensorflow-app-structure_2.png">
 </p>
