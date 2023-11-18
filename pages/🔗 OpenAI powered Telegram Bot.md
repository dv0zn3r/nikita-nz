type:: [[awesome tools] 
author:: [[Đào Hoàng Sơn]]
category:: [[GitHub Repo]] 
topic:: [[OpenAI Assistant]], [[Telegram bot]]
related:: [[Using the OpenAI Assistant as a Telegram Bot]], [[My Research Workflow with OpenAI Assistants]] 
url:: [link](https://github.com/daohoangson/bubby)

- This repository contains the code for a [[Telegram bot]] powered by [[OpenAI]]. The bot implements [[OpenAI Assistant]] API and uses different [[OpenAI models]] for various tasks such as conversing with users, analysing images, and generating images. The bot also has a feature for memory recall and there are plans to add more features like searching for old messages, setting reminders, and integrating with Gmail.
- The bot is deployed on [[AWS]] using the [[Serverless Stack Toolkit]] (SST). The deployment process is managed through [[GitHub Actions]], which is configured to assume a specific AWS role for the deployment. The repository uses `pnpm` as its package manager.
- The bot is configured to only allow admins to initiate a chat, but it can be invited to a group chat where it will reply to everyone. The bot's configuration and secrets, such as the [[OpenAI API]] key and [[Telegram bot token]], are managed through environment variables.