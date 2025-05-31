# NewRelic


# 1: Add Helm Repositories

helm repo add open-telemetry https://open-telemetry.github.io/opentelemetry-helm-charts
helm repo update


# 2: Install the Helm Chart

helm upgrade --install newrelic-otel open-telemetry/opentelemetry-collector -f otel_values.yaml



