0x19-postmortem

Title and Introduction:
A postmortem is a tool widely used in the tech industry. After any outage, the team(s) in charge of the system will write a summary that has 2 main goals:
To provide the rest of the compan employees easy access to information detailing the cause of the outage. Often outages can have a huge impact on a company, so managers and executives have to understand what happened and how it will impact their work.
And to ensure that the root cause(s) of the outage has been discovered and that measures are taken to make sure it will be fixed.

Issue summary:
*Date of Problem: 2024/01/18
*User Impact: 70% of Asia users & 10% of EU users
duration of the outage with start and end times (including timezone) what was the impact (what ser/vice was down/slow? What were user experiencing? How many % of the /users were affected?) what was the root cause

A Timeline:
*Total impact time - 120 minutes
list the timezone.Covers the outage duration. When outage began. When staff was notified. When service was restored

Root cause analysis:
*Wrong configuration rolled out to production environment
explain in detail what was causing the issue explain in detail how the issue was fixed

Impact and Mitigation:
*15,000 users could download files for two hours
Give detailed explanation of actions taken (includes time)

Resolution and recovery:
*Business impact : 1M in advertisement & 3k for repair cost
*User impact: 1000 users from Asia, 500 users from EU & 1500 users global
*Team impact: Network team is not able to & Security team is impacted by
*System(s) affected: Network app1:Down for 30 mins, Storage system:Down for 30mins & Upload system:Partial down for 60 mins*
*Detection: Datadog monitoring & User report
Give detailed explanation of actions taken (includes time)

Corrective and preventative measures:
*The new configuration change was schedule for reason a, because it is an emergency change, it didnt go through all the tests
*It is important to understand how your monitoring system or alerting system detected this incident, or more importantly how fast
what are the things that can be improved/fixed (broadly speaking) a list of tasks to address the issue (be very specific, like a TODO, example: patch Nginx server, add monitoring on server memory)
