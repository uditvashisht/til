# Save Login Credentials/Secret Keys in .env files
If you are working on a shared project or posting stuff on web resources like github or bitbucket, saving your secret credentials in .env files rather than hard coding it in the code is a better option.

First of all install Python-dotenv using the following command:-

`pip install python-dotenv`

Then create a .env file, open in your favorite editor and save the entries like this

```
USERNAME = 'your-user-name'
PASSWORD = 'your-password'
```
Then, you can include it in your code using following lines of command:-
```
import os
from dotenv import load_dotenv, find_dotenv
load_dotenv(find_dotenv())
username = os.getenv("USERNAME")
password = os.getenv("PASSWORD")

```
And you are done. Don't forget to add .env files to .gitignore
