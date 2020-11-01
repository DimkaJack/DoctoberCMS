# Docker with OctoberCMS

## Installation

* Install October CMS `git clone https://github.com/octobercms/october.git october`
* `cd october`
* `git clone https://github.com/DimkaJack/DoctoberCMS.git .docker`
* `docker-compose -f .docker/docker-compose.yml up -d --build`
* `docker-compose -f .docker/docker-compose.yml exec php composer install`