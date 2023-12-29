# BrainVault

BrainVault is a standalone, browser-based application that securely generates a BIP39 mnemonic from a password input. It uses Argon2id for password hashing and produces a mnemonic that can be used as a seed for cryptographic purposes, such as a Bitcoin wallet.

## Features

- **Argon2id Hashing**: Implements `argon2-browser` for state-of-the-art password hashing.
- **BIP39 Mnemonic Generation**: Utilizes `bitcoinjs/bip39` to convert the hash into mnemonic phrases.
- **Offline Capability**: Can be run offline for increased security.
- **Simple Interface**: Easy-to-use HTML interface.

## How to Use

1. Download the `brainvault.html` file from this repository.
2. Disconnect from the internet and open the file in a web browser to enhance security.
3. Enter a unique salt (e.g., email address) and a strong password.
4. Click 'Submit' to generate your BIP39 mnemonic phrase.
5. Record the mnemonic phrase securely.

## Security Practices

- Employ a strong, unique password that is not used elsewhere.
- Keep the salt confidential and unique to you.
- Use BrainVault on a trusted and secure device.
- Do not share your salt, password, or mnemonic with anyone.
- Enhance your mnemonic with an additional passphrase for extra security.

## Contributing

BrainVault is open-source and licensed under the GNU General Public License v3.0. Contributions are welcome following these steps:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b my-new-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin my-new-feature`).
5. Submit a Pull Request.

## Licenses

- The BrainVault code is licensed under the GNU General Public License v3.0.
- The `argon2-browser` library is licensed under the MIT License.
- The `bitcoinjs/bip39` library is licensed under the ISC License.

For exact terms and conditions, see the `LICENSE` file for BrainVault's license and the respective licenses included in the subdirectories or documentation of the third-party libraries.

## Acknowledgments

- `argon2-browser` by Antelle ([argon2-browser](https://github.com/antelle/argon2-browser)), MIT Licensed.
- `bitcoinjs/bip39` by Wei Lu and Daniel Cousens ([bitcoinjs/bip39](https://github.com/bitcoinjs/bip39)), ISC Licensed.

## Disclaimer

BrainVault is provided "as is", without warranty of any kind. Please see the `LICENSE` file for the full GNU General Public License v3.0 terms. The authors and contributors of BrainVault and the utilized libraries are not liable for any damages arising from its use.
