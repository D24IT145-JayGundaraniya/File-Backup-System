# File Backup System

This project is a command-line tool built with Node.js to back up files from a specified source directory to a backup folder, preserving the original folder structure. It also provides the option to compress the backup folder into a `.zip` file.

## Features
- Copy files and directories from a source folder to a backup folder while maintaining the directory structure.
- Log the details of the backup operation, including file names, sizes, and timestamps, into a `backup-log.txt` file.
- Optionally, compress the backup folder into a `.zip` file using the `archiver` package.

