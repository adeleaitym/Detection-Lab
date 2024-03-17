# RDP Attack Log Parser and Geolocation Lookup

This repository contains a PowerShell script responsible for parsing Windows Event Log information for failed Remote Desktop Protocol (RDP) attacks. It utilizes a third-party API, such as ipgeolocation.io, to collect geographic information about the attackers' locations based on their IP addresses.
![Screenshot 2024-03-17 at 19 27 10](https://github.com/adeleaitym/Detection-Lab/assets/161321795/b28ef096-b0e2-4587-bb83-ede46d7d89f7)


## Objective

The PowerShell script is utilized in a demo scenario where Azure Sentinel (SIEM) is set up and connected to a live virtual machine acting as a honey pot. This setup allows observation of live RDP brute force attacks from various locations worldwide. The custom PowerShell script is then used to extract attackers' geolocation information, which is plotted on an Azure Sentinel Map for visualization.

### Skills Learned

- Understanding of PowerShell scripting for log parsing and automation.
- Integration of third-party APIs for geolocation lookup.
- Utilization of Azure Sentinel for SIEM and visualization purposes.
- Knowledge of RDP attack patterns and defensive strategies.
- Hands-on experience in cybersecurity threat detection and response.

### Tools Used

- PowerShell for scripting and automation.
- Third-party geolocation API for retrieving attacker locations.
- Azure Sentinel for SIEM and visualization.
- Windows Event Log for capturing RDP attack logs.

 ## Attacks from the Netherlands coming in; Custom logs being output with geodata
 ![Screenshot 2024-03-17 at 19 21 15](https://github.com/adeleaitym/Detection-Lab/assets/161321795/a605a054-8ca7-41d3-ba3b-f429545be3f3)

 ## World map of incoming attacks after 6 hours (built custom logs including geodata)
 ![Screenshot 2024-03-17 at 19 32 53](https://github.com/adeleaitym/Detection-Lab/assets/161321795/be07f9e3-db9a-45c2-ae4b-859b45b95922)


