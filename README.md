# HWID

A HWID spoofer for Windows. Tested on x64 Windows 10 19018. 

- The driver handles disk, volume, NIC (+ ARP), SMBIOS, boot, and GPU identifiers
- The usermode program handles the registry keys and common tracking files

## Note
- IP address, SIDs, and AC/game specific files can still be used to identify you.
- NVME specific IOCTLs are not handled.
- When using a VPN, load the driver after the VPN's TAP driver is loaded
