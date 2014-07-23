# Overview

This script is meant to automate the various steps involved in installing Kuali Coeus Bundle with MySQL Server, with very minimum settings in the kc-config.xml file for testing... You can expand on it once you have it up and running...

**_Warning:_** _This will overwrite your MySQL config file(my.cnf), so if you already have one configured the way you like, make a backup before running the script..._

I've tested it on a fresh Ubuntu Server 14.04 and a CentOS release 6.5... 

## Getting Started

1. Make sure MySQL Server is installed and have root access
2. Download the zip file & unzip it or use git
3. Run install_kuali_coeus as root
