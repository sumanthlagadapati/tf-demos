# tf-demos

DevOps CI/CD pipeline using DevOps tools.

## Sample configurations

This repository includes ready-to-use infrastructure and observability snippets to serve as a starting point for new projects.

### Terraform

`samples/terraform` provisions an Amazon S3 bucket with versioning enabled. Update `bucket_name` in `terraform.tfvars` (or provide it via the CLI) before applying.

### Helm

`samples/helm/simple-app` is a minimal Helm chart that deploys a containerized web application with an optional Ingress resource and configurable resource requests/limits.

### OpenTelemetry Collector

`samples/opentelemetry/otel-collector-config.yaml` configures the OpenTelemetry Collector with OTLP and Prometheus receivers, basic processors, and exporters for OTLP, Prometheus, and structured logging.
