# ARP Poisoner
A python3-based tool for scanning devices on a local network and performing an ARP poisoning to test or stress the network connnectivity
You can either target specific devices or poison the entire network.
P.s: This script supports Windows

## Disclaimer
This tool is for educational purposes only. Unauthorized use of this tool on networks that you do not own or have explicit permission to test is illegal and unethical. Use responsibly.


# Requirements
-Python3

## Features
- **Network Scanner:** Scans devices in the local network to retrieve their IP and MAC addresses.
- **ARP Poisoning:** Performs ARP spoofing to disrupt the network connectivity of selected devices or all users on the network.
- **MAC Address Lookup:** Retrieves the manufacturer of devices with the help of the MAC address and an API.
- **Device List Saving:** Allows saving and restoring of previously scanned devices.
  
# Installation

Open cmd in the project directory and type in:
```
pip install -r requirements.txt
```
Then lauch the script by typing:
```
python wifieliminator.py
```

