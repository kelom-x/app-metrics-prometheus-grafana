# app-metrics-prometheus-grafana
Configuring App-Metrics with Prometheus and Grafana


prom-grafana-docker-compose.yml
------------------------------
make the necessary changes/modifications especially the volumes  to suit your environment



prometheus > prometheus.yml
------------------
change the target and name of the test_api job to suit your environment, or you can add 
your own service(s)



grafana > datasources.yml 
--------------------------
add your datasources to this file



grafana > grafana.ini
---------------------
setup initial grafana username and password in this file

