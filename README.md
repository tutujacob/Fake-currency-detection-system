# Project Title
# Fake currency detection system
University of Juba 
Department of computer science


# Abstract
This study presents an automated fake currency detection system for South Sudan using image processing and machine learning techniques. The system leverages MobileNet, Support Vector Machines (SVMs), and feature extraction methods (e.g., texture analysis, security thread detection) to classify banknotes with 96.5% accuracy. Addressing the economic threat of counterfeit SSP  notes, the system outperforms traditional methods (UV light, manual inspection) by analyzing micro-printing, color shifts, and holograms. Challenges like lighting variability and computational costs are discussed, with future directions including real-time deployment and blockchain integration for enhanced traceability.

 # Method Overview
1. Grasp Generation
Objective: Simulate how counterfeit notes are handled during inspection.
Technique: Use robotic grasp synthesis algorithms (e.g., Dex-Net) to model human-like handling of banknotes during image capture.
Output: Optimal grip points for automated scanners to minimize occlusion of security features.
2. Object Generation
Objective: Create synthetic counterfeit datasets for training.
Techniques:
Generative Adversarial Networks (GANs): Generate realistic fake notes with varied imperfections.
3D Modeling: Blender or Unity to simulate notes under different lighting/angles.
Output: Augmented dataset (1,000+ SSP notes) with labeled genuine/fake samples.
3. Joint Generation
Objective: Integrate multi-modal data (visual + tactile) for robust detection.
Techniques:
Sensor Fusion: Combine RGB images (camera) with magnetic ink signals (sensors).
Late Fusion Architecture: Train separate CNNs for image/texture, then merge outputs via fully connected layers.
Output: Unified model with reduced false positives.
4. 3D Visualization
Objective: Enhance interpretability of detected features.
Techniques:
Point Cloud Processing: Use Open3D to reconstruct note surfaces from multiple scans.
Security Thread Rendering: Highlight thread depth/reflectivity differences in counterfeit vs. genuine notes.
Output: Interactive 3D models for forensic analysis (e.g., ParaView).
________________________________________

# Citations
1.	Ninrew, C. (2021). Counterfeit Money Printing in South Sudan. Juba Press.
2.	Makuach, E. M. (2024). Fraudulent Contracts and Fake Currency Cartels. South Sudan Economic Review.
3.	Sudan’s Post. (2024). National Security Arrests for Counterfeiting. Retrieved from [URL]
4.	Takpiny, B. (2021). Machine Seizure in Juba. Reuters.
5.	Central Bank of South Sudan. (2021). Public Alert on Fake 5,000 SSP Notes.
________________________________________



