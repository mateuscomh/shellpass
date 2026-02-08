# shellpass - Secure Password Generator for Terminal

[![Release](https://img.shields.io/badge/version-4.1.1-blue)](https://github.com/mateuscomh/shellpass/releases/latest)
[![License](https://img.shields.io/badge/license-GPL--3.0-orange)](https://github.com/mateuscomh/shellpass/blob/main/LICENSE)
[![Build Status](https://github.com/mateuscomh/shellpass/actions/workflows/super-linter.yml/badge.svg)](https://github.com/mateuscomh/shellpass/actions/workflows/super-linter.yml)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/mateuscomh/shellpass/pulls)

A lightweight, secure, and customizable password and words generator for command-line enthusiasts.

## ✨ Features

- Generate cryptographically secure passwords using /dev/urandom
- Password generated direct on your clippboard (Ctrl+C) - look dependencies
- Blazing fast execution 
- Customizable password length and complexity
- Cross-platform support (Linux, macOS, WSL2)
- Copy to clipboard functionality (where available)
- Short history local on .gitignore
  
## 🚀 Installation

### Basic Installation
```bash
git clone https://github.com/mateuscomh/shellpass.git
cd shellpass
chmod +x shellpass.sh
```
### System-wide Installation (Optional)
```bash
sudo cp shellpass.sh /usr/local/bin/shellpass
```
Basic password generation:
    To generate a default password, run and set quantity and complexity of password:
```bash
$ ./shellpass.sh
```
To generate a password with specific length (ex: 20 chars):
```bash
$ ./shellpass.sh 20
```

To show the help menu with all available options:
```bash
$ ./shellpass.sh -h
```

For quick access, add this alias to your shell configuration file (.bashrc, .zshrc, etc.):
```bash
$ alias passgen='~/path/to/shellpass.sh'
```

## Contribution
Contributions to this project are welcome. If you have any suggestions, bug fixes, or improvements, feel free to open an issue or submit a pull request.

## License
This project is licensed under the GPL-3.0 License. See the [LICENSE](https://github.com/mateuscomh/shellpass/blob/main/LICENSE) file for more details.

Made with ❤️ by [Matheus Martins](https://www.linkedin.com/in/matheushsmartins)
