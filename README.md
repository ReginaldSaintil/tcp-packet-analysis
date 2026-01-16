# tcp-packet-analysis
# Machine learning and network anomaly detection using TCP packet analysis
# Network Traffic Analysis of TCP Packets
# Final Project – Computer Networks
# Project Overview

# This project applies machine learning and data analysis to TCP packet traffic with the goal of identifying network anomalies, understanding usage patterns, and enhancing cybersecurity monitoring. Using Wireshark, a packet capture dataset was collected and analyzed to detect irregular activity such as packet # duplication, port scanning, and retransmissions.

# Objectives

# Capture and analyze real-world network traffic using Wireshark.

# Apply Python-based machine learning models to classify and detect anomalies.

# Visualize and explain common anomalies in TCP traffic (e.g., retransmissions, port scans).

 # Propose actionable strategies for network security monitoring.

# Tools & Technologies

# Wireshark – For packet capture and inspection.

# Python – For data processing and analysis.

# Scikit-learn – To build classification models.

# Jupyter Notebook – For analysis documentation and experimentation.

# PowerPoint – For presenting insights and project walkthrough.

# Key Features & Deliverables

# Anomaly Detection: Detected signs of port scanning and excessive retransmissions in traffic flow.

# Visualization: Captured network packet behavior patterns to flag suspicious activity.

# Classification: ML models trained on TCP session features to flag anomalies.

# Use Case Examples:

# Excessive use of SYN packets indicating a SYN flood attempt.

# Packet duplication potentially tied to malware or proxy attacks.

# TCP resets hinting at service denial or policy enforcement.

# Insights

# Over 15,000 packets were analyzed across multiple sessions.

# Certain destination IPs showed frequent scanning activity, with abnormal TCP flag sequences.

# Identified security risks including:

# Repeated retransmissions from same source → network congestion or DoS pattern.

# Short-lived TCP connections → signature of botnet-like activity.
