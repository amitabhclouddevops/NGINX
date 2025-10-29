# NGINX

NGINX is a powerhouse! It's one of the most popular web servers and reverse proxies in the DevOps world, powering millions of websites for incredible speed, scalability, and reliability. 🌐
Here are the essential commands every cloud or DevOps engineer absolutely needs to master! 👇


🔹 Installation & Setup
 sudo apt update → Update system packages
 sudo apt install nginx → Install NGINX web server
 nginx -v → Check installed version
 nginx -t → Test configuration syntax for errors

🔹 Service Management
 sudo systemctl start nginx → Start NGINX service
 sudo systemctl stop nginx → Stop NGINX service
 sudo systemctl restart nginx → Restart NGINX after changes
 sudo systemctl reload nginx → Reload configuration without downtime
 sudo systemctl status nginx → View current service status

🔹 Enable/Disable on Boot
 sudo systemctl enable nginx → Enable NGINX to start on boot
 sudo systemctl disable nginx → Disable auto-start on boot

🔹 Configuration & Site Management
 sudo nano /etc/nginx/nginx.conf → Edit main config file
 sudo nano /etc/nginx/sites-available/default → Edit default site config
 sudo ln -s /etc/nginx/sites-available/<site> /etc/nginx/sites-enabled/ → Enable a site
 sudo rm /etc/nginx/sites-enabled/<site> → Disable a site

🔹 Logs & Signals
 sudo tail -f /var/log/nginx/access.log → Monitor live access logs
 sudo tail -f /var/log/nginx/error.log → Monitor live error logs
 sudo nginx -s reload → Gracefully reload configuration
 sudo nginx -s stop → Stop NGINX immediately
 sudo nginx -s quit → Stop NGINX gracefully

💡 Pro-Tip: Always run nginx -t before reloading! Testing your config syntax first is a lifesaver and will protect your production environment from unnecessary downtime. 🛡️
hashtag#NGINX hashtag#DevOps hashtag#Linux hashtag#WebServer hashtag#CloudComputing hashtag#SysAdmin hashtag#ServerManagement ☁️🛠️
