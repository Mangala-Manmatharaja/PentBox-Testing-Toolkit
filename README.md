# 🔒 PentBox - A Security Testing Toolkit

PentBox is a lightweight, open-source security toolkit designed to streamline penetration testing tasks. Written in Ruby, it is primarily oriented for GNU/Linux but supports Windows, macOS, and any system with Ruby installed. PentBox provides a collection of tools for network scanning, web testing, and more, making it a versatile choice for security professionals.

## ✨ Features


  🌐 Network Tools: Includes port scanners, DNS and host gathering, and DoS testing modules.

  🕸️ Web Tools: Features HTTP directory and file brute-forcing, as well as MAC address geolocation.

  🔐 Cryptography: Supports password hashing and cracking with an expanded wordlist.
  
  🛡️ Honeypot: Detects and logs intrusions with attacker IP and port details.

  💻 Cross-Platform: Runs on any system with Ruby installed.


## 🛠️ Installation


  To get started with PentBox, follow these steps:
  
### Clone the repository
  
  git clone (https://github.com/Mangala-Manmatharaja/PentBox-Testing-Toolkit)

### Navigate to the project directory
    cd pentbox

### Extract the tarball
    tar -zxvf pentbox.tar.gz

### Enter the extracted directory
    cd pentbox

### Run the main script
    ./pentbox.rb

### Ensure Ruby is installed on your system. For Ubuntu/Debian, you can install it with:
    sudo apt-get install ruby

## 🚀 Usage
  
  Run ./pentbox.rb to access the main menu, where you can select various tools and modules. Each module includes detailed prompts to guide usage. For detailed documentation,   
  refer to Kali Linux's guide on honeypots.
  
## 📜 Changelog

## 🆕 Version 1.8 (Latest)

  
   ➕ Added command execution in STDIN (!command).
  
   📍 Enhanced honeypot with attacker IP/port logging.
  
   🌐 Introduced web tools: HTTP directory and file brute-forcing, MAC address geolocation.
  
   💥 Added DoS exploits for various systems (e.g., 3Com, Windows FTP, SMB).
  
   🔄 Included pb_update.rb for updates via SVN.
  
   🐛 Fixed SHODAN API issues and improved permissions checking.
   

## 🔧 Version 1.5


   ⚡ Optimized for Ruby 1.9.x and JRuby with native threads.

   📈 Improved TCP port scanner and hash cracker performance.

   🔑 Added RIPEMD-160 hashing, HTTP header fuzzing, and protected mode for DoS tools.

   🛠️ Unified DoS tools into net_dos.rb and included new DNS search module.
   

### 🛡️ Version 1.3.2

   🚀 Enhanced FTP fuzzing and CLI interface.

   🔍 Added dictionary-bruteforce hybrid attack for hash cracking.

   📝 Improved honeypot logging and module integration for better performance.

   📚 Older Versions

  Version 1.3: Added cryptographic ciphers (GOST, ARC4, Rijndael) and file encryption.
  Version 1.2: Introduced fuzzing tool and honeypot logging improvements.
  Version 1.1: Added secure IM client and optimized DoS tools.
  Version 1.0: Initial release with core functionality.

## 🤝 Contributing
  
  - We welcome contributions to improve PentBox! To contribute:
    

## 🍴 Fork the repository.


-🌱 Create a feature branch (git checkout -b feature/YourFeature).
- 💾 Commit your changes (git commit -m "Add YourFeature").
- 🚀 Push to the branch (git push origin feature/YourFeature).
- 📬 Open a pull request with a clear description of your changes.
  

### Please focus on meaningful updates, such as new features, bug fixes, or performance improvements. Avoid submitting typo fixes or minor formatting changes.


## 📄 License

  PentBox is licensed under the GNU General Public License v3.0. See the LICENSE file for details.
