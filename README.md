# VisionGuard
AI-powered computer vision safety and security project
VisionGuard – Project Details
Project Name & Title
Project Name: VisionGuard
Project Title: Image Captioning and Segmentation
Students: Megha C & Sharmila B
Register Numbers: 312723143016 & 312623243028
Problem Statement
Urban traffic scenes contain many objects and interactions causing hazards, such as:
Jaywalking
Signal violations
Existing image captioning models:
Describe general scenes but not safety-critical details
Need:
Detect & segment traffic-relevant objects
Identify hazards from spatial & behavioral cues
Generate short, safety-focused captions for real-time risk awareness
Project Overview
VisionGuard is an AI-powered system to improve urban traffic safety, integrating:
Instance segmentation
Hazard detection
Natural Language Generation (NLG)
Output: Safety-prioritized captions of traffic scenes
Applications:
Real-time monitoring for traffic management
Autonomous vehicles
Smart city solutions
Data Collection & Preparation
Image Captioning Dataset: COCO
330,000+ images, each with 5 captions
Captions describe objects & interactions
Preprocessing:
Pairing images with captions
Converting words into sequences
Normalizing sequence lengths
Segmentation Datasets: Cityscapes & ADE20K
Pixel-level labels (road, vehicle, pedestrian, etc.)
Preprocessing:
Resizing images & masks
Adjusting colors & values
Matching labels
Data augmentation (flipping, rotating)
Performance (Results)
Captioning model generates context-aware descriptions
Segmentation model accurately detects hazards/objects (IoU & Dice scores)
Real-time video streaming with low latency and stable outputs
System generalizes well to unseen scenarios
Improvements (Future Work)
Expand and diversify datasets for better accuracy
Use transformer-based captioning
Adopt attention-driven segmentation
Edge computing and efficient streaming
Add explainability and error-detection mechanisms
Final Evaluation
VisionGuard integrates captioning, segmentation, and video streaming into a single system.
Provides strong performance in real-time hazard detection and scene understanding
Scalable and adaptable for practical use
Potential for further improvement via model optimization and dataset expansion
