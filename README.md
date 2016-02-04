## docker-binaries
Shell scripts for your ```$HOME/bin``` directory for easy use of dockerized apps

### Usage
Copy files into your ```$HOME/bin``` directory and make it executable (```chmod -x```). On Ubuntu this is in your ```$PATH``` by default.

### List of scripts

- **node**   - [**nodejs.org**](https://nodejs.org/en/) - runs with a "hack" to retain user rights also on multi user and LDAP systems
- **bower**  - [**bower.io**](http://bower.io)          - runs with a "hack" to retain user rights also on multi user and LDAP systems
- **grunt**  - [**gruntjs.com**](http://gruntjs.com/)   - runs with a "hack" to retain user rights also on multi user and LDAP systems
- **gulp**   - [**gulpjs.com**](http://gulpjs.com/)     - runs with a "hack" to retain user rights also on multi user and LDAP systems
- **npm**    - [**npmjs.com**](https://www.npmjs.com/)  - runs with a "hack" to retain user rights also on multi user and LDAP systems
- **docker-ip** - list ip's of all running containers
- **docker-kill-all** - stop all running containers
- **docker-clean-containers** - delete all stopped containers except "data" containers ("data" in container name)
- **docker-clean-images** - delete all images that aren't releated with existing containers
- **filezilla** - [**filezilla-project.org**](https://filezilla-project.org/) - FTP Client
- **heidisql** - [**heidisql.com**](http://www.heidisql.com/) - SQL Client for windows
- **heidisql-vpn** - [**heidisql.com**](http://www.heidisql.com/) - SQL Client for windows. Runs and connects to ```vpn```.
- **vpn** - [**tsari/vpn-proxy**](https://github.com/tsari/vpn-proxy) - openvpn client and squid proxy in a docker container.






