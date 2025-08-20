# Ex-02 InformationGathering
## AIM:
To perform information gathering techniques using kali linux 
## STEPS:
### Step 1:
Install kali linux either in partition or virtual box or in live mode

### Step 2:
Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```
## OUTPUT:
### Whois : 
<img width="1622" height="949" alt="image" src="https://github.com/user-attachments/assets/14a6fb5c-587e-4d15-b0cc-f0395b573359" />

### Finding Hosting Company :
<img width="1722" height="951" alt="image" src="https://github.com/user-attachments/assets/e0712487-5478-4b70-9a3f-5b7b47531219" />
<img width="1727" height="950" alt="image" src="https://github.com/user-attachments/assets/7105e60b-c983-4a7d-bc5a-b65e3b55751f" />


### History of the website :
<img width="1730" height="951" alt="image" src="https://github.com/user-attachments/assets/9e7bc4ac-b968-4e79-a409-2c54f43a80c4" />

### nmap :
<img width="955" height="323" alt="image" src="https://github.com/user-attachments/assets/21d9169f-06e9-488e-b275-bd8a7da7a454" />

### whatweb :
<img width="938" height="758" alt="image" src="https://github.com/user-attachments/assets/2bb991f0-228f-4d8c-b601-269ecd492282" />

### httprint :
<img width="1648" height="836" alt="image" src="https://github.com/user-attachments/assets/8dd93fd8-7359-4777-b19d-24b98258618c" />

### TCP traceroute :
<img width="1034" height="148" alt="image" src="https://github.com/user-attachments/assets/5053f965-93ec-4ce2-aece-b1c18d354d88" />
<img width="1047" height="767" alt="image" src="https://github.com/user-attachments/assets/c48347bf-1cba-4bb5-a572-a7e40fee4304" />


### UDP traceroute :
<img width="1028" height="773" alt="image" src="https://github.com/user-attachments/assets/bfba50d1-7211-4bb6-bd8f-ab45dec779fe" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
