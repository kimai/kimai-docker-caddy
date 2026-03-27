# kimai-docker-caddy

Get up and running with Kimai on the following platforms:

* [Hetzner Cloud](https://www.kimai.org/documentation/hosting-hetzner-cloud.html)
* [Digital Ocean](https://www.kimai.org/documentation/hosting-digital-ocean.html)

If you have questions after trying the tutorials, check out the [forums](https://github.com/kimai/kimai/discussions).

## Prerequisites

Self-hosting Kimai requires technical knowledge, including:

* Setting up and configuring servers and containers
* Managing application resources and scaling
* Securing servers and applications
* Configuring Kimai

Kimai recommends self-hosting for expert users. 
Mistakes can lead to data loss, security issues, and downtime. 
If you aren't experienced at managing servers, Kimai recommends [Kimai Cloud](https://www.kimai.org/).

## Install plugins

Extract Kimai plugin ZIPs into the `kimai_plugins/` directory, 
e.g. `kimai_plugins/WorkContractBundle/`, 
then run `docker compose exec kimai /opt/kimai/bin/console kimai:bundle:workcontract:install`  
