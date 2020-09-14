# kube-state-metrics

摘取自 release 1.9.7 <https://github.com/kubernetes/kube-state-metrics/tree/master/examples/standard> 并结合 release 1.8.0 添加服务自动被 Prometheus 发现

```yaml
  annotations:
    prometheus.io/scrape: 'true'
```