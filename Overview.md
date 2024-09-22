# Threat Actor Profile: Twelve

## Executive Summary

The hacktivist group known as "Twelve" emerged in spring 2024, initially focusing on Doxxing individuals through a Telegram channel. After a period of inactivity due to Telegram's suspension of their channel, recent cyberattack investigations in June 2024 indicate that the group remains operational, utilizing tactics and infrastructure consistent with their previous activities.

## Timeline

- **Spring 2024**: Twelve emerges, posting personal data on Telegram
- **Mid-2024**: Telegram suspends Twelve's channel for ToS violations
- **Late June 2024**: Cyberattack investigation reveals Twelve's continued operations

## Tactics, Techniques, and Procedures (TTPs)

### Specialization
- Encryption and deletion of victim data
- Aims to inflict maximum damage
- Similar to Shamoon Wiper and WhisperGate attacks

### Infrastructure
- Shares infrastructure with DARKSTAR ransomware
- Possible connection or collaboration between the groups

### Initial Access
- Compromised contractor/vendor VPNs
- Valid credentials

### Tools
Extensive use of publicly available tools:
- Cobalt Strike
- Mimikatz
- BloodHound

### Advanced Techniques
- Sophisticated persistence mechanisms
- Lateral movement strategies
- Privilege escalation in Active Directory environments

### Execution and Evasion
- Web shells
- Custom scripts
- Scheduled tasks

### Payload Delivery
- Coordinated across compromised domain
- Utilizes group policy modifications

## Implications

This analysis underscores the evolving complexity of cyber threats, particularly:
1. The importance of supply chain security
2. The need for robust Active Directory security measures
3. The potential for hacktivist groups to evolve into more sophisticated threat actors

## Recommendations

1. Implement strict access controls and monitoring for third-party vendors and contractors
2. Regularly audit and secure Active Directory environments
3. Deploy advanced endpoint detection and response (EDR) solutions
4. Conduct regular threat hunting exercises focusing on the TTPs associated with Twelve
5. Enhance security awareness training, particularly regarding social engineering and credential protection

## Conclusion

While Twelve's initial activities focused on doxxing, their evolution into a more sophisticated threat actor poses significant risks. Organizations should remain vigilant and proactively strengthen their security posture against these emerging threats.
