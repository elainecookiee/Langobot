![Langobot](/images/bot.png)

# Langobot
A conversational language learning bot using API.ai and an HTML JS sdk. Currently the application only supports English. Other languages will be implemented.

Click this link to chat with [Langobot](http://tranela.dev.fast.sheridanc.on.ca/Langobot/)

## Instructions - How to build your own chatbot!

### I. Planning

1. Plan your bot's content and logic using a visual build for multi-platform messaging such as [TextIt](https://textit.in/).

![textit](/images/textit.png)

2. Create your own assets and links.

![story](/images/story.png)

### II. Setup AI Dialogue using API.ai

#### Steps:

1. Create an Agent in API.ai - Agents are Natural Language Understanding (NLU) modules that transform user input into data that actions can be performed on.

You can read more about these Key Concepts in API.ai's [documentation](https://docs.api.ai/docs/key-concepts)

2. Create Entities to represent concepts that you want the bot to recognize from the user's input.

3. Create Intents which maps what the user says to what action should be taken.

4. Enable Machine Learning.

5. Add images and links to send as a rich message.

6. Enable and set up Small Talk to allow your bot to respond with predefined phrases to common user questions.

7. Enable One-Click integrations to connect with third party messaging platforms such as Facebook Messenger, Actions on Google, Amazon Alexa and Slack.

8. Train your bot by matching dialogue with the correct Intent.

![apiai](/images/apiai.png)


### III. Download the HTML and JavaScript example SDK to build your own interface!

This list of SDKs recommended by API.ai can be found [here](https://docs.api.ai/docs/sdks)

#### Steps:

1. Under Agent Settings in API.ai, find the Client Access Token. Copy and paste the token into the code.

2. Create functions in the JavaScript file to check for text or image content and display results dynamically in the DOM using DOM manipulation.

3. Create your own interface by adding a stylesheet using CSS.


![sdk](/images/htmljs.png)



