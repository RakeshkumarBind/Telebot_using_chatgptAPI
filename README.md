# Telebot_using_chatgptAPI

Basic commands : /n

Creating a environment : conda create -n telebot python=3.8 -y /n
Activating the environment : conda activate telebot /n

Install the requirements : /n
pip install -r requirements.txt /n

Cloning the github repository: /n
git clone https://github.com/RakeshkumarBind/Telebot_using_chatgptAPI.git /n

Create .env file to add your secret key : /n
OpenAI_API_KEY =" Paste here the key generated from OpenAI" /n

In Telegram : Search for BotFATHER  /n
       1. Start /n
       2./newbot /n
       3.copy the token and paste it to .env by the name of token /n

why skip_updates=False at the end of the telebot.py program? /n
Whenever the user inputs the query and the bot is offline than whenever the bot comes online then the bot will gwnerate the response and show. /n
But if True than it will not generate the response when it will come online. /n


GITHUB COMMAND FOR COMMIT AND PUSH : /n
git add . /n
git commit -m "your commit message" /n
git push origin main /n
