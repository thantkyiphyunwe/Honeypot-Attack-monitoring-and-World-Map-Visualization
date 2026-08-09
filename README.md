# Honeypot-Attack-monitoring-and-World-Map-Visualization
Finish? not yet but almost.

## 📌 Project Overview
This repository contains the setup, implementation, and dashboard visualization for a **Honeypot Attack Monitoring System** developed for the Cybersecurity module. The system deploys honeypots to attract and capture real-time malicious traffic, logging attack telemetry (IP addresses, targeted ports, geolocation data) and displaying real-time threat vectors on an interactive **World Map Visualization**.

## 📄 Key Features & Concepts
* **Honeypot Deployment:** Setting up low-to-medium interaction honeypots (e.g., Cowrie, Dionaea) to log unauthorized access attempts.
* **Log Ingestion & Parsing:** Extracting attacker IP addresses, SSH/FTP brute-force logs, and payload samples.
* **IP Geolocation Enrichment:** Mapping attacker IP addresses to geographic coordinates (Country, City, ISP) using GeoIP databases.
* **World Map Dashboard:** Real-time visual tracking of global cyberattacks using an interactive map interface (e.g., ELK Stack / Grafana / Leaflet.js).

## 🛠️ Tools & Technologies
* **Honeypots:** Cowrie / Dionaea / T-Pot Framework
* **Data Pipeline & Storage:** Logstash / Python / Elasticsearch
* **Visualization:** Kibana / Grafana / Leaflet.js

---
*Cybersecurity Individual Project*
