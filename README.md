# Piggy metrics Local Host Version

## Overview
A local deployed version of piggymetrics (https://github.com/sqshq/piggymetrics) without using docker.
Guided by https://www.yuanqingfei.com/2021-12-27%20%E5%AD%A6%E4%B9%A0Spring%20Cloud%E4%B9%8B%E6%9C%AC%E5%9C%B0%E9%83%A8%E7%BD%B2/ .

## How to run
You can run this microservice project by simply git clone the repository then right click on its folder and select "Open Folder as IntelliJ IDEA Project". IDEA will automatically recognize this as a microservice project and use relevant supporting services.
Noted that there are dependencies between the 8 separated microservice modules, make sure to open *AuthApplication* module and *GatewayApplication* module **AFTER** you launched all other applications. Or you'll face some dependency problems.
