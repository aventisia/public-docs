# Encrypt Text with AES

## Description

This screenshot demonstrates an interface for encrypting text using the **AES (Advanced Encryption Standard)** algorithm. Users can input the text, specify an encryption key, and configure advanced settings such as encoding, salt, and initialization vector (IV).

![alt text](../../assests/app-integrations/assests%20cryptography/encrypt-text-with-aes.png)

---

## Configuration

### Encoding

- **Option**: Select the encoding type (e.g., Unicode).

### Text to Encrypt

- **Field**: Enter the text you want to encrypt.

### Encryption Key

- **Field**: Provide the encryption key used for the AES algorithm.

### Advanced Settings

- **Salt**: Optional field to add a salt value for additional security.
- **Initialization Vector (IV)**: Optional field to specify an IV for the encryption process.

---

## Output

- **EncryptedText**: The resulting encrypted text.
- **Salt**: The salt value used (if provided).
- **InitializationVector**: The IV used (if provided).

---

## Summary

This tool is useful for securely encrypting text using the AES algorithm. It provides options for encoding, encryption key input, and advanced settings like salt and initialization vector for enhanced security.
