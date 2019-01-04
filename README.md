# aicamcam.github.io
Smart webcam service. Object(person/dog/cat) detection and record video. Running without any server connection. Powered by HTML5, Tensorflow.js

<img src="docs/images/aicamcam_capture.png" width="1200" height="675" />


### Tested Environment
Chrome - 71.0.3578.98
 
### How to use
#### 1. Configuration
<img src="docs/images/setting.png" width="366" height="308" />

Please allow chrome to use "Webcam".  
If you want to auto download for recorded video, Please allow "Automatic Downloads".   

#### 2. Object detection  
<img src="docs/images/side_button_od.png" width="230" height="86" />

To test object detection, click "Test Object Detection" button. 
Loading TFJS model take 1~2 minutes.  
This button draw bounding box to video. 

#### 3. Smart Recording  
<img src="docs/images/side_button_smart_recording.png" height="86" />

To start smart recording, click "Smart Recording" Button.  
During smart recording mode,   
If a object is detected, Recording is started.  
If the object disapear for 3 seconds, Recording is stoped.   
If recording is continued for 1 minute, Video is created and recording is re-started.  

#### 4. Recording 
<img src="docs/images/side_button_recording.png" height="86" />

To start recording, click "Recording" Button.  
This button start recording regardless of object detection. 
If recording is continued for 1 minute, Video is created and recording is re-started.  

#### 5. Navigator
<img src="docs/images/hamburger_button.png" height="86" />

##### 5.1. video
Click "hamberger" button and check out the created video.   
User can download or remove video. 
The video hold system memory until user remove it.   
To save system memory, please download and remove video from navigator.   

##### 5.2. Auto download
<img src="docs/images/auto_download.png" height="146" />
If you plan to use long-term recording, 
Click auto download and remove button.  

##### 5.3. download all and remove all 
Download all and remove all videos
