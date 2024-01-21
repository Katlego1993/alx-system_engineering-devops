0x19-postmortem

Title and Introduction:
A postmortem is a tool widely used in the tech industry. After any outage, the team(s) in charge of the system will write a summary that has 2 main goals:
To provide the rest of the compan employees easy access to information detailing the cause of the outage. Often outages can have a huge impact on a company, so managers and executives have to understand what happened and how it will impact their work.
And to ensure that the root cause(s) of the outage has been discovered and that measures are taken to make sure it will be fixed.

Issue summary:
duration of the outage with start and end times (including timezone) what was the impact (what service was down/slow? What were user experiencing? How many % of the users were affected?) what was the root cause

A Timeline:
list the timezone.Covers the outage duration. When outage began. When staff was notified. When service was restored

Root cause analysis:
explain in detail what was causing the issue explain in detail how the issue was fixed

Impact and Mitigation:
Give detailed explanation of actions taken (includes time)

Resolution and recovery:
Give detailed explanation of actions taken (includes time)

Corrective and preventative measures:
what are the things that can be improved/fixed (broadly speaking) a list of tasks to address the issue (be very specific, like a TODO, example: patch Nginx server, add monitoring on server memory)
