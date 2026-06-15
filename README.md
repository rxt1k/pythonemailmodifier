Email Modifier
A tiny desktop app built with Python's tkinter that lets you quickly pull the username from an email address or change its domain.

What it does
Get Username – Extracts the part before @ and shows it.

Change domain – Replaces the domain (e.g., @example.com) with anything you type.

How to use it
Run the script.

Enter an email in the box (like user@example.com).

Click Get Username – the username part appears below.

Click Change domain – a new box appears where you type the new domain (e.g. @gmail.com), then click the second Change domain button.

The modified email shows up at the bottom.

Example
Email entered: user@example.com

Click Get Username → user

Click Change domain → type @yahoo.com → new email: user@yahoo.com

Requirements
Python 3.x (tkinter comes built‑in)

Run it
bash
python email_modifier.py
Notes
This is a very simple script made for practice / small personal use.

It doesn't check if the email format is 100% valid — just looks for the first @.

The "Change domain" window appears inside the main app (no separate pop‑up).

Possible improvements
Add a clear button

Validate email format before processing

Let user edit the whole email, not just the domain
