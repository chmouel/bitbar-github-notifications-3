# github notification for bitbar

This is a python3 port from https://github.com/matryer/bitbar-plugins/blob/master/Dev/GitHub/notifications.30s.py with some code cleanups.. 

It adds a new feature to allow to shut the notifications between a time span (ie outside of work hour) the time is by default between `08h30` and `18h30` but you can configure different time into the `TIMESPAN` variable in the script.

It will try to detect your token with the command `git config --get github.oauth-token` assuming this was set in your gitconfig (be careful to publish your github token in a public repo)
