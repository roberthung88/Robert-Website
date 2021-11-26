---
name: Left Turn Safety System
tools: [Python, Jetson Nano]
image: /assets/images/16271-NVIDIA_Jetson_Nano_Developer_Kit__V3_-01.jpeg
description: System that determines whether it is safe to turn left
external_url: 
---
{% include elements/button.html link="https://github.com/roberthung88/Left_Turn_Safety_System" text="GitHub Link" style="outline-dark" size="lg" %}

- Used **OpenCV** and trained the **MobileNet-SSD** detection network to detect vehicles. Measured their distances using binocular camera--preprocessed images using **Rectification, Stereo-matched** images from both cameras, and used **Stereo Vision** method (trigonometry, focal length… etc.). Velocity is determined by dividing distance by 1/FPS. Distance and Time of Arrival are then processed to determine if it is safe for a vehicle to turn left. 




