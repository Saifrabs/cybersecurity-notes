# Day 06 - Cryptography Basics

## What is Cryptography?

Cryptography is the science of protecting information by converting readable data (plaintext) into unreadable data (ciphertext). Only authorized users with the correct key can convert it back to its original form.

### Example

**Plaintext:**
```
Hello Agent X
```

**Ciphertext:**
```
J8s9@Lm2#Qx7
```

Only someone with the correct decryption key can read the original message.

---

## Why is Cryptography Important?

Cryptography helps to:

- Protect sensitive information
- Keep passwords secure
- Secure online banking
- Protect emails and messages
- Secure websites (HTTPS)
- Protect digital identities

---

## Key Terms

### Plaintext

The original readable message.

**Example:**
```
Cybersecurity is important.
```

### Ciphertext

The encrypted version of the message.

**Example:**
```
9Fk@2Lm#8Pd
```

### Encryption

Encryption is the process of converting plaintext into ciphertext.

```
Plaintext → Encryption → Ciphertext
```

### Decryption

Decryption is the process of converting ciphertext back into plaintext.

```
Ciphertext → Decryption → Plaintext
```

### Encryption Key

A secret value used to encrypt data. Without the correct key, encrypted information cannot be read.

### Decryption Key

A secret key used to decrypt encrypted data.

---

## Types of Cryptography

### 1. Symmetric Encryption

Symmetric encryption uses **one key** for both encryption and decryption.

**Example:**
```
Secret Key
     ↓
Encrypt
     ↓
Ciphertext
     ↓
Decrypt
     ↓
Original Message
```

#### Advantages

- Fast
- Efficient
- Good for large files

#### Disadvantages

- The secret key must be shared securely.

**Examples:**

- AES
- DES

---

### 2. Asymmetric Encryption

Asymmetric encryption uses **two keys**:

- Public Key
- Private Key

**Example:**
```
Public Key → Encrypt

Private Key → Decrypt
```

#### Advantages

- More secure for communication
- No need to share the private key

#### Disadvantages

- Slower than symmetric encryption

**Examples:**

- RSA
- ECC

---

## Hashing

Hashing converts data into a fixed-length value.

Unlike encryption, hashing **cannot be reversed**.

**Example:**

Password:
```
AgentX123
```

Hash:
```
3f79bb7b435...
```

Hashing is commonly used to store passwords securely.

### Common Hashing Algorithms

- SHA-256
- SHA-512
- MD5 (Not recommended for security)

---

## Real-Life Uses of Cryptography

- HTTPS websites
- Online banking
- VPNs
- Password managers
- Digital signatures
- Cryptocurrency
- Secure messaging applications

---

## Best Practices

- Use strong passwords.
- Never share encryption keys.
- Use modern encryption algorithms.
- Enable Multi-Factor Authentication (MFA).
- Keep software updated.

---

## Summary

- Cryptography protects sensitive information.
- Encryption converts plaintext into ciphertext.
- Decryption restores the original message.
- Symmetric encryption uses one key.
- Asymmetric encryption uses two keys.
- Hashing protects passwords.
- Cryptography is essential for secure communication and cybersecurity.

---

## Key Takeaways

- Cryptography keeps information confidential.
- Encryption protects data from unauthorized access.
- Hashing is commonly used for password storage.
- Modern cybersecurity relies heavily on cryptography.
- Every cybersecurity professional should understand encryption fundamentals.
