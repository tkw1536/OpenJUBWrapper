# What is it?

A wrapper around [OpenJUB](https://github.com/OpenJUB/openjub-api). Still a work in progress.

# How to install?

1. Make sure you have MongoDB, Node.JS and Git installed. Make sure the ```node``` command starts Node.JS and ```npm``` is available.
2. Edit settings in jub_config.json. Leave the "database" untouched.
3. Install the script. Make sure you are on Campus while doing this.
```
scripts/install
```

# How to use?

 1. To start: Run "scripts/start"
 2. To stop: Run "scripts/stop"
 3. To sync: Run "scripts/sync"
 4. To create a new token: Run "scripts/token"

* The actual installation of the openjub-api can be found under data/repo.
* Logs can be found in "data/jublog" and "data/dblog".

# License

MIT License, see LICENSE file.
