# Profiles App API

![recipe-app-api](./images/image1.jpg)

[![Build Status](https://travis-ci.org/masoudr/profiles-app-api.svg?branch=master)](https://travis-ci.org/masoudr/profiles-app-api)

This is a Profile RESTful API written with Django and Django REST framework built over Docker.

This project is a sample app that can be used for other projects.

## Features

A REST API that supports the following:

* Custom User Model
* Creating new profiles.
* Logging in with a profile.
* Adding profile status updates.
* Viewing users profile fields.
* Searching for users profiles.

## Usage

To start project, run:

```shell
cd <project_dir>
docker-compose build
docker-compose up
```

The API will be available at [http://127.0.0.1:8000](http://127.0.0.1:8000)
