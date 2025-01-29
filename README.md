# spring-boot-helm-chart
A versatile helm chart that can be used to deploy images containing spring boot apps

See our [gitops-playground](https://github.com/cloudogu/gitops-playground) for examples.


# Helm Chart Unit Testing

This repository contains unit tests for the Helm chart using the [Helm Unittest](https://github.com/helm-unittest/helm-unittest) framework.

## Prerequisites

Before running the tests, ensure you have the following installed:

- [Helm](https://helm.sh/docs/intro/install/) (version X.X.X or later)
- [Helm Unittest](https://github.com/helm-unittest/helm-unittest)

## Running Unit Tests

To run the unit tests for the Helm chart:

1. Navigate to the root directory of the Helm chart.

2. Run the following command:

   ```bash
   helm unittest . -f tests/test-*

