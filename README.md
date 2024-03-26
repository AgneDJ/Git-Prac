Hi there
Git-Prac
Fitness web app for competing with your friends by using step count.

Features
Send/receive/cancel friend requests
Add/remove friends
Participate in challenges
Invite friends to challenges
See progress
Receive achievements
Requirements
Python 3
PostgeSQL
Google Service Account Key
How to use
Expose environment variables:

APP_SECRET_KEY
GOOGLE_CLIENT_ID
GOOGLE_CLIENT_SECRET
Install the project:

$ git clone https://github.com/AgneDJ/StepOdyssey.git
$ virtualenv env
$ source env/bin/activate
(env) $ pip3 install -r requirements.txt
(env) $ createdb step_challenge
$ python3 model.py
To run the server:

$ python3 server.py
open localhost: https://127.0.0.1:5000/
