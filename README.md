## Ansible Script to Install ODOO19
This script is to install ODOO19 on Ubuntu.
Database used is postgres.

##Sequence to run Script
1. postgres.yml (Make necessary changes in variables like system user, dbuser, dbpassword and dbname before running the script).
2. odoo19.conf file( Make necessary changes in this file before running odoo19.yml, make changes in addons_path, logfile etc.)
3. odoo19.yml ( Make changes in user_name, group and dbuser)

After completing the above steps
Hit http://<server-IP>:8069
