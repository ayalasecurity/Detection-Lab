# Detection-Lab - Categorizing Phishing Emails

## Objective

In this project, my objective was to enhance my skills in analyzing and categorizing suspicious emails, particularly phishing emails. I accessed a set of emails in a designated folder and practiced identifying characteristics of each email to determine the most appropriate category. This project aimed to develop my proficiency in categorizing emails, a crucial skill for investigating various types of phishing attempts.

### Skills Learned

- Email Analysis: I learned to analyze the content, structure, and characteristics of emails to identify potential phishing attempts.
- Categorization: Through this activity, I developed the ability to categorize emails based on their attributes, distinguishing between different types of phishing emails.
- Critical Thinking: By assessing the nuances of each email, I sharpened my critical thinking skills, enabling me to make informed decisions regarding email categorization.
- Cybersecurity Awareness: Engaging with phishing emails enhanced my awareness of cybersecurity threats, helping me recognize and respond to malicious attempts effectively.

### Tools Used

- Mozilla Thunderbird: I utilized the Mozilla Thunderbird email client to access and analyze the provided emails. The client enabled me to view email content, structure, and metadata crucial for categorization.

## Steps
![56dbd7fd36b2cd01c07028cc9f8977a50f6dc1754c4a0773667e7aeea1767ca845c5ed623f81c3ae7ba53130d34d](https://github.com/ayalasecurity/Detection-Lab/assets/157613993/cefe0bbf-baf6-42fb-96f0-c04dd282a331)
- In email one, I noticed that the sender was attempting to elicit a response from the recipient. It was sent from a random email address, with the sender's name not matching and utilizing a different Reply-to address to receive the email response (if the recipient replied). The email didn't request us to click a link or download a file. Based on this information, it seemed like a recon email trying to solicit a response from me and initiate a conversation. Alternatively, it could have been used simply to verify if the target mailbox existed and could receive emails, although typically those emails don't include any content in the email body.

![97d4ae3a3002ff452d76e02ed2781bced57de1b2650d7afca8f8744798d2034f9e728db68944de6a0155a13578ba](https://github.com/ayalasecurity/Detection-Lab/assets/157613993/a1d83eba-dc39-4b52-9153-d5266401427c)
- Firstly, considering the context of the email, it purported to be a fraud alert for our Amazon account. However, the email lacked any Amazon branding or styling, and the sending address was actually non-reply@email.lanhdaotaiba.com, which certainly wasn't an Amazon email address. The email employed a sense of urgency to prompt users to click on the button without careful consideration. It requested confirmation of some personal information to purportedly verify ownership of the account. Based on this information, it seemed highly probable that this email was a credential harvester, aiming to extract private information from email recipients.

![5f78f1b0ec69fffceae1104ec5c02216db43e5b01f0c52f7a25b65b859b260c728b8fd09cff91136f574848deedb](https://github.com/ayalasecurity/Detection-Lab/assets/157613993/e6da1135-6b35-4a46-955a-bb57269bc62d)
- This email didn't exhibit any suspicious or malicious indicators, and judging from the information within the email body, it appeared to be a spam or newsletter email, which is non-malicious, also known as junk mail.

![6e1eb9b8ec5c77dfb7e697a5e8fbd0ac036539c0e17a04137b9e3ae587a1e18ad57ffaff484d2e72169270222668](https://github.com/ayalasecurity/Detection-Lab/assets/157613993/ca82722f-28f9-47b3-97bf-b36f7b264378)
- The first thing I noticed about this email was the subject line, which created a sense of urgency, a tactic often employed by malicious emails. Additionally, the email contained an attachment, which warranted caution as it could potentially be malicious. Furthermore, the sending address was a Gmail address, which seemed highly suspicious, especially considering the email claimed to be from a 'Finance and Collection Department' of a company. Based on this information, it appeared to be a malicious attachment email, wherein the email recipient was being persuaded to open the attached docx file (which could potentially contain malicious macros or a link to a malicious website) by asserting there would be financial consequences to the company.


*Ref 1: Thunderbird Client Email*
