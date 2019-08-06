# :bird: pterodactyl-installer

Unofficial scripts for installing Pterodactyl on both Panel & Daemon.

Read more about [Pterodactyl here](https://pterodactyl.io/).

# Supported installations

List of supported installation setups for panel and daemon (installations supported by this installation script).

### Supported panel operating systems and webservers

| Operating System  | Version | nginx support      | Apache support |
| ----------------- | ------- | ------------------ | -------------- |
| Ubuntu            | 14.04   | :red_circle:       | :red_circle:   |
|                   | 16.04   | :white_check_mark: | :red_circle:   |
|                   | 18.04   | :white_check_mark: | :red_circle:   |
| Debian            | 8       | :white_check_mark: | :red_circle:   |
|                   | 9       | :white_check_mark: | :red_circle:   |
|                   | 10      | :red_circle: *     | :red_circle:   |
| CentOS            | 6       | :red_circle:       | :red_cirlce:   |
|                   | 7       | :red_circle: **    | :red_circle:   |

### Supported daemon operating systems

| Operating System  | Version | Supported          |
| ----------------- | ------- | ------------------ |
| Ubuntu            | 14.04   | :red_circle:       |
|                   | 16.04   | :white_check_mark: |
|                   | 18.04   | :white_check_mark: |
| Debian            | 8       | :red_circle:       |
|                   | 9       | :white_check_mark: |
|                   | 10      | :red_cirlce:*      |
| CentOS            | 6       | :red_circle:       |
|                   | 7       | :white_check_mark: |

_* Debian 10 is not listed as officially supported by Pterodactyl yet._
_** CentOS 7 is only supported by this script on daemon installations, not panel._

# Using the installation scripts

Using the Pterodactyl Panel installation script:

`bash <(curl -s https://raw.githubusercontent.com/VilhelmPrytz/pterodactyl-installer/master/install-panel.sh)`

Using the Pterodactyl Daemon installation script:

`bash <(curl -s https://raw.githubusercontent.com/VilhelmPrytz/pterodactyl-installer/master/install-daemon.sh)`

The script will guide you through the install.

*Note: On some systems it's required to be already logged in as root before executing the one-line command.*

# Contributing

Feel free to fork the project and send a PR! :smiley:
