# How to Connect to Azure with GitHub Actions with OpenID Connect

##Prepare a service principal for Login with OIDC
###Create a service principal and assign a role to it
###Configure a federated identity credential on an service principal

##After it, create GitHub Action secrets for following values: (Refer to Using secrets in GitHub Actions.)

  ###AZURE_CLIENT_ID: the service principal client ID or user-assigned managed identity client ID
  ###AZURE_SUBSCRIPTION_ID: the subscription ID
  ###AZURE_TENANT_ID: the tenant ID
