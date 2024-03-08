# archlinux-gaming
Script to install necessary packages for gaming in archlinux

To install Lutris(Wine), Mangohud and Steam, you can run this command, which uses *curl* to download the script that will also install the packages.

> **Warning**: Always be careful when running scripts from the Internet.

```
bash -c "$(curl -sS https://raw.githubusercontent.com/ayu2805/archlinux-gaming/main/archlinux-gaming-setup)"
```
(or run this if you are facing some [issues in India](https://timesofindia.indiatimes.com/gadgets-news/github-content-domain-blocked-for-these-indian-users-reports/articleshow/96687992.cms))

```sh
wget -q -nc --show-progress https://github.com/ayu2805/archlinux-gaming/releases/latest/download/archlinux-gaming-setup && bash archlinux-gaming-setup && rm archlinux-gaming-setup
```
