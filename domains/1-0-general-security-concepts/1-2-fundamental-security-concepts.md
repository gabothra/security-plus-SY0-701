# CIA Triad

The CIA Triad is like a superhero team that helps keep our information safe and secure.

- **Confidentiality**: Imagine you have a secret diary that only you can read. Access controls are like the lock on your diary, making sure only you (or other authorized people) can open it.
- **Integrity**: This is like making sure no one can sneak in and change the words in your diary without you knowing. It ensures that data or system settings aren’t changed unless someone with permission says so.
- **Availability**: This means you can get to your diary whenever you want. Authorized people need to be able to use things like websites or apps quickly and easily. 

> Confidentiality and Integrity are useless if you can’t access the information when you need it (Availability).

# Non-Repudiation

Non-repudiation is a fancy way of saying that no one can lie about something they did.

- **Digital Signatures**: Imagine you put a special mark on your drawing that proves you made it. A digital signature shows that a document hasn’t been changed since it was signed. It uses a special kind of math called asymmetric cryptography (public/private key pair).

# AAA

AAA stands for Authentication, Authorization, and Accounting. These are like the rules for who can play with your toys, what they can do with them, and keeping track of what they did.

## Authentication, Authorization, and Accounting

- **Authentication**: Proving who you are, like showing your ID to a teacher. 
- **Authorization**: Deciding what you can do, like being allowed to play certain games because you have permission.
- **Accounting**: Keeping a record of what you do, like writing down every time you play a game and for how long.

### Authorization Models

Different ways to decide who gets to do what with the toys:

- **Non-discretionary Access Control (RBAC)**: Giving permission based on roles. If you’re the “puzzle master,” you get to solve puzzles.
- **Discretionary Access Control (DAC)**: The owner of a toy decides who can play with it.
- **Role-Based Access Control (RBAC)**: Using roles and groups to give permission, like “teacher,” “student,” etc.
- **Rule-Based Access Control**: Everyone follows the same rules, like “no running in the hallway.”
- **Mandatory Access Control (MAC)**: Everything and everyone gets a label, and you need the right label to use something.
- **Attribute-Based Access Control (ABAC)**: Deciding based on things like where you are or what group you belong to.

> **Subjects**: People, groups, or services using resources.
> **Objects**: Things like files, folders, or printers that subjects use.

# Gap Analysis

Gap Analysis is like a regular check-up to see if you are following the rules properly and fixing any mistakes.

- It’s done regularly and often before an external audit.
- Problems found are reported as **Control Gaps**.

# Zero Trust

Zero Trust is like being super careful and not trusting anyone by default.

### Based on Principles

- **Assume Breach**: Act as if bad guys are already inside and protect everything.
- **Verify Explicitly**: Always check who is trying to get in.
- **Least Privilege Access**: Only give people the access they absolutely need.

## Access Policy Enforcement

- **Policy Enforcement Point**: Like a security guard checking and controlling who gets in and out.
- **Policy Decision Point**: Where decisions are made based on who, when, where, what, and why someone is trying to access something.

### Key Elements of Zero Trust Network Architecture

- **Control Plane**: This is like the brain that decides the rules.
  - **Adaptive Identity**: Changes how the system asks you to prove who you are based on where you are, what device you’re using, etc.
  - **Threat Scope Reduction**: Making things safer by reducing risks.
  - **Policy-Driven Access Control**: Deciding access based on who you are, not just where your computer is.
  - **Policy Administrator**: The one who tells everyone the rules.
  - **Policy Engine**: The brain that decides if you can use something.

  > **PA + PE = PDP**

- **Data Plane**: This is like the muscles that enforce the rules.
  - **Implicit Trust Zones**: Old way of protecting things by putting them inside a safe zone (like behind a firewall).
  - **Subject/System**
  - **Policy Enforcement Point**

# Physical Security

Physical security means keeping real-world things safe.

- **Bollards**: Strong posts that stop cars from going where they shouldn’t.
- **Access Control Vestibule**: A small room with locked doors that control entry.
- **Fencing**: Fences that keep people out.
- **Video Surveillance**: Cameras that watch what’s happening.
- **Security Guard**: People who watch and protect.
- **Access Badge**: Cards that let you into secure areas.
- **Lighting**: Lights that help people see and keep bad guys away.
- **Sensors**: Gadgets that sense if something’s happening.
  - **Infrared**: Senses heat.
  - **Pressure**: Senses weight.
  - **Microwave**: Senses motion.
  - **Ultrasonic**: Uses sound waves to sense motion.

# Deception and Disruption Technology

These are tricks to catch bad guys.

- **Honeypot**: A trap that attracts bad guys so you can watch them.
- **Honeynet**: A network of honeypots.
- **Honeyfile**: A fake file that looks interesting to bad guys.
- **Honeytoken**: A fake record in a database to catch thieves.