# Windows Threat Hunting Dashboard

This project is a **SOC Analyst portfolio dashboard** created in Splunk to monitor Windows logs for security events.

---

## Panels Included

1. **Failed Login Attempts** – Shows all login failures by user and host, helps detect brute force attacks.  
2. **Top Hosts with Failed Logins** – Highlights machines targeted most by failed login attempts.  
3. **System/Application Errors** – Shows top system and application errors for monitoring unstable hosts.  
4. **Top Processes / Events** – Highlights frequently executed processes or events for anomaly detection.

---

## Tools Used

- Splunk 
- **Windows Security & Application Logs**

---

## How to Use

1. Download or clone this repository.  
2. Import the XML file (`windows_threat_hunting_dashboard.xml`) into Splunk to view the dashboard.  
3. All panels are ready to monitor events.

---

## Dashboard Preview

### Failed Login Attempts
![Failed Login Attempts](https://github.com/user-attachments/assets/7356f57e-2e74-4e5e-adc2-780324f8af46)

### Top Processes / Events
![Top Processes / Events](https://github.com/user-attachments/assets/bdf4a305-9328-415f-ba47-33ff0fa272cd)
