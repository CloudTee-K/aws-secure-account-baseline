## Threat Model — AWS Account Baseline

### Threat: Root Account Compromise
Impact: Complete account takeover  
Mitigation: MFA enforced, root usage eliminated

### Threat: Unauthorized API Calls
Impact: Resource manipulation, data loss  
Mitigation: CloudTrail enabled across all regions

### Threat: Configuration Drift
Impact: Security controls silently disabled  
Mitigation: AWS Config continuous monitoring

