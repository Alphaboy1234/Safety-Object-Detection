# Safety-Object-Detection
This project implements an AI-powered object detection system for identifying critical safety equipment in space station environments
Developed for the AI Space Station Hackathon, our solution leverages YOLO (You Only Look Once) architecture and synthetic data from Duality AI's Falcon digital twin platform to create a robust, real-time safety monitoring system.
<img width="981" height="710" alt="image" src="https://github.com/user-attachments/assets/27913465-cd81-4de6-a895-7cd9c06ff36b" />

Critical Equipment Monitoring
Oxygen tanks, fire extinguishers, and emergency tools essential for crew survival
Manual Oversight Limitations
Error-prone tracking in dynamic, confined environments with limited crew bandwidth
Real-Time Detection Need
Automated systems vital to prevent emergencies and ensure rapid response capabilities

Powered by Advanced Computer Vision
YOLO Architecture
YOLO (You Only Look Once) is a single-stage object detection architecture that detects objects in an image in one forward pass of a neural network.

👉 Instead of first finding regions and then classifying them, YOLO does everything at once:

Finds where objects are (bounding boxes)

Decides what they are (class labels)

Estimates confidence

All in real time.
Synthetic Training Data
How YOLO Works (Step-by-Step):
Image passes through the backbone
Features are fused in the neckDetection head outputs predictions
Apply NMS
Final bounding boxes are produced
Multi-Class Detection
Identifies oxygen tanks, fire extinguishers, toolboxes, and other critical equipment

Google Technologies used in the solution:
Co-Lab;
Google Drive;
Google Cloud Services.
