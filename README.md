# NetProbe - Mini Network Scanner

## Overview

NetProbe is a versatile and lightweight network scanning tool designed to help you discover open ports, detect service versions, and identify the operating system of remote hosts. Whether you're a network administrator, a cybersecurity enthusiast, or just curious about the devices on your network, NetProbe simplifies the process of probing and gathering information.

## Features

### 1. Port Scanning

Easily scan a range of ports on a target host to determine which services are running and accessible. NetProbe offers quick and efficient port scanning capabilities, making it an essential tool for network diagnostics.

### 2. Service Version Detection

For each open port, NetProbe can optionally detect and display the service version. This feature provides valuable insights into the software running on a remote host, aiding in vulnerability assessment and service identification.

### 3. Operating System Detection

NetProbe employs the power of Nmap to perform operating system detection. By analyzing network packets and responses, it provides information about the remote host's operating system family. This can be particularly useful for network profiling and security auditing.

### 4. User-Friendly Interface

NetProbe's command-line interface is intuitive and user-friendly. It prompts you for target details, scan parameters, and output preferences, ensuring a smooth and hassle-free experience.

### 5. Output to File

Results from NetProbe scans can be easily saved to a file of your choice. This feature allows you to maintain records, share findings, or integrate NetProbe into your network monitoring workflows.

## Getting Started

1. Run the script by executing `python NetProbe.py` in your terminal.

2. Follow the on-screen prompts to configure your network scan. Provide the target IP address or domain name, specify the range of ports to scan, and choose whether to detect service versions.

3. Set the timeout for the port scan (default is 1 second) and specify the output filename for your results.

4. NetProbe will initiate the scan, providing real-time feedback about open ports and service versions. Once complete, the results will be saved to the specified output file.

5. Review the saved results to gain insights into the target host's network configuration and services.

## Notes

NetProbe is designed for educational and network diagnostic purposes. Please ensure that you have the necessary permissions before scanning a network. Unauthorized scanning may violate legal and ethical standards.

## Acknowledgments

NetProbe leverages the power of Nmap for operating system detection. We express our gratitude to the Nmap project for providing this essential tool for network exploration and security auditing.

## License

This script is provided under an open-source license. Refer to the source code for licensing details.
