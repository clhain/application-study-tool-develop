---
layout: home
title: Home
nav_order: 1
---
# Application Study Tool

### Overview
The Application Study Tool is intended to provide enhanced insights into (classic) BIG-IP products, leveraging best in class
open source telemetry tools. The full installation includes:

* Custom Instance of OpenTelemetry Collector with enhanced BIG-IP data receivers (data fetched via iControlRest) [Receiver Metrics Info]({{site.baseurl}}/components/otel_collector/receiver_metrics.html).
* Prometheus timeseries database for storing and querying collected data.
* Grafana Instance with pre-configured dashboards for quick insights at the device and "fleet" levels.

The Application Study Tool has everything needed to quickly get up and running with application insights at less than
production levels of reliability. For production/operational use cases, you can build on the included components,
accounting for things like high availability, enhanced security via e.g. Grafana OIDC integration, and similar. Alternatively,
the Openetlemetry Collector can be configured to send data to existing production ops monitoring tools as desired.

![](./assets/ui.gif)

 