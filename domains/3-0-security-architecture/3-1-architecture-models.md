# Domain 3: Security Architecture

## Section 1: Architecture Models

### Architecture and Infrastructure Concepts

#### Cloud

- **Shared Responsibility Model**: Defines the division of security responsibilities between the cloud service provider and the customer.
  - *Example*: In IaaS (Infrastructure as a Service), like Google Cloud Platform's Compute Engine, the provider manages the infrastructure, while the customer is responsible for securing their applications and data.

- **Hybrid Considerations**: Integration of on-premises infrastructure with cloud services.
  
- **Third-Party Vendors**: Utilizing services from external providers to augment cloud capabilities.

#### Infrastructure as Code

- **Declarative**: Describes the desired state of the infrastructure without specifying the steps to achieve it.
  
- **Idempotent**: Executing the same operation multiple times produces the same result as if it had only been executed once.

- **Example**: Tools like Terraform or AWS CloudFormation enable infrastructure deployment through code, reducing configuration errors and drift.

#### Serverless

- Cloud provider manages server provisioning and scaling automatically based on demand.
  
- Application code only executes when invoked.

#### Microservices

- Architecture approach where applications are built as a collection of small, loosely coupled services.

#### Network Infrastructure

- Physical and virtual components that enable communication between devices and systems.

#### Physical Isolation

- Segregating systems physically to prevent unauthorized access.
  - *Example*: Air-gapped networks are completely isolated from external networks.

#### Logical Segmentation

- Dividing networks into smaller segments for better management and security.
  - *Example*: VLANs (Virtual Local Area Networks) segment a network logically.

#### Software Defined Networking (SDN)

- Network architecture where network control is decoupled from hardware and implemented through software.

#### On-Premises

- Infrastructure and systems hosted and managed within an organization's premises, rather than in the cloud.

#### Centralized vs Decentralized

- Centralized architecture consolidates resources and management, while decentralized distributes them across multiple locations.

#### Containerization

- Encapsulating applications and their dependencies into lightweight containers for efficient deployment and scalability.

#### Virtualization

- Creating virtual instances of computing resources, such as servers, storage, and networks.

#### IoT (Internet of Things)

- Network of interconnected devices embedded with sensors, software, and other technologies for data exchange and automation.

#### Industrial Control Systems (ICS) / Supervisory Control and Data Acquisition (SCADA)

- Systems used to control and monitor industrial processes, often in critical infrastructure sectors.

#### Real-Time Operating System

- Operating systems optimized for applications with real-time requirements, such as wearables and automotive embedded systems.

#### Embedded Systems

- Computing devices integrated into other systems or products to perform specific functions.

#### High Availability

- Designing systems to ensure continuous operation and minimize downtime.

### Considerations

#### Why

- **Availability**: Ensuring systems are accessible when needed.
  
- **Resilience**: Ability to recover quickly from failures or disruptions.

- **Cost**: Managing expenses related to infrastructure deployment and maintenance.

- **Responsiveness**: How quickly systems can respond to changes or requests.

- **Scalability**: Ability to accommodate growth or increased demand.

- **Ease of Deployment**: Simplifying the process of deploying new services or updates.

- **Risk Transference**: Shifting security risks to third-party vendors or insurance providers.

- **Ease of Recovery**: How easily systems can be restored after an incident or failure.

- **Patch Availability**: Availability of patches to address vulnerabilities and maintain security.

- **Inability to Patch**: Managing systems or devices that cannot be easily updated or patched.

- **Power**: Availability of power sources to ensure uninterrupted operation.

- **Compute**: Ability to process and handle computing tasks effectively.