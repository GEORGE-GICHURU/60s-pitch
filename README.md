# ONE-MINUTE-PITCH

## An application that allows users to make one minute pitches and get feedback and votes on them., 11/5/2022


## By **[George Gichuru](https://github.com/GEORGE-GICHURU)**

## Description
[This](https://python-one-minute-pitch.herokuapp.com) is a web application that allows users to submit a pitch. Also, other users are allowed to vote on submitted pitches and leave comments to give their feedback on the pitches. For a user to submit a pitch, vote on a pitch or give feedback on a pitch they need to have an account. <br>

The pitches are organized by categories. Examples of categories: <br> 
- pickup lines
- interview pitches
- product pitches
- promotion pitches

## User Stories
As a user I would like:
* to view the different categories
* to see the pitches other people have posted
* to submit a pitch in any category
* to comment on the different pitches and leave feedback
* to vote on the pitch and give it a downvote or upvote

## Specifications

| Behavior        | Input           | Outcome  |
| ------------- |:-------------:| -----:|
| Register to be a user | Your email : gichurugeorge092@gmail.com <br> Username : Gichuru <br> Password : 1234 | New user is registered |
| Log in | Your email : gichurugeorge092@gmail.com <br> Password : 1234 | Logged in |
| Display pitch categories | N/A | List of various pitch categories |
| See pitches from selected category | **Click** a category | Directed to a page with a list of pitches from the selected category |
| Create a pitch | **Click Create A Pitch** | An authenticated user is directed to a page with a form where the user can create and submit a pitch |
| See a pitch | **Click** on a pitch | A user is directed to a page containing the pitch, its comments and its votes |
| Comment on a pitch | **Click Comment** | An authenticated user is directed to a page with a form where the user can create and submit a comment on a pitch |
| Upvote on a pitch | **Click** on upvote glyphicon | The votes on the pitch increases by one |
| Downvote on a pitch | **Click** on downvote glyphicon | The votes on the pitch decreases by one |

## Setup/Installation Requirements

* Click [one-minute-pitch] <br/>
  or <br/>
* Copy [One Minute Pitch] and  Paste the link on your prefered browerser

This requires internet connection.

## Running the Application

- Creating the virtual environment

        $ python3.10.4 -m venv --without-pip env
        $ source env/bin/activate
        $ curl https://bootstrap.pypa.io/get-pip.py | python

- Installing Flask and other Modules

        $ python3.9 -m pip install Flask
        $ python3.9 -m pip install Flask-Bootstrap
        $ python3.9 -m pip install Flask-Script
        $ python3.9 pip install flask-login
        $ python3.9 pip install flask-migrate
        $ python3.9 pip install flask-SQLAlchemy

## Known Bugs

- Vote count

## Technologies Used
- Python3.9
- Flask
- Bootstrap
- Postgres Database
- CSS
- HTML

### License

MIT (c) 2022 **[George Gichuru](https://github.com/GEORGE-GICHURU)**

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions
