# RaspPi-Code
<h2>1. Raspberry Pi Push Button Video Recorder</h2>
<p>The file VideoCamera.py contains the code used for this project. The code will wait for someone to press the button before recording a 10 second video. While the video is recording, a LED will light up to let the user know that it is recording. Once finished, the video will be saved with the current date and time as the filename. To play the video, go to the directory it is stored in from Terminal and type <code>omxplayer "<i>name of video file</i>"</code> and press enter </p>


Components
<ul>
<li>Raspberry Pi 3</li>
<li>330 ohm resistor</li>
<li>A Push Button</li>
<li>Breadboard</li>
<li>Jumper Wires</li>
<li>LED</li>
<li>Raspberry Pi Camera V2</li>
</ul>
<br>
<img src = "https://github.com/mbaker92/RaspPi-Code/blob/master/Photos/VideoCamera.png?raw=true" align="middle" height="630" width="460">
<br>

<h2>2. Raspberry Pi Motion Detector/Email Alert System</h2>
<p>The file PIRCamera.py contains the code used for this project. The code will initialize a PIR(Passive Infared) sensor that is used to detect motion. If the PIR sensor detects motion, the Raspberry Pi camera will take a photo in the area of motion and email the photo to a specified email address.</p>

<p> The following lines in the file should be modified with the information you will use.<br>
<code> fromAddr = 'Address Sending Email'</code><br>
<code> toAddr = 'Address Receiving Email'</code><br>
<code> username = 'Email Address'</code><br>
<code> password = 'Password'</code></p>

Components 
<ul>
<li>Raspberry Pi 3</li>
<li>Jumper Wires</li>
<li>PIR Sensor</li>
<li>Raspberry Pi Camera V2</li>
<li>Breadboard (Optional)</li>
</ul>
<br>
<img src = "https://github.com/mbaker92/RaspPi-Code/blob/master/Photos/PIRCameraCircuit.png?raw=true" align="middle" height="342" width="653">
<br>

<h2>3. Raspberry PI Two Buttons as Input For Camera Control</h2>
<p>The file Two Button Camera.py contains the code used for this project. The code will set GPIO pins 17 and 18 as Input with the internal pull up resistors. One button (connected to GPIO 17) records a 10 second video. The other button (connected to GPIO 18) captures a picture. Both video and picture files are saved to the Documents folder with the current date and time as the filename. Since the code contains an infinite loop, it should be run from the Terminal. To end the program press <code> Ctrl + c</code>. </p><br>

Components
<ul>
<li>Raspberry Pi 3</li>
<li>Jumper Wires</li>
<li>2 Press Buttons</li>
<li>Raspberry Pi Camera V2</li>
<li>Breadboard</li>
</ul>
<br>
<img src = "https://github.com/mbaker92/RaspPi-Code/blob/master/Photos/TwoButtonCamera.png?raw=true" align="middle" height="630" width="460" >
<br>
