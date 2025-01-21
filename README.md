# Keystore-Unlock

Keystore-Unlock is a lightweight, secure, and client-side tool designed to decrypt EVM keystore files and extract private keys locally. All operations are performed entirely on your device, ensuring that no data is ever transferred to any server. Built with the robust ethereumjs/keythereum library.

## Key Features

- **Multi-Blockchain Support:** Decrypts keystore files for Ethereum, Binance Smart Chain (BNB), and Polygon networks.
- **100% Client-Side:** Ensures complete security of your private keys by executing all operations locally in your browser.
- **User-Friendly Interface:** Simply paste your keystore JSON and enter your password to retrieve your private key.

## Getting Started

### 1. Clone or Download

Clone this repository or download it as a ZIP file:

```bash
git clone https://github.com/jam3on/keystore-unlock.git
```

### 2. Open in Your Browser

Navigate to the project folder and open `keystore-unlock.html` in your preferred web browser.

### 3. Decrypt Your Keystore

1. Paste your keystore JSON into the provided input field.
2. Enter the corresponding password.
3. Click **Decrypt** to reveal your private key securely.

## Security Guidelines

To maximize the security of your private keys:

- **Work Offline:** Disconnect your internet connection while using this tool.
- **Protect Your Private Key:** Never share your private key with anyone or expose it to untrusted platforms.
- **Isolated Environment:** Whenever possible, use this tool on an air-gapped or isolated machine.

## Disclaimer

This tool is provided "as is" without warranty of any kind. Use it at your own risk. The authors are not responsible for any loss of funds or data due to improper usage or external threats.

## Contributing

Contributions are welcome! Feel free to fork the repository, open issues, or submit pull requests to improve this tool.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

This tool is powered by the fantastic work from the [ethereumjs/keythereum](https://github.com/ethereumjs/keythereum) library and [chaingateway/keystore-decryptor](https://github.com/chaingateway/keystore-decryptor).