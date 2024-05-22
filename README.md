# Secure Message Encryptor

Welcome to the Secure Message Encryptor! This is a web application designed to securely encrypt and decrypt messages using AES encryption. The application also includes a hash-based access system to ensure that only authorized users can encrypt or decrypt messages.

## Features

- **AES Encryption**: Securely encrypt and decrypt messages with a user-provided password.
- **Hash-Based Access Control**: Generate a hash to gain access to the encryption and decryption functionalities. The hash is valid for 1 hour and users must wait 1 hour before generating a new one.
- **Particle Background**: Enjoy a visually appealing, interactive particle background that responds to mouse movements.
- **Download Encrypted Message**: Download the encrypted message as a text file.
- **Copy Hash**: Easily copy the generated hash to the clipboard for convenience.
- **History Tracking**: Keep track of generated hashes and encrypted messages.

## How to Use

### Step 1: Generate a Hash

1. Click on the `Generate Hash` button.
2. Copy the generated hash using the `Copy` button.
3. Enter the hash into the `Enter Hash` input field and click `Submit`.

### Step 2: Encrypt a Message

1. Once the hash is validated, the encryption panel will be displayed.
2. Enter your message into the `Message` input field.
3. Enter a password into the `Password` input field.
4. Click the `Encrypt` button to encrypt your message.
5. The encrypted message will be displayed below.

### Step 3: Decrypt a Message

1. Enter the encrypted message into the `Encrypted Message` input field.
2. Enter the password used for encryption into the `Password` input field.
3. Click the `Decrypt` button to decrypt your message.
4. The decrypted message will be displayed below.



## Technologies Used

- **HTML**: For the structure of the web page.
- **CSS**: For styling and layout.
- **JavaScript**: For encryption/decryption logic and interactive functionalities.
- **GitHub Pages**: For hosting the web application.

## Contributing

We welcome contributions to improve this project! Please feel free to fork the repository, create a feature branch, and submit a pull request.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some amazing feature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.






