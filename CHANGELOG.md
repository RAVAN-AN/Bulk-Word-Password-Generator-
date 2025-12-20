# Changelog

All notable changes to the KeyGenesis - Bulk Password Generator will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [1.0.0] - 2024-12-01

### Added
- Initial release of KeyGenesis - Bulk Password Generator
- Client-side password generation with word combinations
- Support for local folder wordlist import
- IndexedDB caching for large wordlists
- Multiple output formats (plain, indexed, CSV, JSON)
- Configurable password parameters:
  - Words per password (1-10)
  - Digits per password (0-20)
  - Separator options (dash, underscore, space, none)
  - Digit placement strategies
- Advanced options:
  - Capitalize first word
  - Unique words per password
  - Bulk generation capabilities
- Professional UI with logo integration
- Responsive design for various screen sizes
- Copy functionality for generated passwords
- Built-in word pool as fallback
- Manual word input via textarea

### Security
- All processing happens client-side
- No data transmission to external servers
- Cryptographically secure random number generation
- Privacy-focused design with no tracking

### Performance
- Optimized for large wordlists (50k+ words)
- Efficient memory management
- Fast generation algorithms
- IndexedDB for persistent caching

---

## Planned Features (Future Releases)

### [1.1.0] - Planned
- [ ] Dark mode theme
- [ ] Export/import settings
- [ ] Password strength indicators
- [ ] Additional output formats
- [ ] Keyboard shortcuts

### [1.2.0] - Planned
- [ ] Custom separator characters
- [ ] Pattern-based generation
- [ ] Word filtering options
- [ ] Batch wordlist management

---

## Support

For questions about changes or to report issues:
- Open an issue on [GitHub](https://github.com/RAVAN-AN/Bulk-Word-Password-Generator-/issues)
- Include version information and browser details

---

**Developed by**: Bcreate Systems - ALOK  
**License**: Custom License (Free to use and distribute, not to modify or resell)