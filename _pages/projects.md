---
title: "Projects"
layout: categories
permalink: /projects/
---

# Selected Projects

## 🚀 IoT Smart Environmental Monitor
**Role:** Developer & Hardware Integrator  
A project focused on building an end-to-end IoT device for real-time environmental data collection.
-   **Hardware:** Integrated a Raspberry Pi with DHT11 (temperature/humidity) and MQ-135 (air quality) sensors to capture environmental metrics.
-   **Software:** Developed a Python script to read sensor data and publish it to a cloud dashboard via the MQTT protocol for remote monitoring and analysis.
-   **Outcome:** Successfully created a functional prototype that provides live data visualization, demonstrating skills in both hardware integration and software development for IoT solutions.

---

## 💻 Secure E-Learning Portal
**Role:** Full-Stack Developer  
Developed a web-based e-learning platform in collaboration with my team members,with a focus on secure access control and distinct user functionalities.
-   **Core Feature:** Implemented a robust Role-Based Access Control (RBAC) system to manage permissions for different user types (Admin, Instructor, Student).
-   **Technology Stack:** Built using **PHP** for the back-end logic, **MySQL** for the database, and **HTML/CSS/JavaScript** for a responsive user interface.
-   **Functionality:** The portal allows admins to manage the site, instructors to create and manage courses, and students to enroll and access educational content securely.
-   [View on github](https://github.com/gisembaberryl/webproject.git)

---

## 🚀 Mama's Hub Bootcamp Project
**Role:** Front-End Developer  
A hands-on bootcamp project focused on developing a community-focused platform, providing real-world experience in a collaborative tech environment.
-   Developed visually appealing and responsive web pages using HTML, CSS, and JavaScript.
-   Used Git for version control to manage and track code changes throughout the development lifecycle.
-   Collaborated with back-end developers, improving features and engaging in a continuous learning process.
-   Gained experience in containerizing applications using Docker images and containers.
-   [View on Github](https://github.com/gisembaberryl/mamashub-web.git)

---
---

# Lab Challenges

## 🛡 Lab: Network Footprinting & Reconnaissance
This lab is based on the initial modules of the Cisco Ethical Hacking course, focusing on information gathering.

-   **Problem Statement:** To gather preliminary data and map the network infrastructure of a target organization using passive and active reconnaissance techniques.
-   **Approach:** Employed tools like `Nmap`, `whois`, and `nslookup` to identify active hosts, open ports, running services, and DNS records.
-   **Tools Used:** `Nmap`, `Wireshark`, `whois`, `nslookup`, `theHarvester`.
-   **Key Lessons Learned:** Mastered the critical first phase of an ethical hack and learned how seemingly minor pieces of information can be aggregated to reveal significant attack vectors.

---

## 🔍 Lab: Vulnerability Scanning & Analysis
This lab reflects the vulnerability analysis section of the ethical hacking curriculum.

-   **Problem Statement:** To identify, categorize, and prioritize security vulnerabilities in a given set of target systems using automated scanning tools.
-   **Approach:** Configured and executed a vulnerability scan using Nessus against the target IP range. Analyzed the generated report to identify critical vulnerabilities and filter out potential false positives.
-   **Tools Used:** `Nessus`, `OpenVAS`, `Metasploit Framework` (for verification).
-   **Key Lessons Learned:** Gained hands-on experience in operating industry-standard vulnerability scanners and learned to interpret scan results to enable efficient remediation.

---

## 💻 Lab: System Hacking & Exploitation
This lab is based on the exploitation modules of the Cisco Ethical Hacking course.

-   **Problem Statement:** To gain unauthorized access to a target machine by exploiting a known vulnerability and subsequently escalate privileges to gain administrative control.
-   **Approach:** Used information from a vulnerability scan to select and configure an exploit from the Metasploit Framework. Executed the exploit to gain an initial shell and then used post-exploitation techniques to escalate privileges.
-   **Tools Used:** `Metasploit Framework`, `Meterpreter`, `John the Ripper`.
-   **Key Lessons Learned:** Understood the practical application of the hacking lifecycle, from exploitation to privilege escalation, reinforcing the importance of timely patching.

---

## 🌐 Lab: Web Application Hacking - SQL Injection
This lab demonstrates a common web vulnerability attack.

-   **Problem Statement:** To bypass a login form on a vulnerable web application to gain unauthorized access without valid credentials.
-   **Approach:** Analyzed the login form for SQL injection vulnerabilities by inputting malicious SQL queries (`' OR 1=1 --`) to manipulate the back-end database query and trick the application into authenticating the user.
-   **Tools Used:** `Burp Suite`, `sqlmap`, browser developer tools.
-   **Key Lessons Learned:** A deep understanding of how improper input sanitization can lead to critical security breaches. Reinforced the necessity of using parameterized queries (prepared statements) in web development.

---

## 📡 Lab: Network Sniffing & Man-in-the-Middle Attacks
This lab focuses on intercepting and analyzing data in transit.

-   **Problem Statement:** To intercept and analyze network traffic to capture credentials being transmitted over an insecure protocol (e.g., FTP, Telnet).
-   **Approach:** Used ARP spoofing to redirect network traffic through an attacker-controlled machine. The captured traffic was then analyzed using a packet sniffer to filter and extract sensitive information in clear text.
-   **Tools Used:** `Wireshark`, `Ettercap`, `arpspoof`.
-   **Key Lessons Learned:** Demonstrated the severe risks associated with using unencrypted communication protocols and the importance of implementing encryption standards like TLS/SSL for all data in transit.

---

## 📶 Lab: Wireless Network Security Auditing
This lab covers the fundamentals of testing wireless network security.

-   **Problem Statement:** To audit the security of a WPA2-protected wireless network by attempting to crack its pre-shared key (PSK).
-   **Approach:** Placed a wireless adapter in monitor mode to capture the WPA2 four-way handshake. An offline dictionary attack was then performed on the captured handshake file to recover the network password.
-   **Tools Used:** `Aircrack-ng` suite (`airodump-ng`, `aireplay-ng`).
-   **Key Lessons Learned:** Acquired practical skills in auditing wireless network security. Understood the critical importance of using a strong, complex password to defend against dictionary and brute-force attacks.


