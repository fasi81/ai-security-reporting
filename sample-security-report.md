# Sample Security Report

## Summary
A review of the Nmap scan identified several open services, including SSH, HTTP, HTTPS, and RDP.

## Key Findings
- Port 22 SSH is open.
- Port 80 HTTP is open.
- Port 443 HTTPS is open.
- Port 3389 RDP is open.

## Risk Level
Medium to High

## Security Concern
The exposed RDP service may increase the risk of brute-force attacks or unauthorised access if not properly restricted.

## Recommended Remediation
- Restrict RDP access using VPN or allowlisted IP addresses.
- Enforce multi-factor authentication where possible.
- Disable unused services.
- Monitor authentication logs for failed login attempts.

## Follow-up
Validate whether exposed services are required and confirm remediation with the technical team.
