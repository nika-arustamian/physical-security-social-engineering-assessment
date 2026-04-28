# Physical Security & Social Engineering Assessment

## Overview

This project is a training-based security assessment focused on physical security, social engineering risks, and protection of critical financial workstations.

The scenario is based on a fictional agricultural company, LLC “Symyrenky”, where the main objective is to evaluate how human trust, weak access control, and poor workstation security can lead to compromise of sensitive systems.

## Objective

The goal of this assessment is to identify potential weaknesses in:

- physical access control
- employee awareness
- workstation security
- remote access protection
- protection of financial systems
- visitor verification procedures

## Scenario Summary

The company uses a magnetic lock at the main entrance, has an alarm system, and does not have external video surveillance.

The most critical asset is the workstation of the Chief Accountant because it may provide access to financial reporting, payroll, banking, and internal accounting systems.

## Key Risks Identified

### 1. Tailgating

Unauthorized access may be possible if an employee opens the door and allows an unknown person to enter without verification.

### 2. Social Engineering

An attacker may pretend to be an external IT contractor performing a software licensing or security audit.

### 3. Weak Visitor Verification

Employees may trust a person who sounds professional and uses official terminology such as:

- Software Asset Management audit
- Microsoft license verification
- workstation compliance check
- security configuration review

### 4. Workstation Exposure

If the Chief Accountant’s computer is unlocked or left active during lunch, sensitive systems may be exposed.

### 5. Remote Access Risk

If credentials are compromised, legitimate remote access tools such as RDP may be abused by an attacker.

### 6. Magnetic Lock Weakness

A magnetic lock depends on electricity. If power is lost, it may switch to a fail-safe state and open automatically.

### 7. Alarm System Weakness

If the alarm system does not have backup power or is not activated due to operational habits, the office may remain vulnerable.

### 8. Visual Exposure / Shoulder Surfing

If the Chief Accountant’s workstation is located near a window, credentials or confidential financial data may be visible from outside.

## Impact

Successful exploitation of these weaknesses could lead to:

- unauthorized access to the office
- compromise of the Chief Accountant’s workstation
- exposure of financial data
- account takeover
- unauthorized changes in financial systems
- payroll disruption
- reputational damage
- financial loss

## Recommendations

### Physical Security

- Implement a strict no-tailgating policy
- Require visitor registration
- Use visitor badges
- Ensure all visitors are escorted
- Install external video surveillance
- Review magnetic lock configuration
- Add backup power for access control systems

### Employee Awareness

- Conduct regular security awareness training
- Teach employees how to verify external contractors
- Establish a clear rule: never enter passwords when requested by third parties
- Train staff to report suspicious behavior

### Workstation Security

- Enable automatic screen lock after 5 minutes of inactivity
- Require MFA for critical systems
- Apply the principle of least privilege
- Restrict access to financial systems
- Monitor login activity

### Remote Access Security

- Allow RDP only through VPN
- Restrict RDP access by IP address
- Enable MFA for remote access
- Monitor unusual login times and locations
- Disable unnecessary remote access services

### Alarm and Power Protection

- Use UPS backup power for alarms and access control
- Monitor power loss events
- Test alarm response procedures regularly
- Ensure the alarm is activated after business hours

### Visual Privacy

- Move critical workstations away from windows
- Use privacy screen filters
- Install blinds or curtains
- Avoid displaying sensitive financial data in visible areas

## Conclusion

This assessment demonstrates that the most dangerous security weaknesses are often not purely technical. Human trust, poor verification procedures, weak physical access control, and lack of awareness can create serious risks for an organization.

Even if a company has a magnetic lock, alarm system, and basic IT controls, these protections may fail if they are not supported by strong procedures, employee training, and continuous monitoring.

The strongest defense is a layered security approach that combines physical controls, technical protections, and human awareness.

## Skills Demonstrated

- Physical Security Assessment
- Social Engineering Risk Analysis
- Threat Modeling
- Risk Identification
- Security Awareness Evaluation
- Security Recommendations Development

---
This project is created for educational purposes and demonstrates practical understanding of real-world security risks.
