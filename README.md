# MarcNotes-v1.0
MarcNotes - An Improved Windows Notepad Application
# MarcNotes - An Improved Windows 10/7/8 Notepad Application

![MarcNotes Logo](app.png) 

##  Overview

MarcNotes is an enhanced text editor built with Qt C++ that improves upon the standard Windows Notepad with additional features and a modern interface. Developed by Marcbrain Ltd., it provides a seamless writing and coding experience with essential text editing capabilities.

##  Features

### File Operations
- **New, Open, Save, Save As** - Full file management capabilities
- **Auto-save prompt** - Never lose your work accidentally
- **Recent files support** - Quick access to frequently used documents

###  Editing Tools
- **Cut, Copy, Paste** - Standard text manipulation
- **Undo/Redo** - Complete edit history
- **Find & Replace** - Advanced text searching
- **Go To Line** - Navigate large documents easily
- **Select All** - Quick document selection

### Customization
- **Font Selection** - Choose your preferred typing font
- **Dark/Light Theme** - Toggle between color schemes
- **Zoom Controls** - Adjust text size for comfortable reading
- **Word Wrap** - Enable/disable text wrapping

### Output Options
- **Print Support** - Direct printing from the application
- **Multiple Format Support** - Work with .txt and .html files

### Additional Features
- **Bing Search Integration** - Quickly search selected text online
- **File Association** - Set as default for text files
- **Social Media Integration** - Quick access to support channels

## Installation

### Prerequisites
- Windows 7 or later
- 50MB free disk space
- Screen resolution: 1024x768 or higher

### Installation Steps

1. Download the latest installer from the [Releases page](https://github.com/yourusername/MarcNotes/releases)
2. Run `MarcNotesSetup.exe`
3. Follow the installation wizard prompts
4. Choose whether to create desktop and start menu shortcuts
5. Launch MarcNotes from the shortcuts or Start Menu

### Silent Installation
For enterprise deployment:
```cmd
MarcNotesSetup.exe /VERYSILENT /SUPPRESSMSGBOXES /NORESTART
```

## File Associations

MarcNotes can associate with these file types:
- `.txt` - Text files
- `.html` - HTML documents

During installation, you'll be prompted to set these associations. You can change them later through Windows File Associations settings.

## Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| New File | Ctrl+N |
| Open File | Ctrl+O |
| Save File | Ctrl+S |
| Save As | Ctrl+Shift+S |
| Cut | Ctrl+X |
| Copy | Ctrl+C |
| Paste | Ctrl+V |
| Undo | Ctrl+Z |
| Redo | Ctrl+Y |
| Find | Ctrl+F |
| Replace | Ctrl+H |
| Select All | Ctrl+A |
| Zoom In | Ctrl++ |
| Zoom Out | Ctrl+- |
| Reset Zoom | Ctrl+0 |

## Support

### Documentation
- [User Guide](https://github.com/yourusername/MarcNotes/wiki)
- [FAQ](https://github.com/yourusername/MarcNotes/wiki/FAQ)

### Contact Information
- **Developer**: Marcellinus Atampugre
- **Company**: Marcbrain Ltd.
- **Website**: https://www.marcbrain.com
- **Phone**: 0248770024 / 0504276573
- **Telegram**: https://t.me/+JGG8k9vcy78yNDQ0
- **WhatsApp**: https://wa.me/message/IXPKWICDRZ4II1

### Reporting Issues
Found a bug or have a feature request? Please [create an issue](https://github.com/yourusername/MarcNotes/issues) on our GitHub repository.

## Development

### Building from Source

#### Prerequisites
- Qt 5.15+ or Qt 6.x
- C++17 compatible compiler
- Inno Setup (for creating installers)

#### Build Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/MarcNotes.git
   cd MarcNotes
   ```

2. Open the project in Qt Creator or build from command line:
   ```bash
   qmake MarcNotes.pro
   make
   ```

3. To create an installer, use the provided Inno Setup script (`finalScripts.iss`)

### Project Structure
```
MarcNotes/
├── src/                 # Source files
│   ├── mainwindow.cpp  # Main application logic
│   ├── mainwindow.h    # Class definitions
│   └── main.cpp        # Application entry point
├── ui/                 # UI design files
│   └── mainwindow.ui   # Qt Designer file
├── icons/              # Application icons
├── installers/         # Installation scripts
└── docs/               # Documentation
```

### Contributing
We welcome contributions! Please see our [Contributing Guidelines](https://github.com/yourusername/MarcNotes/blob/main/CONTRIBUTING.md) for details.

## License

MarcNotes is developed and maintained by Marcbrain Ltd. All rights reserved.

For licensing information, please see the [LICENSE](https://github.com/yourusername/MarcNotes/blob/main/LICENSE.txt) file included with the application.

## Version History

### v1.0 (Current)
- Initial release
- Basic text editing functionality
- File operations (New, Open, Save, Save As)
- Find and Replace
- Font customization
- Theme support (Light/Dark)
- Printing support
- Zoom controls

### Planned Features
- [ ] Tabbed interface
- [ ] Syntax highlighting
- [ ] Auto-save
- [ ] Session restore
- [ ] Plugin system
- [ ] Cloud synchronization

## Acknowledgments

- Qt Framework for the application foundation
- Inno Setup for installation packaging
- All contributors and testers

---

*MarcNotes - Making note-taking simple and powerful*

© 2025 Marcbrain Ltd. All rights reserved.
