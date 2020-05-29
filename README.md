# Istio, Envoy

## Envoy

### xDS 구현 및 원리 (ADS, EDS, CDS)
- [envoy practice github: prac 1~6](https://github.com/tjtjtj/envoyprac)
- [envoy basics: Envoy 기본](https://jvns.ca/blog/2018/10/27/envoy-basics/)
- [Detailed explanation of xDS REST and gRPC protocols in Envoy from Envoy Team](https://www.servicemesher.com/blog/envoy-xds-protocol/)
- [Envoy xDS Hello world!](https://medium.com/@salmaan.rashid/envoy-control-plane-hello-world-2f49b2865f29)
- [katacoda로 Envoy 기본 익히기](https://www.katacoda.com/envoyproxy/)
- [REST 기반 EDS 구현하기 (주의: REST는 polling임)](https://github.com/salrashid123/envoy_discovery)
- [Envoy HTTP LB 기본: nginx, httpd](https://i-beam.org/2019/02/03/envoy-static-load-balancer/)

### Envoy Network Traffic Flow
- [iptables 규칙으로 Envoy network flow 살펴보기](https://blog.51cto.com/14625168/2477363)
- [Envoy Inbound / Outbound traffic flow](https://jimmysong.io/en/blog/sidecar-injection-iptables-and-traffic-routing/)

## Istio

### Adapter Pattern
- [Mixer를 이용한 다양한 Adapter + Handler 사용해보기 (prom, redis, quota 등등)](https://knowledge.sakura.ad.jp/20681/)
- [Envoy Attribute 디버깅할 때 유용한 controlZ](https://aidanbae.github.io/code/devops/k8s/istio-mixer-debug/)

# Kubernetes
- [Kubernetes 1.18 Hard way](https://github.com/sgargel/kubernetes-the-hard-way-virtualbox)

## Distributed Tracing
- [A Life of Span](https://medium.com/jaegertracing/the-life-of-a-span-ee508410200b)
- [How istio send tracing spans to jaeger](https://stackoverflow.com/questions/53459759/how-istio-send-tracing-spans-to-jaeger)
- [Complete Guide for Tracing gRPC](https://programmaticponderings.com/tag/istio/)

## Prometheus, AlertManager
- [Understanding alertmanager delays](https://pracucci.com/prometheus-understanding-the-delays-on-alerting.html)

# Linux

## Bash Basic
- [nohub과 disown](https://velog.io/@jakeseo_me/nohup-disown-%EB%8A%94-%EC%96%B8%EC%A0%9C-%EC%96%B4%EB%96%BB%EA%B2%8C-%EC%8D%A8%EC%95%BC%EB%90%A0%EA%B9%8C-9fjv7q9bz8)

## Network
- [DNS Troubleshooting Guide of Google Cloud](https://cloud.google.com/blog/topics/inside-google-cloud/google-cloud-support-engineer-solves-a-tough-dns-case)
