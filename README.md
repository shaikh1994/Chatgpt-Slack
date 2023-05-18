# Chatgpt-Slack

This is a slackbot which can use chatgpt. The script is hosted on Azure.

**Features**

	Use /chategpt trigger to activate chatgpt prompt

**How To Use**

	1. Create a slack bot in api.slack
	
	2. Obtain signing secret (SLACK_SIGNING_SECRET) and bot token (SLACK_BOT_TOKEN). 
	Bot token can be obtained from OAuth & Permissions section after adding scopes.
	
	3. Add to workspace.
	
	4. Set up a webapp in Azure and connect to the github repo. 
	Add the environment secrets (SLACK_BOT_TOKEN, SLACK_SIGNING_SECRET, OPENAI_API_KEY)
	 
