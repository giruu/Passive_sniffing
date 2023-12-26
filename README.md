# Passive sniffer

**Overview**
This script provides a simple interface for scanning the local network using the netdiscover tool.

**Dependencies**
* netdiscover command (install with sudo apt-get install netdiscover on Debian-based systems)

**Usage**
* 
```bash
git clone https://github.com/giruu/Passive_sniffing.git
```
Navigate to the cloned directory:

```bash
cd Passive_sniffing
```
* Make the script executable: chmod +x netdiscover_passive.sh
* Run the script: ./netdiscover_passive.sh
* Enter the desired network interface name when prompted.

**Notes**
* Ensure netdiscover is installed on your system.
T* he script assumes the "Logo" subdirectory and "introxt_logo" file are present in the same directory if you want to display a logo.
