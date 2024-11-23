# Digital Egypt Pioneers Initiative (DEPI)  
**Group Code:** CAI1_ISS5_S3e  
**Track:** Penetration Tester / Vulnerability Analyst  

---

## **Project Overview**  
This project focuses on vulnerability assessment and penetration testing of virtual machines, including **Metasploitable2** and TryHackMe machines such as **GoldenEye**, **Blue**, and **Stapler1**. The aim is to identify, exploit, and document vulnerabilities while providing actionable recommendations to strengthen system security.

---

## **Team Members**  
| Name                              | ID Number       |
|-----------------------------------|-----------------|
| Thomas Ehab Elfeel Ibrahim        | 21002701        |
| Fathy Waleed Hassan Mahdy         | 1110132392      |
| Ibrahim Muhammed Ibrahim ElSayed  | 21012569        |
| Ahmed Sherif Mahmoud Awd          | 21048           |
| Mahmoud Muhammed Abdelrahman Saad | 1110165787      |

---

## **Key Objectives**  
1. **Identify Vulnerabilities:** Conduct comprehensive scans to discover services and their weaknesses.  
2. **Exploit Vulnerabilities:** Use various tools and techniques to exploit the identified issues.  
3. **Evaluate Security Posture:** Assess the system’s defense mechanisms and identify gaps.  
4. **Provide Recommendations:** Suggest mitigations to address vulnerabilities and improve security.

---

## **Project Scope**  
- **Target Machines:** Metasploitable2, GoldenEye, Blue, Stapler1.  
- **Services Tested:**  
  - FTP  
  - Telnet  
  - SMB  
  - MySQL  
  - HTTP/HTTPS  
  - Rexec, Rlogin  

---

## **Findings Summary**  
- **GoldenEye:** Medium risk due to weak authentication on SMTP and brute-force vulnerability on POP3.  
- **Blue:** High risk via EternalBlue SMB exploit leading to remote code execution and full system compromise.  
- **Stapler1:** High risk from anonymous FTP login, SSH brute force, and exploitable WordPress.  
- **Metasploitable:** Critical risk across services like Telnet, Samba, MySQL, and FTP.

---

## **Recommendations**  
- Disable insecure services (e.g., Telnet, Rexec).  
- Enforce strong passwords and multi-factor authentication.  
- Regularly update and patch software.  
- Limit access to critical services using firewalls.  
- Conduct periodic vulnerability assessments and penetration testing.  
- Train users on secure practices.

---

## **Conclusion**  
This project demonstrates the importance of identifying and addressing security weaknesses. By applying the recommendations provided, organizations can enhance their cybersecurity posture and reduce risk exposure.

---

## **Tools Used**  
- **Nmap** for network scanning.  
- **Metasploit** for vulnerability exploitation.  
- **Hydra** for brute force attacks.  
- **Enum4Linux** for enumeration.  
- **Nikto** and **WPScan** for web application testing.

---

> **Disclaimer:** All activities were conducted in controlled environments for educational purposes only.
