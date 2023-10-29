# Monitoring
Monitoring for a project using Prometheus.

## Alert sending to telegram group
Create a Telegram bot by following the guide in the Telegram docs. After creating the bot, you will receive a token that will be used to configure the Alertmanager.

Next, create a new group in Telegram and add the bot to this group. You can get the chat ID of the group by sending a message to the bot and using the Telegram IDBot

Extra reading: https://grafana.com/blog/2020/02/25/step-by-step-guide-to-setting-up-prometheus-alertmanager-with-slack-pagerduty-and-gmail/
