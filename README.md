## Cloud Native Wizard Apps Helm Charts
This repository contains the Helm charts for the Cloud Native Wizard Apps.

<p align="center">
<img src="src/images/cnwizards.jpeg" alt="cnwizards" width="300"/>
</p>

## How to install the Helm charts
To install the Helm charts, you need to add the Helm repository to your local Helm client. To do so, run the following command:

```bash
# to add the Helm repository
helm repo add cnwizards https://charts.cloudnativewizards.dev
# to pull the latest Helm charts
helm pull cnwizards/node-wizard   
# to install the Helm charts
helm install node-wizard cnwizards/node-wizard --namespace node-wizard --create-namespace
```
