# Domain 2: Threats, Vulnerabilities, and Mitigations

## Section 5: Mitigation Techniques

### Safeguards and Countermeasures

Safeguards are proactive measures taken to prevent security breaches, while countermeasures are reactive actions taken in response to a security incident.

### Segmentation

- **Physical Segmentation**: Using hardware-based controls to separate network segments.
- **Logical Segmentation**: Implementing software-defined controls to partition network traffic.
- *Example*: Firewall rules restricting traffic between different segments.

### Access Control

- **Mandatory Access Control**: Access is determined by the system, not the object owner.
- **Discretionary Access Control**: Owners or creators of objects control and define their accessibility.
- **Non-discretionary Access Control**: Access control determined by factors other than the object owner.
- **Role-Based Access Control (RBAC)**: Access is based on predefined roles or job functions.
- **Rules-Based Access Control**: Access is determined by predefined rules or conditions.
- **Access Control List (ACL)**: Lists of permissions attached to an object.
- **Permissions**: Specific rights granted to users or groups for accessing resources.

### Application Allow List

- Defining a list of approved applications allowed to run on a system, blocking all others.

### Isolation

- Isolating critical systems or sensitive data from the rest of the network to minimize the impact of a breach.

### Patching

- Regularly applying updates and patches to fix vulnerabilities in software and systems.

### Encryption

- Protecting data by converting it into a coded form that only authorized parties can access.

### Monitoring

- Continuous monitoring of network traffic, system logs, and user activities for signs of suspicious behavior.

### Least Privilege

- Providing users with only the minimum level of access necessary to perform their job functions.

### Configuration Enforcement

- Enforcing security configurations and policies to ensure compliance with organizational standards.

### Decommissioning

- Properly removing or retiring outdated systems or services to prevent security risks.

### Hardening Techniques

- Strengthening security by implementing various measures such as encryption, host-based firewalls, and intrusion detection systems.
- *Example*: Changing default passwords, disabling unnecessary ports and protocols.

## SIEM & SOAR

- **SIEM (Security Information and Event Management)**: A system that collects data from various sources within the network, providing real-time monitoring, analysis, correlation, and notification of potential security threats.
- **SOAR (Security Orchestration, Automation, and Response)**: Centralized alert and response automation platform with threat-specific playbooks. Responses may be fully automated or initiated with a single click.