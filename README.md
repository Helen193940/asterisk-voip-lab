# Asterisk VoIP Lab

Virtualized VoIP lab using Asterisk PBX on Ubuntu and Linphone SIP clients on Windows virtual machines.

## Technologies
- Ubuntu Linux
- Asterisk PBX
- PJSIP
- Linphone
- SIP networking
- Virtual machines

## Topology
- Ubuntu VM: Asterisk SIP server
- Windows VM 1: Linphone extension 1003
- Windows VM 2: Linphone extension 1004

## Features
- Configured PJSIP SIP accounts
- Created internal dialplan routing
- Registered SIP clients
- Tested internal VoIP calls
- Troubleshot registration and dialplan issues

## Key Commands
```bash
sudo asterisk -rvvv
pjsip show endpoints
pjsip show contacts
dialplan show from-internal

## What I Learned
This project strengthened my hands-on skills in Linux server administration, SIP/PJSIP configuration, VoIP troubleshooting, and virtualized networking.
