# Remote-control-car-by-raspberry-pi

<h3 dir=auto><b>Forword:</b> It is my iOT project. I know it's not remarkable, yet I tried my best.</h3>
<hr>
<p>  As the title, what I did is a remote control car. With the camera on it, the car can move and monitor on the flat floor, using the program to make it go wherever the user want.</p>
<br><p>To reach the goal, we need to prepare these materials in advance:</p>
<h4>Raspberry pi, Camera module, The car chassis with motor, Motor control board, Battery case, Bracket</h4>
<hr>
<br><h3><b>THE HARDWARE</b></h3><br>
<h3>Step 1. assemble the car chassis and fix the battery case on it.</h3><a href="https://ibb.co/X3DR7Kj"><img src="https://i.ibb.co/vQhn3TV/DSC-5455.jpg" alt="DSC-5455" border="0"></a><a href="https://ibb.co/m68xnXR"><img src="https://i.ibb.co/KFw1tL5/DSC-5456.jpg" alt="DSC-5456" border="0"></a><a href="https://ibb.co/CHdwyGS"><img src="https://i.ibb.co/LZw0y7s/DSC-5457.jpg" alt="DSC-5457" border="0"></a>
<hr>
<h3>Step 2. Using the wires to connect the motor and the motor control board.</h3><a href="https://ibb.co/7YLPvpJ"><img src="https://i.ibb.co/0DvTq9j/DSC-5460.jpg" alt="DSC-5460" border="0"></a><br /><a href="https://ibb.co/DCC7yW8"><img src="https://i.ibb.co/3NN0qdM/DSC-5479.jpg" alt="DSC-5479" border="0"></a><a href="https://ibb.co/j4QjwYx"><img src="https://i.ibb.co/nkYK1yV/DSC-5480.jpg" alt="DSC-5480" border="0"></a>
<hr>
<h3>Step 3. Using Dupont line to link the motor control board and the raspberry pi. And also plug the power wire into the motor control board.</h3><a href="https://ibb.co/5kv9hFj"><img src="https://i.ibb.co/ZSKJzmg/DSC-5461.jpg" alt="DSC-5461" border="0"></a><a href="https://ibb.co/4p2GNH2"><img src="https://i.ibb.co/RcNmHqN/DSC-5463.jpg" alt="DSC-5463" border="0"></a>
<h3>Step 4. Install the camera module and fasten them on thebracket</h3><a href="https://ibb.co/4m8BjCD"><img src="https://i.ibb.co/qyNbRh4/DSC-5477.jpg" alt="DSC-5477" border="0"></a><br /><a href="https://ibb.co/wCj6Zsq"><img src="https://i.ibb.co/7VLyx4D/DSC-5478.jpg" alt="DSC-5478" border="0"></a>
<h4>So far, the hardware part is finished.</h4>
<hr>
<br><h3><b>THE SOFTWARE</b></h3><br>
<h3>Step 1. Download the raspberry pi OS. Go to their official website and download the linux edition.
<br><a href="https://ibb.co/gRSfvk9"><img src="https://i.ibb.co/5RrSYb4/scrot1.png" alt="scrot1" border="0"></a><a href="https://ibb.co/6mxddws"><img src="https://i.ibb.co/2yQbbhK/scrot2.png" alt="scrot2" border="0"></a><a href="https://ibb.co/zQYFwJS"><img src="https://i.ibb.co/MZ4fL6R/scrot3.png" alt="scrot3" border="0"></a>
<hr>
<h3>Step 2. Set the ssh on, so that we can control the raspberry pi via VNC.
<br><a href="https://ibb.co/GP97C4B"><img src="https://i.ibb.co/ZTSdcpt/MQ7LgQx.png" alt="MQ7LgQx" border="0"></a><a href="https://ibb.co/djz3r2X"><img src="https://i.ibb.co/n65Vbc4/L1n2jMT.png" alt="L1n2jMT" border="0"></a><a href="https://ibb.co/bRHsRhN"><img src="https://i.ibb.co/G3sW3wC/tJULIFF.png" alt="tJULIFF" border="0"></a><a href="https://ibb.co/v38W3pw"><img src="https://i.ibb.co/YcGScmR/codKHLi.png" alt="codKHLi" border="0"></a>
<hr>
  <h3>Step 3. Set the camera option, letting raspberry pi can use it.</h3>
<a href="https://ibb.co/GP97C4B"><img src="https://i.ibb.co/ZTSdcpt/MQ7LgQx.png" alt="MQ7LgQx" border="0"></a><a href="https://ibb.co/svNRsCr"><img src="https://i.ibb.co/991gyhj/1-hh-BEv-X-wbjts2-XTn-Hj0zd-A.jpg" alt="1-hh-BEv-X-wbjts2-XTn-Hj0zd-A" border="0"></a><a href="https://ibb.co/9cdT6qS"><img src="https://i.ibb.co/cksF0NV/1-psh-Wp6r2-Xe8l-YKvl-U39ag.jpg" alt="1-psh-Wp6r2-Xe8l-YKvl-U39ag" border="0"></a>
<hr>
<h3>Step 4. Download flask kit. And copy it to the home directory</h3>
<br><a href="https://imgbb.com/"><img src="https://i.ibb.co/qRk5yWn/flask-download.jpg" alt="flask-download" border="0"></a>
<a href="https://ibb.co/L6VXzmW"><img src="https://i.ibb.co/K7Tpjdk/FLASK-copy.jpg" alt="FLASK-copy" border="0"></a>
<hr>
<h3>Step 5. Select the flask-video-streaming folder and open the app.py with python compiler, then modify the program as below:</h3>
<a href="https://ibb.co/2sxFFJM"><img src="https://i.ibb.co/JyVccZp/2022-01-09-172207-1024x768-scrot.png" alt="2022-01-09-172207-1024x768-scrot" border="0"></a><a href="https://ibb.co/v14GJTz"><img src="https://i.ibb.co/4WRGjXN/2022-01-09-172501-1024x768-scrot.png" alt="2022-01-09-172501-1024x768-scrot" border="0"></a><a href="https://ibb.co/56tzqmm"><img src="https://i.ibb.co/ZVtwy55/2022-01-09-172513-1024x768-scrot.png" alt="2022-01-09-172513-1024x768-scrot" border="0"></a><a href="https://ibb.co/JtrC3jS"><img src="https://i.ibb.co/ZXcN2zb/2022-01-09-172515-1024x768-scrot.png" alt="2022-01-09-172515-1024x768-scrot" border="0"></a>
<hr>
<h3>Step 6. We also need to change the html file, sothat we can control the car via the web.</h3>
<a href="https://ibb.co/tsJqvCW"><img src="https://i.ibb.co/mqc92zM/2022-01-09-172546-1024x768-scrot.png" alt="2022-01-09-172546-1024x768-scrot" border="0"></a>
 
