# GCE-Intune
Google Enterprise Enrolment for Intune

Enroll Google Chrome browsers on Windows devices
The second action is to enroll Google Chrome browsers on Windows devices by using the generated enrollment token. For that purpose I’ve created a small PowerShell script that will be deployed via Microsoft Intune. That means two steps. The first step is to create the PowerShell script and second step is distribute the PowerShell script via Microsoft Intune.

Let’s start with the first step. The following PowerShell script provides a simple example that will create the registry path and key if needed. Simply add the copied enrollment token as the value of the $KeyValue variable.
