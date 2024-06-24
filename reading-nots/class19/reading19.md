

### Cryptography
Cryptography is the practice of securing information by transforming it into a format that is unreadable to unauthorized users. It involves techniques for secure communication in the presence of adversaries and ensures confidentiality, integrity, and authenticity of data.

### 7 Cryptography Concepts Every Developer Should Know

1. **Symmetric Encryption**: Uses the same key for both encryption and decryption. It's fast but requires secure key distribution.
   - Example: AES (Advanced Encryption Standard).

2. **Asymmetric Encryption**: Uses a pair of keys - a public key for encryption and a private key for decryption. It's secure but slower than symmetric encryption.
   - Example: RSA (Rivest-Shamir-Adleman).

3. **Hash Functions**: Converts data into a fixed-size string of characters, which is typically a digest that is unique to each unique input.
   - Example: SHA-256 (Secure Hash Algorithm 256-bit).

4. **Digital Signatures**: Ensures data integrity and authenticity by allowing the receiver to verify the sender’s identity.
   - Example: DSA (Digital Signature Algorithm).

5. **Public Key Infrastructure (PKI)**: A framework for managing digital keys and certificates. It supports the distribution and identification of public encryption keys.
   - Example: SSL/TLS certificates for secure web browsing.

6. **Key Exchange Algorithms**: Methods for securely exchanging cryptographic keys over a public channel.
   - Example: Diffie-Hellman key exchange.

7. **Cryptographic Protocols**: Sets of rules that dictate secure communication and data transfer methods.
   - Example: HTTPS (Hypertext Transfer Protocol Secure).

### Understand Hashing in Cryptography
Hashing is a fundamental concept in cryptography used to ensure data integrity. It involves taking an input (or 'message') and returning a fixed-size string of bytes. The output is typically a 'digest' that is unique to each unique input, meaning even a slight change in the input will produce a significantly different digest. Hashing is widely used in password storage, data integrity checks, and digital signatures.