# Windows-Firewall
"Windows Firewall task: created inbound/outbound rules, tested blocking/allowing ports (Telnet 23 / SSH 22) using PowerShell, and documented with screenshots + commands."
# Task 4 — Windows Firewall

## What I Did
- Opened Windows Defender Firewall with Advanced Security.
- Listed current firewall rules and saved them (`firewall_rules_before.txt`).
- Created a blocking inbound rule for port 2323 (as test for Telnet port).
- Tested with `Test-NetConnection` before and after blocking (success → fail).
- Created a rule to allow SSH (port 22).
- Removed the test rule to restore firewall.

## Evidence
- Screenshots are saved in the `screenshots` folder.
- Command outputs are saved in `firewall_rules_before.txt` and `commands_used.txt`.

## Notes
- Used PowerShell (Admin) for creating rules and testing.
- Port 2323 was used for safe testing instead of port 23.
