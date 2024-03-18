# Server Health Check PowerShell Script
** Overview
This PowerShell script is designed to check the health status of servers by analyzing CPU utilization, memory utilization, drive status, and uptime. It requires a CSV file named "ServerList.csv" containing a list of server names to perform the health checks. The script generates an HTML report with the health status details, including CPU utilization, memory utilization, drive status, and uptime. The HTML report is saved with a timestamp indicating when the file was generated.

** Prerequisites
PowerShell 5.1 or later
Permission to execute PowerShell scripts
CSV file named "ServerList.csv" containing a list of server names
Usage
Place the "ServerList.csv" file containing server names in the same directory as the script.
Execute the PowerShell script by running the command:
powershell
Copy code
.\ServerHealthCheck.ps1
The script will process the servers listed in the CSV file and generate an HTML report.
Output
The script generates an HTML report named "ServerHealthReport.html" in the same directory as the script.
The HTML report includes detailed information about the health status of each server, including CPU utilization, memory utilization, drive status, and uptime.
The report also contains a timestamp indicating when the report was generated.

Notes
--> There is an HTML file added with this code which can create a CSV file with the name "ServerList". (Use this for generation of server List)
Ensure that the CSV file "ServerList.csv" is properly formatted with the header "ServerName" and a list of server names in subsequent rows.
This script assumes that the servers are accessible and that the necessary permissions are in place to gather system information remotely.
Disclaimer
This script is provided as-is without any warranty. Use it at your own risk. The author is not responsible for any damage caused by the use or misuse of this script.

Author
Aswindev P

Feel free to reach out for any assistance or feedback!
