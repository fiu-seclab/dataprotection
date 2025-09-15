# Security Questionnaire

This repository contains the **Security Questionnaire** survey. Below is the full structure of the survey, including **sections, questions, answer types, and possible answers**.

---

## Section 1: Identification
- **Prolific ID**  
  *Type:* `text` (required)  

---

## Section 2: Demographics
- **What is your sex?**  
  *Type:* `radiogroup` (required)  
  *Choices:* Female, Male, Prefer not to say, Other (specify)  

- **In which age group do you belong?**  
  *Type:* `radiogroup` (required)  
  *Choices:* <18, 18–24, 25–34, 35–44, 45–54, 55+  

- **Which income bracket best represents your household income?**  
  *Type:* `radiogroup` (required)  
  *Choices:* <$25,000, $25,000–$50,000, $50,001–$75,000, $75,001–$100,000, $100,001–$200,000, $200,001+  

- **What is your highest level of education completed?**  
  *Type:* `radiogroup` (required)  
  *Choices:* None, High school diploma, Some College (no degree), Technical Certification, Associate Degree, Bachelor’s, Master’s, Ph.D., Prefer not to say  

- **Which best describes your profession or area of study?**  
  *Type:* `checkbox` (required, multiple allowed)  
  *Choices:* Architecture & Engineering, Arts & Entertainment, Business & Administration, Communications, Community & Social Services, Education, Science & Technology, Installation & Maintenance, Farming & Forestry, Health & Medicine, Law, Not in school, Other (specify)  

- **What is your current employment status?**  
  *Type:* `radiogroup` (required)  
  *Choices:* Employed full-time, Employed part-time, Unemployed, Student, Student + employed full-time, Student + employed part-time, Retired, Homemaker  

---

## Section 3: Education & Interests
- **Which degree are you currently pursuing?**  
  *Type:* `radiogroup` (required)  
  *Choices:* Undergraduate, Graduate, Certificate, Other (specify)  

- **Have you taken courses in any of the following subjects?**  
  *Type:* `checkbox` (required)  
  *Choices:* Cybersecurity, Computer Science, Information Technology, None of these  

- **Have you been employed in any of the following areas?**  
  *Type:* `checkbox` (required)  
  *Choices:* Cybersecurity, Computer Science, Information Technology, None of these  

- **Do you take interest in cybersecurity, computer science, or IT?**  
  *Type:* `radiogroup` (required)  
  *Choices:* Yes, No  

- **Which of the following media outlets have you visited during the last week?**  
  *Type:* `checkbox` (required)  
  *Choices:* Threatpost, Dark Reading, Wired, PC World, CNET, CIO, None of these  

- **Which ad-blocker do you use?**  
  *Type:* `radiogroup` (required)  
  *Choices:* I don’t use any, Ghostery, Ad-blocker  

- **Which Password Manager do you use?**  
  *Type:* `radiogroup` (required)  
  *Choices:* None, LastPass, NordPass, 1Password, Other (specify)  

- **How important is backup security to you?**  
  *Type:* `radiogroup` (required)  
  *Choices:* Very important, Somewhat important, Somewhat unimportant, Not important at all, I don’t know what backup security is  

- **Which operating system is your main OS?**  
  *Type:* `radiogroup` (required)  
  *Choices:* Windows, Unix-based (Ubuntu, Fedora, etc.), MacOS, Other (specify)  

- **Rate your cybersecurity skills (0–5).**  
  *Type:* `rating` (required)  
  *Scale:* Zero Experience → Cybersecurity Maestro  

---

## Section 4: Technical Knowledge
- **Which programming languages are you familiar with?**  
  *Type:* `checkbox` (required, multiple allowed)  
  *Choices:* Java, JavaScript, C/C++, C#, Python, HTML, PHP, Perl, Ruby, SQL, Assembly, None  

- **Buffer overflow attacks are most likely in which language?**  
  *Type:* `radiogroup` (required)  
  *Choices:* Java, Python, C/C++, I don’t know  

- **Which cyber attacks are you familiar with?**  
  *Type:* `checkbox` (required)  
  *Choices:* MitM, Phishing, SQL injection, XSS, Ransomware, DoS/DDoS, CSRF, None  

- **SQL injection occurs because _____ has vulnerabilities.**  
  *Type:* `radiogroup` (required)  
  *Choices:* Database Server, Browser, Web Application, I don’t know  

- **Cross-site scripting is a ______ attack.**  
  *Type:* `radiogroup` (required)  
  *Choices:* Server-side, Client-side, Database, I don’t know  

- **ASLR is a defense mechanism against ______.**  
  *Type:* `radiogroup` (required)  
  *Choices:* XSS, Buffer Overflow, DDoS, I don’t know  

- **When was the last time you used SSH?**  
  *Type:* `radiogroup` (required)  
  *Choices:* Within a week, Within a month, Within 6 months, Within a year, Never  

- **SSH command syntax validation.**  
  *Type:* `radiogroup` (required)  
  *Choices:* Multiple options (syntax errors, correct, or don’t know SSH)  

- **What does ransomware do?**  
  *Type:* `radiogroup` (required)  
  *Choices:* Remote control, DDoS automation, Encrypts data until ransom, Tracks browsing  

---

## Section 5: Ransomware
- **Have you been a ransomware victim?**  
  *Type:* `radiogroup` (required)  
  *Choices:* Victim + paid, Victim + not paid, Not a victim, Don’t know  

- **Reason for not paying ransom?**  
  *Type:* `radiogroup` (required)  
  *Choices:* Not worth it, Had backup, Outside recovery, Never a victim  

- **Importance of ransomware protection (1–5).**  
  *Type:* `rating` (required)  

- **How likely are you to be targeted?**  
  *Type:* `dropdown` (required)  
  *Choices:* Very likely, Somewhat likely, Somewhat unlikely, Very unlikely, Don’t know  

- **Would you pay a ransom if no backup?**  
  *Type:* `radiogroup` (required)  
  *Choices:* Definitely No, Yes (<$1000), Yes (<$500), Yes (installments)  

---

## Section 6: Antivirus & Backup
- **Do you use antivirus on your PC? (duration)**  
  *Type:* `radiogroup` (required)  

- **Do you currently have ransomware protection installed?**  
  *Type:* `radiogroup` (required)  

- **Do you use backup services on your PC? (duration)**  
  *Type:* `radiogroup` (required)  

- **What tier of backup security service do you use?**  
  *Type:* `radiogroup` (required)  

- **Which backup services have you used?**  
  *Type:* `checkbox` (required)  

- **Automated vs. manual backups.**  
  *Type:* `radiogroup` (required)  

- **Preferred backup method.**  
  *Type:* `radiogroup` (required, with Other)  

- **Backup provider preference.**  
  *Type:* `radiogroup` (required)  

---

## Section 7: Data Value & Protection
- **How much is your data worth (in $)?**  
  *Type:* `text (numeric)` (required)  

- **How much would you pay per month for guaranteed protection? Why?**  
  *Type:* `comment` (required)  

- **Would you enroll in a $200/year data protection plan?**  
  *Type:* `radiogroup` (required)  

- **Explain your response.**  
  *Type:* `comment` (required)  

---

## Section 8: Security Concepts
- **What does “Social Engineering” mean to you?**  
  *Type:* `comment` (required)  

- **Have you taken cybersecurity training workshops?**  
  *Type:* `radiogroup` (required, with Other)  
  *Choices:* No, Yes (specify)  

---

## Completion
Participants are thanked and redirected to Prolific for submission.
