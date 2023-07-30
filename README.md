
# Brute-Force Attack
**Description:** This is a Python script for performing a simple brute-force attack on a login page. It takes a username and a list of passwords from a file, and then iterates through each password, attempting to log in to the target website until a valid password is found.

## Requirements :
- Python 3.x
- `requests` library (install with `pip install requests`)
- `termcolor` library (install with `pip install termcolor`)

## Usage:
1. Make sure you have Python installed on your system.
2. Install the required libraries by running the following commands:

  ```python
  pip install requests
  pip install termcolor
  ```
3. Save the list of passwords in a file. Each line in the file should contain one password.
4. Run the script using the following command:

```python
python script.py
```

5. The script will prompt you to provide the necessary information:

- Enter the URL of the login page.
- Enter the username for the account you want to brute-force.
- Enter the path to the password file.
- Provide the string that occurs on the page when login fails.
- Optionally, provide the cookie value if the website requires it.

6. The script will start the brute-force attack and display the attempted passwords. If it successfully finds the correct password, it will print the username and password and exit.

## Important Notes :
- This script is intended for educational and ethical purposes only. Only use it on systems that you have explicit permission to test.
- Brute-force attacks are not recommended as they can be illegal and may cause harm to the target system. Use it responsibly and with caution.
- Always use strong and unique passwords to protect your online accounts.

# Disclaimer
**The author of this script is not responsible for any misuse or damages caused by using this script. Use it at your own risk.**

*Happy hacking responsibly!*
