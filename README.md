## Serverless Telegram bot on AWS Lambda

### Intro
This is a simple template of echo Telegram chatbot written in Python 3 and deployed to AWS Lambda using Serverless framework.
You can find the tutorial of how to deploy it [here](https://medium.com/@andriidvoiak/serverless-telegram-bot-on-aws-lambda-851204d4236c)

### Requirements
 1. Python 3
 2. Node.js v6.5.0 or later
 3. AWS account with Admin rights

### Deploying

Install Serverless framework:

`npm install -g serverless`

Export credentials:

```
export AWS_ACCESS_KEY_ID=<Access key ID>
export AWS_SECRET_ACCESS_KEY=<Secret access key>
export TELEGRAM_TOKEN=<Your Telegram Token>
```

Install pip requirements:

`pip install -r requirements.txt -t vendored`

Deploy to AWS:

`serverless deploy`

### P.S. 
If you need more complex solution, take a look on this example: https://github.com/Andrii-D/telegram-stepfunctions-bot/
