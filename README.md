


## Laravel passport

What is Passport? APIs typically use tokens to authenticate users and do not maintain session state between requests. Laravel makes API authentication a breeze using Laravel Passport, which provides a full OAuth2 server implementation for your Laravel application development in a matter of minutes.

## You have to just follow a few steps to get following web services

- Login API
- Register API
- Details API




## Getting Started

## Step 1: Install Package

composer require laravel/passport

## open config/app.php file and add service provider.

#### config/app.php

'providers' =>[
Laravel\Passport\PassportServiceProvider::class,
],

### Step 2: Run Migration and Install

- php artisan migrate
- php artisan passport:install

## Step 3: Passport Configuration app/User.php


## Step 4 :config/auth.php


##  Create API Route

## Step 6: Create the Controller

## Step 6: Run

php artisan serve

