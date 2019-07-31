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
  
2. OSRS-VT-Contacted-Domains
   - Contacted domains is used to record the domains that the sample attempted to communicate with.  This object Containst the following attrubtues:
     - Domain
* OSRS-VT-Contacted-IPs
* OSRS-VT-Files-Copied
* OSRS-VT-Files-Deleted
* OSRS-VT-Files-Dropped
* OSRS-VT-Files-Imported
* OSRS-VT-Files-Opened
* OSRS-VT-Files-Written
* OSRS-VT-Mutexes-Created
* OSRS-VT-Mutexes-Opened
* OSRS-VT-Premissions-Requested
* OSRS-VT-Process-Tree
* OSRS-VT-Processes-Created
* OSRS-VT-Registry-Keys-Deleted
* OSRS-VT-Registry-Keys-Opened
* OSRS-VT-Registry-Keys-Set
* OSRS-VT-Runtime-Modules-Loaded
* OSRS-VT-Services-Opened
* OSRS-VT-Shell-Commands
