# [![Travis (.org)](https://img.shields.io/travis/EpicMorg/docker-scripts?style=flat-square)](https://travis-ci.org/EpicMorg/docker-scripts) [![Activity](https://img.shields.io/github/commit-activity/m/EpicMorg/docker-scripts?label=commits&style=flat-square)](https://github.com/EpicMorg/docker-scripts/commits) [![GitHub issues](https://img.shields.io/github/issues/EpicMorg/docker-scripts.svg?style=popout-square)](https://github.com/EpicMorg/docker-scripts/issues) [![GitHub forks](https://img.shields.io/github/forks/EpicMorg/docker-scripts.svg?style=popout-square)](https://github.com/EpicMorg/docker-scripts/network) [![GitHub stars](https://img.shields.io/github/stars/EpicMorg/docker-scripts.svg?style=popout-square)](https://github.com/EpicMorg/docker-scripts/stargazers)  [![Size](https://img.shields.io/github/repo-size/EpicMorg/docker-scripts?label=size&style=flat-square)](https://github.com/EpicMorg/docker-scripts/archive/master.zip) [![Release](https://img.shields.io/github/v/release/EpicMorg/docker-scripts?style=flat-square)](https://github.com/EpicMorg/docker-scripts/releases) [![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/3658/badge)](https://bestpractices.coreinfrastructure.org/projects/3658) [![CodeScene System Mastery](https://codescene.io/projects/6535/status-badges/system-mastery)](https://codescene.io/projects/6535) [![GitHub license](https://img.shields.io/github/license/EpicMorg/docker-scripts.svg?style=popout-square)](LICENSE.md) [![Changelog](https://img.shields.io/badge/Changelog-yellow.svg?style=popout-square)](CHANGELOG.md)

