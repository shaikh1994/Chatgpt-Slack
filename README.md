# Chatgpt-Slack

This is a slackbot which can use chatgpt. The script is hosted on Azure.

**Features**

	Use /chategpt trigger to activate chatgpt prompt

**How To Use**

	1. Create a slack bot in api.slack
	
	2. Obtain signing secret (SLACK_SIGNING_SECRET) and bot token (SLACK_BOT_TOKEN). 
	Bot token can be obtained from OAuth & Permissions section after adding scopes.
	
	3. Create /chatgpt slash commmand.  
	URL will be Azure webapp url. (E.g- https://slackbotprod.azurewebsites.net/mp3_trigger)
	
	4. Add to workspace.
	
	4. Set up a webapp in Azure and connect to the github repo. 
	Add the environment secrets (SLACK_BOT_TOKEN, SLACK_SIGNING_SECRET, OPENAI_API_KEY)
	 
** Usage**


![chatgpt](https://github.com/shaikh1994/Chatgpt-Slack/assets/43321233/5fa62eb5-00ac-435f-8dfe-536894d4fb2f)

