Apache2
=======


What is does this role do?
--------------------------

This role installs Apache2.


Meta
----

Files Managed:
  * /etc/iptables.d/apache2.rules
  * /etc/httpd/httpd.conf
  * /etc/httpd/sites-eabled/default
  * /var/service/httpd

Defaults Provided:
  * apache_ServerAdmin: Systems Administrator

Variables Required:
  * None

Optional Variables:
  * apache_ServerAdmin: The name or title of the webserver's administrator.

Files Required:
  * None

Optional Files:
  * None

Conflicting Roles:
  * None

Depends On:
  * [network](https://github.com/void-ansible-roles/network)
