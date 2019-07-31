# OSRS-Objects
For the creation of custom objects in MISP

## This repository contains the following objects:

### 1. OSRS-VT-Base-Object
   - Base object used for creating the anchor to all other objects by reference.  This object contains the following attributes:
     - MD5 Hash Value
     - SHA-1 Hash Value
     - SHA-256 Hash Value
     - File Names
     - Link to VirusTotal Report
     - File Type
  
### 2. OSRS-VT-Contacted-Domains
   - Contacted domains is used to record the domains (or URLs) that the sample attempted to communicate with.  This object contains the following attrubtues:
     - Domain
### 3. OSRS-VT-Contacted-IPs
   - Contact IPs is used to record the IP address(es) that the sample attempted to communicate with.  The object contains the following attributes:
     - Destination IP
### 4. OSRS-VT-Files-Copied
### 5. OSRS-VT-Files-Deleted
### 6. OSRS-VT-Files-Dropped
### 7. OSRS-VT-Files-Imported
### 8. OSRS-VT-Files-Opened
### 9. OSRS-VT-Files-Written
### 10. OSRS-VT-Mutexes-Created
### 11. OSRS-VT-Mutexes-Opened
### 12. OSRS-VT-Premissions-Requested
### 13. OSRS-VT-Process-Tree
### 14. OSRS-VT-Processes-Created
### 15. OSRS-VT-Registry-Keys-Deleted
### 16. OSRS-VT-Registry-Keys-Opened
### 17. OSRS-VT-Registry-Keys-Set
### 18. OSRS-VT-Runtime-Modules-Loaded
### 19. OSRS-VT-Services-Opened
### 20. OSRS-VT-Shell-Commands
