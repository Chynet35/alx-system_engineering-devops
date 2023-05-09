# 0x19. Postmortem

## Issue Summary: 1
On May 10th, 2023, from 10:00 AM to 11:30 AM (WAT), the "CatPics" website experienced an outage that impacted 50% of its users. The service was down, `causing users to be unable to view or upload pictures of cats. The root cause of the outage was a server misconfiguration that caused a critical component of the database to fail.
## Timeline:
10:00 AM - The issue was first detected by the CatPics
monitoring system, which sent out alerts to the engineering team.
10:05 AM - The engineering team investigated the issue and discovered that the database was down.
10:10 AM - The team started troubleshooting the database and ran some diagnostic tools.
10:15 AM - The team realized that the issue was related to a server misconfiguration and started investigating that.
10:25 AM - After some initial investigation, the team mistakenly assumed that the issue was with the network configuration.
10:30 AM - The team escalated the incident to the senior engineering team for further investigation.
11:00 AM - The senior engineering team discovered the root cause of the issue was a server misconfiguration and fixed it.
11:30 AM - The CatPics website was restored to full functionality.
## Root Cause and Resolution:
The root cause of the outage was a misconfiguration of the server that was hosting the CatPics database. Specifically, a critical component of the database was not properly configured, leading to its failure. The senior engineering team fixed the issue by properly configuring the server, allowing the database to function correctly.
## Corrective and Preventative Measures:
To prevent similar outages from occurring in the future, the engineering team has identified several corrective and preventative measures that will be implemented. These measures include:
Regular reviews of the server configurations to ensure proper settings.
Improved monitoring to detect server misconfigurations and failures more quickly.
Increased documentation and training for the engineering team to improve their troubleshooting skills.

  In conclusion, the CatPics website experienced an outage due to a server misconfiguration that caused a critical component of the database to fail. The issue was resolved by the senior engineering team, and measures have been put in place to prevent similar outages from happening in the future. Remember to always double-check your server configurations, or risk losing access to cute cat pictures!

