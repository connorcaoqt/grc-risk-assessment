# NIST CSF Mapping

| Risk ID | Risk | NIST CSF Function | Control | Reason |
|---|---|---|---|---|
| R-01 | Unauthorized access to customer data through stolen employee credentials | Protect | Multi-factor authentication (MFA) | MFA helps prevent unauthorized access even if an employee's password is stolen |
| R-02 | Unauthorized access to an unattended employee laptop | Protect | Passwords and automatic screen locks | Passwords and automatic screen locks help prevent unauthorized users from viewing sensitive company information |
| R-03 | Temporary cloud service outage caused by a DDoS attack | Protect | DDoS protection and rate limiting | These controls help reduce malicious traffic and prevent the cloud service from being overwhelmed |
| R-04 | Temporary outage of the internal employee portal | Govern | Documented risk acceptance | Management accepts the low risk because temporary downtime is tolerable and does not justify additional safeguards |

The following section provides a deeper example of how a single risk can involve multiple NIST CSF functions throughout the incident lifecycle.

## R-03 DDoS Risk - NIST CSF Lifecycle

| NIST CSF Function | Control or Action | Purpose |
|---|---|---|
| Protect | DDoS protection and rate limiting | Reduce malicious traffic before it overwhelms the service |
| Detect | Traffic spike alerts | Alert the security team when unusual traffic is detected |
| Respond | Block malicious traffic | Limit the attack while it is occurring |
| Recover | Restore affected services | Return systems and services to normal operation |
