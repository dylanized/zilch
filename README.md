ZILCH - Command Line Internet Blocker
===

How to install:
---

- download the repo into a folder in your home directory called ".zilch"
- source ~/.zilch/zilch from your bash profile
- from the command line, run "zilch import". This will import your current hosts file into ~/.zilch/on.txt and off.txt
- edit on.txt to list all the websites you want to block a sample version is included

Now you can run "zilch" to block sites, and "zilch off" to unblock them.

How to customize:
---

- edit the script to change default folders
- you can create additional blockfiles, like "socialmedia.txt". Then you could run "zilch socialmedia" to apply this list
