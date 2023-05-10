# ChatBot

## Goal

The objective of this repository is to learn how to incorporate DialogFlow to build Flutter ChatBot app.

## What is the project

I build a simple chatbot app using flutter and dialogflow where users can ask questions whose answers are predetermined.

![Finished App](https://github.com/iArpitVerma/Flutter_ChatBot/blob/main/chatbot.gif)

## What I have learnt

- How to incorporate Dialogflow into Flutter projects.
- How to create intents with custom training phrases and responses.
- How to use ListViews and SingleChildScrollView to build scrolling views.

## How to setup the project

- Clone the repository.
- Open it in VSCode or Android Studio
- Go to pubspec.yaml and click on 'Pub get' to download all the dependencies used in project.
- Go to 'https://dialogflow.cloud.google.com/#/login' and sign with google.
- Click on 'Create Agent' button and then give any name to agent and click on 'Create' button.
- Click on settings icon, copy the 'Project ID' and go to 'https://console.cloud.google.com' click on dropdown, select All and select your project which has the same name as your Project ID.
- Click on side bar menu, then 'APIs and services', then 'Credentials'.
- Click on '+ Create Credentials', then 'Service account'.
- Give any name to Service account and click on 'Continue', again 'Continue' and then 'Done'.
- Now under 'Service Accounts' section click on your account, then click on 'Keys' in the top bar, then 'Add Key' button, select 'JSON' and then on 'Create' button.
- Now a file will be downloaded, rename this file to 'dialog_flow_auth.json' (strictly) and paste this file in assets folder to be used by the chatbot.
- Now go to dialogflow site, click on 'intents', then 'Default Fallback Intent' to get idea of how this intent thing works, then on 'Create Intent' button.
- Under the 'Training phrases' section, add the questions which you want to be answered by the bot and under 'Responses' section add the answers to that particular question.
- Remember one intent is for a particular question and answer, for different questions add as many intents you want.
- Now the whole setup thing is done.
- Use and Modify the project as per your choice.