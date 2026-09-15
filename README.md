
# Simple File Encryptor

A simple and secure Python script to encrypt and decrypt files using symmetric encryption (`cryptography.fernet`).

## Prerequisites
To run the script, you need Python installed along with the `cryptography` library. You can install it via the terminal using the following command:
```bash
pip install cryptography

```

## How to Use the Program

Run the script in your terminal:

```bash
python encryption.py

```

When you start the program, you will be greeted with a menu containing the following options:

1. **Generate an encryption key:** Generates a new encryption key and saves it (default: `encryption_key.key`).
2. **Encrypt a file:** Encrypts a chosen file using a key.
3. **Decrypt a file:** Decrypts a file back to its original form.
4. **Exit the program:** Closes the program.

## Important Security Notes

* **Protect your key:** If you lose your encryption key (`encryption_key.key`), you **cannot** decrypt your files again!
* **Do not share the key:** Never share your key file publicly if you upload your project to GitHub or elsewhere.

```

```
