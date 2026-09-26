# Ticket #003 — No Internet Connection

**Ticket ID:** 003  
**User:** Jordan Brown  
**Department:** Marketing  
**Issue:** No internet connection  
**Priority:** High  
**Status:** Resolved  

## User Description

Jordan Brown reports that websites are not loading and the computer appears to have lost internet access.

## Resolution Notes

Investigated the user’s reported loss of internet connectivity and reviewed the system’s network configuration. Identified that both TCP/IPv4 and TCP/IPv6 were disabled on the Ethernet adapter. Re-enabled both protocols, verified that the system received network configuration again, and confirmed that Jordan Brown could successfully access websites. Issue resolved.
## Screenshots

### No Internet Connection
![Internet connection failure](screenshots/9-ticket-003-no-internet.png)

### IP Configuration Diagnosis
![IP configuration diagnosis using ipconfig](screenshots/10-ticket-003-ipconfig-diagnosis.png)

### Network Protocols Restored
![TCP IPv4 and IPv6 protocols restored](screenshots/11-ticket-003-network-protocols-restored.png)

### Connectivity Restored
![Internet connectivity successfully restored](screenshots/12-ticket-003-connectivity-restored.png)
