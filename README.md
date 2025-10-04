# 🔐 Mr. Decoder

A simple, clean web-based encryption and decryption tool.
My 4th semester mini project.

## ✨ Features

### Text Operations
- **AES Encryption/Decryption** - Secure symmetric encryption with password
- **SHA-256 & SHA-512 Hashing** - One-way cryptographic hashing
- **Base64 Encoding/Decoding** - Simple text encoding
- **Copy to Clipboard** - Quick result copying
- **Download Results** - Save encrypted/decrypted text as file
- **QR Code Generation** - Generate QR codes from results

### File Operations
- **AES File Encryption/Decryption** - Secure file protection
- **Base64 File Encoding/Decoding** - File encoding support
- **XOR Cipher** - Simple file encryption with password

### UI Features
- **Dark/Light Mode Toggle** - Automatic theme switching with persistence
- **Responsive Design** - Works on desktop and mobile
- **Toast Notifications** - User-friendly feedback messages
- **Clean Interface** - Minimal, focused design

## 🚀 Quick Start

1. **Download** or clone this repository
2. **Open** `index.html` in any modern web browser
3. **Start encrypting** - No installation required!

## 📖 Usage

### Text Encryption
1. Select your encryption method (AES, SHA-256, SHA-512, or Base64)
2. Enter a password (required for AES only)
3. Type or paste your text in the input area
4. Click **Encrypt** or **Decrypt**
5. Copy, download, or generate QR code from the result

### File Encryption
1. Choose encryption method (AES, Base64, or XOR)
2. Enter password (required for AES and XOR)
3. Select your file using the file picker
4. Click **Encrypt File** or **Decrypt File**
5. The processed file will download automatically

## 🔧 Technical Details

### Dependencies
- **Tailwind CSS** - For styling and responsive design
- **CryptoJS** - For AES encryption and hashing algorithms
- **QRCode.js** - For QR code generation

### Browser Compatibility
- Chrome/Edge 60+
- Firefox 55+
- Safari 12+
- Any modern browser with ES6 support

### Security Notes
- AES encryption uses CryptoJS implementation
- Passwords are not stored or transmitted
- All operations happen locally in your browser
- SHA hashes are irreversible (cannot be decrypted)

## 📁 File Structure

```
Mr.Decoder/
├── index.html          # Main application file
├── README.md           # This file
├── LICENSE             # MIT License
└── .gitignore          # Git ignore rules
```

## 🎨 Customization

The application uses Tailwind CSS classes for styling. You can easily customize:

- **Colors**: Modify the color classes in the HTML
- **Layout**: Adjust grid and spacing classes
- **Theme**: The dark mode toggle automatically handles theme switching

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

This tool is for educational and personal use. For production applications requiring high security, please use established cryptographic libraries and follow security best practices.

## 🔗 Links

- **Live Demo**: [Open index.html in your browser]
- **Issues**: [Report bugs or request features]
- **Documentation**: This README

---

Made with ❤️ for secure, simple encryption
