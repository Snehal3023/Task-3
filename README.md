# Task-3
Perform a Basic Vulnerability Scan on Your PC.
### 1. Download and install from: https://www.tenable.com/products/nessus
### 2. The scan target:- 
172.22.34.53

### 3. Full vulnerability scan Steps
#### 1.New Scan 
#### 2.Choose a “Basic Network Scan” and use your IP address as the target.
      Give Name and IP address of target to scan vulnerability
#### 3. Schedule the scan once or daily
#### 4. Use plugins or make default all plugins
#### 4. Save and lunch.
After launching It may take 30 to 60 minutes.

### 5. Review the scan report
28  Vulnerability found
SMB Signing not required has Medium Severity 

### 6. Research fixes the Vulnerability
      SMB Signing not required
### Description
Signing is not required on the remote SMB server. An unauthenticated, remote attacker can exploit this to conduct man-in-the-middle attacks against the SMB server.
### Solution
Enforce message signing in the host's configuration. On Windows, this is found in the policy setting 'Microsoft network server: Digitally sign communications (always)'. On Samba, the setting is called 'server signing'.
### 7. Most critical vulnerabilities not found

### 8. Scan result
![Generated Report](https://github.com/user-attachments/assets/54a32ad2-9b9e-4155-9490-9e6abfaeafd0)


      
