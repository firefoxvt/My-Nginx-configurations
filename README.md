# Nginx configrations for your business.

Requirements
---
### Must use Nginx.
- I highly recommend use [Webinoly](https://github.com/QROkes/webinoly) script to setup Nginx properly for Ubuntu ONLY.
- And CentMinMod for CentOS 7.
### Rocket Nginx for serving better HTML static files.
Rocket Nginx is [here](https://github.com/maximejobin/rocket-nginx).
### Notes: Rocket Nginx has some incompatible with Rocket Loader of Cloudflare.
- Uncomment Cloudflare configuration line in Nginx configuration of domain.
- If the header send is "x-rocket-nginx-serving-static: Yes", everything is ok. If it does not, PLEASE disable Rocket Loader first and then purge cache in Cloudflare dashboard, then check again the header.

Documentation for Webinoly
---
For complete documentation, please visit [this site](https://webinoly.com/en/).

This repository contains
---
#nginx-odoo-https.conf

The file contains Nginx configuration file for Odoo v11 with Letsencrypt. Of course, it has the reverse proxy.

=
