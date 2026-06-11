<h1 align="center">Evan Liberto</h1>
<p align="center">
  <b>M.S. Computer Science · Miami University</b><br/>
  Technical Solutions Architect Intern · World Wide Technology
</p>

---

## About

I am a **Master's student in Computer Science** at **Miami University** (graduating December 2026) and a **part-time Technical Solutions Architect Intern** at **World Wide Technology (WWT)** on the **Infrastructure Automation team**.

My work spans **automation, systems engineering, and software development**. I recently earned my **Red Hat Certified System Administrator (RHCSA)** certification and am currently preparing for the **RHCE**.

Outside of work and school, I'm passionate about fitness, continuous learning, and experimenting with new technologies.

---

## Projects

### Sensor-Based Human Activity Recognition
Machine learning model comparison for classifying 11 human activities from raw accelerometer and gyroscope sensor data across 12 users and ~3 million readings.
- Trained and evaluated 10 models (XGBoost, Random Forest, KNN, ANN, SVM, and more) across 10 sliding window configurations
- Best accuracy of **86.24%** achieved with XGBoost using a 500-sample window with 50% overlap
- Validated top model with K-Fold and Stratified K-Fold cross-validation (mean accuracy: 86.54%)

**Stack:** Python, scikit-learn, XGBoost, Pandas, Jupyter | [View Repo](https://github.com/Evan-Liberto11/sensor-based-activity-recognition-ml)

---

### WeatherTrip Infrastructure
Full-stack multi-cloud infrastructure hosting a weather-aware trip planning REST API across OpenStack and AWS.
- Deployed 4 OpenStack VMs and 1 AWS EC2 instance on a custom /29 subnet with static routing
- Configured NGINX load balancer with SSL (Let's Encrypt), bind9 DNS, iptables firewall, and NAT
- Secured all OpenStack–AWS communication through a WireGuard VPN tunnel
- API supports location and trip management with live 7-day weather forecasts and a trip comparison scoring system

**Stack:** Python, Flask, Docker, MariaDB, NGINX, WireGuard, bind9, AWS EC2, OpenStack | [View Repo](https://github.com/Evan-Liberto11/weathertrip-infrastructure)

---

## Contact

- **LinkedIn** – [linkedin.com/in/evan-liberto](https://www.linkedin.com/in/evan-liberto/)
- **Email** – [evanliberto117@gmail.com](mailto:evanliberto117@gmail.com)
- **Resume** – [View My Resume (PDF)](/Evan%20L%20Resume%20October%202024.pdf)