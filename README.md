# Phishing-Email-Lab

## Objective

The phishing email analysis project aimed to investigate a suspicious email purportedly from PayPal in German. The primary focus was to identify key indicators of phishing, such as suspicious return paths, malicious domains, and abnormal SHA-256 signatures. This hands-on experience deepened understanding of email security, threat analysis, and the tools used to verify email authenticity and detect phishing attempts.

### Skills Learned

- Advanced understanding of email phishing analysis and identifying key indicators of malicious intent.
- Proficiency in analyzing email headers, return paths, and URLs for authenticity and potential threats.
- Ability to utilize tools like VirusTotal for scanning URLs and validating security risks.
- Enhanced knowledge of SHA-256 hashing and its role in identifying and categorizing malicious entities.
- Development of critical thinking and problem-solving skills in investigating and mitigating phishing attempts.

### Tools Used

- Email client software for accessing and viewing email source code.
- VirusTotal for scanning and analyzing URLs and domains for malicious activity.
- Web browser tools for inspecting email content and embedded URLs.
- LetsDefend for simulating phishing email analysis and enhancing hands-on investigative skills.

## Steps

- The scenario given is: Your email address has been leaked, and you have received an email from PayPal in German. Try to analyze the suspicious email. I started off by unzipping the EML file and then I entered the password. 
![1](https://github.com/user-attachments/assets/c27b9991-3bb5-4748-8765-269e7769e973)

- Below is the presentation of the original email.
![2](https://github.com/user-attachments/assets/a29e66b7-1a29-4134-9f04-fedbb704a363)

- Q1 What is the return path of the email? To identify the return path of this email, I examined its source code and The return path is “bounce@rjttznyzjjzydnillquh.designclub.uk.com” 
![3](https://github.com/user-attachments/assets/2fae0acd-e629-4dac-9fb3-d3677bc069f0)

- Q2 What is the domain name of the url in this mail? Upon inspecting the URL embedded in the email, the domain name was identified as "storage.googleapis.com"
![4](https://github.com/user-attachments/assets/24b5f31c-aee3-4bfc-a091-73ab299c886c)

- I then proceeded to scan the URL using VirusTotal, which flagged it as malicious.
![5](https://github.com/user-attachments/assets/eb5f6057-6c00-4573-9e89-9ba9932343fa)

- Q3 Is the domain mentioned in the previous question suspicious? Yes, After reviewing the community feedback on VirusTotal and noting the URL's malicious flag, we can confirm that this domain is suspicious.
![6](https://github.com/user-attachments/assets/2f5592cc-16aa-40e7-9776-1f651ee2a403)

- Q4 What is the body SHA-256 of the domain? After looking at the detains of the domain in VirusTotal, The Body SHA-256 is “13945ecc33afee74ac7f72e1d5bb73050894356c4bf63d02a1a53e76830567f5”
![7](https://github.com/user-attachments/assets/315d2d9f-ed27-492b-84fc-ad8627e054c6)

- Q5 Is this email a phishing email? Based on our analysis above, we can confidently conclude that this was a phishing email.




