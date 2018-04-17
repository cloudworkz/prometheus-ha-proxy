# prometheus-ha-proxy
[![license](https://img.shields.io/github/license/google-cloud-tools/prometheus-ha-proxy.svg?maxAge=604800)](https://github.com/google-cloud-tools/prometheus-ha-proxy)

Prometheus HA Proxy is the high availability (hot standby) setup in kubernetes for prometheus.

[![graph](https://raw.githubusercontent.com/google-cloud-tools/prometheus-ha-proxy/master/graph.png)](https://raw.githubusercontent.com/google-cloud-tools/prometheus-ha-proxy/master/graph.png)

### Requirements

- Kubernetes 1.6+
- RBAC enabled
- Google Cloud Storage for pod volume template