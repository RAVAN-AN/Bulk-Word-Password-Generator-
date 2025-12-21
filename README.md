# KeyGenesis - Bulk Password Generator

A powerful, client-side password generator that creates secure passwords using word combinations with customizable options.

## 🚀 Features

- **Local Processing**: All processing happens in your browser - no data sent to servers
- **Flexible Word Sources**: 
  - Load custom wordlists from local folders
  - Use built-in word pool
  - Manual word input via textarea
- **Customizable Generation**:
  - Configure words per password (1-10)
  - Add digits (0-20 per password)
  - Multiple separator options (dash, underscore, space, none)
  - Various digit placement strategies
- **Output Formats**:
  - Plain text (one per line)
  - Indexed format
  - CSV format
  - JSON array
- **Advanced Options**:
  - Capitalize first word
  - Unique words per password
  - Bulk generation (up to thousands of passwords)

## 💾 Saved Configuration

- Auto-saves your settings as you change them (words per password, digits, separator, digit placement, output format, and textarea word list).
- Persists across sessions in all major browsers when not using Private/Incognito windows.
- Uses redundant storage (localStorage + IndexedDB) for improved reliability across browser settings.
- Manual controls: “Save configuration” and “Clear saved”.
- Loaded folder word pool is cached in IndexedDB and automatically rehydrated on next open.
- Note: Private/Incognito modes or browser settings that clear site data on exit will prevent persistence.

## 🎯 Use Cases

- **System Administrators**: Bulk user account creation
- **Security Teams**: Testing password policies
- **Developers**: Mock data generation
- **Personal Use**: Creating memorable yet secure passwords

## 🛠️ Installation & Usage

### Option 1: Direct Download
1. Download the `password-generator.html` file
2. Add your logo as `logo.jpg` and favicon as `favicon.png` (optional)
3. Open the HTML file in any modern web browser
4. Start generating passwords!

### Option 2: Clone Repository
```bash
git clone https://github.com/RAVAN-AN/Bulk-Word-Password-Generator-.git
cd Bulk-Word-Password-Generator-
```

Open `password-generator.html` in your browser.

## 📖 How to Use

1. **Load Wordlist** (Optional): Click "Load wordlist from folder" to import your own .txt files
2. **Configure Settings**:
   - Set number of words per password
   - Choose digit count and placement
   - Select separator style
   - Pick output format
3. **Add Custom Words** (Optional): Use the textarea to add specific words
4. **Generate**: Click "Generate & Show" to create passwords
5. **Copy Results**: Use copy buttons or click in the output area

## 🔧 Technical Details

- **Technology**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Compatibility**: All modern browsers (Chrome, Firefox, Safari, Edge)
- **Storage**: Uses IndexedDB for caching large wordlists
- **Performance**: Optimized for large pools (50k+ words)
- **Security**: Client-side only - no network requests

## 📁 File Structure

```
Bulk-Word-Password-Generator-/
├── password-generator.html    # Main application
├── logo.jpg                 # Logo image (add your own)
├── favicon.png              # Favicon (add your own)
├── README.md               # This file
├── LICENSE                 # License information
└── CHANGELOG.md           # Version history
```

## 🔐 Security Features

- **No Data Transmission**: Everything processes locally
- **Memory Management**: Efficient handling of large wordlists
- **Secure Random**: Uses cryptographically secure random number generation
- **Privacy First**: No tracking, analytics, or external dependencies

## 🤝 Contributing

While we appreciate community interest, this project is currently maintained by Bcreate Systems. 

For bug reports or feature suggestions:
1. Open an issue on GitHub
2. Provide detailed description
3. Include browser and OS information

## 📊 Version History

See [CHANGELOG.md](CHANGELOG.md) for detailed version history.

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/RAVAN-AN/Bulk-Word-Password-Generator-/issues)
- **Documentation**: This README and inline help text
- **Developer**: ALOK (Vibe Coded and Designed)

## 🏢 About

**A Bcreate Systems Project**  
Vibe Coded and Designed by ALOK

---

⭐ **Star this repository if you find it useful!**

📝 **License**: This software is free to use and distribute but not to modify or resell. See [LICENSE](LICENSE) for details.