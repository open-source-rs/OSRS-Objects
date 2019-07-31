# OSRS-Objects
For the creation of custom objects in MISP

## This repository contains the following objects:

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
   - Files copied is used to record the file(s) that were copied by the sample during run time.  The object contains the following attributes:
     - File name
	 - File name with Path
### 5. OSRS-VT-Files-Deleted
   - Files deleted is used to record the file(s) that were deleted by the sample during run time.  The object contains the following attributes:
     - File name
	 - File name with Path
### 6. OSRS-VT-Files-Dropped
   - Files dropped is used to record the file(s) that were dropped onto the system by the sample during run time.  The object contains the following attributes:
     - File name
	 - File name with Path
### 7. OSRS-VT-Files-Imported
   - Files imported is used to record the file(s) that were needed by the sample during run time and were imported during the run time process.  The object contains the following attributes:
     - File name
	 - File name with Path
### 8. OSRS-VT-Files-Opened
   - Files opened is used to record the file(s) that were opened by the sample during the run time process.  The object contains the following attributes:
     - File name
	 - File name with Path
### 9. OSRS-VT-Files-Written
   - Files written is used to record the file(s) that were written to disk during the run time process of the sample.  The object contains the following attributes:
     - File name
	 - File name with Path
### 10. OSRS-VT-Mutexes-Created
   - Mutexes created is used to record the mutex(es) that were created by the sample during run time.  The object contains the following attributes:
     - Mutex
### 11. OSRS-VT-Mutexes-Opened
   - Mutexes opened is used to record the mutex(es) that were opend by the sample during the run time process.  The object contains the following attributes:
     - Mutex
### 12. OSRS-VT-Premissions-Requested
   - Permissions requested is used to record the permissions that were requested by the sample during run time.  The object contains the following attributes:
     - Text
### 13. OSRS-VT-Process-Tree
   - Process tree is used to record the process tree(s) that were created by the sample during the run time process.  The object contains the following attributes:
     - Text (process no id)
	 - Text (process with id)
### 14. OSRS-VT-Processes-Created
   - Processes created is used to record the process(es) that were created by the sample.  The object contains the following attributes:
     - Text (process no id)
	 - Text (process with id)
### 15. OSRS-VT-Registry-Keys-Deleted
   - Registry keys deleted is used to record the registry keys that were removed during the sample run time.  The object contains the following attributes:
     - Regkey
	 - Regkey|value
### 16. OSRS-VT-Registry-Keys-Opened
   - Registry keys opened is used to record the registry keys that were opened during the sample run time.  The object contains the following attributes:
     - Regkey
	 - Regkey|value
### 17. OSRS-VT-Registry-Keys-Set
   - Registry keys set is used to record the registry key and the value set during the sample run time process.  The object contains the following attributes:
     - Regkey
	 - Regkey|value
### 18. OSRS-VT-Runtime-Modules-Loaded
   - Run time modules loaded is used to record the modules that were loaded by the sample.   The object contains the following attributes:
     - Filename
### 19. OSRS-VT-Services-Opened
   - Services opened is used to record the services that were opened by the sample during the run time process.  The object contains the following attributes:
     - Text
### 20. OSRS-VT-Shell-Commands
   - Shell commands is use to record any of the shell commands executed by the sample during the run time process.  The object contains the following attributes:
     - Text










