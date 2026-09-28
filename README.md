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
