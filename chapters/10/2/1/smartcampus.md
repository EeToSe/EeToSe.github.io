# Data Analysis for Smart Buildings

## Background: UNSW Smart Campus

Gain insights into the behavior of real estate usage on UNSW  through the instrumentation of IoT devices. Mainly covered areas: 

1. Bus queue
2. Classroom attendance
3. Car park
4. Wifi

## EE building Sensor Network
1. Deploy a **sensor network** system based on prior work from our research group
2. collect and cleanse sensor data from the HPD camera and beam counters installed in the Electrical Engineering building at UNSW.  
3. Improve the estimated occupancy accuracy by **sensor fusion**.
4. **Data visualization** is performed to answer the question of the elevator and shared study space usage.

### Sensors 

```{figure} ../../../../images/smartcampus/sensors.png
---
scale: 100%
name: Beam counter and Human counting camera
---
Beam counter and Human counting camera
```

```{figure} ../../../../images/smartcampus/device_statistics.png
---
scale: 100%
name: Device installation info
---
Device installation covering labs, meeting rooms and corridors
```


### Sensor Network 
Yellow routers are white listed by IT department provided with Mac address. They could therefore connected with uni_wide device(campus network) through tunnelling of VPN.

### VPN 

Tinc run on routers and the sensor_server with key pairs generated.

Server: open certain port to listen to the connections from routers.

Routers: store the hard-coded server list.

```{figure} ../../../../images/smartcampus/vpn_hosts.png
---
scale: 58%
align: left
---
Vpn hosts
```

```{figure} ../../../../images/smartcampus/vpn_table.png
---
scale: 70%
align: right
---
Vpn table
```


##  Data Visualization  
{download}`Poster <./poster.pdf>`, {download}`Thesis report <./Thesis_Report.pdf>` and {download}`Seminar presentation <./Seminar.pdf>` could be found here if if interested.

