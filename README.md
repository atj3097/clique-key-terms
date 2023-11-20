# Clique Glossary
Clique leverages a variety of cryptographic techniques to enhance security, privacy, and efficiency in its solutions. The table below outlines key cryptographic terms, provides a simple explanation for each, and describes how these technologies are utilized in Clique's ecosystem. This information aims to clarify the complex technologies behind Clique and demonstrate their practical applications in real-world scenarios.
| Term | Explanation (From Clique Documentation) | Explain to me like I'm 5 (ELI5) | How Clique Uses This Tech |
|------|------------------------------------------|---------------------|---------------------------|
| ZKP (Zero-Knowledge Proofs) | A method allowing one party to prove they know a value without revealing the value itself. | Like showing you have a hidden toy without taking it out of the box. | Clique uses ZKPs for integrity checks, ensuring data hasn't been tampered with, and for on-chain storage of proofs and attestations. |
|Membership Proofs | | |
|Query Proofs | | |
| MPC (Multi-Party Computation) | Enables parties to jointly compute a function over their inputs while keeping these inputs private. | Like solving a puzzle together, but no one sees each other’s pieces. | |
| TEE (Trusted Execution Environments) | Secure areas of a processor to protect code and data in terms of confidentiality and integrity. | A special, safe room in a computer where special programs can run safely. | Clique uses TEEs to validate, encrypt, and process data for ZK query proofs. |
| OT (Oblivious Transfer) | A protocol where a sender transfers information to a receiver without knowing what information was transferred. | Like handing over one of several secret envelopes but not knowing which one you gave. | |
| GC (Garbled Circuits) | A protocol for executing computations on encrypted inputs to produce an encrypted result, without revealing any additional information. | Doing a secret math problem where the numbers are in a secret code. |  |
| Intel SGX (Software Guard Extensions) | Security-related codes in Intel CPUs for creating protected memory areas. | A special kind of lock-and-key for computer programs to keep them safe. | Used in Clique's TEE-based approach for identity authentication and data computation. |
| AMD SEV (Secure Encrypted Virtualization) | Encrypts memory of virtual machines with unique keys for security. | Giving each virtual computer its own secret code so others can't peek in. |  |
| ARM TrustZone | Creates an isolated secure area in computing devices for sensitive code. | Making a safe zone in electronic devices where special secrets are kept safe. | |
| Set-membership Proofs | Proving a piece of information is part of a set without revealing the information or the full set. | Like proving you have a piece of a puzzle without showing which piece or the whole puzzle. | Used in Clique's zero-knowledge proof system for verifying witness inclusion in a set. |
| DCAP (Data Center Attestation Primitives) | Technologies for verifying the integrity of hardware in data centers. | Making sure the big computers in a data center are healthy and trustworthy. |  |
| Remote Attestation | Verifying a device's integrity and authenticity remotely. | Checking from afar if a device is working correctly and hasn’t been messed with. |  |
| ORAM (Oblivious RAM) | Obfuscating access patterns to storage to secure data retrieval and storage. | Hiding the tracks of where data is kept or found so no one can tell what you’re storing or getting. | Employed as part of common TEE hardening techniques. |
|Sybil Resistant | | | 
|TLS certificate | | |
|Provenance | | |
|Attestation | | |
|Oracle | | |
|(SSI) | | |

