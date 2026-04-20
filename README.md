# Investigate-and-Identify-Events-with-KQL

![image](https://github.com/garrick8jackson/Investigate-and-Identify-with-KQL/blob/8ae258650a3a022beecd823ba2beb772412483f2/kql%201.png)

After accessing my log analytics workspace and navigating to the logs, i entered a query to search for security events related to a specific user 

![image](https://github.com/garrick8jackson/Investigate-and-Identify-with-KQL/blob/977a03e7eb0fd0fa085e57560b21084beef69a61/kql%202.png)

Next i added to the query to examine the user account’s authentication events to pinpoint any suspicious login attempts 

![image](https://github.com/garrick8jackson/Investigate-and-Identify-with-KQL/blob/35d8978e8751f78dc78e85ee34469109f530a111/kql%203.png)

Lastly i added the summarize and order operators to see the log-on and log-off counts by machine to help identify which machine may have been affected
