# i-Shop
  Online store on Python
### 1. Installation

```bash
$ git clone https://github.com/feispy/i-Shop.git
$ cd i-Shop
$ pip install -r requirements.txt
```
- Open ```bot.py``` file and change variable ```token``` (create a bot using @BotFather, and get the Telegram API token.). And change ```admin_id``` - your chat_id.
- Open ```database.py``` file and change variable ```DATABASE_URL``` (if you need using database).
This project uses a database ```Postgresql```, but you can choose another by changing the variable ```engine```.


### 2. Running The App

```bash
python main.py
```

### 3. Viewing The App

Go to `http://127.0.0.1:5000`
