# winlogbeat-6.8.8
Step 1: Install Winlogbeatedit
Download the Winlogbeat zip file from the downloads page.
Extract the contents into C:\Program Files.
Rename the winlogbeat-<version> directory to Winlogbeat.
Open a PowerShell prompt as an Administrator (right-click on the PowerShell icon and select Run As Administrator).
From the PowerShell prompt, run the following commands to install the service.


If script execution is disabled on your system, you need to set the execution policy for the current session to allow the script to run. For example: PowerShell.exe -ExecutionPolicy UnRestricted -File .\install-service-winlogbeat.ps1.
