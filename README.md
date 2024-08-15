# Banker-Chatbot-AWS-Lambda-Lex

Meet my BankerBot, a new virtual banking assistant. Here’s what it can do:
- Check your balance 📋
- Transfer funds 🔄

How it was built:
- Set up Amazon Lex for a friendly welcome
- Create intents to check account balances
- Use Lambda to generate random balances
- Implement context carryover for a more personalized experience
- Enable fund transfers and leverage AWS CloudFormation to manage resources efficiently

Here’s what I learnt while building my chatbot:
- 🎯 Defined Intents & Utterances: Set up core intents in Amazon Lex and created various phrases for the bot to understand different user requests.
- 🔄 Integrated Lambda Functions: Enhanced the chatbot’s capabilities by linking it with AWS Lambda for dynamic responses.
- 🌟 Set Up Custom Slots: Configured custom slot types to recognize different bank account details and connected them to intents for precise interactions.
- 🚁 Enabled Context Carryover: Made the chatbot smarter by allowing it to remember user details across different intents.
- ☁️ Automated Deployment with CloudFormation: Used AWS CloudFormation to deploy the bot efficiently, ensuring all resources were properly managed.
