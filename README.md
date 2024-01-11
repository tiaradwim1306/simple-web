# Simple Website Using Github Pages
Make a simple HTML website and publish it using Github Pages.  

## Setup Website
Step 1: Download Source Code

    git clone https://github.com/tiaradwim1306/simple-web 

Step 2: edit file 000-default.conf
```sh                                                                                 
<VirtualHost *:80>

        ..................

        ServerAdmin webmaster@localhost
        DocumentRoot /var/www/html

        ..................


</VirtualHost>
```

Step 3: Restart apache2 

    systemctl restart apache2

Step 4: Access web server

    http://ip_address_server/  
