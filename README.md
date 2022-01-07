# Lets Go Splunking
### Job:
SOC Analyst for Vandalay
#### Objective:
Use Splunk for security monitoring, developing searches, custom reports, and alerts to monitor Vandalay's online system and protect them from future attacks.
#### Topics Covered in This Assignment:
- Researching and adding new apps
- Installing new apps
- Uploading files
- Splunk searching
- Using fields
- Custom reports
- Custom alerts
### Step 1: The Need for Speed
#### Background:
As the worldwide leader of importing and exporting, Vandalay Industries has been the target of many adversaries attempting to disrupt their online business. Recently, Vandaly has been experiencing DDOS attacks against their web servers.
Not only were web servers taken offline by a DDOS attack, but upload and download speed were also significantly impacted after the outage. Your networking team provided results of a network speed run around the time of the latest DDOS attack.
#### Task:
Create a report to determine the impact that the DDOS attack had on download and upload speed. Additionally, create an additional field to calculate the ratio of the upload speed to the download speed.

![DDoS Attack]

#### Report Feedback:
Based on the report above, the attack seemed to have ocurred on Feburary 23rd around 14:30 but system operations returned to normal around 23:30, indicating a total of 9 hours of recovery time.
### Step 2: Are We Vulnerable?
#### Background:
Due to the frequency of attacks, your manager needs to be sure that sensitive customer data on their servers is not vulnerable. Since Vandalay uses Nessus vulnerability scanners, you have pulled the last 24 hours of scans to see if there are any critical vulnerabilities.
#### Task:
Create a report determining how many critical vulnerabilities exist on the customer data server. Then, build an alert to notify your team if a critical vulnerability reappears on this server.

![Critical Vulnerabilities]

### Step 3: Drawing the (base)line
#### Background:
A Vandaly server is also experiencing brute force attacks into their administrator account. Management would like you to set up monitoring to notify the SOC team if a brute force attack occurs again.
#### Task:
Analyze administrator logs that document a brute force attack. Then, create a baseline of the ordinary amount of administrator bad logins and determine a threshold to indicate if a brute force attack is occurring.

![Brute Force Attack]

#### Report Feedback:
The attack occurred on February 21, 2020 between 8:59 AM and 2:57 PM. Baseline for normal activity is 15 attempted logins per hour, 20 failed login attempts or greater triggers brute force alert.

