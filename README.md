<p align="center">
    <a href="https://github.com/yiisoft" target="_blank">
        <img src="https://avatars0.githubusercontent.com/u/993323" height="100px">
    </a>
    <h1 align="center">Yii2 Advanced Template</h1>
    <br>
</p>

Yii 2 Advanced Project Template is a skeleton [Yii 2](http://www.yiiframework.com/) application best for
developing complex Web applications with multiple tiers.

The template includes three tiers: front end, back end, and console, each of which
is a separate Yii application.

The template is designed to work in a team development environment. It supports
deploying the application in different environments.

Documentation is at [docs/guide/README.md](docs/guide/README.md).

[![Latest Stable Version](https://img.shields.io/packagist/v/yiisoft/yii2-app-advanced.svg)](https://packagist.org/packages/yiisoft/yii2-app-advanced)
[![Total Downloads](https://img.shields.io/packagist/dt/yiisoft/yii2-app-advanced.svg)](https://packagist.org/packages/yiisoft/yii2-app-advanced)
[![Build Status](https://travis-ci.org/yiisoft/yii2-app-advanced.svg?branch=master)](https://travis-ci.org/yiisoft/yii2-app-advanced)

## PREREQUISITES
Before we start to build our own application, firstly we should have web server and IDE in our local device.

**Web Server**

There are some excellent all-in-one Windows distributions that contain Apache, PHP, MySQL and other applications in a single installation file, e.g. **XAMPP (including a Mac version)**, **WampServer** and **Web.Developer**. In here I used **XAMPP** as Web Server.

**IDE**

There are some excellent IDE for PHP such as NetBeans, Notepad++, and Sublime Text 3, but for me NetBeans is the most popular IDE for development. NetBeans editor provides many pre-configured code templates and code generation tools for faster development support, and In her I used **NetBeans** for IDE.

**COMPOSER**

Composer is a dependency manager for PHP. It solves the following problems:
- Dependency resolution for PHP packages,
- Autoloading solution for PHP packages,
- Keeping all packages updated.


DOWNLOAD:

- XAMPP-7.3.3-1 [_Download_](bit.ly/2InGmvO) for Windows x64    
- NetBeans-11.0 [_Download_](https://pages.github.com/)
- Composer [_Download_](http://bit.ly/2Kp6Y24)

## INSTALLATION
After install all tools above, now we install the Yii2 project, there are 2 ways to do it.

### Install via Composer (recommended)
Get in to your local web server directory, for example: `C:\xampp\htdocs` and then run **_CMD_**.

Run this following command
> php composer.phar create-project yiisoft/yii2-app-advanced advanced

### Install from an Archive File

Download the following archive file, and then extract it to your local web server directory, for example: `C:\xampp\htdocs`.
- Yii2 Advanced Template [_Download as ZIP_](http://bit.ly/2Ge50xh), [_Download as TAR.GZ_](http://bit.ly/2Z4e27F)

## CONFIGURATION

Yii2 Advanced Template has two environment(_Development_ and _Production_), each of them has different configuration. So you should initialized your project environment in here.

### Initialized Environment
Run **_CMD_** inside your project directory, and run this following command
> php init

The following command will create your configuration file

### Create Database
In here I used XAMPP GUI for database, we can access it from `http://localhost/phpmyadmin/`.

Then set your database configuration in `main-local.php`
FILE LOCATION:
```
- apps
   - common
      - config
         - main-local.php //here is the file
```
