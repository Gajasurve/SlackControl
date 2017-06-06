# SlackControl
Slack Bot for remotely executing commands on Linux / Windows .

Requires slackclient. #Install using pip install slackclient

Head to https://api.slack.com/bot-users and create a bot by following on screen instructions. Make of note of API key.

get_uid.py has to be executed  in prior to Server.py. This will fetch your slack bot unique UID ( Required in Server.py ).

Server.py estabilishes connection and keep listening for commands, pipe out result os commands to bot. This script has to be forked in background.
