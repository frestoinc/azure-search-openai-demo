#1. Login with techpass to init template
`azd auth login --tenant-id <string> --use-device-code`

# 2. Setup with existing resources 
## Resource group
1. `azd env set AZURE_RESOURCE_GROUP <string>`
2. `azd env set AZURE_LOCATION <string>
...
...
