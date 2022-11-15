# Azure Sentinel - Initial Deployment

Deploys a Log Analytics Workspace and enables the SecurityInsights (Sentinel) solution.

Note:  Automatically generates the name of the Log Analytics Workspace aligned with SCC defaults (which are CAF aligned):

log-<*workload*>-<*env*>-<*location*>-01

For example:  log-sentinel-prod-uksouth-01

You will be required to create a Resource Group for the deployment.  Make sure to select the Azure region you want as the Log Analytics Workspace and Sentinel will be deployed to the same Azure region as the resource group.

When naming the Resource Group, following the format below:

rg-<*workload*>-<*env*>-<*location*>-01

For example:  rg-sentinel-prod-uksouth-01

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fdavelee212%2Fazure_sentinel_arm%2Fmain%2Fdeploy_sentinel.json)
