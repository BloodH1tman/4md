# Prerequisites
1. Kubernetes 1.19+
2. Helm 3.2.0+

# Installing the Chart
1. Open folder mychart
2. Run the following command:
    1. helm dependency update
    2. helm upgrade --install md . -f .\values.yaml -n md --create-namespace

# Parameters
You can change default parameters in mychart\values.yaml