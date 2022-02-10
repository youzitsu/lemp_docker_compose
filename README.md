# lemp_docker_compose

-- run dockerfile --> image php:version2
-- run dockerfile --> image mysql:version2
--- access folder lemp_docker_compose/config_php  --> image php:version2
+ docker build -t php:version2 -f dockerfile .

--- access folder lemp_docker_compose/config_mysql  --> image mysql:version2

+ docker build -t mysql:version2 -f dockerfile .


-- access lemp_docker_compose:

+ docker-compose up -d

