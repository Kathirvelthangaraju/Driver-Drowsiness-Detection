# Real-Time-Driver-Drowsiness-Detection-
<b>PROPOSED-SYSTEM<b><br>
  The proposed system for a driver drowsiness detection system incorporates advanced technologies to enhance road safety. By leveraging computer vision techniques and machine learning algorithms, the system monitors the driver's facial expressions, eye movements, and Yawning to detect signs of drowsiness. Real-time data from cameras inside the vehicle fed into the system, Then the data is preprocessed and then by using Harr-Cascade algorithm face recognition is done. By Eye Aspect Ratio (EAR) the openness of the eye is checked. Then the Mouth Aspect Ratio is used to check the openness of the mouth for yawning, which then analyzes the collected information to determine the driver's level of alertness. In the event of detecting drowsiness, the system triggers auditory warnings to prompt the driver to regain focus. 

<b>WORKING<b><br>
STEP 1: Importing OpenCV.<br>
STEP 2: Apply Harr cascade algorithm to identify key points on the face, such as eyes, mouth, and nose.<br>
STEP 3: Calculate the Eye Aspect Ratio (EAR) to determine the openness of the eyes.<br>
STEP 4: Monitor the mouth for yawning movements.<br>
STEP 5: If the calculated EAR falls below a certain threshold for a specific duration, it indicates drowsiness.<br>
STEP 6: Then an auditory alert will played to alert the driver to regain his focus.<br>

<b>HOW TO RUN <b><br>
<ul>
<li>Download the <strong>shape_predictor_68_face_landmarks.dat</strong> form <i>https://github.com/italojs/facial-landmarks-recognition/blob/master/shape_predictor_68_face_landmarks.dat</i> and save it in the project folder. </li>
<li>In the <i>drowsiness_yawn.py</i> file, change the path of <i>alert.wav</i>.</li>
<li>Install all the requirements in the <strong>requirements.txt</strong> file.</li>
<li>Run the <i>drowsiness_yawn.py</i> file.</li>
</ul>
<br>
<b>CONTACT</b>
<ul>
<li><p>NAME: KATHIRVEL T</p></li>
<li><p>PHONE: 9025610912</p></li>
<li><p>E-MAIL: kathirvelthangaraju@gmail.com</p></li>
</ul>
