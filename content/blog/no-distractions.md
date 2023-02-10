---
title: "No Distractions"
date: 2023-02-10
draft: false
---

# Spotify No Longer Keeps Me Up

I always stay up way too late (even after getting work done) because I'm hooked on Spotify.

So I wrote a script and cron job to close Spotify automatically and scold me every night at 1:30 AM, 2:30 AM, and 3:30 AM!

## Python

This is my computer systems knowledge coming to play! `killall` will send the SIGTERM signal to all Spotify processes running at the time, giving Spotify time to clean up so that essential operations can finish before shutting down. 

Right afterwards, Tkinter renders a nasty pop-up at me!

Here's the contents of the script (edit with `vim ~/stop-spotify.py`):
```py
# ~/stop-spotify.py

import tkinter as tk
import subprocess

subprocess.call(['killall', 'Spotify'])

root = tk.Tk()
root.title("IT'S PAST YOUR BEDTIME")

screen_width = root.winfo_screenwidth()
screen_height = root.winfo_screenheight()

margin = min(screen_width, screen_height) // 4

label = tk.Label(root, text="I shut off Spotify for you, now go to bed FFS!", font=("TkDefaultFont", 14))
label.pack(pady=margin, padx=margin)

root.update_idletasks()

width = root.winfo_width()
height = root.winfo_height()
x = (root.winfo_screenwidth() // 2) - (width // 2)
y = (root.winfo_screenheight() // 2) - (height // 2)
root.geometry(f"{width}x{height}+{x}+{y}")

root.mainloop()
```

## Cron

And here's the crontab info (edit with `crontab -e`):

The first two numbers are straightforward, and the last three asterisks `*` imply the task is run every day, every month, every year.
```bash
30 1 * * * /usr/local/bin/python3 ~/stop-spotify.py
30 2 * * * /usr/local/bin/python3 ~/stop-spotify.py
30 3 * * * /usr/local/bin/python3 ~/stop-spotify.py
```

Maybe this will help you in some way if you get distracted by a certain app.