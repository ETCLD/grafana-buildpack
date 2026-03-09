# Grafana buildpack

Buildpack for running a Grafana instance on Scalingo.

The buildback download the file `GRAFANA_DOWNLOAD_URL` and extracts it to `$BUILD_DIR/grafana`.

The `GRAFANA_DOWNLOAD_URL` is the url of the standalone linux binaries. It can be found to the grafana download page : https://grafana.com/grafana/download

For the 12.4.0 OSS : https://dl.grafana.com/grafana/release/12.4.0/grafana_12.4.0_22325204712_linux_amd64.tar.gz
