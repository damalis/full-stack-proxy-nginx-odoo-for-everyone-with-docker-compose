# [full stack proxy nginx Odoo for everyone with docker compose](https://github.com/damalis/full-stack-proxy-nginx-odoo-for-everyone-with-docker-compose)

If You want to install Odoo at short time;

#### Full stack Proxy Nginx Odoo:
<p align="left">
<a href="https://www.odoo.com/" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/6368483?s=200&v=4" alt="odoo" height="40" width="40"/> </a>&nbsp;&nbsp;&nbsp; 
<a href="https://www.docker.com/" target="_blank" rel="noreferrer" style="text-decoration: none;"> <img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/docker/docker.png" alt="docker" width="40" height="40" width="40"/> </a>&nbsp;&nbsp;&nbsp; 
<a href="https://github.com/mailhog" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/10258541?s=200&v=4" alt="mailhog" height="40" width="40"/> </a>&nbsp;&nbsp;&nbsp; 
<a href="https://www.postgresql.org/" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/177543?s=200&v=4" alt="postgresql" height="40" width="40"/> </a>&nbsp;&nbsp;&nbsp; 
<a href="https://www.pgadmin.org/" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/113517144?s=200&v=4" alt="pgadmin" height="40" width="40"/> </a>&nbsp;&nbsp;&nbsp; 
<a href="https://www.nginx.com" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/1412239?s=200&v=4" alt="nginx" height="40" width="40"/> </a>&nbsp;&nbsp;&nbsp; 
<a href="https://en.wikipedia.org/wiki/Bash_(Unix_shell)" target="_blank" rel="noreferrer" style="text-decoration: none;"> <img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/bash/bash.png" alt="Bash" height="50" width="50" style="max-width: 100%;"> </a>&nbsp;&nbsp;&nbsp; 
<a href="https://letsencrypt.org/" target="_blank" rel="noreferrer" style="text-decoration: none;"> <img src="https://avatars.githubusercontent.com/u/9289019?s=200&v=4" alt="letsencrypt" height="40" width="40"/> </a>&nbsp;&nbsp;&nbsp; 
<a href="https://certbot.eff.org/" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/17889013?s=200&v=4" alt="certbot" height="40" width="40"/> </a>&nbsp;&nbsp;&nbsp; 
<a href="https://www.offen.dev/" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/47735043?s=200&v=4" alt="backup" height="35" width="35"/> </a>
</p>

Plus, manage docker containers with Portainer.

#### Supported CPU architectures:
<p align="left"> arm64/aarch64, x86-64 </p>

#### Supported Linux Package Manage Systems:
<p align="left"> apk, dnf, yum, apt/apt-get/dpkg, zypper, pacman </p>

#### Supported Linux Distributions:
<p align="left"> centos, debian, fedora, raspbian, rhel, sles, static, ubuntu </p>
 
#### Supported Linux Operation Systems:
<p align="left">
<a href="https://alpinelinux.org/" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/7600810?s=200&v=4" alt="alpine linux" height="40" width="40"/> </a>&nbsp;&nbsp;&nbsp; 
<a href="https://fedoraproject.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/github/explore/e6b1e7f0fb8d0bf920bd719c7289243138bdc1b4/topics/fedora/fedora.png" alt="fedora" height="40" width="40"/> </a>&nbsp;&nbsp;&nbsp; 
<a href="https://www.centos.org/" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/79192?s=200&v=4" alt="centos" height="40" width="40"/> </a>&nbsp;&nbsp;&nbsp; 
<a href="https://www.debian.org/" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/1854028?s=200&v=4" alt="debian" height="40" width="40"/> </a>&nbsp;&nbsp;&nbsp; 
<a href="https://ubuntu.com/" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/4604537?s=200&v=4" alt="ubuntu" height="40" width="40"/> </a>&nbsp;&nbsp;&nbsp; 
<a href="https://www.raspberrypi.com/" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/1294177?s=200&v=4" alt="ubuntu" height="40" width="40"/> </a>&nbsp;&nbsp;&nbsp; 
<a href="https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/33972111?s=200&v=4" alt="redhat on s390x (IBM Z)" height="40" width="40"/> </a>&nbsp;&nbsp;&nbsp; 
<a href="https://www.suse.com/products/server/" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/623819?s=200&v=4" alt="opensuse on s390x (IBM Z)" height="40" width="40"/> </a>&nbsp;&nbsp;&nbsp; 
<a href="https://archlinux.org/" target="_blank" rel="noreferrer"> <img src="https://gitlab.archlinux.org/uploads/-/system/group/avatar/23/iconfinder_archlinux_386451.png?width=48" alt="arch linux" height="40" width="40"/> </a>
</p>

