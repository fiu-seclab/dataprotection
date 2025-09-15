# Security Questionnaire

This repository contains the **Security Questionnaire** survey. Below is the full structure of the survey, including **sections, questions, answer types, and all possible answers explicitly enumerated**.

---

## Section 1: Identification
1. **Prolific ID**  
   *Type:* `text` (required)  

---

## Section 2: Demographics
2. **What is your sex?**  
   *Type:* `radiogroup` (required)  
   *Choices:*  
   1. Female  
   2. Male  
   3. Prefer not to say  
   4. Other (specify)  

3. **In which age group do you belong?**  
   *Type:* `radiogroup` (required)  
   *Choices:*  
   1. <18  
   2. 18–24  
   3. 25–34  
   4. 35–44  
   5. 45–54  
   6. 55+  

4. **Which income bracket best represents your household income?**  
   *Type:* `radiogroup` (required)  
   *Choices:*  
   1. <$25,000  
   2. $25,000–$50,000  
   3. $50,001–$75,000  
   4. $75,001–$100,000  
   5. $100,001–$200,000  
   6. $200,001+  

5. **What is your highest level of education completed?**  
   *Type:* `radiogroup` (required)  
   *Choices:*  
   1. None  
   2. High school diploma  
   3. Some College, No Degree  
   4. Technical Certification (e.g: mechanic, carpentry, etc.)  
   5. Associate Degree  
   6. Bachelor's  
   7. Master's  
   8. Ph.D  
   9. Prefer not to say  

6. **Which best describes your profession or area of study?**  
   *Type:* `checkbox` (required, multiple allowed)  
   *Choices:*  
   1. Architecture and Engineering  
   2. Arts, culture, and entertainment  
   3. Business, management, and administration  
   4. Communications  
   5. Community and social services  
   6. Education  
   7. Science and technology  
   8. Installation, repair, and maintenance  
   9. Farming, fishing, and forestry  
   10. Health and medicine  
   11. Law  
   12. I am not in school at the moment  
   13. Other (specify)  

7. **What is your current employment status?**  
   *Type:* `radiogroup` (required)  
   *Choices:*  
   1. Employed full-time  
   2. Employed part-time  
   3. Unemployed  
   4. Student  
   5. Student + employed full-time  
   6. Student + employed part-time  
   7. Retired  
   8. Homemaker  

---

## Section 3: Education & Interests
8. **Which degree are you currently pursuing?**  
   *Type:* `radiogroup` (required)  
   *Choices:*  
   1. Undergraduate  
   2. Graduate  
   3. Certificate Programs  
   4. Other (specify)  

9. **Have you taken courses in any of the following subjects?**  
   *Type:* `checkbox` (required)  
   *Choices:*  
   1. Cybersecurity  
   2. Computer Science  
   3. Information Technology  
   4. None of these  

10. **Have you been employed in any of the following areas?**  
    *Type:* `checkbox` (required)  
    *Choices:*  
    1. Cybersecurity  
    2. Computer Science  
    3. Information Technology  
    4. None of these  

11. **Do you take interest in cybersecurity, computer science, or information technology?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. Yes  
    2. No  

12. **Which of the following media outlets have you visited during the last week?**  
    *Type:* `checkbox` (required)  
    *Choices:*  
    1. Threatpost  
    2. Dark Reading  
    3. Wired  
    4. PC World  
    5. CNET  
    6. CIO  
    7. None of these  

13. **Which ad-blocker do you use?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. I don't use any adblocker  
    2. Ghostery  
    3. Ad-blocker  

14. **Which Password Manager do you use?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. I don't have a password manager  
    2. LastPass  
    3. NordPass  
    4. 1Password  
    5. Other (specify)  

15. **How important is backup security to you?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. Very important  
    2. Somewhat important  
    3. Somewhat unimportant  
    4. Not important at all  
    5. I don't know what backup security is  

16. **Which operating system is your main operating system?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. Windows OS (Windows7, 8, or 10)  
    2. Unix-based OS (Ubuntu, Fedora, Redhat, etc)  
    3. MacOS  
    4. Other (specify)  

17. **Give a score to your current cybersecurity skills.**  
    *Type:* `rating` (required)  
    *Scale:* Zero Experience → Cybersecurity Maestro  

---

## Section 4: Technical Knowledge
18. **Which of the following programming languages are you familiar with? (More than a year of experience)**  
    *Type:* `checkbox` (required)  
    *Choices:*  
    1. Java  
    2. JavaScript  
    3. C/C++  
    4. C#  
    5. Python  
    6. HTML  
    7. PHP  
    8. Perl  
    9. Ruby  
    10. SQL  
    11. Assembly  
    12. None of these  

19. **What programming language is the most susceptible to buffer overflow attacks?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. Java  
    2. Python  
    3. C/C++  
    4. I don't know  

