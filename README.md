# Elasticsearch Monitoring Mixin for OpenShift Aggregated Logging

> NOTE: This project is *alpha* stage. Flags, configuration, behaviour and design may change significantly in following releases.

A set of Grafana dashboard and Prometheus alerts for Elasticsearch deployed as part of [Origin-Aggregated-Logging](https://github.com/openshift/origin-aggregated-logging/).

## How to use

This repository has been heavily inspired by <https://github.com/kubernetes-monitoring/kubernetes-mixin>.
Follow that repository for further information about deployment.

### Quick and dirty hint

```
$ make clean && make

# dashboard json is build here:
$ file dashboards_out/logging-elasticsearch.json 
dashboards_out/logging-elasticsearch.json: ASCII text 
```