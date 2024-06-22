# Public Key Infrastructure (PKI)

PKI is like a secure system for sharing information. It uses keys to keep things safe.

### Public Key

A public key is like a lock you put on your mailbox. Everyone can see it, but only someone with the right key (private key) can open it.

### Private Key

A private key is like the key to your mailbox. Only you have it, and it lets you open the lock.

### Key Escrow

Key escrow is a way to make sure you don’t lose your keys.

- **Purpose**: To recover lost keys.
- Imagine giving a copy of your house key to a trusted friend in case you lose yours.

### Trust Models

Trust models are like rules for who trusts whom in the world of digital certificates.

- **Bridge**: A way for different systems to trust each other.
- **Hierarchical**: Like a family tree where trust flows from the top (root) down.
- **Hybrid**: A mix of different trust models.
- **Mesh**: Everyone trusts each other directly.

# Encryption

Encryption is like a magic trick that turns readable information into secret code, and back again if you have the right key.

### Levels of Encryption

- **Full Disk**: Encrypts everything on a disk.
- **Partition**: Encrypts a specific part of a disk.
- **File**: Encrypts individual files.
- **Volume**: Encrypts a specific section of storage.
- **Database**: Encrypts a whole database.
- **Record**: Encrypts specific records in a database.

### Transport/Communication Encryption

- **Data in Transit**: Information traveling from one place to another, like messages.
- **TLS/HTTPS**: Secure methods to keep data safe while traveling.

### Types of Encryption

#### Asymmetric Encryption

- Uses two keys: a public key and a private key.
- **Examples**:
  - **RSA**: A common asymmetric encryption method.
  - **ECC (Elliptic Curve Cryptography)**: Uses smaller keys but is very secure.
- **Key Types**:
  - **Static Keys**: Stay the same.
  - **Ephemeral Keys**: Change for each session.

#### Symmetric Encryption

- Uses one key shared between parties.
- **Pros**: Fast and good for encrypting large amounts of data.
- **Cons**: Hard to manage many keys securely.
- **Examples**:
  - **AES**: Very secure and commonly used.
  - **3DES**: An older method, now replaced by AES.
  - **Twofish** and **Blowfish**: Other secure methods.

### Key Exchange

How to securely share keys between people or systems.

### Algorithms

The math behind how encryption works.

### Key Length

How long the keys are, affecting security and speed.

### Database Encryption

- **Transparent Data Encryption**: Encrypts data in real-time, at the database level.

### Ciphers

Ways to encrypt and decrypt information.

- **Stream Cipher**: Encrypts data one bit at a time.
- **Block Cipher**: Encrypts data in fixed-size chunks. More secure than stream ciphers.
- **Substitution Cipher**: Replaces letters or bits with other letters or bits.
- **Transposition Cipher**: Rearranges the letters or bits.

# Tools

### Trusted Platform Module (TPM)

- A chip on your computer’s motherboard that stores encryption keys. It checks the keys when your computer starts to ensure it hasn’t been tampered with.

### Hardware Security Module (HSM)

- A removable device that securely manages keys.

### Hardware Root of Trust

- Verifies the keys match before allowing a secure boot.

### Key Management System (KMS)

- Manages and stores keys securely. An example is Google Cloud’s Secrets.

### Secure Enclave

- A secure area within a system for processing sensitive data.

# Obfuscation

Making information hard to understand or find.

### Steganography

- Hiding information within other media, like a secret message in a picture.

### Tokenization

- Replacing important data with a random token, storing the original data securely elsewhere.

### Data Masking

- Showing only part of the data, like showing only the last four digits of a credit card.

### Pseudonymization

- Replacing personal information with fake identifiers.

### Anonymization

- Removing all identifying information so no one can tell who the data is about.

### Data Minimization

- Only collecting and keeping the data you really need.

# Hashing

Hashing is like taking a picture of your data. You can't turn the picture back into the data, but you can compare pictures to see if they match.

### Requirements of Good Hash Functions

- **Input of Any Length**: Can handle any amount of data.
- **Fixed Output Length**: Always produces the same size output.
- **One-Way Functionality**: Can't go backward from the hash to the original data.
- **Easy to Compute**: Quick to create the hash.
- **Collision-Free**: No two different inputs should produce the same hash.

# Salting

Adding random data to passwords before hashing them to make them harder to crack.

- **Purpose**: Protect against rainbow table attacks.

# Digital Signatures

Digital signatures are like signing a document to prove it’s really from you.

- **How it Works**: Encrypt a hash of the message with your private key.
- **Benefits**:
  - **Authentication**: Proves who sent the message.
  - **Non-Repudiation**: The sender can't deny they sent it.
  - **Integrity**: Ensures the message wasn’t changed.

# Key Stretching

A way to make weak passwords stronger by processing them with algorithms to make them harder to crack.

# Blockchain

A digital ledger that is decentralized and uses consensus to validate transactions.

### Open Public Ledger

- **Maintained and Centralized by a Single Authority**: One entity controls it.
- **Transparency**: All transactions are visible to everyone.

# Certificates

Certificates are digital documents that prove who you are online.

### Types of Certificates

- **User Certificate**: Represents a user’s digital identity.
- **Root Certificate**: The top-level certificate in a trust chain.
- **Domain Validation**: Proves ownership of a domain.
- **Extended Validation**: Provides higher security and assurance.
- **Wildcard**: Covers a domain and its subdomains.
- **Code Signing**: Verifies the integrity of software code.
- **Self-Signed**: Created and signed by the same person or organization.
- **Machine/Computer Certificate**: Used by devices to identify themselves.
- **Email Certificate**: Used to secure email communication.
- **Third Party**: Issued by a trusted certificate authority (e.g., DigiCert, GoDaddy).
- **SAN Certificate**: Covers multiple hostnames with a single SSL certificate.

### Certificate Authorities

- **Best Security**: Uses a three-tier system (Issuing CA → Subordinate CA → Root CA).

### Certificate Revocation Lists (CRLs)

- Lists of certificates that are no longer valid.

### Online Certificate Status Protocol (OCSP)

- Checks the status of certificates in real-time.

### Self-Signed Certificates

- Certificates signed by the same entity that created them.

### Third-Party Certificates

- Certificates issued by a trusted certificate authority.

### Root of Trust

- The foundation of trust in a PKI.

### Certificate Signing Request (CSR) Generation

- The process of requesting a certificate from a certificate authority.

### Stapling

- A method used with OCSP that allows a web server to provide information about the validity of its own certificate.

### Pinning

- Ensures that only specific certificates are trusted, preventing the use of fraudulent certificates.

# Digital Signature Standard

- Uses **SHA2** and **SHA3** for hashing.