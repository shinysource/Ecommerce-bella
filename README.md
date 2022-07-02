## Introduction to e-commerce system

This online shopping platform is powered by Laravel 5.4. in development on the version.

## Server specification

PHP >= 5.6.4
MySQL >= 5.7
OpenSSL PHP Extension
PDO PHP Extension
Mbstring PHP Extension
Tokenizer PHP Extension
XML PHP Extension


<a name="installation"></a>
## Install

Clone this project by running the following command:

```
git clone https://github.com/tortuvshin/ecommerce.git
```

Download and install Composer

```
[Get Composer](https://getcomposer.org/download/)
```

Next, go to the downloaded folder and run the composer update/install command

```
composer install
```

Download and install Nodejs

```
https://nodejs.org/en/download/
```

Download NPM libraries
```
npm install
```

## Adjust

Next, modify the .env-example file to .env to configure your database and server

After creating and configuring the database, create the tables with the following command:

```
php artisan migrate
```

Enter the test data with the following command:

```
php artisan db:seed
```

```
php artisan key: generate
```

Add the required libraries for frontend development with the following command:

```
bower installation
```

Get reChaptcha code:

```
https://www.google.com/recaptcha/admin#list
```

```
RECAPTCHA_PUBLIC_KEY, and RECAPTCHA_PRIVATE_KEY
```

Paste your reCaptcha codes into the .env file. For example:

```
RECAPTCHA_PUBLIC_KEY = ModuRecaptchaPublicKeyObtained

RECAPTCHA_PRIVATE_KEY = ModuRecaptchaPrivateKeyObtained
```

***Note:*** reCaptcha will not be used when ```APP_DEBUG == true``` or debug is on



Install NPM libraries:

```
npm install
```

If you are developing using the Windows operating system and VM, run the following command:
```
npm install --no-bin-links
```

Using Laravel Mix

```
npm run dev
```

Test user information

Username: admin@admin.com
Password: admin


[NODEJS]: https://nodejs.org/en/download/
[COMPOSER]: https://getcomposer.org/download/
[RECAPTCHA]: https://www.google.com/recaptcha/admin#list
