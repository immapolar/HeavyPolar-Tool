# HeavyPolar

![type](https://img.shields.io/badge/Type-Malware-red)
![language](https://img.shields.io/badge/Language-Python%203.10-3776AB?style=flat&logo=python&logoColor=white)
![platform](https://img.shields.io/badge/Platform-Windows-0078D6?style=flat&logo=windows&logoColor=white)
![availability](https://img.shields.io/badge/Availability-PAID-white)
![contact](https://img.shields.io/badge/Discord-@zsgd-5865F2?style=flat&logo=discord&logoColor=white)

<pre align="center">
                                ___      _            
  /\  /\___  __ ___   ___   _  / _ \___ | | __ _ _ __ 
 / /_/ / _ \/ _` \ \ / / | | |/ /_)/ _ \| |/ _` | '__|
/ __  /  __/ (_| |\ V /| |_| / ___/ (_) | | (_| | |   
\/ /_/ \___|\__,_| \_/  \__, \/    \___/|_|\__,_|_|   
                        |___/                         
</pre>

A Python-based tokens theft malware targeting victim Discord tokens.

## Core
- Token extraction from multiple browsers and Discord clients
- Multi-threaded token collection
- System persistence via registry modification
- Screenshot and system info gathering
- Tokens, system pieces informations and screenshot collected get sent to Discord webhook

### Targeted Paths
```python
TARGETED_PATHS = [
    "Discord",
    "DiscordCanary",
    "DiscordPTB",
    "Chrome",
    "Brave",
    "Edge",
    "Opera",
    "Opera GX"
]
```

### Dependencies
```python
LIBRARIES = [
    'requests',
    'psutil',
    'pywin32',
    'pycryptodome',
    'pyautogui',
    'prettytable',
    'py-cpuinfo'
]
```
## Features

### Data Access Features
- Browser-stored credentials
- Discord authentication tokens
- System information
- Victim montior screenshot

### Anti-Analysis Features
- Execution delays
- Process lineage checks
- Hidden file operations
- Windowless execution

### Automated Features
1. Automated Python 3.10 verification and installation
2. Automated dependency installation
3. Automated system persistence setup
4. Automated hidden marker creation
5. Automated extraction on startup
6. Extraction performed repeatedly every specified period

### Extraction Method
- Chrome-based browser token decryption
- Multi-path token scanning
- Encrypted token parsing
- Token validation and verification

> [!NOTE]
> The tool is paid as Python source code. Contact @zsgd on Discord for purchase or further help and assistance.

> [!WARNING]
> The extraction works as Windows-based malware targeting Discord authentication tokens, system modification, and advanced persistence techniques. All features are documented. The code could be harmful and potentially illegal. Any use for malicious purposes is strictly prohibited and potentially illegal.
