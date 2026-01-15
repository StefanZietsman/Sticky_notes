# Sticky Notes Application

Sticky_notes application using Django.

## Description

The Sticky_notes app lets users add a small visual yellow note box, on a dark grey background, with a title and content to help set reminders or to/do tasks for multiple users. A detailed view, with a note date and time, can be obtained by selecting a sticky_note. Each sticky_note can be edited and ultimately, if not needed or completed, can be deleted. User accounts are setup and managed by Django module by an administrator.

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)

## Installation

Copy source files to virtual environment and install requirements in virtual environment as in `requirements.txt`.

## Usage

In terminal, run command `python manage.py runserver` in the path where `manage.py` is located. In your http browser, log on to http://localhost:8000/admin/ to access Django management page. The account log on credentials are:

**Admin login**
* Username: admin
* Email: example@email.com
* Password: password

Once users are registered, using Django management, users can add their own sticky_note with manipulation tools by logging on to http://localhost:8000 with your http browser.

## Credits

Thank you to the creators of Django module and Bootstrap.
