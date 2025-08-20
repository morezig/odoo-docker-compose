## Usage
```bash
$ git clone --depth=1 https://github.com/morezig/odoo-18-docker-compose
# then
$ cd odoo-18-docker-compose
$ docker-compose up -d
```


## Custom addons

The **addons/** folder contains custom addons. Just put your custom addons if you have any.


## Odoo configuration & log

* To change Odoo configuration, edit file: **etc/odoo.conf**.
* Log file: **etc/odoo-server.log**
* Default database password (**admin_passwd**) is `passw0rd123`, please change it @ [etc/odoo.conf#L60](/etc/odoo.conf#L60)