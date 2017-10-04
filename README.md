# Telegram mining pool statistics bot

Bot helps you retreive your farm statistics and pool balance
See configuration example in `settings.sample.ini`

# Develop
```sh
$ pipenv install -d # install venv and requirements
$ pipenv shell  # start virtualenv shell
```

# TODO
* Add travis tests and coverage
* Store state in redis
* Allow users to add own pools accounts with owner-only access
* Docker environment configuration support
* Notify when balance changed
* Add more pool interfaces `see pools module`