##### Note: Fedora 37, 39 and alpine linux x86-64 compatible, could not try sles IBM Z s390x, rhel IBM Z s390x and raspberrypi.
##### After installing the repository, a system reboot is required on Red Hat OS, Arch Linux.
																																																												  
#### With this project you can quickly run the following:

- [Odoo](https://hub.docker.com/_/odoo)
- [mailhog](https://github.com/mailhog)
- [postgreSQL](https://hub.docker.com/_/postgres)
- [pgAdmin](https://hub.docker.com/r/dpage/pgadmin4)
- [proxy (nginx)](https://hub.docker.com/_/nginx)
- [certbot (letsencrypt)](https://hub.docker.com/r/certbot/certbot)
- [backup](https://hub.docker.com/r/offen/docker-volume-backup)

#### For certbot (letsencrypt) certificate:

- [Set DNS configuration of your domain name](https://support.google.com/a/answer/48090?hl=en)

#### IPv4/IPv6 Firewall
Create rules to open ports to the internet, or to a specific IPv4 address or range.

- http: 80
- https: 443
- portainer: 9001
- pgadmin: 9090

#### Requirements, These CPU, memory and storage requirements apply to a host with 10 users installation of Odoo

| Deployment Size | vCPUs | RAM | Storage |
|---|---|---|---|
| Small | Up to 2 | Up to 4 GB | 20 GB |
| Medium | Up to 4 | Up to 6 GB | 30 GB |

#### Contents:

- [Auto Configuration and Installation](#automatic)
- [Manual Configuration and Installation](#manual)
	- [Requirements](#requirements)
	- [Configuration](#configuration)
	- [Installation](#installation)
- [Usage](#usage)
	- [Odoo](#odoo)
	- [Mail](#mail)
	- [Database](#database)
	- [pgAdmin](#pgadmin)
	- [Proxy](#proxy)
    - [backup](#backup)

### Automatic

#### Exec install shell script for auto installation and configuration

download with

```
git clone https://github.com/damalis/full-stack-proxy-nginx-odoo-for-everyone-with-docker-compose.git
```

Open a terminal and `cd` to the folder in which `docker-compose.yml` is saved and run:

```
cd full-stack-proxy-nginx-odoo-for-everyone-with-docker-compose
chmod +x install.sh
sudo LC_ALL=C.UTF-8 ./install.sh # LC_ALL=C.UTF-8 if not os language english
```

### Manual

#### Requirements

Make sure you have the latest versions of **Docker** and **Docker Compose** installed on your machine and require up to 2 GB of RAM.

- [How install docker](https://docs.docker.com/engine/install/)
- [How install docker compose](https://docs.docker.com/compose/install/)

Clone this repository or copy the files from this repository into a new folder.

Make sure to [add your user to the `docker` group](https://docs.docker.com/install/linux/linux-postinstall/#manage-docker-as-a-non-root-user).

#### Configuration
				 
download with
```
git clone https://github.com/damalis/full-stack-proxy-nginx-odoo-for-everyone-with-docker-compose.git
```

Open a terminal and `cd` to the folder in which `docker-compose.yml` is saved and run:

```
cd full-stack-proxy-nginx-odoo-for-everyone-with-docker-compose
```

Copy the example environment into `.env`

```
cp env.example .env
```

Edit the `.env` file to change values of

|```LOCAL_TIMEZONE```|```DOMAIN_NAME```|```DIRECTORY_PATH```|```LETSENCRYPT_EMAIL```|
|```DB_USER```|```DB_PASSWORD```|```DB_NAME```|```PGA_CONTROLPASS```|```SSL_SNIPPET```|

<table><thead>
  <tr>
    <th>Variable </th>
    <th colspan="2">Value</th>
  </tr></thead>
<tbody>
  <tr>
    <td><code>LOCAL_TIMEZONE</code></td>
    <td colspan="2"><code><a href="https://en.wikipedia.org/wiki/List_of_tz_database_time_zones#List" rel="nofollow">to see local timezones</a></code></td>
  </tr>
  <tr>
    <td><code>DIRECTORY_PATH</code></td>
    <td colspan="2"><code>pwd</code> at command line</td>
  </tr>
  <tr>
    <td rowspan="2"><code>SSL_SNIPPET</code></td>
    <td>localhost</td>
    <td><code>echo 'Generated Self-signed SSL Certificate at localhost'</code></td>
  </tr>
  <tr>
    <td>remotehost</td>
    <td><code>certbot certonly --webroot --webroot-path /tmp/acme-challenge --rsa-key-size 4096 --non-interactive --agree-tos --no-eff-email --force-renewal --email ${LETSENCRYPT_EMAIL} -d ${DOMAIN_NAME} -d www.${DOMAIN_NAME} -d mail.${DOMAIN_NAME}</code></td>
  </tr>
</tbody>
</table>

#### Installation

Firstly: will create external volume

```
docker volume create --driver local --opt type=none --opt device=${PWD}/certbot --opt o=bind certbot-etc
```

Localhost ssl: Generate Self-signed SSL Certificate with guide [mkcert repository](https://github.com/FiloSottile/mkcert).

```
docker compose up -d
```

then reloading for proxy ssl configuration

```
docker container restart proxy
```

The containers are now built and running. You should be able to access the odoo installation with the configured IP in the browser address. `https://example.com`.

For convenience you may add a new entry into your hosts file.

### Portainer

```
docker compose -f portainer-docker-compose.yml -p portainer up -d 
```

manage docker with [Portainer](https://www.portainer.io/) is the definitive container management tool for Docker, Docker Swarm with it's highly intuitive GUI and API. 

You can also visit `https://example.com:9001` to access portainer after starting the containers.

### Usage

#### You could manage docker containers without command line with portainer.

#### Here’s a quick reference of commonly used Docker Compose commands

```
docker ps -a # Lists all containers managed by the compose file
```

```
docker compose start # Starts previously stopped containers
```

```
docker compose stop # Stops all running containers
```

```
docker compose down # Stops and removes containers, networks, etc.
```

```
docker compose down -v # Add --volumes to remove volumes explicitly
```

```
docker rm -f $(docker ps -a -q) # Removes portainer and the other containers
```

```
docker volume rm $(docker volume ls -q) # Removes all volumes
```

```
docker network prune # Remove all unused networks
```

```
docker system prune # Removes unused data (containers, networks, images, and optionally volumes)
```

```
docker system prune -a # Removes all unused images, not just dangling ones
```

```
docker rmi $(docker image ls -q) # Removes portainer and the other images
```

```
docker container logs container_name_or_id # Shows logs from all services
```

#### Project from existing source

Copy all files into a new directory:

```
docker compose up -d # Starts services in detached mode (in the background)
```

#### Docker run reference

[https://docs.docker.com/reference/cli/docker/compose/](https://docs.docker.com/reference/cli/docker/compose/)

#### Odoo

[How to install, maintain and upgrade Odoo databases.](https://www.odoo.com/documentation/19.0/administration.html)

```
Email: admin
Password: admin
```

#### Mail

Send Email Node;

SMTP account: ```Host: mail; Port: 1025; SSL/TLS: off;```

The authorize screen: user: |`DB_USER`| and password: |`DB_PASSWORD`| in the `.env` file.

#### Database

Postgres account; |```Host: database; Port: 5432; Database: `DB_NAME`; User: `DB_USER`; Password: `DB_PASSWORD````| in the `.env` file.

#### pgAdmin

You can also visit |```https://`DOMAIN_NAME`:9090````|.

The login screen, |```username: `LETSENCRYPT_EMAIL```` and ```password: `PGA_CONTROLPASS````| in the `.env` file.

You don't see the login page in your browser;\
pgAdmin runs as the pgadmin user (UID: 5050) in the pgadmin group (GID: 5050) in the container.
You must ensure that all files are readable, and where necessary (e.g. the working/session directory) writeable for this user on the host machine.

```sudo chown -R 5050:5050 ./pgadmin``` and/or ```sudo chown -R 5050:5050 ./certbot/live/`DOMAIN_NAME````

#### Proxy

Proxying is typically used to distribute the load among several servers, seamlessly show content from different websites, or pass requests for processing to application servers over protocols other than HTTP.

add or remove code in the ```./proxy/templates/proxy.conf.template``` file for custom proxy configurations

[Odoo Configuration sample](https://www.odoo.com/documentation/19.0/administration/on_premise/deploy.html#id8)

[https://docs.nginx.com/nginx/admin-guide/web-server/reverse-proxy/](https://docs.nginx.com/nginx/admin-guide/web-server/reverse-proxy/)

#### backup

This will back up the all files and folders in database/dump sql and html volumes, once per day, and write it to ```./backups``` with a filename like backup-2023-01-01T10-18-00.tar.gz

##### can run on a custom cron schedule

```BACKUP_CRON_EXPRESSION: '20 01 * * *'``` the UTC timezone.
