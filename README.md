# Photo Processing App
# Table of contents
1. [Project Description](#introduction)
2. [Features](#features)
  
## Project Description <a name="introduction"></a>
This project is a photo processing application developed with Kotlin for Android. The app allows users to capture photos, display the taken pictures, and perform various actions such as sending the photo via email, and opening the camera using a voice command.
## Features: <a name="features"></a>
#### Camera Integration 
Capture photos using the built-in camera functionality. The app is built with the CameraX library.  <br/> 
More information: [CameraX Documentation](https://developer.android.com/training/camerax).

#### Email Photo
Users can send the captured photo via email. The app uses Android Intents to compose an email with the attached photo. <br/> 
More information: [Sending Email Intent](https://developer.android.com/guide/components/intents-common#ComposeEmail).

#### Voice Command Integration
Apart from the button, users can open the camera using a voice command ("open camera app"). This feature utilizes Android App Actions. <br/> 
More information: [App Actions Overview](https://developer.android.com/guide/app-actions/overview).

#### Automatic Text Overlay
Before sending the photo via email, the app automatically overlays text (e.g., user's name and surname) onto the photo.

## How to Run the Project: <a name="installation"></a>
1. Clone this repository to your computer.
```bash
https://github.com/vestinabert/Photo_Processing_App.git
```
2. Open the project in Android Studio.

3. Build and run the application on an Android emulator or physical device.


