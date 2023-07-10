# Telebot_using_chatgptAPI

Basic commands : 

Creating a environment : conda create -n telebot python=3.8 -y
Activating the environment : conda activate telebot

Install the requirements :
pip install -r requirements.txt

Cloning the github repository:
git clone https://github.com/RakeshkumarBind/Telebot_using_chatgptAPI.git

Create .env file to add your secret key :
OpenAI_API_KEY =" Paste here the key generated from OpenAI"

In Telegram : Search for BotFATHER  
       1. Start
       2./newbot
       3.copy the token and paste it to .env by the name of token

why skip_updates=False at the end of the telebot.py program?
Whenever the user inputs the query and the bot is offline than whenever the bot comes online then the bot will gwnerate the response and show.
But if True than it will not generate the response when it will come online.


GITHUB COMMAND FOR COMMIT AND PUSH :
git add .
git commit -m "your commit message"
git push origin main
