# Learnination Machine by Team Pupiter Classroom
[![Actions Status](https://github.com/emz1003/softdev-p05/workflows/Web%20app/badge.svg)](https://github.com/emz1003/softdev-p05/actions)

[video demo here](https://youtu.be/4zvHlHehMjU)

**Roster/Roles**
- Emily Zhang (Project Manager)
  - Oversees project development
  - Updates devlog and design doc
  - Gradebook
  - Archive classes
 - Kevin Li
   - Interfacing with Google Classroom/Calendar APIs
     - Sign in with Google
     - GET data, POST data back to Google
   - Deployment to droplet via Flask (and Apache, if time permits)
 - William Lin
   - Database work
   - Front end
 - Henry Liu
   - Search mechanism for posts
   - Calendar/To Do List

**Description**

Our website aims to be an alternative portal to Google Classroom with added features/quality of life improvements, such as a better integrated calendar, the ability to hide classes, searching for posts, etc. However, due to lack of permissions, everything is strictly *read-only*.

**API(s) used**
- [Google Classroom API](https://developers.google.com/classroom/reference/rest)
- [Google Calendar API](https://developers.google.com/calendar/v3/reference)

## Launch codes
**Dependencies**

Your first step is to procure the client_secret.json file from collaborator Kevin Li. For security purposes, the file cannot be stored publicly. His email is kli00@stuy.edu.

After procuring the file, merely drop it into the app/ directory.

Next, you must install the pip modules listed in the requirements.txt file. To do so, install them in a terminal session with:
```
pip install -r requirements.txt
```

It is recommended to run the above command inside a virtual environment. To create one, do:
```
python3 -m venv <name_of_venv>
```
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
