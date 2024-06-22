# Domain 2: Threats, Vulnerabilities, and Mitigations

## Section 4: Malware Attacks

### Malware Attacks

- **Ransomware**: A type of malware that encrypts files and demands payment for their release.
  - *Countermeasures*:
    - Back up your computer regularly.
    - Store backups separately from your main system.
    - Provide user awareness training to recognize and avoid phishing attempts.

- **Trojan**: Appears to be harmless but carries a hidden malicious payload.

- **Worm**: Self-replicating program that spreads across networks.

- **Spyware**: Software that secretly gathers user information without their consent.

- **Bloatware**: Software that takes up excessive space and resources on a system, often unwanted or unnecessary.

- **Virus**: Malicious code that attaches itself to legitimate programs or files and spreads when those programs or files are executed.
  - *Types*:
    - **Multipartite**: Spreads through multiple methods, such as infecting files and boot sectors.
    - **Stealth**: Attempts to hide its presence on a system.
    - **Polymorphic**: Mutates its code to evade detection by antivirus programs.

- **Keylogger**: Records keystrokes on a computer, often used to capture sensitive information like passwords.

- **Logic Bomb**: Malicious code triggered by a specific event or condition.

- **Rootkit**: Software that provides unauthorized access to a computer system, often used to conceal other malware.

## Physical Attacks

- **Brute Force**: Attempting to gain unauthorized access by trying many different passwords or keys.

- **Radio Frequency Identification (RFID) Cloning**: Copying RFID tags to gain unauthorized access.

- **Environmental**: Attacks targeting physical infrastructure, such as temperature or power supply manipulation.

## Network Attacks

- **Distributed Denial of Service (DDoS)**: Flooding a network or server with traffic to disrupt services.
  - *Types*:
    - **Amplified**: Exploiting systems that amplify the volume of traffic sent to the target.
    - **Reflected**: Spoofing the source IP address to redirect responses to the target.

- **Domain Name System (DNS) Attacks**: Manipulating DNS responses to redirect users to malicious sites.

- **Wireless Attacks**: Exploiting vulnerabilities in wireless networks, such as intercepting traffic or unauthorized access.

- **On-path Attacks**: Intercepting and manipulating communication between two parties.

- **Credential Replay**: Reusing stolen credentials to gain unauthorized access.

- **Malicious Code**: Software designed to disrupt, damage, or gain unauthorized access to computer systems.

## Application Attacks

- **Injection**: Inserting malicious code or commands into an application to exploit vulnerabilities.

- **Buffer Overflow**: Writing data outside the bounds of allocated memory buffers.

- **Privilege Escalation**: Exploiting vulnerabilities to gain higher levels of access within an application or system.

- **Forgery**: Creating fake data or commands to deceive an application or user.

- **Directory Traversal**: Exploiting insufficient input validation to access files outside of the intended directory.

- **Replay**: Capturing and replaying valid data packets to gain unauthorized access.

## Cryptographic Attacks

- **Downgrade**: Forcing the use of weaker cryptographic protocols or algorithms.

- **Collision**: Generating two different inputs that produce the same output hash value.

- **Birthday**: Exploiting the mathematical probability that two individuals share the same cryptographic hash value.

## Password Attacks

- **Spraying**: Attempting to authenticate with a small number of commonly used passwords across multiple accounts.

- **Brute Force**: Trying every possible password until the correct one is found.

## Indicators

- **Account Lockout**: Excessive failed login attempts leading to account lockout.

- **Concurrent Session Usage**: Unexpected multiple sessions from the same user.

- **Blocked Content**: Preventing access to certain content or services.

- **Impossible Travel**: Logins from geographically distant locations in a short period.

- **Resource Consumption**: Unusual consumption of system resources, such as CPU or memory.

- **Resource Inaccessibility**: Inability to access critical resources or services.

- **Out-of-Cycle Logging**: Logging events that occur outside of expected timeframes.

- **Missing Logs**: Absence of expected log entries, indicating potential tampering or manipulation.