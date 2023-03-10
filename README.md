# Prometheus-Grafana-AlertManager-WMI
## Download Prometheus
Go to the follwing link - https://prometheus.io/download/
Copy link address prometheus-2.42.0.linux-amd64.tar.gz

Download to your server using - wget https://github.com/prometheus/prometheus/releases/download/v2.42.0/prometheus-2.42.0.linux-amd64.tar.gz

## Download & Install Grafana

```
wget -q -O - https://packages.grafana.com/gpg.key | sudo apt-key add -
sudo add-apt-repository "deb https://packages.grafana.com/oss/deb stable main"
sudo apt update
sudo apt install grafana
sudo systemctl start grafana-server
sudo systemctl status grafana-server
sudo systemctl enable grafana-server.service
http://your_ip:3000

```
## Download AlertManager
Go to the link - https://prometheus.io/download/
copy link address alertmanager-0.25.0.linux-amd64.tar.gz

Download to your server using - wget https://github.com/prometheus/alertmanager/releases/download/v0.25.0/alertmanager-0.25.0.linux-amd64.tar.gz

## Download WMI Exporter
Go to the following link - https://github.com/prometheus-community/windows_exporter/releases

Download Install the window.msi, make sure check the service is running 

```
NOTE: Please check the YML Files and check the syntax using promtool & amtool

```
