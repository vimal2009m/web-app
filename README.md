# Ansible Sample WebApp

# Simple Web Application

This is a simple web application using [Python Flask][df1] and [MySQL][df1] database. This is used in the demonstration of development of Ansible Playbooks.

Below are the steps required to get this working on a base linux system.

* Install all required dependencies
* Install and Configure Database
* Start Database Service
* Install and Configure Web Server
* Start Web Server
# 1. Install all required dependencies
*Python and its dependencies*
```sh
apt-get install -y python python-setuptools python-dev build-essential python-pip python-mysqldb
```
# 2. Install and Configure Database
Install MySQL database
```sh
apt-get install -y mysql-server mysql-client
```


