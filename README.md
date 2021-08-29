# TM Video Editor Android

Icons made by <a href="https://www.flaticon.com/authors/good-ware" title="Good Ware">Good Ware</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a>

## Problem Statement
To create an android application which can fullfill the given points of tests.

#### Discription
1.	Should make an Activity which holds the camera preview in realtime and render any filter which could be rendered using openGL or Vulkan and modify the content of camera preview in real time.

2.	The activity should provide an option to record the processed camera preview along with any audio data captured during the camera preview recording session.

3.	The recording button should act as a photo capture if it is tapped and released immediately, and should act as a recording button if held longer than a tap. 

4.	If a photo is captured, the photo should be rendered as a video of 3 seconds using a single image repeating for all frames during 3 seconds.

5.	Once the video is rendered, it should be possible to save the video into a local gallery. It should be possible to be viewed in android video player.


#### Bonus:

1.	Changing the orientation of the video by 90 degrees without sacrificing the quality of the video.

2.	Rendering video through any shader function using openGL or equivalent script.

3.	Processed videos may qualify 5th requirement.

4.	Experience with ARCore is a huge plus.

#### Functionalities
1. Capture videos or Photos with or without Filter applied.
2. Preview the camera view in Real Time with filter applied (if any).
3. Choose from a list of filters.
4. Option to switch between front and back camera.
5. Capture video or photo in portrait or landscape.
6. Save the captured video/ photo in local storage(Internal Storage).
7. Turn on or off the flash.
8. Compatible with latest Android (tested on Android 10, Android 11 and Android 12 beta 4.1).
9. Day and Night Theme switchable.

## Installation Guide
#### To View Source Code
Requires Android Studio Arctic Fox | 2020.3.1, Gradle tools v7.0.1	
- Extract the zip file in 
18BCE10283-Android-2/TMVideoEditorAndroid/TM Video Editor Android.zip and open the folder with Android Studio.
#### To Run Application
Requirement Android device running on Android 5.0+
- Download the apk file given in 18BCE10283-Android-2/TMVideoEditorAndroid/Output.
- Open the apk file in your android device and install the application.
- For 1st run, during splash screen, give permission for camera, storage and microphone usage.

## Referrences
- Referred to [Camera Recorder](https://github.com/MasayukiSuda/CameraRecorder-android) for Filters and shaders.
- Used [Camera from flaticon](https://www.flaticon.com/free-icon/camera_685672?term=camera&page=1&position=49&page=1&position=49&related_id=685672&origin=tag) for icon
- [Android Documentation](https://developer.android.com/docs)
- Stack Overflow.


