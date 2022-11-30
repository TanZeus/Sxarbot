# INITIAL Installation
```
id- root
pass- toor
sudo apt-get update && apt-get upgrade
sudo apt install python3.9.14
sudo apt install pip
pip install venv
sudo apt-get install python-venv

```
```
no module found - pip install <module name>
```
# Use these commands in linux environment.
```
git clone https://github.com/TanZeus/Sxarbot.git
cd sxarbot
python3 -m venv venv
source venv/bin/activate
python3 -m pip install -r requirements.txt
python3 create_db.py <DB_FILENAME>.sql
```
## Search botfather on telegram and chat
```
/start 
/newbot
```
### Then follow the instructions to make your bot. Copy the Http Token api.
## Starting Bot -
```
TG_TOKEN="<PASTE_TOKEN_HERE>" DB_NAME="<DB_FILENAME>.sql" python3 bot.py 
```

## Presenting Time
```
cd Sxarbot
python3.9 -m venv venv
source venv/bin/activate
TG_TOKEN="<PASTE_TOKEN_HERE>" DB_NAME="<DB_FILENAME>.sql" python3.9 bot.py 
```
