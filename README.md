# rancher-wamp
How my own website is setup to run on multiple machines

# docker-compose.yml
Everything for Rancher is defined here.

Find and replace `pbknet22` with your own project name

# PHP/Apache

PHP is running v8.1

modrewrite is active

mysqli module is active

# Ports

Find and replace ports as needed

|Port|Exposed|
|---|---|
|8921|Web interface pointing at the contents of the `www` folder|
|8923|PHPmyAdmin|
