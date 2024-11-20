<div align="center">

# B-Backup 💾

B-Backup is a Bash tool designed to simplify file and directory backups on Linux systems. It offers a range of features including encryption, compression, logging, and more. Despite its CLI nature, it boasts a sleek and user-friendly interface.

[![Project Phase](https://img.shields.io/static/v1?label=Project%20Phase&message=Submitted&color=green)](https://github.com/An0n-00/B-Backup/releases)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-No-red.svg)](https://GitHub.com/an0n-00/B-Backup/graphs/commit-activity)
[![GitHub issues](https://img.shields.io/github/issues/an0n-00/B-Backup.svg)](https://GitHub.com/an0n-00/B-Backup/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/an0n-00/B-Backup.svg)](https://GitHub.com/an0n-00/B-Backup/pulls/)
[![GitHub license](https://img.shields.io/github/license/an0n-00/B-Backup.svg)](https://github.com/an0n-00/B-Backup/blob/main/LICENSE)
</div>

## Features

- **Backup**: Easily back up files and directories to a hidden location on your system.
  
- **Encryption**: Encrypt backups using PKZIP encryption for added security.
  
- **Compression**: Compress backups using DEFLATE compression to save storage space.
  
- **Deletion**: Option to delete original files and directories after a successful backup.
  
- **Restore**: Restore backups to the original location or a custom destination.
  
- **Export**: Export backups to a custom location for external storage or sharing.
  
- **Logging**: Record all actions and operations in a log file for future reference.
  
- **List Backups**: View a list of all backups created by B-Backup.
  
- **Delete Individual Backups**: Remove specific backups as needed.
  
- **Search Backup Contents**: Easily search for specific files within any B-Backup created backup.
  
- **Error Handling**: Gracefully handle errors and provide informative messages to users.
  
- **Help Menu**: Access a comprehensive help menu for assistance with using B-Backup.

## Getting Started

### Prerequisites

- Linux operating system
- Bash shell
- Sufficient disk space for storing backups

### Installation

1. Clone the B-Backup repository to your local machine:

   ```bash
   git clone https://github.com/An0n-00/B-Backup.git
    ```

2. Navigate to the B-Backup directory:

   ```bash
   cd B-Backup
   ```

3. Ensure the script is executable:

   ```bash
   chmod +x b-backup.sh
   ```

4. Run the script:

   ```bash
    ./b-backup.sh
    ```

5. Follow the on-screen instructions to start using B-Backup.

## Usage

> [!IMPORTANT]  
> **B-Backup CANNOT run with root privileges.**
>
> B-Backup prevents the script from running with root privileges, which could potentially cause harm to the system and cause unwanted side effects while using the script. If the script is run with root privileges, the script will exit with an error message. Therefore, **please run the script as a regular user.**

1. Run the script to launch the interactive menu:

   ```bash
   ./b-backup.sh
   ```

2. Follow the on-screen prompts to perform backup, restoration, or other operations.

## Screenshots

| The Startup animation if you run the script | The nice and intuitive backup management menu |
|---------------------------------------------|-----------------------------------------------|
| ![Startup Image](/docs/images/startup.png)               | ![Backup management menu](/docs/images/manage-menu.png)    |

## Contributing

Contributions to B-Backup are welcome! If you have suggestions, feature requests, or would like to report issues, please open an issue or submit a pull request on GitHub.

### Contibutors

[![Contributors](https://contrib.rocks/image?repo=an0n-00/B-Backup)](https://github.com/an0n-00/B-Backup/graphs/contributors)

## License

This project is licensed under the [GNU General Public License v3.0](https://github.com/an0n-00/B-Backup/blob/main/LICENSE).
