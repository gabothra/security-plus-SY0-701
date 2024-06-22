# Strategies to Protect Data

## Data Types
- **Regulated**: Subject to specific laws and regulations. Examples include Personally Identifiable Information (PII) and Protected Health Information (PHI).
- **Trade Secret**: Intellectual property that belongs to an inventor or organization.
- **Intellectual Property**: Creations of the mind, such as patents, trademarks, and copyrights.
- **Legal Information**: Data related to legal proceedings, contracts, and agreements.
- **Financial Information**: Data related to financial transactions, accounts, and assets.
- **Human and Non-Human Readable**: Data can be in formats that are readable by humans (e.g., text) or only by machines (e.g., binary).

## Data Classifications
- **Sensitive**: Data that requires protection due to its sensitive nature.
- **Confidential**: Information that should be kept confidential and restricted to authorized personnel.
- **Public**: Information intended for the general public and does not require protection.
- **Restricted**: Data that has restrictions on access and usage.
- **Private**: Information that is private and not intended for public disclosure.
- **Critical**: Data that is crucial to the organization's operations and requires the highest level of protection.

## General Data Considerations
- **Data States**:
  - **Data at Rest**: Data stored in databases, files, or archives.
  - **Data in Transit**: Data being transmitted over networks or communication channels.
  - **Data in Use**: Data actively being processed or accessed by applications or users.
- **Data Sovereignty**: The legal concept that data is subject to the laws and regulations of the country where it is located.
- **Geo-Location**: The physical location or region where data is stored or processed, which may have legal and compliance implications.

## Methods to Secure Data
- **Geographic Restrictions**: Limiting access to data based on geographical locations or IP addresses.
- **Encryption**: Converting data into a coded form to prevent unauthorized access. Examples include AES encryption for data at rest and TLS encryption for data in transit.
- **Hashing**: Generating a unique fixed-size string (hash) from input data to verify data integrity. Example: SHA-256 for password hashing.
- **Masking**: Hiding part of sensitive data while preserving its format and usability. For example, masking credit card numbers by displaying only the last four digits.
- **Tokenization**: Replacing sensitive data with a token or placeholder value. For instance, replacing credit card numbers with tokens in payment processing systems.
- **Obfuscation**: Making data difficult to understand or interpret. This can involve techniques like data shuffling or encryption.
- **Segmentation**: Dividing data into segments or compartments with different access controls and security measures.
- **Permission Restrictions**: Enforcing access controls and permissions to ensure that only authorized users can access or modify data.