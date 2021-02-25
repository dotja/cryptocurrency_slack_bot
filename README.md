# Cryptocurrency Slack Bot

Used to automate Slack notifications of cryptocurrency prices.

### Python Modules
```
requests
slackclient
```

### Cron setup

Configure a Cron job for the script wrapper to run every 10 minutes.

```
*/10 * * * * /path/to/cryptocurrency_slack_bot/run_bot.sh
```
