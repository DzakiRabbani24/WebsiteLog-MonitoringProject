README: Loki, Promtail, and Website Setup

LOKI
Copy the file loki/config.yaml to the directory:
/etc/loki/config.yaml
Make sure Loki is running using this configuration file:
loki --config.file=/etc/loki/config.yaml

==================================================

PROMTAIL
Copy the file promtail/config.yaml to the directory:
/etc/promtail/config.yaml
Make sure Promtail is running using this configuration file:
promtail --config.file=/etc/promtail/config.yaml

==================================================

WEBSITE
Copy all files from the website/ folder to the web server root directory:
/var/www/html/
Make sure the latest version of PHP is installed on your system.