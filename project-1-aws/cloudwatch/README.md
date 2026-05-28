\# Project 1D — CloudWatch Monitoring \& Alerting



\## What I Built

Set up AWS CloudWatch monitoring for EC2 instance with

custom alarms, SNS email notifications, and a monitoring

dashboard.



\## Resources Created



| Resource | Name | Purpose |

|---|---|---|

| CloudWatch Alarm | indira-high-cpu-alert | Alert when CPU > 70% |

| CloudWatch Alarm | indira-status-check-failed | Alert if server is down |

| SNS Topic | indira-alerts | Email notification channel |

| Dashboard | indira-aws-monitoring | Visual monitoring panel |



\## Alarm Configuration



\### CPU Alarm

\- Metric: CPUUtilization

\- Threshold: Greater than 70%

\- Period: 5 minutes

\- Action: Email via SNS



\### Status Check Alarm

\- Metric: StatusCheckFailed

\- Threshold: Greater than or equal to 1

\- Action: Email via SNS



\## Key Concepts Learned

\- CloudWatch collects metrics automatically from AWS services

\- Alarms trigger actions when thresholds are breached

\- SNS (Simple Notification Service) sends email/SMS alerts

\- Dashboards give visual overview of infrastructure health

\- This is how real production systems are monitored 24/7

