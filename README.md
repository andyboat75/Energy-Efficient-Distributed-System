# <div align="center">Energy-Efficient-Distributed-System</div>

## <div align="center">Background And Motivational Scenario</div>

<div>
<p>
Massive amounts of data are constantly generated from the growing number of Internet of Things
(IoT) devices. Nowadays, sensor-based data are used in many applications, like eHealth, smart
manufacturing, intelligent traffic management, smart building systems. Such systems rely on
monitoring of parameters (e.g., temperature, movement, heart rate, energy consumption, power
production, radiation, pressure or air quality) coming from many sensors. Managing these
systems generally requires (i) sensor data collection, (ii) data processing and (iii) acting based on
the obtained results. Traditionally, such processing is done by employing geographically
distributed and massive data centers. Recently, edge computing has been proposed as a solution
to perform near-real-time decisions in the proximity of the user. Edge analytics rely on edge nodes
(e.g., Raspberry Pi, edge gateway or micro data center) that can be deployed closer to IoT
sensors and devices. By keeping data analytics close to the source of data, edge nodes can
minimize the latency for decision-making processes as well as to improve energy efficiency of
data transmission networks1
. Furthermore, predictive analytics have a huge potential to
revolutionize critical and proactive IoT systems such as accurate diagnosis of patients in eHealth,
timely maintenance services and failures prevention in smart manufacturing and building systems.
</p>
</div>

</br>

<div>
<p>
However, meeting the strict latency and accuracy requirements of decision-making processes
while performing predictive analytics in modern edge/IoT systems, imposes several issues.
Limited (i) storage capabilities and (ii) scalability of edge nodes can hinder the accuracy of
predictive analytics and timely decision-making for IoT systems. Also, users and IoT applications
can require various prediction horizons (windows) as well as different accuracy thresholds. 
</p>
</div>

<br>

<div>
<p>
We consider data generated by sensor-based monitoring, classified as time-series data. Based
on a certain amount of historical time series and recognized patterns, it is possible to predict future
values. The conclusions based on analyzed data generally assume that the future system
behavior will follow a behavior (pattern or trend) from the measured past. Accordingly, we can
use predictive analytics in the context of proactive decision-making. 
</p>
</div>

</br>

<div>
<p>
Figure 1 represents an edge analytics model for smart building use cases. In step (1), data are
collected from smart buildings. Due to the rapidly increasing amount of data generated, data can
be transferred to the edge layer in step (2). Once a certain amount of data is transferred to the
edge layer, the monitoring service cleans data and stores them to the limited edge storage (step
3). The available data are used in step (4) for near-real-time decision-making processes based
on the results of predictive analytics, while checking the knowledge base that can be updated with
dynamic user/application requirements. The knowledge base should contain recommendations
on the best trade-offs between the quantity of the data and prediction accuracy as well as the
most suitable forecasting methods for a particular dataset type regarding the prediction horizon.
The analytics results are used to take operative decisions, e.g., commands sent to actuators in
step (5). The mediator supports the edge layer and communicates with the cloud data repository
for resource-demanding batch analytics (step 6)
</p>
</div>
