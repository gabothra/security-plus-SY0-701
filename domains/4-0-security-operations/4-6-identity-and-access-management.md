# Implement and Maintain Identity and Access Management

## Provisioning/De-provisioning User Accounts
Provisioning involves creating and managing user accounts, while de-provisioning refers to disabling or removing user accounts when they are no longer needed. Proper provisioning and de-provisioning processes are essential for maintaining security and compliance.

## Permission Assignments and Implications
Assigning permissions to user accounts or groups dictates what actions they can perform and what resources they can access. Understanding the implications of permission assignments helps ensure that users have appropriate access levels and privileges.

## Identity Proofing
Identity proofing involves verifying the identity of users before granting them access to resources or systems. This helps prevent unauthorized access and protects sensitive information.

## Federation
Federation enables users to access multiple systems or applications using a single set of credentials. It establishes trust relationships between identity providers and service providers to facilitate seamless authentication and authorization across different domains.

## Single Sign-On (SSO)
SSO allows users to authenticate once and access multiple applications or services without having to log in again. Key protocols used for SSO include:

- **Lightweight Directory Access Protocol (LDAP)**: A protocol used for accessing and managing directory services, such as user authentication and authorization data.
  
- **OAuth (Open Authorization)**: An open standard for access delegation, commonly used for granting third-party applications access to resources on behalf of a user.

- **Security Assertion Markup Language (SAML)**: An XML-based standard for exchanging authentication and authorization data between identity providers and service providers.

## Interoperability
Interoperability ensures that different identity and access management systems can work together seamlessly, enabling users to access resources across diverse platforms and environments.

## Attestation
Attestation involves verifying the integrity and authenticity of user identities and credentials. It ensures that users are who they claim to be and that their access rights are accurate and up-to-date.

## Access Controls
Access controls enforce security policies and regulate user access to resources based on various factors. Common access control models include:

- **Mandatory Access Control**: Access decisions are based on security labels assigned to users and objects by a system administrator.

- **Discretionary Access Control**: Access decisions are at the discretion of the resource owner, who can grant or revoke access permissions.

- **Role-Based Access Control**: Access rights are assigned to users based on their roles within an organization.

- **Rule-Based Access Control**: Access decisions are determined by predefined rules or conditions.

- **Attribute-Based Access Control**: Access decisions are based on attributes associated with users, resources, or the environment.

- **Time-of-Day Restrictions**: Access to resources is restricted based on specific times or schedules.

- **Least Privilege**: Users are granted the minimum level of access required to perform their job functions, reducing the risk of unauthorized access.

## Multifactor Authentication (MFA)
MFA enhances security by requiring users to provide multiple forms of authentication before granting access. Implementations include:

- **Biometrics**: Using physiological or behavioral characteristics, such as fingerprints or voice recognition, to verify a user's identity.

- **Hard/Soft Authentication Tokens**: Physical or virtual devices that generate one-time passwords or authentication codes.

- **Security Keys**: Hardware devices or cryptographic keys used for authentication.

MFA Factors include:

- **Something You Know**: Passwords, PINs, or security questions.
- **Something You Are**: Biometrics, such as fingerprints or facial recognition.
- **Something You Have**: Authentication tokens, smart cards, or mobile devices.
- **Somewhere You Are**: Geolocation-based authentication.

Password Concepts:

- **Password Best Practices**: Guidelines for creating strong passwords, including length, complexity, and regular rotation.
- **Password Managers**: Tools for securely storing and managing passwords.
- **Passwordless**: Authentication methods that eliminate the need for passwords, such as biometrics or security keys.

## Privileged Access Management (PAM) Tools
PAM tools help organizations manage and monitor privileged accounts, which have elevated access privileges. Features include:

- **Just-in-Time Permissions**: Temporarily granting access to privileged accounts only when needed.
- **Password Vaulting**: Securely storing and managing passwords for privileged accounts.
- **Ephemeral Credentials**: Short-lived credentials generated dynamically for privileged access, reducing the risk of exposure.