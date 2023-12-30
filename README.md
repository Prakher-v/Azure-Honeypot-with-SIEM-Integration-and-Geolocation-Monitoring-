# Azure-SIEM-Honeypot
We are going to set up a SIEM (Security Information and Event Management) tool using Azure to capture attacks on our Honey-pot. The Honey-pot will be deployed on a Windows 10 VM machine within the Azure environment.

The steps involved in this project include:

1. Setting up the Honey-pot: We will deploy the Honey-pot on an Azure VM.
2. Making the VM vulnerable: We will intentionally expose vulnerabilities in the VM to attract potential attackers.
3. Monitoring Windows Event Viewer: After a few hours, we will check the Windows Event Viewer on our VM to gather data on any attempted attacks.
4. Linking our VM with SIEM: We will connect our VM to the SIEM tool, and also create a Log Analytics Workspace for centralized logging.
5. Enhancing data representation: To provide a geographical context, we will utilize a third-party API, such as IPGeolocation.io, to obtain the attacker's geo-location, latitude, and altitude. This information will then be visualized on a map in our SIEM dashboard.

Languages and utilities used in this project include PowerShell for automation, Azure for cloud infrastructure, Azure Sentinel as our SIEM tool, IPGeolocation.io for obtaining attacker location data, and KQL (Kusto Query Language) for querying and analyzing the collected data.

![GEO_script](https://github.com/Prakher-v/Azure-SIEM-Honeypot/assets/92503482/ad7d474e-168a-4ab2-9e30-c53d09f92bc9)
