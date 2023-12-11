# Demo: OpenTelemetry

## Summary

OpenTelemetry is an Observability framework and toolkit designed to create and manage telemetry data such as traces, metrics, and logs. Crucially, OpenTelemetry is vendor- and tool-agnostic, meaning that it can be used with a broad variety of Observability backends, including open source tools like Jaeger and Prometheus, as well as commercial offerings. OpenTelemetry is a Cloud Native Computing Foundation (CNCF) project. [More Info](https://opentelemetry.io/) and [OpenTelemetry Registry](https://opentelemetry.io/ecosystem/registry/)

## OpenTelemetry Operator for Kubernetes

An implementation of a Kubernetes Operator, that manages collectors and auto-instrumentation of the workload using OpenTelemetry instrumentation libraries.

To install the operator in an existing cluster, make sure you have cert-manager installed and run:
```bash
kubectl apply -f https://github.com/open-telemetry/opentelemetry-operator/releases/latest/download/opentelemetry-operator.yaml
```