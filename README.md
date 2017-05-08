# slackcli simple slack webhook CUI curl only

## Usage

### Install

```
curl https://raw.githubusercontent.com/ryurock/slackcli/master/slackcli > /usr/local/bin/slackcli
```

### Option --conf Example

write slack.ini

```
[default]
slack_webhook_url=https://hooks.slack.com/services/{{ your webhook url }}
slack_icon=:slack:
slack_channel=#random
slack_username=slackcli default title
```

### read slack.ini

```
slackcli -c ./slack.ini "text message"
```

