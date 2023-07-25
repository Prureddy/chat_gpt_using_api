Creating your own chatgpt using ChatGPT api key
# ChatGPT Application

This is a simple Node.js application that utilizes the ChatGPT API to create a chat-based interface with the GPT-3.5-turbo model provided by OpenAI.

## Setup

1. Clone this repository.

2. Install dependencies:

```
npm install
Create a .env file in the root directory and add your OpenAI API key:
makefile
Copy code
OPEN_AI_API_KEY=YOUR_OPENAI_API_KEY_HERE
```
## Run the application:
```
node chat_gpt_using_api.js
```
## Usage

### The application will prompt you to enter a message, and it will respond with a generated message using the GPT-3.5-turbo model. Type "exit" to quit the application.

## Requirements
```
Node.js (v14 or higher)
Dependencies
dotenv
openai
readline
```
## License
```
This project is licensed under the MIT License - see the LICENSE file for details.
```

Please make sure to replace `YOUR_OPENAI_API_KEY_HERE` with your actual ChatGPT API key in the `.env` file.

