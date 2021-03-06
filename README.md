
# Certbot Webmin Module

# Info
Certbot Module for Webmin.  Install and manage SSL certificates and Certbot plugins via Webmin.

# Quick Install

1. Log into Webmin
2. Go to Webmin Configuration > Webmin Modules
3. Select "From HTTP or FTP Url"
4. Enter https://github.com/cited/Certbot-Webmin-Module/blob/master/scripts/certbot.wbm.gz?raw=true
5. Click the Install button.


# Install via Script

As Root:

```bash

wget https://raw.githubusercontent.com/cited/Certbot-Webmin-Module/master/scripts/pre-install.sh

chmod +x pre-install.sh

./pre-install.sh
```

When script completes. go to Servers-> Certbot to complete installation.

# How to install from GIT
Archive module

$ git clone https://github.com/cited/Certbot-Webmin-Module

$ mv Certbot-Webmin-Module-master certbot

$ tar -cvzf certbot.wbm.gz certbot/


Upload from Webmin->Webmin Configuration->Webmin Modules

Go to Servers-> Certbott (you may need to refresh page)

# Additional
- CentOS has more Certbot plugins
- Apache vconf is not updated, after deleting a certificate!

## **Issues**
Please report issue here or at hello@acugis.com

# Certbot Links
- [Certbot User Guide](https://certbot.eff.org/docs/using.html)
- [Certbot config file](https://certbot.eff.org/docs/using.html#config-file)

Copyright
---------

* Copyright AcuGIS, 2020
* Copyright Cited, Inc., 2020
