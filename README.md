# ACME-Zabbix

#### Table of Contents

1. [Overview](#overview)
2. [Module Description ](#module-description)
3. [Setup ](#setup)
    * [What zabbix affects](#what-zabbix-affects)
    * [Setup requirements](#setup-requirements)
    * [Beginning with zabbix](#beginning-with-zabbix)
4. [Usage](#usage)
5. [Limitations](#limitations)

## Overview

A puppet module for install and configre zabbix agent on RHEL 6 and 7 OS.

## Module Description
It will confgure Zabbix server ip address in configuration file and keeping zabbix agent service runing.
ACME is demo company name in this SOE demo.


## Setup

### What zabbix affects

* Install zabbix-agent and zabbix-sender packages.
* Enable zabbix-agent services

### Setup Requirements **OPTIONAL**

It is tested only in RHEL 6 and 7 64bit operation system. Yum sources is configured by Satellite 6 using content view.

### Beginning with zabbix

Put in in your core build content view.

## Usage

Include this module in baseline configuration group.

## Limitations

Only for RHEL.

