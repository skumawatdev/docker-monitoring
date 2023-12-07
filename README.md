# docker-monitoring

# create seprate network for these conatiners.
    docker network create network monitoring
# Give permision to the grafana for /var/li/grafana
    chmod -Rf 777 grafana
