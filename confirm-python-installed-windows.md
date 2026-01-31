# Install Check: Confirming Python is Installed and Working on Windows

## What this guide helps you do

This guide helps you confirm that Python is installed and working before you move on.

---

## Before you begin

You’ll need the following:

1. **A Windows PC**

2. **Access to a command-line interface**

   - You can open Command Prompt by typing `cmd` in the Windows search bar, or PowerShell by typing `PowerShell`.

3. **Python installed on your system**

   - If you’re not sure whether Python is installed, this guide will help you check safely.

4. **Permission to run commands**
   - You do not need administrator access for this check.

> This guide focuses on Windows. Steps for macOS and Linux are similar but not covered here.

---

## Check that Python is installed

1. Open **Command Prompt** or **PowerShell**.
2. Type the following command and press Enter:

   ```bash
   python --version
   ```

If that doesn't work, try:

python3 --version

## Confirm it worked

You'll know it worked when you see a version number, such as:

Python 3.11.2

This confirms that Python is installed and available from the command line.

## If something didn't work

- **“python is not recognized”**
- This usually means Python is not installed or not added to your system PATH.

- **A version number doesn’t appear**
- Try using `python3 --version` instead.

- **Unexpected output or errors**
- Close the terminal and try again to ensure no previous commands are interfering.

If you don’t see a version number, nothing is broken; you’ve simply confirmed that Python is not yet ready to use.
