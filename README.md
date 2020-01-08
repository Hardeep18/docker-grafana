# Docker-compose files for a simple uptodate
# InfluxDB + Grafana stack
#  Telegraf



```
git clone https://github.com/Hardeep18/docker-grafana.git
cd docker-grafana
docker pull grafana/grafana
docker pull influxdb
docker pull telegraf

```

Run your stack:

```
docker-compose up --build -d

```

Show me the logs:

```
docker-compose logs
```