# idea-bot
Beautiful telegram bot that can save ideas for you and your friends

## Setting up
### Python 
You need to install psycopg2
```
    pip3 install psycopg2
```
You need to install aiogram
```
    pip3 install aiogram
```

### PostgreSQL
You should have [PostgreSQL](https://www.postgresql.org/) installed on your machine. 

Then you need to configure it and add new database.

In the directory of the project you need to create **config.json** file in configs folder. You can use config_template.json as an example. 

Then you need to run **create_table.py**
