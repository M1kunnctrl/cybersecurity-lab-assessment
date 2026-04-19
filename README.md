Basic Security Assessment (Lab Environment)
Author: Ayomikun Akinade

 Overview

This project documents a basic cybersecurity assessment performed on a simulated vulnerable web application in a controlled lab environment.

The goal was to identify common vulnerabilities, demonstrate simple exploitation techniques, and provide practical security recommendations.

Objective

To perform a basic security evaluation and identify weaknesses in a test environment.

 Target

A simulated web application designed for cybersecurity learning and practice.


Key Findings

Open Port

* Port 80 (HTTP) was open
* Indicates an active web service

 Weak Authentication

* Default credentials were accepted
* Example: `admin / admin`

 Input Validation Issue

* No proper validation of user input
* Potential risk of injection attacks

 Tools & Techniques

* Nmap – Network scanning
* Web Browser – Application interaction
* Manual Enumeration Techniques


Exploitation Summary

1. Performed network scan using Nmap
2. Identified open port (80)
3. Accessed web interface via browser
4. Tested common credentials
5. Gained unauthorized access

 Recommendations

* Enforce strong password policies
* Implement input validation
* Enable account lockout after failed attempts
* Secure or close unused ports
* Use HTTPS for encrypted communication

 Conclusion

This lab demonstrates how simple vulnerabilities can lead to unauthorized access if basic security practices are not implemented.



