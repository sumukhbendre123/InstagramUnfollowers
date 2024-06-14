# Instagram Unfollowers Checker

This Python script uses Selenium to log into Instagram, navigate to the user's profile, and fetches lists of followers and following. It then identifies users who are followed by you but do not follow you back.

## Prerequisites

- Python 3.x installed on your system
- Required Python packages installed:
  - selenium
  - webdriver_manager
  - requests

You can install these packages using pip:
```bash
pip install selenium webdriver_manager requests
git clone https://github.com/sumukhbendre123/InstagramUnfollowers.git
cd InstagramUnfollowers
pip install -r requirements.txt
username = 'your_instagram_username'
password = 'your_instagram_password'

### Instructions:

- Replace `your_instagram_username` and `your_instagram_password` with your actual Instagram credentials in the `instagram_followers.py` script.
- Make sure to have Chrome installed on your system as the script uses ChromeDriver for Selenium automation.

This README.md provides basic setup instructions, usage guidelines, and notes for running your Instagram unfollowers checker script. Adjust it further based on any specific details or additional functionalities of your script.
