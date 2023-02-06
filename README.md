# ChatGPT Slack Bot

## Introduction
This application is a Slack Bot that uses OpenAI's language model to provide assistance with a wide range of tasks. The bot uses a natural language processing technique to understand and respond to messages in a human-like manner.

## Features
- The bot is designed to assist with a wide range of tasks and provide valuable insights and information on a wide range of topics.
- The bot can process and understand large amounts of text, allowing it to provide accurate and informative responses.
- The bot is capable of engaging in natural-sounding conversations and providing coherent and relevant responses.


## Usage
To use the Assistant Slack Bot, the following environment variables need to be set:
- SLACK_BOT_TOKEN: Token for the Slack Bot.
- SLACK_APP_TOKEN: Token for the Slack app.
- OPENAI_API_TOKEN Token for openai


Implementation Details
The implementation of the  Slack Bot uses the Slack Bolt library for handling Slack events and the langchain library for generating responses using OpenAI's language model. The langchain library also provides a ConversationalBufferWindowMemory that stores conversations in a conversation memory

The chatgpt_chain is an instance of the LLMChain class, which generates responses using OpenAI's language model with a temperature of 0 for factual output. The prompt for the chain is specified using the PromptTemplate class, which defines the format for the input and output of the model. 