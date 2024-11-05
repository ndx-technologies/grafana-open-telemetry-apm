APM[^1] Grafana dashboard based on Open Telemetry spanmetrics[^2] from traces

- Golden Metrics / RED (volume, errors, latency)
- standard Open Telemetry spanmetrics labels from traces
- breakdown by `service`, `version`, `namespace` (e.g. `production`, `staging`), `kind` (e.g. `server`, `client`, `consumer`, `producer`)

[^1]: Application Performance Monitoring
[^2]: https://github.com/open-telemetry/opentelemetry-collector-contrib/blob/main/connector/spanmetricsconnector/README.md
