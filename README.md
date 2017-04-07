# SyntaxedCore Installer
## Script installation instructions:
### Make sure you have the following installed...
- PHP7.x
- WGET

To install PHP7.x:
`sudo apt-get install python-software-properties`
`sudo add-apt-repository ppa:ondrej/php-7.0`
`sudo apt-get update`
**If you have PHP5 installed (check with `php -v`)**: `sudo apt-get purge php5-fpm`
`sudo apt-get install php7.0-cli php7.0 php7.0-common`

To install WGET:
`sudo apt-get install wget`
`sudo apt-get update`

### Now, to install and run the script...
Move to the directory you want to run your server on. (e.g., `cd /servers/myserver/`)

Install the script:
`wget https://raw.githubusercontent.com/Syntaxed-Inc/SyntaxedCore-Installer/master/./installer.sh`

Give our script the correct permissions:

`chmod 777 installer.sh`

Finally, run the script:
`./installer.sh`


