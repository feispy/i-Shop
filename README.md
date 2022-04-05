# i-Shop
  Telegram bot with books for upgrading soft skills.
### 1. Installation

```sh
$ git clone https://github.com/feispy/i-Shop.git
$ cd i-Shop
$ pip install -r requirements.txt
```
- Open ```bot.py``` file and change variable ```token``` (create a bot using @BotFather, and get the Telegram API token.). And change ```admin_id``` - your chat_id.
- Open ```database.py``` file and change variable ```DATABASE_URL``` (if you need using database).
This project uses a database ```Postgresql```, but you can choose another by changing the variable ```engine```.

- Run
    ```
    python main.py
    ```
