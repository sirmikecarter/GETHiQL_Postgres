# GETHiQL postgres schema

## how to install (mac)
* `brew install psql`
* `./initdb.sh`
* `psql gethiql_db` to start the psql shell

# how to install (Ubuntu)

sudo apt-get update
sudo apt-get install postgresql postgresql-contrib

## Switch to postgres account

sudo -i -u postgres

## Clone GitHub

git clone https://github.com/anthonyvmai/GETHiQL_Postgres.git

## View Directory

cd GETHiQL_Postgres

## Run Script

./initdb.sh

## Start Shell

psql gethiql_db

## View Tables

\dt
