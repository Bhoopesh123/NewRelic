# NewRelic


Step 1: Add Helm Repositories

helm repo add open-telemetry https://open-telemetry.github.io/opentelemetry-helm-charts
helm repo update


Step 2: Install the Helm Chart

helm upgrade --install newrelic-otel open-telemetry/opentelemetry-collector -f otel_values.yaml

    helm repo add open-telemetry https://open-telemetry.github.io/opentelemetry-helm-charts  

    helm upgrade --install my-opentelemetry-collector open-telemetry/opentelemetry-collector -f otel_k8s_metrics_processors.yaml

