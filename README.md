# Adversarial Knowledge Workflow Suite (AKWS)

## Overview

Adversarial Knowledge Workflow Suite (AKWS) is a comprehensive framework designed to provide both red and blue teams with a structured template for simulating cyber-attacks and defending against them using machine learning techniques. The suite consists of various modules, each targeting a specific aspect of cyber-security, from basic attacks like password spraying to advanced persistent threats like the Golden Ticket attack. The modules are named sequentially from AK1 to AK47, where each module addresses a distinct attack vector or defensive measure.

## Modules

### AK1 - Password Spray

**Objective:** Simulate a password spray attack where a few common passwords are tried against many accounts to avoid account lockouts and detect weak credentials.

**Features:**
- Customizable list of common passwords.
- Configurable rate limits to mimic real-world attack scenarios.
- Logging and reporting of successful attempts.

### AK2 - Golden Ticket

**Objective:** Simulate a Golden Ticket attack, where a forged Kerberos ticket grants unauthorized access to resources within the domain.

**Features:**
- Emulation of ticket creation using compromised domain credentials.
- Simulation of ticket usage to access protected resources.
- Detection algorithms to identify Golden Ticket usage.

## Features

- **Modular Design:** Each attack and defense module is independent, allowing easy integration and customization.
- **Machine Learning Integration:** Leverages machine learning algorithms to enhance attack simulations and defensive strategies.
- **Scalable and Configurable:** Designed to work in various environments, with configuration options to tailor the behavior of each module.
- **Detailed Reporting:** Provides comprehensive reports on each simulated attack, including success rates and detected vulnerabilities.

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Required Python libraries (specified in `requirements.txt`)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/akws.git
    cd akws
    ```

2. Install the required libraries:

    ```bash
    pip install -r requirements.txt
    ```


## Contribution
We welcome contributions from the community. To contribute, please fork the repository and submit a pull request with your changes. Ensure that your code adheres to the existing style and includes appropriate tests.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Brought to you by:

HADESS

HADESS performs offensive cybersecurity services through infrastructures and software that include vulnerability analysis, scenario attack planning, and implementation of custom-integrated preventive projects. We organized our activities around the prevention of corporate, industrial, and laboratory cyber threats.