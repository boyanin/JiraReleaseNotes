# JIRA Relase notes
A simple meta-runner for TeamCity that generates release notes based on the commit messages to your version control system.

## Dependencies
I use other meta runners that communicate with JIRA, so I rely extensively on [PSJira](https://github.com/replicaJunction/PSJira) - a PowerShell module that eases the communication with JIRA's REST API. I have also included this module here. If you don't want to use it, though, you may write the HTTP requests directly in the script.

## Installation
You can read more about working with TeamCity meta-runners on their [official site](https://confluence.jetbrains.com/display/TCD8/Working+with+Meta-Runner).
