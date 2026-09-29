## Week-3 Internship Project: Password Cracking & Web Penetration Testing

![Kali Linux](https://img.shields.io/badge/Kali_Linux-Security-blue)
![John the Ripper](https://img.shields.io/badge/John_the_Ripper-Password_Cracking-purple)
![Nmap](https://img.shields.io/badge/Nmap-Network_Scanning-green)
![License](https://img.shields.io/badge/Licenes-Educational-blue)
![Ethical Hacking](https://img.shields.io/badge/Ethical_Hacking-Lab-red)
## project overview
This project focuses on password cracking in an authorized cybersecurity lab environment. John the Ripper (JTR) is used with the RockYou wordlist to test password candidates and recover passwords from extracted hashes.

NetworkWalks Hash Calculator is used to generate crackable hashes from password-protected PDFs, while the NetworkWalks Password Cracker is used to perform password-recovery testing with those hashes. The project provides practical experience in hash extraction, password cracking, and result verification.
## Tools & Technologies Used
|**category**|**Tools**|
|------------|--------|
|Password Cracking|John the Ripper(JTR),Johnny GUI|
|Online/Web Tools|Networkwalks Hash Calculatore,Networkwalks Password Cracker|
|Wordlists| rockyou.txt|
## Key Findings & Results
|**Task**|**Target**|**Recovered Password**|**Time Taken**|
|--------|----------|----------------------|--------------|
|JTR(terminal)|My locked PDF1.pdf|password1|20 seconds|
|JTR(terminal)|My locked PDF2.pdf|password1|< 1 second|
|JTR(terminal)|My locked PDF3.pdf|1qaz2WSX|1 second|
|NW Tools (online)|All 3 pdfs|confirmed matches|Instant|
|Johnny(GUI)|All 3 pdfs|confirmed matches|Instant|
## Methodology & Execution
### 1 Offline Password Cracking (JTR)
Extracted PDF hashes using John The Ripper .
### 2. Browser-Based Cracking (NW Tools)
Utilized the Networkwalks Hash Calculator to extract the $pdf$ hash and submitted it to the Password Cracker for online dictionary analysis.

### 3. GUI Auditing (Johnny)
Loaded extracted hashes into the Johnny GUI, selected a wordlist, and executed attacks via a point-and-click interface to verify consistency.
## ⚠️ Ethics & Disclaimer
All activities were performed strictly within an authorized training environment using provided lab files and simulated targets. The techniques and tools documented here are intended for educational and defensive security purposes only. Unauthorized access to systems, networks, or data is illegal and unethical.
# 👤 About the Author

**Pavithra.P** is a cybersecurity enthusiast and intern at Networkwalks Academy (Batch B083). With a learning the  network security, penetration testing, and OSINT reconnaissance, Pavithra is passionate about understanding attacker methodologies to build better defenses.

**Areas of Interest:**
- 🔍 Offensive Security & Penetration Testing
- 🌐password cracking
- 🛡️ Network Security & Defense
- 📊 Security Reporting & Documentation

**Certifications Pursuing:**
- Networkwalks Cybersecurity Internship
- Ethical Hacking
**Connect:**
 - [![LinkedIn](https://img.shields.io/badge/LinkedIn-Pavithra-blue?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pavithra-p-202131427/)
[![GitHub](https://img.shields.io/badge/GitHub-Pavithra-black?logo=github&logoColor=white)](https://github.com/pavithrap99)
 ## 🙏 Acknowledgments

- **Networkwalks Academy** – For creating this hands-on internship program
- **Waqas Karim (CCIE)** – For technical mentorship and industry perspective
- **Batch B083 Cohort** – For collaborative troubleshooting and shared insight
- 
**© 2026 Pavithra.p | Networkwalks Cybersecurity Internship | Batch B083**



