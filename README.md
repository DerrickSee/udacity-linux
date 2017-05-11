# udacity-linux

## Project Information

IP Address: 54.243.16.175

Port: 2200

url: http://54.243.16.175/

## Software Installed and Configurations Made

1. apache2 & libapache2-mod-wsgi
  * Added /etc/apache2/sites-available/catalog-app.conf with config for flask application
  * Added catalog.wsgi in app
2. postgresql
  * Created DB user catalog, giving it all privileges to DB catalog
3. NodeJS & NPM to install bower
4. virtualenv to create local environment. (Updated catalog-app.conf to point python path towards virtualenv)
5. Deny all incoming port connections except SSH (port 2200), HTTP (port 80), and NTP (port 123).

## Third Party Resources

All third party resources can be found in requirements.txt.
