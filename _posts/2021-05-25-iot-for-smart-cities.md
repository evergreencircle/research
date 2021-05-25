---
layout: post
---
Smart cities use IoT devices such as connected sensors, lights, and meters to collect and analyze data. The cities then use this data to improve infrastructure, public utilities and services, and more. 

Below, i've outlined how smart cities provide a more efficient and higher quality lifestyle for their residents, and the methods they use to reach these goals.

<img src="https://raw.githubusercontent.com/evergreencircle/research/master/Screenshot%202021-05-25%20at%2017.32.07.png" alt="Generative architecture">


<h2>Smart Agriculture</h2>
The major applications of AI in IoT for agriculture are crop monitoring/disease detection and data driven crop care and decision making. 
Considering the scarcity of water, the authors develop irrigation systems which monitor and control the amount of water being used for crops, 
all structured around a cloud computing system. This problem has been devised both as a classification as well as a regression problem,
who develop a closed loop water irrigation system using support vector regression and K-Means clustering. The authors propose cloud based
greenhouse monitoring systems using images and a host of physical parameters from plants such as temperature, humidity and light using several machine
and deep learning methods. Plant disease detection is also an important task within smart agriculture and has been worked on by the authors
who present schemes for disease detection for various crops including tomatoes and potatoes. The proliferation of sensing systems in agricultural fields
has also provided an avenue for data driven decision making and planning for farmers. This involves predicting various physical parameters which can affect 
crop growth like solar radiance and temperature, humidity, windspeed to help in decision making in terms of plant care but also classification
systems for recommending crops to be sown. It is important to note that all of these implementations are cloud based.

<h2>Smart City Services</h2>

A popular component of smart city initiatives is the management of waste and involves having bins equipped with sensors and connected to the cloud to 
not only inform the relevant authorities of the need to empty them but also using AI to determine the best route to reduce fuel consumption.
The use of IoT systems for waste management has been observed in the works  who utilize IoT systems to help reduce energy wastage in waste collection
by municipalities. Hussain  develop a waste management system that not only determines if bins are full and need collecting (using data from various 
sensors placed in the bin) but also predicts the air quality around it using RNNs. The sensing modalities in each of these applications is pretty similar 
in that they indicate to whether a waste bin is full or not which is then used for route planning. Considering the requirements of such a system, 
in terms of implementation, all of these systems are cloud based. Sewer monitoring has been performed in a cloud based system, they use sewer water level
and rain gauge data along with a RNN to perform sewer overflow monitoring. The RNN is used to predict sewer overflow ahead in time. Water quality 
has monitoring has been the focus  where the authors use multiple sensors measuring pH value, chloride, nitrate content and hardness of
water to determine whether it is fit for drinking or not. In the paper they  use data from water monitoring stations along the Yangtze river to predict water quality.
Like the classification-based systems, they use multiple chemical measurements from the water such as oxygen, pH, turbidity etc. Apart from air quality, 
city monitoring systems are an important application within the smart city services domain. This includes urban noise, which has been the focus of researchers in
as well as other more comprehensive monitoring systems as proposed. All these systems are cloud based and use a combination of sensors for sound and/or image 
data for performing noise monitoring/detection and various smart city dashboard applications. In Table 6, we summarize the type of deployments, applications 
task and data for smart city services applications. It is noted that most of the applications relating to city services such as air quality monitoring and 
prediction, sewer monitoring, waste collection have been proposed as cloud systems as data needs to be collected from nodes at various points in a city.
It is envisaged that due to the nature of the applications, many smart city services would still rely on cloud or fog architectures as the decision-making 
taking place in such situations isn’t possible on only a local level. It is also observed that most of the applications required data from multiple sensors 
and therefore utilized heterogeneous data to carry out the task at hand.

<h2>Smart Energy</h2>

Load/energy consumption forecasting is an essential task for monitoring and control of electrical power supply in the electricity
grid and ensure appropriate demand side management. It has been performed by the authors who use data collected from consumers in a smart grid 
to determine load for up to 24 h in advance. They treat this as primarily a clustering problem where they form clusters of similar load profiles
and then use distance functions to determine energy consumption for the future. The authors also use a cloud based clustering approach, using historical power data,
they use K-Means clustering to determine the closest historical records and then combine them to predict energy consumption 24 h in advance. 
The load forecasting problem has been dealt as a regression  using a SVM and through an RNN using electricity power data.
A regression approach is also followed by who use electricity consumption in addition to environmental data for load forecasting using deep learning methods 
(DNN and a combination of Autoencoders and RNNs (GRU)). Edge based systems have been suggested by the authors for load forecasting for household consumers, 
the authors use federated learning to train a RNN. In addition to load forecasting, smart grid management/monitoring is also a necessary application 
in this domain. The authors use decision trees in a cloud based system to classify between different faults in a smart grid. The authors use power consumption 
data from consumers in China to determine electricity theft in a cloud based system. They use wide and deep convolutional neural networks to capture
the periodic and nonperiodic components from electricity consumption data and show their network to be suitable for electricity theft detection. 
The authors present a framework for edge computing based monitoring of the smart grid. Edge computing in the smart grid has several advantages as it 
reduces delay and secure in terms of data privacy.

<h2>Smart Health</h2>

