# mostwanted
MostWanted is the result of a TED Sync Week hackfest where we used <a target="_blank" href="https://www.projectoxford.ai/">Project Oxford</a>'s facial recognition and machine learning APIs to begin building a modular system that helps border control agents maintain security. 
<p>
Through an interactive console, the app will allow the border agent to:
<ul>
<li>Capture a photograph of the traveller and compare it to known criminals
<li>Scan their luggage and automatically identify weapons
</ul>

<p>
<pre>
                                -------------------------
                                |                       |	
   Traveler -->   Kinect --->   |                       |   <----- Oxford Similar Face API
                                |                       |           |
                                |     Most Wanted       |           |------- FBI Most Wanted
                                |                       |
                                |       Console         |
   Luggage --->   X-Ray ---->   |                       |   <----- Weapon Detection Web Service
                                |                       |           |
                                |                       |           |------- Azure ML
                                -------------------------
</pre>
<p>
v2 will leverage Kinect's biometric scanning capabilities to identify travelers with abnormal temperature and heart rate, flagging potential Ebola sufferers for further health screening:
<p>
<pre>
                                -------------------------
                                |                       |	
   Traveler --> Kinect RGB ->   |                       |   <----- Oxford Similar Face API
                     |          |                       |           |
                     |          |     Most Wanted       |           |------- FBI Most Wanted
                     |          |                       | 
                     |          |                       |           
                    IR ----->   |                       |   <----- Sick Traveller Web Service
                                |                       |           |
                                |                       |           |------- Azure ML
                                |                       |
                                |       Console         |
   Luggage --->   X-Ray ---->   |                       |   <----- Weapon Detection Web Service
                                |                       |           |
                                |                       |           |------- Azure ML
                                -------------------------
</pre>
<h2>Team Members</h2>
Nathalie Goh-Livorness<br>
Marc Kuperstein<br>
Sofya Shinkareva<br>
Kelsey Huebner<br>
Simon Powell<br>
Giovanni Marchetti<br>
Dale Linneman<br>


