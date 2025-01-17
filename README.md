# Load Environment Variables Script

This script loads environment variables from a `.env` file located in the `/configuration` subdirectory and prints them. It is useful for managing environment variables in a structured and secure way.

## Features
- Reads environment variables from a `.env` file.
- Skips comments and empty lines.
- Prints loaded variables for confirmation.

## Prerequisites
- Bash shell (available by default on most Unix-based systems).

## Setup
1. **Create a `.env` file:**
   - Place your environment variables in a file named `.env` inside the `/configuration` subdirectory relative to the script location.
   - Example `.env` file:
     ```env
     VAR1=value1
     VAR2=value2
     # This is a comment
     VAR3=value3
     ```

2. **Download or create the script:**

   Save the script as `install.sh`:

## Usage:
Save this script as install.sh.
Make it executable:
 ```
chmod +x install.sh
 ```

Ensure the .env file exists in the /configuration subdirectory.
Run the script:
 ```
./install.sh
 ```
