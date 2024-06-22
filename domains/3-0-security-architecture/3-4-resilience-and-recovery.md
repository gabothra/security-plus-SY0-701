# Resilience and Recovery

## High Availability
- **Load Balancing vs Clustering**: 
  - **Load Balancing**: Distributing incoming network traffic across multiple servers to ensure no single server is overwhelmed. Example: Using a load balancer to distribute web requests across multiple web servers.
  - **Clustering**: Connecting multiple servers together to work as a single system, providing redundancy and fault tolerance. Example: Setting up a cluster of database servers for high availability and failover.

## Site Considerations
- **Hot Site**: Fully equipped data center with all necessary infrastructure and data ready to be activated immediately after a disaster.
- **Cold Site**: Barebones facility with minimal infrastructure and equipment. Data and systems need to be restored and configured after a disaster.
- **Warm Site**: Partially equipped facility with some infrastructure in place. Data and systems need to be restored and configured, but the process is faster than with a cold site.
- **Geographic Dispersion**: Spreading data centers and infrastructure across multiple geographical locations to mitigate the impact of regional disasters. Example: Establishing data centers in different regions or countries.

## Platform Diversity
- Using multiple platforms, technologies, or vendors for critical systems and services to avoid a single point of failure. Example: Using both on-premises servers and cloud services for hosting applications.

## Multi-Cloud Systems
- Utilizing services from multiple cloud providers to distribute risk and ensure continuity of operations. Example: Running workloads on both AWS and Azure cloud platforms.

## Continuity of Operations
- Implementing strategies and plans to ensure that essential functions can continue during and after a disaster or disruption. Example: Having remote work capabilities in place for employees during a pandemic or natural disaster.

## Capacity Planning
- **People**: Ensuring that there are enough trained personnel available to handle operations during normal and emergency situations.
- **Infrastructure**: Planning and provisioning adequate hardware and network resources to support operations under normal and peak loads.
- **Technology**: Ensuring that software and systems are capable of handling increased loads and traffic during peak usage or in case of failures.

## Testing
- **Tabletop Exercises**: Scenario-based discussions to simulate disaster scenarios and assess response plans without actually executing them.
- **Failover**: Testing the failover capabilities of systems and applications to ensure they can switch to backup components or systems seamlessly.
- **Simulation**: Running simulations of disaster scenarios to evaluate the effectiveness of response plans and identify areas for improvement.
- **Parallel Processing**: Running production workloads in parallel with simulated disaster scenarios to validate the resilience and performance of systems.

## Backups
- **Onsite/Offsite**: Storing backup copies of data and systems both onsite (within the same location) and offsite (at a remote location) to protect against localized disasters.
- **Frequency**: Regularly scheduled backups to ensure that data is backed up frequently enough to minimize data loss in case of a failure.
- **Encryption**: Encrypting backup data to protect it from unauthorized access during transmission and storage.
- **Snapshots**: Capturing point-in-time snapshots of system or application state to facilitate fast recovery to a known good state.
- **Recovery**: Testing the process of restoring data and systems from backups to ensure that it can be done quickly and effectively.
- **Replication**: Replicating data and systems to secondary locations in real-time or near-real-time to ensure data availability and minimize downtime.
- **Journaling**: Keeping detailed records (journals) of changes made to data or systems to facilitate recovery to specific points in time.

## Power
- **Generators**: Backup power generators to provide electricity in case of a grid power failure. Example: Diesel generators that automatically start up when grid power is lost.
- **Uninterruptible Power Supply (UPS)**: Battery backup systems that provide short-term power to critical systems and devices in case of a sudden loss of mains power. Example: UPS units installed in data centers to keep servers running until backup generators kick in.