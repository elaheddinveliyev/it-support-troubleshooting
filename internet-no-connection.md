# Internet Connection Issue

## Problem
User has no internet access on Windows PC.

## Environment
- Windows 10/11 workstation (simulated corporate environment)

## Possible Causes
- Incorrect IP configuration
- DNS issues
- Network adapter disabled
- Router or gateway issue

## Troubleshooting Steps

### 1. Check physical connection
- Ensure Ethernet cable is connected or Wi-Fi is enabled

### 2. Check IP configuration
Run:
ipconfig /all

If IP starts with 169.254 → DHCP issue detected

### 3. Renew IP address
ipconfig /release  
ipconfig /renew

### 4. Flush DNS cache
ipconfig /flushdns

### 5. Test connectivity
ping google.com

## Result
Issue resolved after IP renewal and network reset.
