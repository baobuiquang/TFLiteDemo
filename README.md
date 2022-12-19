# TFLiteDemo

Simple TFLite Demo with MNIST Digits Classification

How to build TFLite model:

There are many ways. In this demo, we will train and build a TF model first, then convert to TFLite model.

1. Use the notebook "Building_TFLite_Model.ipynb"

2. Run the notebook

3. Download the file "model.tflite" for later use

How to run/use the source code:

1. Prepare the source code folder. There are 2 ways:

   - Clone the Github repository with the link in the "GithubLink.txt"

     (https://github.com/baobuiquang/TFLiteDemo)

   - Extract the "TFLiteDemo-main.zip" file

2. Open the folder with Android Studio

   - Recommended version: Android Studio Dolphin // 2021.3.1

3. Wait until Android Studio finish loading project and building gradle scripts

4. Run app (Shift + F10). Must connect to android device first. There are several ways:

   - Create virtual android device.

   - Connect to real android device through USB cable or WIFI.

5. Test the app using images

   - Took from camera

   - Load from files

How to load new TFLite model in the project:

1. Navigate to app\src\main\ml

2. Replace the old "model.tflite" with new "model.tflite"

Please contact 19120454@student.hcmus.edu.vn (Bui Quang Bao) for any problem.