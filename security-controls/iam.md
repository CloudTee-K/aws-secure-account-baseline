## IAM Security Controls

### Controls Implemented
- Root account protected with MFA
- Dedicated admin IAM user
- MFA enforced on all privileged users
- Strong password policy configured

### Security Rationale
IAM is the primary security boundary in AWS. Compromised credentials lead directly to account takeover if not properly protected.

### Risks if Misconfigured
- Privilege escalation
- Credential stuffing attacks
- Persistent unauthorized access
