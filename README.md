This C program is a file encryption and decryption tool that supports multiple encryption methods, including XOR cipher, Caesar cipher, AES encryption with PBKDF2 key derivation, and RSA key generation.

Features:
XOR Cipher – Performs simple bitwise XOR encryption/decryption using a fixed key.
Caesar Cipher – Applies a shift-based encryption to text data.
AES Encryption with PBKDF2 – Uses a password-based key derivation function (PBKDF2) to securely encrypt/decrypt files with AES-128.
RSA Key Generation – Generates an RSA key pair (public and private keys) using OpenSSL.
User-Friendly CLI – The user inputs file names and chooses encryption or decryption, along with the preferred method.
How It Works:
The user specifies an input file and an output file.
They select an operation (encrypt, decrypt, or generate RSA keys).
If encryption/decryption is selected, they choose a method.
For AES with PBKDF2, the user provides a password.
The program processes the file using the selected encryption method and saves the output.
Dependencies:
Requires OpenSSL for AES, RSA, and PBKDF2 functions.
This script is useful for securely encrypting files with different cryptographic techniques, making it a simple yet versatile encryption tool.
