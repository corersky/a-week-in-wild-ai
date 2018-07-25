

#### A brief survey : Autonomous Vehicles

------------
> Contents

- [Timeline](#timeline)
- [The why](#the-why)
- [Autonomy Levels](#autonomy-levels)
- [Autonomous vehicle enabling technologies](#autonomous-vehicle-enabling-technologies)
  - Sensors & Cameras
  - Local Data Processors
  - High-performance GPS
  - Radar
  - LIDAR
  - Smart Technologies
  - Connectivity to the Internet of Things
  - Cloud-Based Data Processing & Management
  - Artificial Intelligence
  - Machine Learning
- [Autonomous vehicle architecture](#autonomous-vehicle-architecture)
- [Literature review](#literature-review)
- [Implementations and libraries](#implementations-and-libraries)
- [startups](#startups)

-------------

#### Timeline

- [History of autonomous cars](https://en.wikipedia.org/wiki/History_of_autonomous_cars)
- [Intelligent transportation system](https://en.wikipedia.org/wiki/Intelligent_transportation_system)
- [A Timeline of the Automobile Industry](https://www.scaruffi.com/politics/cars.html)
- [History of the Automotive Industry](https://www.preceden.com/timelines/263578-history-of-the-automotive-industry)
- [The Evolution of the Auto industry](https://www.timetoast.com/timelines/1201032)
- [Timeline of motor vehicle brands](https://en.wikipedia.org/wiki/Timeline_of_motor_vehicle_brands)
- [List of automobile manufacturers](https://en.wikipedia.org/wiki/List_of_automobile_manufacturers)
- [List of current automobile manufacturers by country](https://en.wikipedia.org/wiki/List_of_current_automobile_manufacturers_by_country)
- [List of current automobile manufacturers (alphabetical)](https://en.wikipedia.org/wiki/List_of_current_automobile_manufacturers_(alphabetical))
- [Autonomous car](https://en.wikipedia.org/wiki/Autonomous_car)
- [The Self-Driving Car Timeline – Predictions from the Top 11 Global Automakers](https://www.techemergence.com/self-driving-car-timeline-themselves-top-11-automakers/)
- [The Evolution of Self-Driving Cars](https://nytjournal.org/articles/ai_articles/evolution_of_self_driving_cars.php)
- [Evolution of Self Driving Autonomous Car](http://robotglobe.org/evolution-of-self-driving-autonomous-car/)

--------------

#### The why

- [73 Mind-Blowing Implications of Driverless Cars and Trucks](https://medium.com/@DonotInnovate/73-mind-blowing-implications-of-a-driverless-future-58d23d1f338d)
- [The Unintended Ways Self-Driving Cars Will Change Our World](https://medium.com/swlh/the-unintended-ways-self-driving-cars-will-change-our-world-3b15d1db9026)
- [Why do we need self-driving cars?](https://www.quora.com/Why-do-we-need-self-driving-cars-1)
- [Andrew Ng: Do we really need self driving cars?](https://www.quora.com/Andrew-Ng-Do-we-really-need-self-driving-cars)
- [Top 20 Pros and Cons Associated With Self-Driving Cars](https://www.autoinsurancecenter.com/top-20-pros-and-cons-associated-with-self-driving-cars.htm)
- [Why do we need Driverless Cars?](https://www.quora.com/Why-do-we-need-Driverless-Cars)
- [We don't need fully self-driving cars to save lives](https://www.usatoday.com/story/tech/columnist/2018/02/04/we-dont-need-fully-self-driving-cars-save-lives/1085965001/)
- [~$1 trillion of real estate is on the move … here’s why](https://medium.com/99-mph/1-trillion-of-real-estate-is-on-the-move-heres-why-94ee9233e5eb)

--------------

#### Autonomy Levels

SAE (J3016)


<table class="wikitable">
<caption>
</caption>
<tbody><tr>
<th>SAE Level</th>
<th>Name</th>
<th colspan="2">Narrative definition</th>
<th>Execution of<br />steering and<br />acceleration/<br />deceleration</th>
<th>Monitoring of driving environment</th>
<th>Fallback performance of dynamic driving task</th>
<th>System capability (driving modes)
</th></tr>
<tr>
<td colspan="8"><i><b>Human driver monitors the driving environment</b></i>
</td></tr>
<tr>
<td>0</td>
<td>No Automation</td>
<td colspan="2">The full-time performance by the human driver of all aspects of the dynamic driving task, even when "enhanced by warning or intervention systems"</td>
<td>Human driver</td>
<td rowspan="3">Human driver</td>
<td rowspan="3">Human driver</td>
<td>n/a
</td></tr>
<tr>
<td>1</td>
<td>Driver Assistance</td>
<td>The driving mode-specific execution by a driver assistance system of "either steering or acceleration/deceleration"</td>
<td rowspan="2">using information about the driving environment and with the expectation that the human driver performs all remaining aspects of the dynamic driving task</td>
<td>Human driver and system</td>
<td rowspan="2">Some driving modes
</td></tr>
<tr>
<td>2</td>
<td>Partial Automation</td>
<td>The driving mode-specific execution by one or more driver assistance systems of <i>both steering and acceleration/deceleration</i></td>
<td>System
</td></tr>
<tr>
<td colspan="8"><i><b>Automated driving system monitors the driving environment</b></i>
</td></tr>
<tr>
<td>3</td>
<td>Conditional Automation</td>
<td rowspan="3">The driving mode-specific performance by an automated driving system of all aspects of the dynamic driving task</td>
<td>with the expectation that the <i>human driver will respond appropriately to a request to intervene</i></td>
<td rowspan="3">System</td>
<td rowspan="3">System</td>
<td>Human driver</td>
<td>Some driving modes
</td></tr>
<tr>
<td>4</td>
<td>High Automation</td>
<td><i>even if a human driver does not respond appropriately to a request to intervene</i></td>
<td rowspan="3">System</td>
<td>Many driving modes
</td></tr>
<tr>
<td>5</td>
<td>Full Automation</td>
<td><i>under all roadway and environmental conditions</i> that can be managed by a human driver</td>
<td>All driving modes
</td></tr></tbody></table>

---------------------

#### Autonomous vehicle enabling technologies


- [The Building Blocks of Autonomous Control](https://s3.amazonaws.com/visionsystemsintelligence/pdfs/VSI%20AUVSI%20Presentation_July_2016.pdf)
- [Autonomous Vehicles – Risk or Opportunity?](https://higherlogicdownload.s3.amazonaws.com/AUVSI/14c12c18-fde1-4c1d-8548-035ad166c766/UploadedImages/documents/Com/ComSeries-Full.pdf)
- [Autonomous Car](https://www.slideshare.net/asertseminar/autonomous-car-32512833)
- [Machine Learning for Self-Driving Cars](https://www.slideshare.net/jwiegelmann/machine-learning-for-selfdriving-cars)
- [Autonomous Vehicle Implementation Predictions
Implications for Transport Planning](https://www.vtpi.org/avip.pdf)
- [GM: 2018
SELF-DRIVING
SAFETY REPORT](https://www.gm.com/content/dam/gm/en_us/english/selfdriving/gmsafetyreport.pdf)
- [Towards Autonomous Driving](https://s21.q4cdn.com/600692695/files/doc_presentations/2018/CES-2018-final-MBLY.pdf)
- [Measurements Systems and Sensors for
Autonomous Vehicle and Smart Mobility](http://vancouver.ieee.ca/files/2017/12/IEEE-DL-Saponara.pdf)
- [Three Sensor Types Drive Autonomous Vehicles](https://www.sensorsmag.com/components/three-sensor-types-drive-autonomous-vehicles)
- [Industry 4.0: the fourth industrial revolution – guide to Industrie 4.0](https://www.i-scoop.eu/industry-4-0/)


------------


![sd-tech](https://github.com/gopala-kr/a-week-in-wild-ai/blob/master/04-ai-in-transportation/sd-tech.JPG)


Source: [MIT-TR](https://www.technologyreview.com/s/609674/whats-driving-autonomous-vehicles/)

--------


![cs](https://github.com/gopala-kr/a-week-in-wild-ai/blob/master/04-ai-in-transportation/img/c_s.JPG)

--------------

![gps](https://github.com/gopala-kr/a-week-in-wild-ai/blob/master/04-ai-in-transportation/img/gps.JPG)

---------------

![radar](https://github.com/gopala-kr/a-week-in-wild-ai/blob/master/04-ai-in-transportation/img/radar.JPG)

----------------------
![lidar](https://github.com/gopala-kr/a-week-in-wild-ai/blob/master/04-ai-in-transportation/img/lidar.JPG)

----------------------

![smart](https://github.com/gopala-kr/a-week-in-wild-ai/blob/master/04-ai-in-transportation/img/smart.JPG)

-----------------

![iot1](https://github.com/gopala-kr/a-week-in-wild-ai/blob/master/04-ai-in-transportation/img/iot1.JPG)

------------------------
![cloud](https://github.com/gopala-kr/a-week-in-wild-ai/blob/master/04-ai-in-transportation/img/cloud.JPG)

----------------------

![ai](https://github.com/gopala-kr/a-week-in-wild-ai/blob/master/04-ai-in-transportation/img/ai.JPG)

-------------------------


![ml](https://github.com/gopala-kr/a-week-in-wild-ai/blob/master/04-ai-in-transportation/img/ml.JPG)

-------------------------

![ldp](https://github.com/gopala-kr/a-week-in-wild-ai/blob/master/04-ai-in-transportation/img/ldp.JPG)

-------------------------

AI, deep learning, Kalman filter, MPC controller, Path Planning, Semantic Segmentation, Localization, sensor fusion

Machine Learning
Deep Learning
C++
Python
Computer Vision
Robotics
Perception
Prediction
Localization
Calibration
Motion Planning
Motion Controls
Simulation
UI / Visualization
Vehicle Infrastructure
Backend / Front End Software Engineers


➢ Computer Vision and Deep Learning
- Traffic Sign Classifier
- Behavioural Cloning
- Advanced Lane Finding
- Vehicle Detection and Tracking
➢ Sensor Fusion, Localisation and Control
- Extended Kalman Filter Project
- Unscented Kalman Filter Project
- Kidnapped Vehicle Project
- PID Controller Project
- Model Predictive Control Project
➢ Path planning, Concentrations and Systems
- Path Planning Project
- Semantic Segmentation
- Programming a Real Self-Driving Car



---------------

#### Autonomous vehicle architecture

Working mechanism of AV's

-------------

![gm](https://github.com/gopala-kr/a-week-in-wild-ai/blob/master/04-ai-in-transportation/img/gm.JPG)

------------------

#### Literature review




-------------------

#### Implementations and libraries

---------------

#### startups


- [44 Corporations Working On Autonomous Vehicles](https://drivinghacks.quora.com/Quicklook-44-Corporations-Working-On-Autonomous-Vehicles)
- [Moving Bits and Atoms at Scale – Uber Marketplace Architecture](https://docs.google.com/presentation/d/1aAkDp5JViza6UVT9Dbi02MI0ByE8iOu8UNMcotXR0cM/pub?start=false&loop=false&delayms=3000&slide=id.g1db52c1b40_0_232)
- [9 Startups In India Working On Self Driving Technology](https://analyticsindiamag.com/9-startups-india-working-self-driving-technology/)


---------------
---------------