# HAARS-CASCADE_GENERATOR
<hr/>
<h3>Step 1</h3>
<br/>
<p>Put the images of what you want to identify on the positives folder</p>
<hr/>
<h3>Step 2</h3>
<br/>
<p>Put images of things that are not what you want to identify on negatives folder</p>
<hr/>
<h3>Step 3</h3>
<br/>
<p>Run start.exe</p>
<br/>
<h2>How it works: </h2>
<p>Object Detection using Haar feature-based cascade classifiers is an effective object detection method proposed by Paul Viola and Michael Jones in their paper, "Rapid Object Detection using a Boosted Cascade of Simple Features" in 2001. It is a machine learning based approach where a cascade function is trained from a lot of positive and negative images. It is then used to detect objects in other images.

Here we will work with face detection. Initially, the algorithm needs a lot of positive images (images of faces) and negative images (images without faces) to train the classifier. Then we need to extract features from it. For this, Haar features shown in the below image are used. They are just like our convolutional kernel. Each feature is a single value obtained by subtracting sum of pixels under the white rectangle from sum of pixels under the black rectangle.</p>

<img src="https://docs.opencv.org/master/haar_features.jpg"/>
<img src="https://docs.opencv.org/master/haar.png">
<br/>
<p>font: https://docs.opencv.org/master/db/d28/tutorial_cascade_classifier.html</p>
