# AgriVision-Early-Crop-Stress-Detection
AI-powered early detection of crop stress using multispectral imaging and sensor data


Project Overview

AgriVision is an AI-powered agro-advisory platform designed to detect crop stress and disease at an ultra-early stage (~0.1%), long before visible symptoms appear. The system combines multispectral/hyperspectral imaging, sensor data, and AI-based analysis to deliver actionable insights to farmers—even in internet-free regions via SMS alerts.


Problem Statement

Crop diseases are typically identified only after ~20% visible damage, when yield loss has already begun. Existing advisory systems are reactive, delayed, and often inaccessible to small and marginal farmers, especially in low-connectivity regions.


Our Solution

AgriVision enables proactive farming by:
- Detecting early physiological stress using spectral signatures
- Analyzing crop, soil, and weather data using AI
- Delivering alerts via mobile app and SMS
- Supporting regional languages and farmer-friendly insights


Key Innovations

- 0.1% Early Stress Detection using spectral analysis
- Multispectral / Hyperspectral Imaging
- Fusion-First AI (crop + soil + weather)
- Internet-independent SMS alerts
- Designed for small & marginal farmers


Product Workflow

Crop & Sensor Data
        ↓
Spectral Processing (NDVI, PCA)
        ↓
AI / CNN Models
        ↓
Early Stress Detection
        ↓
Decision Engine
        ↓
Mobile App Dashboard + SMS Alerts


Technologies Used

- AI & Data Processing
- MATLAB (Image Processing, Deep Learning Toolboxes)
- Python (TensorFlow, Keras, OpenCV)

Frontend
- Flutter / React Native
- Web Dashboard (HTML, CSS, JavaScript)
- Cloud & IoT
- Firebase
- AWS IoT / ThingSpeak

Hardware
- Multispectral / Hyperspectral Cameras
- Soil & Environmental Sensors
- GSM Module (SMS Alerts)

Prototype & Results

- Under test Dataset: https://www.kaggle.com/datasets/janmejaybhoi/cotton-disease-dataset
- ThingSpeak Channel: [Live Dashboard] Channel Id:3093053 (AgriVision)
- ThingSpeak Live : (https://github.com/user-attachments/assets/fbce8cf0-ea60-4666-9e82-ec1ec0eacaf2)
- Dashboard(Matlab Based): (https://github.com/user-attachments/assets/13a0cd38-758e-43ce-a930-acdf3033debd)
- Simulink model: (https://github.com/user-attachments/assets/11ddb2ac-fa7b-426e-b6ea-ca859fc974f5)

 
 Target Users
- Small & marginal farmers
- Agri-tech startups
- Government bodies & NGOs


Roadmap

- Field pilots and validation
- Multi-crop & multi-region expansion
- Government and institutional integration
- Predictive disease outbreak mapping



Team
Team AgriVision

📜 References

Hyperspectral Remote Sensing for Early Plant Disease Detection (MDPI)

MATLAB Hyperspectral Image Processing Docs

Kaggle Plant Disease Datasets