[![](https://codescene.io/projects/6535/status.svg)](https://codescene.io/projects/6535/jobs/latest-successful/results)

# Containers Map

![](https://raw.githubusercontent.com/EpicMorg/docker-scripts/master/.github/docker-scripts.png)

# Some popular products  [![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/B0B81CUI4)

| Application   | Pulls | Notes
| ------  | ------ | ------
| [![Atlassian Bitbucket](https://img.shields.io/badge/Atlassian%20Bitbucket--brightgreen.svg?style=popout-square)](https://www.atlassian.com/software/bitbucket/download) | [![](https://img.shields.io/docker/pulls/epicmorg/bitbucket.svg?style=popout-square)](https://hub.docker.com/r/epicmorg/bitbucket/) | `Atlassian Bitbucket` server. You also can install `datacenter` edition.
| [![Atlassian Confluence](https://img.shields.io/badge/Atlassian%20Confluence--brightgreen.svg?style=popout-square)](https://www.atlassian.com/software/confluence/download) |   [![](https://img.shields.io/docker/pulls/epicmorg/confluence.svg?style=popout-square)](https://hub.docker.com/r/epicmorg/confluence/) | `Atlassian Confluence` server. You also can install `datacenter` edition.
| [![Atlassian Jira](https://img.shields.io/badge/Atlassian%20Jira--brightgreen.svg?style=popout-square)](https://www.atlassian.com/software/jira/download) | [![](https://img.shields.io/docker/pulls/epicmorg/jira.svg?style=popout-square)](https://hub.docker.com/r/epicmorg/jira/) | `Atlassian Jira: Softrware` server.  You also can install `servicedesk`, `core` or `datacenter` editions.
| [![Nginx Mainline](https://img.shields.io/badge/Nginx--brightgreen.svg?style=popout-square)](https://nginx.org/en/download.html) |   [![](https://img.shields.io/docker/pulls/epicmorg/balancer.svg?style=popout-square)](https://hub.docker.com/r/epicmorg/balancer/) | Mainline custom build by [EpicMorg Team](https://github.com/EpicMorg) with http2 support and some modules.
| [![Apache2](https://img.shields.io/badge/Apache2--brightgreen.svg?style=popout-square)](https://deb.sury.org/)  |  [![](https://img.shields.io/docker/pulls/epicmorg/websites.svg?style=popout-square)](https://hub.docker.com/r/epicmorg/websites/ ) | Latest pure apache2.
| [![php7](https://img.shields.io/badge/php7--brightgreen.svg?style=popout-square)](https://deb.sury.org/) | [![](https://img.shields.io/docker/pulls/epicmorg/websites.svg?style=popout-square)](https://hub.docker.com/r/epicmorg/websites/ ) |  php 7.3 custom build by [Ondrej Sury](https://launchpad.net/~ondrej). Component of container above.
| [![nc](https://img.shields.io/badge/NextCloud--brightgreen.svg?style=popout-square)](https://hub.docker.com/_/nextcloud)  |  [![](https://img.shields.io/docker/pulls/epicmorg/nextcloud.svg?style=popout-square)](https://hub.docker.com/r/epicmorg/nextcloud/ ) | Fixed `nextcloud:latest` build by [EpicMorg Team](https://github.com/EpicMorg) with benefits.
| [![zabbix-agent](https://img.shields.io/badge/Zabbix%20Agent--brightgreen.svg?style=popout-square)](https://github.com/zabbix/zabbix-docker)  | [![](https://img.shields.io/docker/pulls/epicmorg/zabbix-agent.svg?style=popout-square)](https://hub.docker.com/r/epicmorg/zabbix-agent/ ) | Fixed `zabbix/zabbix-agent:ubuntu-latest` build by [EpicMorg Team](https://github.com/EpicMorg) with benefits.
| [![zabbix-server](https://img.shields.io/badge/Zabbix%20Server--brightgreen.svg?style=popout-square)](https://github.com/zabbix/zabbix-docker)  | [![](https://img.shields.io/docker/pulls/epicmorg/zabbix-server-mysql.svg?style=popout-square)](https://hub.docker.com/r/epicmorg/zabbix-server-mysql/ ) | Fixed `zabbix/zabbix-server-mysql:ubuntu-latest` build by [EpicMorg Team](https://github.com/EpicMorg) with benefits.
| [![zabbix-web](https://img.shields.io/badge/Zabbix%20Web--brightgreen.svg?style=popout-square)](https://github.com/zabbix/zabbix-docker)  | [![](https://img.shields.io/docker/pulls/epicmorg/zabbix-web-apache-mysql.svg?style=popout-square)](https://hub.docker.com/r/epicmorg/zabbix-web-apache-mysql/ ) | Fixed `zabbix/zabbix-web-apache-mysql:ubuntu-latest` build by [EpicMorg Team](https://github.com/EpicMorg) with benefits.
| [![zabbix-java-gateway](https://img.shields.io/badge/Zabbix%20JavaGW--brightgreen.svg?style=popout-square)](https://github.com/zabbix/zabbix-docker)  | [![](https://img.shields.io/docker/pulls/epicmorg/zabbix-java-gateway.svg?style=popout-square)](https://hub.docker.com/r/epicmorg/zabbix-java-gateway/ ) | Fixed `zabbix/zabbix-java-gateway:ubuntu-latest` build by [EpicMorg Team](https://github.com/EpicMorg) with benefits.
| [![teamcity-agent](https://img.shields.io/badge/TeamCity%20Agent--brightgreen.svg?style=popout-square)](https://github.com/JetBrains/teamcity-docker-agent)  | [![](https://img.shields.io/docker/pulls/epicmorg/teamcity-agent.svg?style=popout-square)](https://hub.docker.com/r/epicmorg/teamcity-agent/ ) | Custom build by [EpicMorg Team](https://github.com/EpicMorg) with benefits.
| [![qbittorrent](https://img.shields.io/badge/qBittorrent--brightgreen.svg?style=popout-square)](https://github.com/qbittorrent/qBittorrent)  | [![](https://img.shields.io/docker/pulls/epicmorg/qbittorrent.svg?style=popout-square)](https://hub.docker.com/r/epicmorg/qbittorrent/ ) | Custom build by [EpicMorg Team](https://github.com/EpicMorg) with benefits.


## Thanks

* [@Aleks-Z](https://github.com/Aleks-Z)
* [@alex4rks](https://github.com/alex4rks)
* [@kasthack](https://github.com/kasthack)
