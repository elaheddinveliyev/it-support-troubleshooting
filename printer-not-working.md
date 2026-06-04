# Printer Not Working Issue

## Problem
User is unable to print documents.

## Environment
- Windows 10/11 workstation
- Shared office printer setup

## Possible Causes
- Printer not set as default
- Print spooler service issue
- Driver problem
- Connection issue

## Troubleshooting Steps

### 1. Check connection
- Verify USB or network connection

### 2. Set default printer
Settings → Devices → Printers → Set as default

### 3. Restart Print Spooler
Run:
services.msc → Print Spooler → Restart

### 4. Clear print queue
Cancel all pending documents

### 5. Reinstall driver if needed

## Result
Printer resumed normal operation after spooler restart.
