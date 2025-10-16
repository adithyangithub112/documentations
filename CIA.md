What is CIA Triad?
Last Updated : 18 Sep, 2025
The CIA Triad which stands for Confidentiality, Integrity, and Availability is a foundational model in information security. It serves as a guiding framework for policies and practices that aim to protect critical information and ensure the reliability of systems within an organization.

The triad’s three core principles are

Confidentiality: Ensures that sensitive data is accessible only to authorized users and protected from unauthorized access.
Integrity: Maintains the accuracy and trustworthiness of data, ensuring it hasn’t been tampered with or altered by unauthorized individuals.
Availability: Guarantees that data and systems are accessible when needed by authorized users, minimizing downtime or disruptions.
CIA Triad

Confidentiality
Confidentiality ensures that sensitive information is accessible only to authorized individuals or systems, preventing unauthorized access. The goal is to protect private data from being viewed, accessed, or misused by unauthorized persons.

Risks to Confidentiality
Unauthorized Access: When attackers bypass security measures or exploit vulnerabilities to gain access to sensitive data.
Weak Encryption: If weak or outdated encryption is used, attackers may decrypt and read sensitive information.
Insider Threats: Employees or trusted individuals may intentionally leak data for malicious reasons or accidentally expose it due to negligence.
How to ensure Confidentiality?
Encryption: Use strong encryption techniques (e.g., AES). This ensures that even if attackers intercept the data, they cannot read it without the decryption key. (Note: DES is outdated and considered insecure, so better to mention AES or RSA instead.)
VPN: A Virtual Private Network (VPN) creates a secure, encrypted tunnel for data transmission over the internet, protecting it from eavesdropping or interception.
file
Confidentiality
Integrity 
Integrity ensures that data remains accurate and unaltered during transmission or storage. If the data is modified in any way, its integrity is compromised. When data becomes corrupted, integrity is lost, which can lead to errors or even malicious manipulation.

Risks to Integrity
Data Tampering: Attackers or unauthorized users may intentionally alter, corrupt, or destroy data to manipulate information for malicious purposes or personal gain.
Malware and Ransomware: Malicious software can infect systems, altering or encrypting data and rendering it unusable until a ransom is paid or the issue is resolved.
How is Integrity Ensured?
To check if our data has been modified or not, we make use of a hash function. 

Common Hash Functions:
MD5: A 128-bit hash function.
SHA: A family of hash functions, with SHA-1 being a 160-bit hash. Other versions include SHA-0, SHA-2, and SHA-3.
How Hash Functions Work
Host A Sends Data: Suppose Host A wants to send data to Host B. To ensure integrity, Host A generates a hash value (H1) by running a hash function on the data.
Attaching the Hash: Host A attaches this hash value (H1) to the data before sending it.
Host B Verifies Integrity: When Host B receives the data, it runs the same hash function on the received data to generate a new hash value (H2).
Comparison: If H1 = H2, the data has not been modified during transmission, confirming that integrity is preserved. If they don’t match, it means the data was altered or corrupted.
file
Hash Function
Note: Even a small change in the input (like altering a single word or character) will completely change the resulting hash."

Availability 
Availability ensures that networks, systems, and data remain accessible and functional for users whenever they are needed. If a network becomes unavailable, it can disrupt business operations and create serious problems for organizations and individuals who rely on it.

Risks to Availability

DoS and DDoS Attacks: Denial of Service (DoS) or Distributed Denial of Service (DDoS) attacks flood network resources with excessive traffic, making them unavailable to legitimate users.
Impact: Such attacks can cause major service disruptions, downtime, and financial losses for companies.
How to Ensure Availability
To ensure availability, network administrators should focus on the following factors:

Hardware Maintenance: Regularly maintain and upgrade hardware to prevent failures and ensure smooth operations.
Regular Upgrades: Keep systems and software updated to maintain performance and security.
Failover Plan: Implement failover systems so that if one component fails, another can take over, minimizing downtime.
Preventing Bottlenecks: Monitor and manage network traffic to avoid congestion or bottlenecks, ensuring consistent performance.
