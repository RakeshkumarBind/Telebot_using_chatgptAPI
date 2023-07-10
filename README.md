# Telebot_using_chatgptAPI

Basic commands : <br>

Creating a environment : conda create -n telebot python=3.8 -y <br>
Activating the environment : conda activate telebot <br>

Install the requirements : <br>
pip install -r requirements.txt <br>

Cloning the github repository: <br>
git clone https://github.com/RakeshkumarBind/Telebot_using_chatgptAPI.git <br>

Create .env file to add your secret key : <br>
OpenAI_API_KEY =" Paste here the key generated from OpenAI" <br>

In Telegram : Search for BotFATHER  <br>
       1. Start <br>
       2./newbot <br>
       3.copy the token and paste it to .env by the name of token <br>

Why skip_updates=False at the end of the telebot.py program? <br>
  Whenever the user inputs the query and the bot is offline than whenever the bot comes online then the bot will gwnerate the response and show.<br>
But if True than it will not generate the response when it will come online.<br>


GITHUB COMMAND FOR COMMIT AND PUSH : <br>
git add . <br>
git commit -m "your commit message" <br>
git push origin main <br>
