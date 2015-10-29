# vagrant-symfony
A vagrant machine with necessary tools for run a symfony2 project

# Use it!

If you have a symfony2 project to run you can use this vagrant machine to execute it.

## How?

* Copy this two files (vagrantfile and provision.sh) to your symfony2 project root folder.
* At your symfony2 project root folder execute `vagrant up`
* When finish execute 'vagrant ssh'
* cd /vagrant
* app/console server:start 0.0.0.0:8000
* From you host machine, go to 10.10.10.10:8000
* You can see you project run!

If you nedd a DB for your project, you can use a postgreSQL from this vagrant machine:
* database_host: 127.0.0.1
* database_port: null
* database_name: hexagonal
* database_user: dbuser
* database_password: db-user
* mailer_transport: smtp
* mailer_host: 127.0.0.1
* mailer_user: null
* mailer_password: null
* secret: anysecretyouwant
* database_driver: pdo_pgsql
* database_path: null
