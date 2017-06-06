# SlackControl
Slack Bot for remotely executing commands on Linux .

Head to https://api.slack.com/bot-users and create a bot by following on screen instructions. Make of not of API key.

get_uid.py has to been in prior to Server.py. This will fetch your slack bot unique UID.

Server.py estabilishes connection and keep listening for commands, pipe out result os os commands to bot. This this script forked in background.
