# Brute-Force Authentication Incident Response

## Detection
- SIEM alert for multiple failed login attempts
- Suspicious account lockouts

## Triage
- Identify affected accounts
- Check source IP addresses
- Correlate with user activity logs

## Containment
- Temporarily lock affected accounts
- Block malicious IP addresses
- Require password reset for compromised accounts

## Eradication
- Remove unauthorized access
- Monitor for repeated attempts
- Apply multi-factor authentication (MFA) if not enabled

## Recovery
- Restore account access after verification
- Review and update password policies
- Educate users on account security

## MITRE ATT&CK
- T1110 – Brute Force
