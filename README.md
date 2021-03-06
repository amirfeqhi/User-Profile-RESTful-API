# RESTful API
A Django rest api for managing user profiles

[![Build Status](https://travis-ci.com/amirfeqhi/DjangoProfile.svg?branch=master)](https://travis-ci.com/amirfeqhi/DjangoProfile)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/amirfeqhi/DjangoProfile/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/amirfeqhi/DjangoProfile/?branch=master)
[![Coverage Status](https://coveralls.io/repos/github/amirfeqhi/rest-api/badge.svg?branch=master)](https://coveralls.io/github/amirfeqhi/rest-api?branch=master)
[![Code Intelligence Status](https://scrutinizer-ci.com/g/amirfeqhi/DjangoProfile/badges/code-intelligence.svg?b=master)](https://scrutinizer-ci.com/code-intelligence)

![Django restapi](http://www.django-rest-framework.org/img/logo.png)

## How to use
* **Attention:** It's a good practice to run your code on a virtual server like Vagrant

### Requirements
1. Vagrant (for more information -> [Vagrant website](https://www.vagrantup.com/))
2. VirtualBox
2. Django Version 1.11.1
3. Django rest framework library Version 3.6.2

### Usage
* Setup And Config Vagrant

  1. `$ vagrant init`

  2. `$ vagrant up`

  3. `$ vagrant ssh`

* Create a virtual-environment on Vagrant

  1. `$ virtualenv "venv_name" --python=python3`
  2. `$ source "venv_name/bin/activate"`

  **Note:** Enter `$ deactivate` for exit from venv

* Run server on vagrant for testing

  1. `$ python manage.py runserver 0.0.0.0:8080`
