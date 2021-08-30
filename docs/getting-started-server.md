# Starting up your own Ginto Server
## Preparing your machine
### Installing MySQL server

**Example for Debian Linux**
```sh
$ cd /tmp
$ sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.13-1_all.deb
$ sudo dpkg -i mysql-apt-config_0.8.13-1_all.deb
$ sudo apt update
$ sudo apt install mysql-server
```
---

**Preparing MySQL server**

Logging into MySQL Server using root user
```sh
$ sudo mysql -u root -p
```

Then enter these MySQL commands

```sql
CREATE DATABASE gintoserver
CREATE TABLE users (id LONG);
CREATE TABLE messages (msgid LONG, userid LONG, text TEXT);
```
---

## Cloning Ginto Server code
```sh
git clone https://github.com/NeticTeam/Ginto.git -b server
```
Now you have Ginto Server source code!

## Preparing Ginto Server

not done yet like the server :)
