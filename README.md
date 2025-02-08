Polygon Area Calculator

The project is based on bus tracking system that is designed to give a real time location of different

buses at different bus stations. We will be monitoring the bus location using RFID sensors, tags. Users can get personalized updates about a particular bus in which he/she wants to travel. User will
get bus location, arrival/departure timing at different bus station and bus routes, providing
passengers with an intuitive interface to check if their bus has reached a station or left. With the
help of tracking user can see how far the bus is, this allows user to plan their route and travel plan
accordingly. Users can enter their route or station to get personalized updates, helping them plan
their journeys and reduce waiting time at stations.
The core technology behind the system is RFID (Radio Frequency Identification), where each bus is
equipped with an RFID tag, and RFID readers are installed at every bus station. As buses arrive at or
depart from a station, their RFID tags are scanned by the station’s reader, allowing the system to
track the precise moment of arrival and departure.

Key Features of the system-
1.Bus Location Detection- When a bus enters a particular bus station the bus arrival is

detected using RFID reader which will be located the entry gate of the station, when a bus leaves
that station, another RFID located at the exit gate will detect the departure of that bus from that
station.
2.RFID-Based Tracking- Each bus is equipped with an RFID tag that is scanned by a RFID reader
when it enters or leaves a station, ensuring accurate movement of the bus.
3.Bus Scheduling- Our system is tracking bus schedules providing important information like bus
delays, timing of arrival, etc to the users.
4.Easy to use app/website- Our website is made in such a way that it will be very easy to
access by the passengers. The UI of the system will help the user to easily understand the
information about a bus.

INTRODUCTION

Motivation behind this project-
Public transportation, especially buses is a lifeline of millions of Indians. Every person find bus as theeasiest way of transportation. Whether in rural or urban, whether going far distances or small, buses
are first choice of Indians. However, one of the most common challenges faced by them is unpredictable timing of arrival and departure of the buses, unknown routes of the bus. Thisproblem leads to long waiting time in bus stations, confusion about route of the bus. This major problem causes inefficiency in bus transportation.
In a densely populated country like India where urban mobility, time is very important for everyone
there is a need of system that gives real time location of the bus a person wants to travel in so that
he/she gets timely update about the bus, they do not waste hours in waiting for that bus. Such a
system can give passengers with timely updates of buses, estimated arrival time and route
information so that their journey can become stress free.
Statistics Data on the Need for a Real-Time Bus Tracking System in India:
Over 70% of urban population in India depend on public transportation, with buses being the most
common mode of commute.

1.Unpredictability of Bus Services- 60% of passengers frequently experience delays, with waiting
times extended by 20 to 30 minutes at bus stops due to the absence of real-time tracking systems.

2.Loss of Time and Productivity- 40% of urban passengers spend an additional 30 minutes or more
each day waiting for buses due to schedule uncertainties. This results in a cumulative annual loss of
hundreds of hours per individual, affecting productivity and personal time.

3.Traffic Congestion and Inefficient Routing- 25% of buses in metropolitan areas operate off-
schedule due to inefficient routing and fleet management.

4.Commuter Dissatisfaction- Over 40% of bus commuters are dissatisfied with the reliability of
public bus services, citing issues such as unpredictable arrival times and frequent breakdowns.

5.Shift Toward Private Vehicles-The inefficiency of the bus system has led to a gradual shift towards
private vehicles, further increasing traffic congestion and pollution in cities.

6.Scale of Public Bus Operations-There are over 1.2 million buses operating across India, highlighting
the scale of the issue and the need for solutions like real-time tracking to improve the efficiency of
public transportation.

Unique Functionality of the project-
1.Real time bus location tracking-The system uses RFID sensors, ESP-32 and IoT technology to
provide real-time updates on the location of the bus. Users can check bus arrival and departure
accurately.

2.Bus Timing detection- Users can see the bus arrival and departure timing at different stations,
helping them to schedule their trip accordingly.

3.No dependency on third party- As we are not using GPS to track the bus so there is no dependency
on third party like satellites.

3. Real-Time Alerts for Users- The system can send notifications to Users through mobile
applications or digital displays, informing them of bus status, delays, or route changes.

4.Accurate information about buses-We are using RFID tags and sensors in place of GPS as it is
highly accurate, cost effective and its independency on other devices.

Technical overview Of Our Project-
1. Hardware Components:

a) ESP32 Microcontroller-Dual-core, with integrated Wi-Fi and Bluetooth.
b) RFID Reader- RC522 or PN532 for reading RFID tags.
c) RFID Tags-Unique identification for each bus.
d) Power Supply-USB or battery-powered.

2. Software Components:

a) Development Environment-
b) Backend Server-Implemented using Node.js and Express.

c)Database- Using MongoDB for storing bus data.

3. System Architecture:

Data Flow-
1.RFID reader detects bus as it enters or exit the station.

2.ESP32 sends bus ID and station data to the backend via HTTP.
3.Backend updates bus status in the database and can send real-time updates to users.

4. Deployment:
1.RFID Readers: Installed at bus stations for coverage
