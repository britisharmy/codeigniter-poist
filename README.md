# Codeigniter Poist
A simple codeigniter project making use of poist

# Install Php

```
sudo apt-get install apache2
sudo apt-get install php libapache2-mod-php php-mcrypt php-mysql
sudo /etc/init.d/apache2 restart
```

# Install Phpmyadmin

```
sudo apt-get install phpmyadmin
```

# Phpmyadmin 404 Fix

Open apache.conf using your favorite editor

```
sudo vim /etc/apache2/apache2.conf
```

Then add the following line:

```
Include /etc/phpmyadmin/apache.conf 
```

# Reload Apache

```
sudo /etc/init.d/apache2 reload
```



