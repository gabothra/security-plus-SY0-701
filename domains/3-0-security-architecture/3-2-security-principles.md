# Domain 3: Security Architecture

## Section 2: Security Principles

### Infrastructure Considerations

#### Device Placement

- **Influencing Factors**:
  - Purpose/Function of the device
  - Network layout/Segmentation
  - Traffic flow optimization
  - Regulatory compliance requirements

#### Security Zones

- **Containment Zones**:
  - Intranet: Private network accessible only to internal users.
  - Extranet: Sectioned off for both private network and limited access to the public internet.
  - Screened Subnet: Also known as a perimeter network or demilitarized zone (DMZ).

#### Attack Surface

- Surface area susceptible to exploitation by threat actors.

#### Connectivity

- **Secure Connectivity With**:
  - Traffic Filtering
  - Network Segmentation
  - Access Control
  - Security Zones

#### Failure Models

- **Fail Open**: Allows all traffic when the system fails, prioritizing availability.
- **Fail Closed**: Blocks all traffic when the system fails, prioritizing safety and security.

#### Device Attributes

- **Inline vs. Tap/Monitor**:
  - **Inline**: Placed directly in the network path, filtering traffic in real-time.
  - **Tap/Monitor**: Devices that replicate traffic for inspection without directly affecting traffic flow.

#### Network Appliances

- **Jump Server**: Secure gateway for accessing other devices within a network.
- **Proxy Server**:
  - Forward Proxy: Filters outbound web traffic.
  - Reverse Proxy: Authenticates and decrypts secure sections for incoming traffic filtering.
- **Intrusion Prevention System (IPS) / Intrusion Detection System (IDS)**:
  - Monitors network traffic for signs of unauthorized access or malicious activities.
- **Load Balancing**:
  - Distributes network or application traffic across multiple servers for improved performance and redundancy.
- **Sensors**: Devices that monitor and collect data on network activity.

#### Port Security

- **802.1X**: Port-based network access control.
- **Wireless Authentication Protocols**:
  - Extensible Authentication Protocol (EAP): Framework for wireless authentication.
  - LEAP, PEAP, EAP-TLS, EAP-TTLS: Variants of EAP for different authentication needs.

#### Firewall Types

- **Static Packet Filtering Firewalls**: Filters traffic based on message header information.
- **Web Application Firewall (WAF)**: Protects web applications by monitoring HTTP traffic.
- **Stateful Inspection Firewalls**: Examines the context of traffic to make filtering decisions.
- **Next-Generation Firewall (NGFW)**: Incorporates deep packet inspection and intelligence features.
- **Unified Threat Management (UTM)**: Multi-function device with several security features.

### Secure Communication Access

- **Virtual Private Network (VPN)**: Extends a private network across a public network for secure remote access.
- **IPSec Protocols & Modes**:
  - Protocols: AH (Authentication Header), ESP (Encapsulating Security Payload).
  - Modes: Transport mode, Tunnel mode.
- **Tunneling**: Securely transmitting data through an untrusted network.
- **Software Defined Wide Area Network (SD-WAN)**: Manages and optimizes WAN connections using software.
- **Secure Access Service Edge (SASE)**: Integrated cloud service combining networking and security functions.

## Selection of Effective Controls

- **Steps**:
  1. Identify assets and vulnerabilities.
  2. Conduct impact analysis.
  3. Assess the threat landscape.