🌐 
DDoS Detection & Prevention with Machine Learning
📜 Project Overview
This project focuses on developing a cloud-based DDoS (Distributed Denial of Service) prevention system using Machine Learning (ML) and Deep Learning (DL) models. The solution aims to detect and mitigate DDoS attacks in real-time, with the ability to learn and adapt to new attack patterns as they emerge.

✨ Features
⚡ Real-time DDoS Detection: Monitors cloud traffic and identifies malicious activities.
🧠 Adaptive Learning: Uses Incremental Learning Models (ILMs) to continuously learn and improve its defense mechanisms against new attack patterns.
🔄 Hybrid ML/DL Architecture: Combines traditional ML for known attack types with ILM for novel, zero-day attacks.
🕵️‍♂️ Honeypot Integration: Optionally incorporates honeypots for deep analysis of suspicious traffic.
🔍 Anomaly Detection: Detects abnormal traffic patterns using anomaly detection techniques.
🏗️ Architecture
Data Collection & Preprocessing: Traffic logs are continuously collected and processed for feature extraction.
Modeling: A hybrid of traditional supervised learning and Incremental Learning is used to identify known and new DDoS attacks.
Real-Time Decision Making: The system employs online learning models to adapt to new traffic patterns in real-time.
Feedback Loop: Detected attacks are labeled and used to retrain the model, ensuring the system keeps evolving.
⚙️ Setup & Installation
Clone the Repository

git clone https://github.com/deepesh611/Minor-Project-DDoS-on-Cloud.git
cd Minor-Project-DDoS-on-Cloud
Run Setup: Ensure you have Python 3.11 or 3.12 installed, then open powershell and run:

.\setup.sh
🔮 Future Enhancements
☁️ Cloud Auto-scaling: Implement an automated cloud scaling mechanism based on detected traffic loads.
🕸️ Advanced Honeypots: Use more sophisticated honeypots for detailed analysis of attackers' behavior.
