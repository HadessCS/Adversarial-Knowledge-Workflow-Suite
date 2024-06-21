# Adversarial Knowledge Workflow Suite (AKWS)

## Overview

Adversarial Knowledge Workflow Suite (AKWS) is a comprehensive framework designed to provide both red and blue teams with a structured template for simulating cyber-attacks and defending against them using machine learning techniques. The suite consists of various modules, each targeting a specific aspect of cyber-security. This README focuses on the Golden Ticket attack simulation (AK2) and its defense using machine learning.

## Golden Ticket Attack (AK2)

### Description

A Golden Ticket attack involves forging a Kerberos Ticket Granting Ticket (TGT), which can then be used to impersonate any user within a domain, including highly privileged accounts. This type of attack can be devastating as it allows an attacker to gain unrestricted access to network resources.

### Attack Flow

1. **Load Configuration**
    - Load necessary parameters from the configuration file (`ak2_golden_ticket_config.json`).

2. **Simulate Golden Ticket Attack**
    - Use compromised domain credentials to forge Kerberos tickets.
    - Use the forged tickets to access protected resources.

3. **Monitor and Log Access Patterns**
    - Track the access patterns using the forged tickets.
    - Log any unusual or suspicious activities.

### Example Configuration

Example `ak2_golden_ticket_config.json`:
```json
{
    "ticket_data": {
        "username": "admin",
        "domain": "example.com",
        "krbtgt_hash": "aad3b435b51404eeaad3b435b51404ee"
    }
}
