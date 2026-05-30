\# Windows Event Log Investigation Report



\## Objective



Investigate Windows Security Events using Event Viewer.



\## Environment



\- Windows 11

\- Event Viewer



\## Events Analyzed



\### Event ID 4624



Description:

Successful Login



User:

Asmit



Date:

30-May-2026



Result:

Successful Authentication



\---



\### Event ID 4625



Description:

Failed Login



User:

Asmit



Date:

30-May-2026



Failure Reason:

Bad Password



Result:

Authentication Failed



\---



\### Event ID 4634



Description:

User Logoff



User:

Asmit



Result:

User Session Ended



\## Findings



Observed both successful and failed authentication events.



\## Conclusion



Windows Security Logs provide valuable visibility into authentication activity and can be used to detect suspicious login behavior.

