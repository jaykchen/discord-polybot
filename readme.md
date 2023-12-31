# Discord Assistant Bot

This multi-purpose Discord bot offers a variety of functionalities. It can summarize text, review code, interpret medical reports, translate text to English, reply to tweets, and answer questions. It accepts both images and text as input.

## Features

- **Text and Image Processing**: The bot accepts both text and images as input. 
- **Help Command**: Get a list of available commands using `/help`.
- **General Conversation**: Initiate a general conversation with the bot using `/start`.
- **Text Summarization**: Summarize large bodies of text with `/summarize`. When invoking the command, you can also input a url to summarize the text from the webpage. Note: due to the complexity of today's websites, not all webpages are supported.
- **Code Review**: Get your code reviewed by the bot using `/code`.
- **Medical Report Interpretation**: Summarize medical reports with `/medical`.
- **Translation**: Translate text to English with `/translate`.
- **Tweet Replies**: Generate replies for tweets using `/reply_tweet`.
- **Q&A**: Get answers to your questions using `/qa`.

Please note that an invoked command will be invalidated if not used within the first 60 seconds. If the command is used, it will timeout if left idle for more than 5 minutes.

## Usage

1. Use /slash_command to invoke a command in a channel where the bot is present, continue to use the same command by directly messaging the bot or using @bot-name in a channel.
2. Use /slash_command again in the channel to start a new command, continue to use the same command by directly messaging the bot or using @bot-name in a channel.

## Setup

1. Configure the necessary environment variables:
   - `discord_token`: Your Discord bot's token.
   - `bot_id`: Your Discord bot's ID.
   - `help_msg`: The default help message.
2. Deploy the bot on the `flows.network` platform.
3. Invoke the desired command in your Discord server. 

Remember to keep your tokens and IDs secure to prevent any unauthorized access to your bot.