# toslack
stdin writes to slack

# setup
1. Set up a private slack
2. [Generate a slack webhook url](https://slack.com/help/articles/115005265063-Incoming-WebHooks-for-Slack)
3. Put it in the toslack file OR save it as a bash variable in your .bashrc
4. Put the toslack file into your path (such as /usr/bin)
5. Now you can write to your slack via stdin like this `echo hello worl | toslack`
