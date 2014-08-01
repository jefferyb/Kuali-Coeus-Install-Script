# Overview

This script is meant to automate the various steps involved in installing Kuali Coeus Bundle with MySQL Server, with very minimum settings in the kc-config.xml file for testing... You can expand on it once you have it up and running...

**_Warning:_** _This will overwrite your MySQL config file(my.cnf), so if you already have one configured the way you like, make a backup before running the script..._

I've tested it on a fresh Ubuntu Server 14.04 and a CentOS release 6.5 and 7... 

## What's new?

* Install of KC 5.2.1
* Install MySQL/MariaDB if not installed

## Getting Started

1. git clone git://github.com/jefferyb/install_kuali_coeus_bundle.git
2. cd install_kuali_coeus_bundle
3. run ./install_kuali_coeus as root

## Documentation

I just created this to document, http://goo.gl/EdOSxW, my process of how I got my KC up and running and hopefully will help someone else looking for a simple, easy & quick installation guide...

http://goo.gl/EdOSxW

You can find the more comprehensive documentation from kuali here http://goo.gl/dxrXkq
