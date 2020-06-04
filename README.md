# Learnination Machine by Team Pupiter Classroom

**Roster/Roles**
- Emily Zhang
  - Project manager
  - Update README, make sure devlog is up to date
  - Update design doc to reflect changes to project midway through
 - Kevin Li
   - Interfacing with Google Classroom API
     - Sign in with Google
     - GET data, POST data back to Google
   - Deployment to droplet via Flask (and Apache, if time permits)
 - William Lin
   - Database work
 - Henry Liu
   - Search mechanism for posts

**Description**

Our website aims to be an alternative portal to Google Classroom with added features/quality of life improvements, such as a better integrated calendar, the ability to hide classes, searching for posts, etc. Everything done on this site is reflected on Google Classroom.

**API(s) used**
- [Google Classroom API](https://developers.google.com/classroom/reference/rest)

## Launch codes
**Dependencies**

Your first step is to procure the client_secret.json file from collaborator Kevin Li. For security purposes, the file cannot be stored publicly. His email is kli00@stuy.edu.

After procuring the file, merely drop it into the app/ directory.

You will also need to create a secret_key.txt file in the app/ directory. Generate a key with os.urandom(32) in Python and paste it into that file.

Next, you must install the pip modules listed in the requirements.txt file. To do so, install them in a terminal session with:
```pip install -r requirements.txt```

It is recommended to run the above command inside a virtual environment. To create one, do:
```python3 -m venv <name_of_venv>```
*Note that if your system only has Python 3 installed, just remove the 3 from the above command.*

To activate the virtual environment, run:
```
source <name_of_venv>/bin/activate
```

**Run the program**

After completing the above tasks, all you need to do to run the program is to cd back to the app/ directory and type into your virtual environment:
```
python3 __init__.py
```
*Again, remove the 3 after the "python" if necessary.*
