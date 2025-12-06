<h1 align="left">AI Hotel Access Anomaly Detection System</h1>
<p align="left"> <strong>An AI-powered security tool that detects suspicious guest or staff access and purchase behavior in hotel environments using machine learning.</strong> </p> <p align="center"> <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.12-blue"></a> <a href="#"><img src="https://img.shields.io/badge/ML-Scikit--Learn-orange"></a> <a href="#"><img src="https://img.shields.io/badge/Security-NIST%20800--53%20|%20ISO%2027001-green"></a> </p>
<h2>Overview</h2>

This project is an AI-powered behavioral anomaly detection system designed to identify unusual or risky activity within hotel room key-card access and purchase logs. Using Python, Pandas, and Scikit-Learn’s Isolation Forest, the system analyzes guest and staff behaviors to flag potential:

<ul>
  <li>Unauthorized room entry</li>
  <li>Account takeover attempts</li>
  <li>Insider threat access</li>
  <li>Suspicious late-night movement</li>
  <li>Impossible travel between rooms or buildings</li>
  <li>Unusual Purchase Patterns</li>
</ul>

The system also supports SMS alerts, mapping to NIST 800-53, ISO 27001, CIS Controls, and PCI-DSS governance frameworks.

<h2>Key Features</h2>

<ul>
  <li>Unsupervised ML (Isolation Forest) to detect abnormal patterns</li>
  <li>Synthetic hotel-access dataset modeled after real PMS system logs</li>
  <li>Feature engineering (time-of-day, access frequency, user class, travel velocity)</li>
  <li>Real-time alerting by SMS notifications</li>
  <li>Visualizations for anomalies and normal behavior clusters</li>
  <li>Governance alignment with NIST, ISO27001 & CIS Security Controls</li>
</ul>

<h2>Project Structure</h2>

<h2>Installation</h2>
<ul>
  <li>git clone https://github.com/nelson-cyberdev/AI-Hotel-Anomaly-Detection-System.git</li>
  <li>cd AI-Hotel-Anomaly-Detection-System</li>
  <li>pip install -r requirements.txt</li>
</ul>

<h2>How It Works</h2>

<ol>
  <li>Load guest/staff room access and Purchase logs</li>
  <li>Engineer features → access frequency, user type, movement patterns</li>
  <li>Train Isolation Forest model on "normal" data</li>
  <li>Score and classify anomalies</li>
  <li>Send SMS alerts for high-risk events</li>
</ol>

<h2>Contributing</h2>

Pull requests are welcome.
For major changes, please open an issue first to discuss proposed updates.

