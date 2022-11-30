# use these commands in linux env
git clone 
cd sxarbot
python3 -m venv venv
source venv/bin/activate
python3 -m pip install -r requirements.txt
# search botfather on telegram and chat
# /start 
# /newbot
# Then follow the instructions to make your bot.
# Copy the Http Token api
TG_TOKEN="PASTE_TOKEN_HERE" DB_NAME="ENTER_FILENAME.sql" python3 bot.py