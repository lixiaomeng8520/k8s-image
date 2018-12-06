# k8s-image


## prometheus

```
docker pull registry.cn-hangzhou.aliyuncs.com/pecid-prometheus/addon-resizer:1.7 && \
docker pull registry.cn-hangzhou.aliyuncs.com/pecid-prometheus/alertmanager:v0.15.1 && \
docker pull registry.cn-hangzhou.aliyuncs.com/pecid-prometheus/grafana:5.2.2 && \
docker pull registry.cn-hangzhou.aliyuncs.com/pecid-prometheus/kube-state-metrics:v1.3.1 && \
docker pull registry.cn-hangzhou.aliyuncs.com/pecid-prometheus/node-exporter:v0.16.0 && \
docker pull registry.cn-hangzhou.aliyuncs.com/pecid-prometheus/prometheus:v2.3.2 && \
docker pull registry.cn-hangzhou.aliyuncs.com/pecid-prometheus/prometheus-operator:v0.23.1

docker tag registry.cn-hangzhou.aliyuncs.com/pecid-prometheus/addon-resizer:1.7 k8s.gcr.io/addon-resizer:1.7 && \
docker tag registry.cn-hangzhou.aliyuncs.com/pecid-prometheus/alertmanager:v0.15.1 quay.io/prometheus/alertmanager:v0.15.1 && \
docker tag registry.cn-hangzhou.aliyuncs.com/pecid-prometheus/grafana:5.2.2 grafana/grafana:5.2.2 && \
docker tag registry.cn-hangzhou.aliyuncs.com/pecid-prometheus/kube-state-metrics:v1.3.1 k8s.gcr.io/kube-state-metrics:v1.3.1 && \
docker tag registry.cn-hangzhou.aliyuncs.com/pecid-prometheus/node-exporter:v0.16.0 quay.io/prometheus/node-exporter:v0.16.0 && \
docker tag registry.cn-hangzhou.aliyuncs.com/pecid-prometheus/prometheus:v2.3.2 quay.io/prometheus/prometheus:v2.3.2 && \
docker tag registry.cn-hangzhou.aliyuncs.com/pecid-prometheus/prometheus-operator:v0.23.1 quay.io/coreos/prometheus-operator:v0.23.1
```