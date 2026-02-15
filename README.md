# Q-SAR: Drone Swarm for Disaster Management

Q-SAR is a multi-tier autonomous drone swarm system designed to enhance Search and Rescue (SAR) operations following natural disasters. By combining high-altitude surveillance with low-altitude specialized sensing, the system overcomes visibility and energy constraints to locate survivors trapped under rubble.

## 📺 Project Media
Check out our project in action:
* **[Watch the Project Demo Video](https://youtu.be/QRfBWPBJPi8)** - A walkthrough of the swarm coordination, radar detection, and the Command-and-Control Center interface.

## 🚀 Key Features
- **Two-Tier Swarm Architecture**: High-Altitude Drones (HAD) for initial scanning and Low-Altitude Drones (LAD) for precision detection.
- **Advanced Survivor Detection**: 
  - **Vision**: YOLOv8x model optimized for identifying visible survivors from aerial feeds.
  - **Under-Rubble**: Sensor fusion of UWB (Ultra-Wideband) and FMCW (Frequency-Modulated Continuous Wave) radars paired with Machine Learning to detect non-visible targets.
- **Autonomous Navigation**: Mission planning using the **Dronekit** library and obstacle avoidance for independent traversal to GPS coordinates.
- **Extended Missions**: Integrated Wireless Power Transfer (WPT) using Series-Series (SS) topology for contact-less charging.

## 🛠️ Technical Stack
- **Hardware**: Holybro X500 v2, Pixhawk 6C, Raspberry Pi, UWB & FMCW Radar Sensors.
- **Software**: Python, C++, Dronekit, MAVLink, ROS.
- **Machine Learning**: YOLOv8x, Random Forest, Decision Trees.
- **Cloud/Backend**: Google Cloud Platform (Pub/Sub, Storage), Web Dashboard.

## 📂 Resources & Documentation
- **[Project Presentation (PPT)](https://docs.google.com/presentation/d/1GuK2ukiBfY5889AIufr_lNgSNQnPzgkO/edit?usp=sharing&ouid=112473724491935455171&rtpof=true&sd=true)** - Detailed slides covering the methodology, hardware design, and experimental results.


## 📊 Performance
- **94.08% Detection Accuracy** achieved through sensor fusion and ML in varied disaster scenarios.
- **20% Improvement** in disaster response efficiency compared to traditional methods.
