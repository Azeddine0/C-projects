🔐 File Encryption & Decryption Tool
A C-based file encryption and decryption tool supporting XOR, Caesar, AES (PBKDF2), and RSA key generation. Uses OpenSSL for cryptographic operations.

✨ Features
✅ XOR Cipher – Simple bitwise XOR encryption/decryption.
✅ Caesar Cipher – Basic shift-based encryption for text files.
✅ AES Encryption (PBKDF2) – Secure AES-128 encryption using a password-derived key.
✅ RSA Key Generation – Creates RSA public and private keys using OpenSSL.
✅ User-Friendly CLI – Easily choose encryption, decryption, and methods via the terminal.

⚙️ Usage
1️⃣ Compile the program:

sh
Copy
Edit
gcc -o encryptor encryptor.c -lcrypto -lssl
2️⃣ Run the program:

sh
Copy
Edit
./encryptor
3️⃣ Follow the prompts to encrypt/decrypt files or generate RSA keys.

📌 Dependencies
OpenSSL (Install using sudo apt install libssl-dev on Linux)
GCC Compiler
📜 License
MIT License
