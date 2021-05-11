### Intro: Data Engineer or Software Developer - Data Framework Development and Data Management

from Taiwan. 

finished bachelors degree in ME, study abroad here in Sweden.
-----------------------------------
The topic of my thesis is about acoustic measurements of cooling fan noise on electric vehicles, 
The main goal is basically to understand the installation effects, 
find out the correlation between different measurement setups and 
explain the reason behind the difference between these acquired sound pressure levels, 
and also the characteristic of fan noise. 
-----------------------------------
At the beginning of my masters degree, I actually didn't have a strong idea about 
what I am really interested in and which domain that I want to devote myself to. 

After noticing autonomous driving, my fascination about it start to grow and I spent time and try to know more about it, for example listening to relevant podcast or online seminars. The more I dig into, the cooler I find this topic. 
So I decide to aim for a job that is related to SDC after graduation. 
-----------------------------------
I start taking online courses and improving my programming skills. But at the same time, I managed to handle the courses and exams at KTH well, despite of the fact that they are completely different fields. And I still have my own time to hang out with friends living in the same corridor. A good time management plays an important role in my case.
-----------------------------------
To be more specific about my programming skills . C++, Python and Matlab
-----------------------------------
As for experiences with sensors, I've been working with several kinds of sensor data, such as Lidar, Camera, distance sensors, pressure sensors, microphones, accelerometers.

Some of them are materials or source data from online courses and some are side projects that I've been doing. 
-----------------------------------
Out of my own interest, I completed two Machine Learning courses at KTH. 
This deepens my understanding about knowledge behind ML&DL algorithm, how to implement them and familiarize me with data-driven approaches. 


The reason why I choose Volvo Cars is 
	- The awesome experience during this thesis work. Feel welcoming
	- Safety is the most important aspect for AD and this prefectly align with the goal of Volvo Cars.
	- With international and diversified working environment, it would be fantastic for me to work here!

### About Me
Why did you come to Sweden?
It's amazing and surprising to me that a small country, in terms of population, has a lot of world class companies
such as Volvo, IKEA, ABB, Spotify. Also well-known for it's social welfare.
My dad have been here few times and he strongly recommended me to come and visit this country

Pros:
-  Learn new things fast.
	ex: 
-  Adapt to new environment quickly.
	ex: 
-  Ability to quickly search for useful information on the Internet
	ex:
-  Great team player: willing to listen and cooperate with each other to come up with new solutions
	ex: 
-  Come up with quick and useful methods/solutions
	ex: 
-  Hard working, decicate to things and challenges that I am really interested in.


Cons:
1. Get nervous easily, especially with important things or things that I really care about
2. Sometimes I can't convey my ideas clearly.
3. Work too hard, forgot to maintain work-life balance
3. Low efficiency 


My hobby: 
- Basketball
- I love to travel, but due to the pandemic situation
- Listen to music, R&B music makes me chill and relax, and play giutar 


Facing some challenges??
 - basketball team captain

Any achievement??

 
### Online courses:
1. Sensor fusion:
	- basic knowledge of Lidar, camera, radar. Strength and weakness of each sensor
	- PCL 
	- Camera object tracking using keypoints detection
	- Project 3D point clouds into 2D images using trasformation matrices(homogenous coordinates)
	- Kalman filter
2. Self driving cars:
	Really gives me a comprehensive overview of how an autonomous vehicle works and what is important for building a self driving car. 
	- Lane detection 
	- Traffic sign classification
	- Behavior cloning
	- Path planning, trajectory generation
	- PID controller



### Projects:

1. Lidar = Point Cloud Library in C++, pipeline of processing lidar data.
	a. Load point cloud data
	b. Segmentation using RANSAC(random sample consensus), separate ground surface points from obstacles
	c. Eulidean Clustering using KD tree(more efficient)
	d. Define bounding boxes(PCL function)
	e. Working with streaming point cloud data
		- downsampling: because sending all these point cloud data in vehicle network is too expensive.
		- filtering with PCL: change resolution

2. KTH Hyperloop: eletronics and software team.
	- establish communication system
	- CAN bus between microautobox and Arduino
	- communication with teammates to make sure our goal and what should be the first priority.
	- Virtual CAN simulation using Vehicle Network Toolbox

3. Lane detection
	A. Preprocess images using computer vision algorithm
	B. Identify lane pixels and fit it to certain lane boundary
	C. Draw the lane on the original image


	a. Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
	b. Apply a distortion correction to raw images.
	c. Use color transforms, gradients, etc., to create a thresholded binary image.
	d. Apply a perspective transform to rectify binary image ("birds-eye view").
	e. Detect lane pixels and fit to find the lane boundary.
	f. Determine the curvature of the lane and vehicle position with respect to lane center.
	g. Warp the detected lane boundaries back onto the original image.
	h. Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position

5. Image caption generator (Google Colab)
	Python, TensorFlow,
	a. Dataset = images + corresponding caption
	- separate into training set, validation set and test set
	b. Concentrate caption sentences into volcabulary vectors
	c. Use word embedding to convert words into numbers
	d. Pass images through CNN to get feature map vector
	e. Pass word embedding as input of LSTM layers
	f. Use these two as input of fully connected(Dense) layer 
	g. Get predicted caption for unseen images




### Questions

- 

1. Direct employment from Scania? Is this a paid internship?

2. What are the IT positions or teams that we can choose from? 
	Is there any position that is related to autonomous driving?

3. 













1. What's the goal of AD? Level 3? L4 or L5?

2. Why decide to use Lidar instead camera-only-based system? Expensive and hard to package?

3. Personal development, possibility of relocation after few years?

4. Safety - driver monitoring system. Current state?

5. In-house production






