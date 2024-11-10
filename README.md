
# CODTECH-INTERNSHIP-TASK-01

Name: K.K.GOKUL

Company: CODTECH IT SOLUTIONS

ID: CT08DS9637

Domain: CYBER SECURITY & ETHICAL HACKING

Mentor:
_____________________________________________________________________________________________________________________________________________________________________

# Vulnerability Scanner Project

## Objective

  ### The goal of this project is to perform a basic vulnerability scan on a target IP address and website URL, checking for open ports, missing HTTP security headers, and outdated software versions. This script is designed for educational and testing purposes, offering insights into common network and web vulnerabilities.
_____________________________________________________________________________________________________________________________________________________________________

## Key Features

### Port Scanning: Checks a list of common ports (e.g., 21, 22, 80, 443) on the target IP address to identify any open ports. 

### HTTP Security Headers Check: Scans HTTP headers of a target URL to see if essential security headers are present, including:

### X-Frame-Options

### X-XSS-Protection

### X-Content-Type-Options

### Strict-Transport-Security

### Content-Security-Policy

### Software Version Check: Checks the local Python version and alerts the user if it's outdated. This part can be extended to check for additional software versions if desired.
_____________________________________________________________________________________________________________________________________________________________________

## Code Structure

### scan_open_ports(target): Scans the target IP for open ports in the COMMON_PORTS list. Open ports are identified and listed in the output.

### check_http_headers(url): Checks for the presence of HTTP security headers on the specified URL, warning the user if any are missing.

### check_software_versions(): Examines the local Python version and provides a warning if it's outdated.

### vulnerability_scanner(target, url): Combines the above steps in sequence to perform a full vulnerability scan on the target.
________________________________________________________________________________________________________________________________________________________________________

## Potential Enhancements

### Extend the list of COMMON_PORTS or dynamically scan a larger range of ports.

### Add checks for more software versions or vulnerabilities.

### Save scan results to a file for record-keeping and further analysis.

### Implement multi-threading for faster scanning on larger networks.
________________________________________________________________________________________________________________________________________________________________________

# Example Output

![pythonw_HbhvLxLGiy](https://github.com/user-attachments/assets/887e423d-dbdb-4474-9730-c1022dec9939)
