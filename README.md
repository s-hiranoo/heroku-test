# Heroku deploy test

This is the test of 'git push heroku master'.

There is a problem now about ssh:

>>
sign_and_send_pubkey: signing failed: agent refused operation
Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights

## How to solve
tried in vain: ssh-add, re-login heroku

good:
$> eval `ssh-agent -s`
$> ssh-add