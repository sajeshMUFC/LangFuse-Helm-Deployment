# LangFuse Helm Deployment

This repository contains Helm deployment scripts for configuring Lang fuse in an EKS environment.

## Prerequisites

- Kubernetes cluster on EKS
- Helm installed

## Deployment Steps

1. Clone the repository:
   ```sh
   git clone https://github.com/sajeshMUFC/LangFuse-Helm-Deployment.git
   cd LangFuse-Helm-Deployment
   ```

2. Deploy the Helm chart:
   ```sh
   helm install langfuse ./helm
   ```

3. Verify the deployment:
   ```sh
   kubectl get pods
   ```

## Notes

- Ensure no credentials or confidential information are included in the deployment scripts.
- Update the `values.yaml` file as per your environment requirements.
