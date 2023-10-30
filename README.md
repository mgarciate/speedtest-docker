# speedtest-docker

A Docker project integrating Telegraf, InfluxDB, and Grafana to monitor internet speeds:

- Use Telegraf with the Speedtest plugin to measure internet speeds at regular intervals and send the data to InfluxDB.
- InfluxDB stores these speed measurements as time series data.
- Grafana visualizes this data in real-time, sourcing from InfluxDB, displaying internet speed trends and metrics.

## References
Grafana dashboard based on https://github.com/pedrolsazevedo/TICK-Speedtest-Grafana