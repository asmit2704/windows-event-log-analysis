\# Windows Event Log Investigation Report



\## Objective



Investigate Windows Security Logs and identify authentication-related events.



\## Environment



\- Operating System: Windows 11

\- Tool: Event Viewer



\## Event Analysis



\### Event ID 4624 - Successful Login



Description:

An account was successfully logged on.



Observation:

A valid user successfully authenticated to the system.



Severity:

Informational



\---



\### Event ID 4625 - Failed Login



Description:

An account failed to log on.



Observation:

An incorrect password was entered during authentication.



Severity:

Low



\---



\### Event ID 4634 - Logoff



Description:

An account was logged off.



Observation:

User session ended normally.



Severity:

Informational



\---



\### Event ID 4672 - Special Privileges Assigned



Description:

Administrative privileges were assigned to a new logon session.



Observation:

Privileged account activity detected.



Severity:

Medium



\## Findings



\- Windows records detailed authentication activity.

\- Failed login attempts can be identified using Event ID 4625.

\- Successful logins can be tracked using Event ID 4624.

\- Administrative activity can be monitored using Event ID 4672.



\## Conclusion



Windows Security Logs provide valuable information for monitoring authentication events and investigating suspicious activity. Understanding these logs is a fundamental SOC Analyst skill.

