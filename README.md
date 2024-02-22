# About
Nginxlog is a Nginx Access log viewer/visualizer written in PHP, with a MySQL database to store the data once it is extracted from the log file.  
<hr />
# Requirements
Nginx Server <br />
PHP 8+ <br />
MySQL Database <br />
Ipinfo.io API Key
<hr />
# Install
Download the code, update the config files with the database login details & API key.
<hr />
# Additional Setup
Add code to nginx.conf to modify what is stored in the log file, and where the log file is.<br />
If you have cloudflare or another proxy, you will need to modify nginx.conf to use the correct IP address.<br />
Create cronjob to run script nightly to extract previous days data from the log files into the database.
