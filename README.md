# **energy team** 


# Installation

Debian/Ubuntu and derivatives:
```bash
# Tested on Ubuntu 16.04
sudo apt-get update && sudo apt-get upgrade -y && sudo apt-get install git redis-server lua5.2 liblua5.2-dev lua-lgi libnotify-dev unzip tmux -y && add-apt-repository ppa:ubuntu-toolchain-r/test && sudo apt-get update && apt-get upgrade && sudo apt-get install libconfig++9v5 libstdc++6 && sudo apt autoremove
```                   
In case of errors like `version GLIBCXX_3.4.21 not defined`, download manually libstdc++6 from [here](https://packages.ubuntu.com/xenial/libstdc++6), install the package with `dpkg -i` and repeat the previous step.

If you are not able to install the bot in Ubuntu 14, an upgrade to Ubuntu 16.04 is recommended. Upgrade from terminal: `sudo do-release-upgrade`

---------------------------------

After installing the dependencies, lets install the bot:
```bash
 git clone https://github.com/telebombang2018/cerner_helper
 cd cerner_helper
 chmod +x C
 ./C install
 ./C config
 ./C login-Cli # Will ask you for a phone number & confirmation code.
 ./C login-Api
 ./C Change-Login #Changed Login
 ./C start
```
داخل پوشه

bot

فایل

bot.lua

در خط ۲۸ بجای توکن توکن ربات هلپر آفلاین ینی ای پی ای رو بزارید 

خط ۳۹ بجای ۸۵ ایدی عددی خودتون و بجای ۶۹ ایدی عددی ربات آنلایتون سی ال ای

در خط ۴۰ ایدی عددی خودتون رو بجای ۸۵ بزارید

در خط ۴۱ ایدی عددی کانالتون رو بجای ۱۳ بزارید

در خط ۴۲ ایدی عددی ربات آفلاین ای پی ای رو بزارید بجای ۹۰ 

در خط ۴۳ ایدی کانالتون رو بزارید بجای کانال 


برید داخل فایل 

api.lua 

در پوشه اصلی

در خط ۱۱ توکن ربات ررو بجای توکن بزارید

در خط ۱۹ بجای ۸۵ ایدی عددی خودتون و بجای ۶۹ ایدی عددی ربات آنلاین

در خط ۲۹۹ بجای ۸۵ ایدی عددی خودتون و بجای ۶۹ ایدی عددی ربات آنلاین ینی سی ال ای رو بزارید

بعد از همه اینا حتما سیو کنید

و کد های پایینو بزنید

----------------------
اتولانچ ربات آنلاین ینی سی ال ای


killall -9 bash

ـــــــــــــــــــــــــــ
killall screen

cd cerner_helper

chmod +x Company

screen ./Company

-----------------------------------------
روشن کردن ربات هلپر آفلاین ینی همون ای پی ای

cd cerner_helper

chmod +x api.lua

screen lua api.lua
----------------------------------------------
اتولانچ ربات آفلاین ینی ای پی ای

cd cerner_helper

chmod +x api.sh

chmod +x apiauto.sh

screen ./apiauto.sh
------------------------------------
collecting by: me

Company Channels: @richenergy

Debugging by: @sudoshell
-------------------


