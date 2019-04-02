# Slack_Bots
An array of simple slack bots implemented using different technologies

Prerequisites

1) In order to use any of the slack bots an API token for slack is needed, this can be generated here: https://api.slack.com/slack-apps

  Steps to creating a token:

  •Create a new slack app (you should be part of the HMHCO workspace on Slack, allowing you to deploy your app there)
  •Navigate to Install your app to your workspace (You should be prompted to add "permission scope" before installation)
  •Follow the link for permission scope
  •Under scopes, select the permissions you wish to give the api token (e.g chat:write:bot)
  •Once permissions are selected, choose Install App
  •Authorise your permissions, you should then see your api token in the format: xoxp-XXXXXXXXXX- etc

2) A Slack Channel needs to exist in order to post to it

Usage
To use any of the slack bots you should run any of the files with arguements in the following order:

<slack_token> <slack_channel> <bot_name> <slack_message>

e.g: ./slack_bot.sh xoxp-XXXXXXXXXX test_channel "Friendly Bot" "Hello!"
