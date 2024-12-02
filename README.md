# Google-Course---Determine-appropriate-data-handling-practices


ChatGPT said:
ChatGPT
Data Leak Worksheet
Issue(s):
The data leak occurred because the principle of least privilege was not followed. A manager shared access to a folder with a customer success representative but forgot to revoke access. The representative accidentally shared the link to the entire folder with an external partner, leading to the leak of internal business plans on social media.

Review:
NIST SP 800-53: AC-6 emphasizes the principle of least privilege by ensuring users have access only to the information and resources necessary for their role. It also includes enhancements such as implementing time-based or task-based access controls and providing automated mechanisms for monitoring and managing access rights.

Recommendation(s):

Time-based access controls: Grant temporary access to shared folders that automatically expire after a specific time period.
Automated access monitoring: Use tools to log, track, and alert administrators about unusual or unauthorized access to sensitive data.
Justification:
The implementation of time-based access controls will ensure that access to sensitive folders expires promptly after it is no longer required, reducing the likelihood of accidental oversharing. Automated monitoring will help detect and prevent unauthorized access by alerting administrators to potential breaches in real time, increasing accountability and security. These measures will reinforce adherence to the principle of least privilege and reduce the risk of data leaks.
