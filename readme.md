# SQL Basics



### From the command line


To install postgresql via Homebrew - 

```
brew install postgresql
```

Check which version of postgresql is installed - 

```
postgres -V
```

To access the `psql` command line - 

```
psql postgres
```

To see what users are installed in postgresql- 

```
postgres=# \du
```

To create a new user (postgresql calls this a "role") - 

```
CREATE ROLE username WITH LOGIN PASSWORD 'quoted password' [OPTIONS]
```

To display list of users - 

```
\du
```