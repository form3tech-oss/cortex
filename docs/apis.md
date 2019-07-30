# Cortex APIs

[this is a work in progress]

## Remote API

Cortex supports Prometheus'
[`remote_read`](https://prometheus.io/docs/prometheus/latest/configuration/configuration/#remote_read)
and
[`remote_write`](https://prometheus.io/docs/prometheus/latest/configuration/configuration/#remote_write)
APIs.  The encoding is Protobuf over http.

Read is on `/api/prom/read` and write is on `/api/prom/push`.


## Configs API

See [here](configs-api.md)
