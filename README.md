# Quick-Browser

Multi-browser account management platform — easily manage and switch between multiple browser accounts.

Quick-Browser provides a lightweight launcher and profile manager to create and run isolated browser profiles for testing, development, and multi-account workflows.

## Features
- Create and manage multiple browser profiles/accounts.
- Launch browsers with isolated storage (cookies, cache, extensions) per profile.
- Save profile metadata (name, notes, associated browser).
- Export and import profiles for backup or sharing.
- Simple GUI and a command-line launcher (quickbrowser.exe).

## Requirements
- Windows 10 or later for `quickbrowser.exe`.
- Target browsers installed (e.g., Google Chrome, Microsoft Edge, Firefox).

## Installation
1. Download `quickbrowser.exe` (or the release bundle) and place it in a folder such as `C:\Program Files\Quick-Browser\`.
2. (Optional) Add that folder to your PATH to run `quickbrowser` from the command line.

## Quick Start (GUI)
1. Run `quickbrowser.exe` to open the Quick-Browser interface.
2. Create a new profile, give it a name and optional notes, and select the browser to use.
3. Click "Launch" to start the browser with that isolated profile.

## Quick Start (Command Line)
The executable supports a simple CLI to launch or manage profiles. Example (placeholders):

- Launch a profile:
  `quickbrowser.exe --launch "Work - Chrome"`
- List profiles:
  `quickbrowser.exe --list`
- Create a profile:
  `quickbrowser.exe --create --name "TestProfile" --browser chrome`
- Export profiles:
  `quickbrowser.exe --export "profiles.zip"`

Note: These options are illustrative. If you provide the actual `quickbrowser.exe` or its `--help` output, this README will be updated to match the real CLI options.

## Configuration & Data
- Profiles are stored in a data directory configurable in the app or via an environment variable.
- You can change default browser paths in Settings if browsers are installed in non-standard locations.

## Troubleshooting
- If a profile won't launch, confirm the selected browser is installed and reachable.
- Run as Administrator if you encounter permission issues.
- Use Import/Export to restore profiles from backups in case of corruption.

## Security & Privacy
- Profiles store cookies, cache, and local storage locally and separately from your main browser profiles.
- Quick-Browser does not upload profile data externally by default. Review settings before enabling any sync or export features.

## Contributing
Contributions and bug reports are welcome. Please open issues describing the problem, steps to reproduce, and environment details (OS, browser versions).

## License
This project is provided under the MIT License. See LICENSE for details.

## Credits
- Programmer: Karthikeyan S A
- Grapinz Technology — Intern

## Contact
Open an issue in this repository for questions or support.
