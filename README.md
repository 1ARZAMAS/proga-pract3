# proga-pract3
The directories contain user functions, triggers for postgresql

Instructions:
sudo apt install pgadmin4-web
sudo /usr/pgadmin4/bin/setup-web.sh
sudo a2enconf pgadmin4
sudo systemctl restart apache2

if still not working:
sudo -u www-data /usr/pgadmin4/venv/bin/python /usr/pgadmin4/web/pgAdmin4.py