20. **Which of the following cyber attacks are you familiar with?**  
    *Type:* `checkbox` (required)  
    *Choices:*  
    1. Man-in-the-middle (MitM)  
    2. Phishing  
    3. SQL injection  
    4. Cross-site-scripting (XSS)  
    5. Ransomware  
    6. Denial-of-service (DoS)/Distributed Denial-of-Service (DDoS)  
    7. CSRF  
    8. None of these  

21. **SQL injection can happen because _____ has vulnerabilities.**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. Database Server  
    2. Browser  
    3. Web Application  
    4. I don't know  

22. **Cross site scripting is a ______ attack.**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. Server side  
    2. Client side  
    3. Database  
    4. I don't know  

23. **ASLR is a defense mechanism against ______.**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. Cross site scripting (XSS)  
    2. Buffer Overflow  
    3. Distributed Denial of Service (DDoS)  
    4. I don't know  

24. **When was the last time you used SSH to connect to a remote server?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. Within the last week  
    2. Within the last month  
    3. Within the last 6 months  
    4. Within the last year  
    5. I have never used SSH  

25. **Consider the following command: 'ssh user1-remotehost -p 12345'. Is something wrong?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. Yes, the first argument should be scp instead of ssh  
    2. Yes, the separation should be with @ instead of -  
    3. Yes, you cannot specify the port this way  
    4. No, there is nothing wrong with the syntax  
    5. I don't know SSH  

26. **Ransomware does which of the following?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. Gives attackers remote control of the victim's machine  
    2. Is used for task automation in DDoS attacks  
    3. Blocks access to victim's data until ransom is paid  
    4. Tracks browsing activities for ads  

---

## Section 5: Ransomware
27. **Have you been a victim of a ransomware attack?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. Yes, paid ransom  
    2. Yes, did not pay ransom  
    3. No, not a victim  
    4. I don't know  

28. **If yes and did not pay ransom, why not?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. Ransom not worth recovery  
    2. Had backup  
    3. Outside recovery available  
    4. Never a victim  

29. **Importance of ransomware protection (1–5).**  
    *Type:* `rating` (required)  

30. **How likely are you to be targeted by ransomware?**  
    *Type:* `dropdown` (required)  
    *Choices:*  
    1. Very likely  
    2. Somewhat likely  
    3. Somewhat unlikely  
    4. Very unlikely  
    5. I don't know  

31. **Would you pay a ransom fee if no backup?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. Definitely No  
    2. Yes, if fee < $1000  
    3. Yes, if fee < $500  
    4. Yes, if installments allowed  

---

## Section 6: Antivirus & Backup
32. **Do you use antivirus on your PC? If so, how long?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. Yes, less than 6 months  
    2. Yes, over 1 year  
    3. Yes, over 5 years  
    4. Yes, over 10 years  
    5. No  

33. **Do you currently have ransomware protection installed?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. Yes  
    2. No and don't plan to  
    3. No but plan to  
    4. I don't know  

34. **Do you use backup services on your PC? If so, how long?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. Yes, over 1 month  
    2. Yes, over 6 months  
    3. Yes, over 1 year  
    4. Yes, over 5 years  
    5. Yes, over 10 years  
    6. No  

35. **What tier of backup security service do you use?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. Free version  
    2. Paid, <50 GB  
    3. Paid, 50-100 GB  
    4. Paid, 100-250 GB  
    5. Paid, 250-500 GB  
    6. Paid, 500-1000 GB  
    7. Paid, >1 TB  
    8. None  

36. **Which backup services have you used?**  
    *Type:* `checkbox` (required)  
    *Choices:*  
    1. Acronis True Image  
    2. Paragon Backup and Recovery  
    3. NovaBackup  
    4. EaseUS ToDo Backup  
    5. Malwarebytes Secure Backup  
    6. Heilig Defense RansomOff  
    7. Google One  
    8. Microsoft OneDrive  
    9. Dropbox  
    10. iCloud  
    11. None of these  

37. **Automated vs. manual backups?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. Prefer only automated  
    2. Prefer only manual  
    3. Prefer both  
    4. No interest in backup security  

38. **What is your preferred backup method?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. I don't use backup security  
    2. Full  
    3. Incremental  
    4. Differential  
    5. Individual files/folders  
    6. I don't know what they are  
    7. Other (specify)  

39. **Preferred backup provider?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. First-party (Apple, Google, Microsoft, etc.)  
    2. Third-party  
    3. No preference (only performance matters)  

---

## Section 7: Data Value & Protection
40. **How much is your data worth in dollars?**  
    *Type:* `text (numeric)` (required)  

41. **How much are you willing to pay per month for guaranteed protection? Why?**  
    *Type:* `comment` (required)  

42. **Would you enroll in a $200/year data protection plan?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. Yes  
    2. No  

43. **Please explain your response.**  
    *Type:* `comment` (required)  

---

## Section 8: Security Concepts
44. **What you think the term Social Engineering means?**  
    *Type:* `comment` (required)  

45. **Have you taken any cybersecurity training workshops before?**  
    *Type:* `radiogroup` (required)  
    *Choices:*  
    1. No  
    2. Yes (specify)  

---

## Completion
- Participants are thanked and redirected to Prolific for submission.
