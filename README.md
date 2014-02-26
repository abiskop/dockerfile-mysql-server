###Dockerfile for *mysql-server* package.

**CAUTION, SHARP EDGES!** 
No bootstrapping will be being done, i.e. after installation, the default root account (without password) of mysql server will be active.
After installation, set a proper root password e.g. like this:
```
mysqladmin --host=localhost --user=root --password='' password 'NEW_ROOT_PASSWORD'
```

Trusted build: [abiskop/mysql-server](https://index.docker.io/u/abiskop/mysql-server/).

**Dependencies**:
- [mirkokiefer/ubuntu-base](https://github.com/mirkokiefer/dockerfile-base)