There are two major applications of IoT with AI in health, these are activity recognition/fall detection and disease diagnosis/health monitoring, 
a summary of the IoT based AI systems used in Smart Health is presented in Table 8. Activity recognition involves the use of movement sensors such 
as accelerometers, gyroscopes and magnetometers with the aim to help provide the user with feedback on their health in terms of them having 
enough physical exercise or not, used for sports therapy, fall detection and for monitoring of different diseases such as Parkinson’s or other motor
degenerative ailments. The most popular sensor for activity recognition are inertial sensors which have been used  in a cloud based setting using various 
deep and machine learning algorithms. The authors. include vital sign data in addition to movement information for human activity recognition
in a cloud environment, they utilize the DT as their classifier. The authors propose an edge-based system to perform activity recognition 
for people by recording their movements using the accelerometer and gyroscope present on the phone. They use a SVM as their
classifier and differentiate between six different activities of daily living. Fall detection has been performed in a fog and edge environment,
respectively, using an accelerometer, the author use a CNN while Yacchirema use RF with both approaches showing promising results.


<h2>Smart Homes</h2>

Ambient assisted living is a huge component of Smart Homes. This is especially needed for the elderly and is typically achieved by the use of ambient sensors,
Wi-Fi and radio frequency systems in smart homes. In this work, we include all monitoring methods that depend on sensors placed in the home/within the smart
home domain. The authors use a network of reed switches connected to the cloud to monitor the activities of elderly people as a clustering problem. They use
the K-NN algorithm to determine anomalies in the daily activities which can then be used to send medical or other help requests to assist people. 
A similar setup for activity recognition for ambient assisted living  where they use data from a number of different sensors including motion, presence,
water float, temperature etc to determine various activities being performed in a home. A cloud based assisted living system for the deaf has been developed 
that performs haptic conversions for sounds detected in a home. An array of sensors are used to monitor environmental sound and the authors use RNNs for
detecting the sound event before its passed on to the haptic vibration producer. Another task within in monitoring is localization of people, this part
of smart homes is also applicable to smart infrastructure in that such systems are used in smart buildings as well. Applications of localization include security,
i.e., detecting unauthorized presence and people monitoring in general (for, e.g., locating elderly people in homes) etc. The authors 
perform localization using a grid of Wi-Fi units that measure signal strength to determine peoples locations indoors for buildings. They formulate this 
both as a classification problem as well as a regression problem. The classification problem being formulated as coded locations (for, e.g., a given room no)
while the regression case estimating the location of the user in a coordinate grid. Their system is cloud based and they use a deep neural 
network to perform this task and have found suitably good results.

<h2>Smart Industry</h2>

One of the major applications of AI in the IoT powered smart industry is towards fault detection in products and anomaly detection in industrial processes. 
This has seen the use of both Machine Learning (SVM, RF as well as Deep Learning (DNN, CNN methods using a cloud computing structure to perform anomaly detection 
/product inspection and monitoring using a variety of heterogeneous and homogenous data sources such as inertial sensors for machines,
images for products and processes and other process specific variables. Other approaches suggested propose a fog computing method along with edge 
computing systems. An edge computing system for anomaly detection where edge devices collaboratively train a deep anomaly detection model. 
Production management is another application that has found usage of AI in IoT based smart Industry. For, e.g., the authors use cloud based data
driven systems along with machine and deep learning algorithms to help with task dispatching, performance analysis as well as worker activity recognition 
utilizing a variety of sensing modalities. The work of the authors are especially interesting as they aim is to not only perform production management 
but also propose data for various health related analysis to create a safer working environment on the factory floor. A fog system for production
management who use activity data to determine resource allocation locations to contribute to manage- ment of a production operation. 
Furthermore, product inspection, which is a common application of instrumentation systems in a factory, who utilize images and sensor data in
a cloud based system to monitor product quality.


<h2>Smart Transport</h2>

Major smart transportation applications involve smart parking and transportation management. 
Smart parking aims to solve the problem of helping users finding parking spots in order to save time as well as reduce gas emissions
and is therefore a much- researched topic for AI deployment towards smart transportation. Solutions to this problem have been formulated 
both as a regression problem as well as a classification one, both utilizing imaging and/or other occupancy sensing modalities. Regression solutions 
are typically used to predict a parking lots occupancy levels in the future whereas classification systems 
involve guiding drivers according to the shortest distance as well as used for user localization purposes within such lots.
In addition to cloud based approaches, edge computing systems for smart parking who deploy CNNs on edge devices for occupancy detection and user
localization, respectively. Another application of AI IoT for smart transportation involves determining traffic flow as well as prediction of
traffic flow for traffic light control and other management tasks such as accident detection. In this regard, video cameras are popular for detection 
of vehicle density on roads for traffic congestion determination. However, with most cars having a GPS device and the commonality of cellphones with 
every driver, many approaches use the data from the GPS along with weather and generic traffic flow information to determine traffic prediction.
The nature of traffic flow prediction using sensing modalities such as GPS require systems to be operated as cloud-based systems. 

The area of AI has a large scope for potential work. 
This includes the development of data fusion techniques that can make the use of heterogeneous data sources easier, intelligent data reduction/feature 
selection methods to ensure that redundant or ’uninteresting’ data is not part of the AI development pipeline.
This will help in a quicker turnaround time as well as improved performance of deployments. Current methods need to be used as well as new 
ones be researched for making ML and DL algorithms more explainable to suit the various applications in a smart city.

<h2>Used Materials</h2>
<ol>
  <li><a  href="https://www.mdpi.com/2624-6511/4/2/24">IoT in Smart Cities: A Survey of Technologies, Practices and Challenges
</a></li>
<li><a href="https://www.businessinsider.com/iot-smart-city-technology">How IoT and smart city technology works: Devices, applications and examples</a></li>

