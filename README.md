# NMEA-2000-influxdb
An esp32 which posts traffic in the NMEA 2000 BUS to an InfluxDB 2.7 instance

## Table of contents

- [Electrical](/Electrical): A KiCad project
- [Mechanical](/Mechanical): 3D files for casing etc.
- [Software](/Software): Arduino IDE sketches
  - [Receiver](/Software/Receiver): A NMEA-2000 Receiver
  - [Listener](/Software/Listener): The ActisenseListener
  - [NMEA-2000-influxdb](/Software/NMEA-2000-influxdb): The main sketch of the programm

## Features

- [x] Listen for all known PGNs
- [x] Post data to an InfluxDB 2.7 instance
- [ ] Save data to an SD-Card while offline 
- [ ] Use wifimanager
