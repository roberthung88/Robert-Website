---
name: IoT Project
tools: [C++, C, Python,  Raspberry Pi, Grove Pi Light Sensor, OpenMote, MQTT, UDP, ]
image: /assets/images/bence-boros-anapPhJFRhM-unsplash.jpg
description: Designed a home IoT system with easily deployable, battery-powered sensor nodes
external_url: 
---
{% include elements/button.html link="https://github.com/roberthung88/IoT-Project" text="GitHub Link" style="outline-dark" size="lg" %}

- Designed a home IoT system with easily deployable, battery-powered sensor nodes that will detect the intensity of light in each room of the house in order to determine when the lights have been turned on and off throughout the day. 
- The Raspberry Pi (Grove Pi Light Sensor) is employed along with an OpenMote to relay data to an MQTT broker using UDP. 
- A Ubuntu virtual machine analyzes data received from the MQTT server and sets up a Flask web server to display the results. 
