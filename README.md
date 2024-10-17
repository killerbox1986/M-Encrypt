M-Encrypt: Post-Quantum Encryption and Secure File Handling in Java
Overview

M-Encrypt is a Java application that demonstrates secure password-based encryption and file handling using modern cryptographic practices, 
including the Argon2 key derivation algorithm and post-quantum cryptography (PQC) integration (with placeholder PQC logic). 
The project showcases best practices for securely encrypting, storing, and deleting sensitive data files while also providing robust password strength validation.

Key Features

   * Argon2 Key Derivation: Derives cryptographic keys from user-provided passwords using Argon2 for enhanced security.
   * Post-Quantum Cryptography (PQC) Integration: (Placeholder) Demonstrates encryption/decryption using PQC concepts with potential for future upgrades to real libraries.
   * Salt Generation & Management: Random salt generation and secure storage in a dedicated salt file.
   * Secure File Encryption: Encrypts plaintext files and securely writes encrypted data using atomic operations.
   * Password Strength Validation: Checks password strength with entropy calculation and detailed feedback.
   * Secure File Deletion: Implements secure file deletion to ensure sensitive plaintext is overwritten and removed.
   * Bouncy Castle Integration: Utilizes Bouncy Castle as a security provider for advanced cryptographic functions.

How it works:

1. User Input: The user provides a password, which is validated for strength.
2. Key Derivation: Argon2 derives a secure key from the password and salt.
3. Encryption: The plaintext is read from plaintext.txt and encrypted using a placeholder PQC algorithm.
4. Secure Storage: The encrypted data is stored in encrypted.txt.
5. Secure Deletion: The plaintext file is securely deleted after encryption.
6. Post-Quantum Placeholder: PQC logic is demonstrated with the potential to integrate libraries such as Open Quantum Safe (OQS).

Prerequisites

   * Java 8 or higher
   * Bouncy Castle Library (v1.70+)
   * Optional: Maven for dependency management
