# Hébergement web

## Configs

- SSH
  - Port: 2003
  - Password auth: No
  - Root login: No
- Firewall
  - UFW
    - Default: Deny
    - Allow: 2003, 80, 443
- Nginx
  - Reverse proxy
  - SSL
    - Let's Encrypt
    - Certbot (2x per day)
- Samba
  - `\\209.38.208.57\partage`
  - `it-connect` : `it-connect`

## App Repository

[https://github.com/NicolasFrouin/hebergement-web-todo-app.git](https://github.com/NicolasFrouin/hebergement-web-todo-app.git)

## Tutos for Debian

- [Change SSH port](https://www.cyberciti.biz/faq/howto-change-ssh-port-on-linux-or-unix-server/)
- Setup firewall
  - [Digital Ocean](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-firewall-with-ufw-on-debian)
  - [CyberCiti](https://www.cyberciti.biz/faq/set-up-a-firewall-with-ufw-on-debian-12-linux/)
- [Install Nginx](https://www.digitalocean.com/community/tutorials/how-to-install-nginx-on-debian-10)
- [Secure Nginx with Let's encrypt](https://www.digitalocean.com/community/tutorials/how-to-secure-nginx-with-let-s-encrypt-on-debian-11)
- [Install Docker](https://docs.docker.com/engine/install/debian/)
- Docker containers
  - [Endlessh](https://github.com/linuxserver/docker-endlessh)
- [Install Samba](https://www.it-connect.fr/serveur-de-fichiers-debian-installer-et-configurer-samba-4/)

## Todo

- [ ] Fail2ban
  - [ ] Nginx
  - [ ] Adminer
