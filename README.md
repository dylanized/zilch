ZILCH - Command Line Internet Blocker
===

Zilch limits all distractions and helps you focus. It does it by swapping your computer's hosts file between a clean version (off.txt) and a version with your favorite websites blocked (on.txt). You can make additional blockfiles too.

How to install:
---

- download the repo into a folder in your home directory called ".zilch"
- source ~/.zilch/zilch from your bash profile
- from the command line, run "zilch import". This will import your current hosts file into ~/.zilch/on.txt and off.txt
- edit on.txt to list all the websites you want to block a sample version is included

How to use:
---

Block sites:

    zilch
    
Unblock sites:

    zilch off
    
Check the status with:

    zilch status

How to customize:
---

- edit the script to change default folders
- you can create additional blockfiles, like "socialmedia.txt". Then you could run "zilch socialmedia" to apply this list
- you can also use the shortcuts "zon" and "zoff"
