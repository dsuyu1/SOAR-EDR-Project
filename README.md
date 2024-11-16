<p align = "center">
<img src="https://i.imgur.com/VfFPlSE.png" width="400">
</p>

# SOAR EDR Project
## Overview
In this project, I learn how to automate security workflows and enhance my cybersecurity posture effectively. Specifically, I use Tines as my SOAR and LimaCharlie as my EDR.
After completing the project, I learned how to create a simple playbook that automates the task of sending messages and emails out about detection. I used rules in LimaCharlie to search for a specific event. In this case, I looked for events that involved LaZagne. I sent that telemetry to my SOAR, Tines. Tines sent out emails and messages through Slack containing important details regarding the event. For example, the messages contain the host's internal IP address, sensor ID, hostname, and more. By the end, I had a working playbook, or "story," as they call it in Tines. 
