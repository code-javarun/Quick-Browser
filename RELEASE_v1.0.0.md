# Quick-Browser v1.0.0 Release

**Release Date:** August 27, 2026

## Overview
Quick-Browser v1.0.0 is the initial public release of a multi-browser account management platform designed to easily manage and switch between multiple browser accounts.

## Features
✅ Create and manage multiple browser profiles/accounts  
✅ Launch browsers with isolated storage (cookies, cache, extensions) per profile  
✅ Save profile metadata (name, notes, associated browser)  
✅ Export and import profiles for backup or sharing  
✅ Simple GUI and command-line launcher  

## System Requirements
- Windows 10 or later
- Target browsers installed (Chrome, Edge, Firefox, etc.)

## Installation
1. Download `QuickBrowser.exe` from the releases page
2. Place it in a folder such as `C:\Program Files\Quick-Browser\`
3. (Optional) Add to PATH for command-line access

## Downloads
- **QuickBrowser.exe** - Main executable (included in release assets)

## Usage

### GUI Mode
```
quickbrowser.exe
```

### Command Line
```bash
# Launch a profile
quickbrowser.exe --launch "Work - Chrome"

# List profiles
quickbrowser.exe --list

# Create a profile
quickbrowser.exe --create --name "TestProfile" --browser chrome

# Export profiles
quickbrowser.exe --export "profiles.zip"
```

## What's New
- Initial release with core functionality
- Multi-profile management
- Browser isolation
- Profile import/export capabilities

## Known Issues
None reported yet. Please open an issue if you encounter any problems.

## Credits
- **Developer:** Karthikeyan S A
- **Organization:** Grapinz Technology (Intern)
- **Repository:** https://github.com/code-javarun/Quick-Browser

## License
MIT License - See LICENSE file in repository

---

**For support and issues, please visit:** https://github.com/code-javarun/Quick-Browser/issues
