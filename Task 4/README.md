# Task 4: Setup and Use a Firewall

## Objective
Configure and test basic firewall rules to block and allow specific network traffic.

## Steps (Windows)
1. Open Windows Firewall with Advanced Security.
2. Create a new inbound rule to block TCP port 23 also for HTTP port 8080.
3. Tested using `Test-NetConnection` command.
4. Deleted the rule to restore original state.

## Summary
Firewalls control inbound/outbound traffic based on rules, helping protect against unauthorized access.
