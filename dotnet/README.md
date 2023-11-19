export OTEL_SERVICE_NAME=myapp
export OTEL_RESOURCE_ATTRIBUTES=deployment.environment=staging,service.version=1.0.0
export OTEL_TRACES_EXPORTER=otlp
export OTEL_METRICS_EXPORTER=otlp
export OTEL_EXPORTER_OTLP_PROTOCOL=grpc
export OTEL_EXPORTER_OTLP_ENDPOINT=http://localhost:4317
export OTEL_DOTNET_AUTO_TRACES_CONSOLE_EXPORTER_ENABLED=true

```sh
curl -sSfL https://github.com/open-telemetry/opentelemetry-dotnet-instrumentation/releases/latest/download/otel-dotnet-auto-install.sh -O

```