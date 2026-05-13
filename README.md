🌿 AgroSense — AI Powered Crop Detection and Residue Utilization System
📌 Overview

AgroSense is an AI-powered smart agriculture system developed to combine plant disease detection, crop identification, and crop residue utilization analysis into a single intelligent platform. The project leverages Deep Learning, Transfer Learning, and Computer Vision techniques to analyze agricultural images and provide meaningful insights for sustainable farming practices.

The system is designed with two dedicated AI analysis modules:

Leaf Analysis Module for disease detection , crop recognition , Possible Residue and Utilization Suggestion
Crop/Fruit Analysis Module for crop identification , Possible Residue and Utilization Suggestion

By integrating agricultural intelligence with sustainable residue management, AgroSense aims to support eco-friendly farming and improve awareness about agricultural waste utilization.

🚀 Features
🍃 Leaf Analysis Module

The Leaf Analysis Module accepts plant leaf images and performs:

Crop type identification
Plant disease detection
Crop residue information extraction
Residue utilization recommendations

This module is trained on labeled plant disease datasets using Deep Learning image classification techniques.

Supported Crops
Apple
Corn (Maize)
Grape
Potato
Tomato
Example Predictions
Apple Scab
Black Rot
Early Blight
Late Blight
Healthy Leaves
🍎 Crop/Fruit Analysis Module

The Crop/Fruit Analysis Module accepts crop or fruit images and:

Identifies the crop type
Displays agricultural residue details
Suggests sustainable residue utilization methods

Unlike the disease detection model, this module uses ImageNet-based prediction through MobileNetV2 to identify crops from general crop/fruit images.

🧠 AI & Deep Learning Architecture
📷 Computer Vision Pipeline

The project uses image classification techniques to process uploaded agricultural images.

Workflow
User uploads an image
Image preprocessing is applied
AI model analyzes the image
Predictions are generated
Crop residue intelligence is displayed

