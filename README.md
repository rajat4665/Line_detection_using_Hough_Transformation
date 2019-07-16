<h3><img class="alignnone size-full wp-image-149" src="https://getpython.files.wordpress.com/2019/07/burnstowndam1563303295.png" alt="burnstowndam1563303295" width="1280" height="720" /></h3>
<h3>A pipeline of Line Detection using Hough Transformation with OpenCV.</h3>
<img class="alignnone size-full wp-image-138" src="https://getpython.files.wordpress.com/2019/07/screenshot-from-2019-07-16-23-20-16.png" alt="Screenshot from 2019-07-16 23-20-16.png" width="643" height="234" />
<h3></h3>
<h3>How to run this code:</h3>
<ul>
	<li>download this code from my Github </li>
	<li>clone this repository</li>
	<li>open it into Jupyter notebook</li>
	<li>Now run its cells one by one</li>
  <li> for more computer vision article pay a visit on my <a href = "https://getpython.wordpress.com"> blog </a>
</ul>
<h3>How to install jupyter notebook in Ubuntu:</h3>
open your terminal and paste these commands one by one.
<pre class="code-pre command"><code>sudo apt install python3-pip python3-dev
</code><code>pip install jupyter</code></pre>
<h3>How to install jupyter notebook in windows:</h3>
Follow this <a href="https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/install.html">Link for windows</a>
<h3>Install these Requirements:</h3>
<pre>pip install OpenCV-python
pip install matplotlib
pip install numpy</pre>
<h3>Introduction:</h3>
Hello friends, welcome back to my another repository on Computer Vision. In this tutorial, I am gonna show you how one can detect lines from an image with the help of Hough transformation.
<h3>What is a Hough Transformation?</h3>
Hough Transform is a popular technique to detect any shape,  if you can represent that shape in mathematical form. It can detect the shape even if it is broken or distorted a little bit.

Basically, Hough Transforms image data from the x,y coordinate system into Hough space where one can easily identify simple boundaries like lines and circle. Nowadays this transform is widely used for shape-recognition, boundary detection and line detection in the world of image processing.

In term of line detection, Hough transform converts a line base features from image space to a hough space. Multiple lines in image space represent multiple dots in Hough space. For more information follow this <a href="https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_imgproc/py_houghlines/py_houghlines.html" target="_blank" rel="noopener">link.</a>
<h3>Practical Use case of the line detection system.</h3>
<ul>
	<li>An automatic lane detection system.</li>
	<li>Robotics</li>
	<li>line follower robot</li>
	<li>Parking Automation system</li>
</ul>
<h3>Step 1:</h3>
<img class="alignnone size-full wp-image-139" src="https://getpython.files.wordpress.com/2019/07/screenshot-from-2019-07-16-23-36-35.png" alt="Screenshot from 2019-07-16 23-36-35" width="792" height="504" />
<h3>Step 2:</h3>
<img class="alignnone size-full wp-image-140" src="https://getpython.files.wordpress.com/2019/07/screenshot-from-2019-07-16-23-37-56.png" alt="Screenshot from 2019-07-16 23-37-56" width="1121" height="439" />
<h3>Step 3:</h3>
I converted this image into grayscale because grayscale images are perfect for edge, line and other shape bases feature extraction.

<img class="alignnone size-full wp-image-141" src="https://getpython.files.wordpress.com/2019/07/screenshot-from-2019-07-16-23-38-51.png" alt="Screenshot from 2019-07-16 23-38-51" width="760" height="369" />
<h3>Step 4:</h3>
<img class="alignnone size-full wp-image-142" src="https://getpython.files.wordpress.com/2019/07/screenshot-from-2019-07-16-23-42-31.png" alt="Screenshot from 2019-07-16 23-42-31" width="902" height="457" />
<h3>Step 5:</h3>
Here you can tune its parameters (threshold, minLineLenght, and MaxLineGap) to obtain better accuracy.

<img class="alignnone size-full wp-image-143" src="https://getpython.files.wordpress.com/2019/07/screenshot-from-2019-07-17-00-09-39.png" alt="Screenshot from 2019-07-17 00-09-39" width="912" height="456" />
<h3>Step 6:</h3>
<img class="alignnone size-full wp-image-144" src="https://getpython.files.wordpress.com/2019/07/screenshot-from-2019-07-17-00-12-33.png" alt="Screenshot from 2019-07-17 00-12-33" width="815" height="458" />
<h3>Step 7:</h3>
<img class="alignnone size-full wp-image-145" src="https://getpython.files.wordpress.com/2019/07/screenshot-from-2019-07-17-00-15-19.png" alt="Screenshot from 2019-07-17 00-15-19" width="793" height="177" />
<h1>Input:</h1>
<img class="alignnone size-full wp-image-146" src="https://getpython.files.wordpress.com/2019/07/photo-1493780758133-e5cfb0d00354.jpeg" alt="photo-1493780758133-e5cfb0d00354" width="897" height="500" />
<h1>Output:</h1>
<img class="alignnone size-full wp-image-147" src="https://getpython.files.wordpress.com/2019/07/output_image.jpg" alt="output_image" width="897" height="500" />
<h1><em>Thank you for reading this article, Stay tuned for more articles.</em></h1>
