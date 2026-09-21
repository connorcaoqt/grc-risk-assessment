# Risk Register

This risk register documents cybersecurity risks identified for SecureCloud Solutions.

|  ID  | Asset | Threat | Vulnerability | Risk Event | Business Impact | Likelihood | Impact | Risk Level | Treatment |
|---|---|---|---|---|---|---|---|---|---|
| R-01 | Customer Database | Threat Actor | No MFA on employee accounts | Attacker steals an employee's logging credentials and access the database | Legal or regulatory consequences and reputational damage | 4 - Likely | 4 - Major | 16 - high risk | Mitigate: Implement MFA and security awareness training |
| R-02 | Employee laptop | Unauthorized person / thief | Laptop left unattended without a password or screen lock | Unauthorized person gains access to the laptop and views stored company information | Competitive disadvantage from exposure of confidential company information | 3 - possible | 4 - major | 12 - high risk | Mitigate: (require passwords and automatic screen locks on employee laptops) |
| R-03 | Cloud service / SaaS application | Threat actor launching a DDoS attack | DDoS protection is in place, but rate limiting is misconfigured or insufficient | DDoS attack overwhelms the cloud service, making it temporarily unavailable | Lost revenue, service disruption, and reduced customer trust | 2 - Unlikely | 4 - Major | 8 - Moderate | Mitigate: Correct rate limiting and strengthen DDoS protections |
