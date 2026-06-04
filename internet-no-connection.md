# Internet Connection Issue

## Problem
User has no internet access on Windows PC.

## Possible Causes
- Wrong IP configuration
- DNS issue
- Router problem
- Network adapter disabled

## Troubleshooting Steps

### 1. Check physical connection
- Ethernet cable plugged in
- Wi-Fi turned on

### 2. Check IP address
Run command:
ipconfig

If IP starts with 169.254 → DHCP issue

### 3. Renew IP
ipconfig /release
ipconfig /renew

### 4. Flush DNS
ipconfig /flushdns

### 5. Test connection
ping google.com

## Result
Issue resolved after IP renewal
