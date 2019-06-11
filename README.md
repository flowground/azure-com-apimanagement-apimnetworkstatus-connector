# ![LOGO](logo.png) ApiManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ApiManagementClient API (version 2017-03-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/apimanagement-apimnetworkstatus/2017-03-01/swagger.json<br/>
Generated at: 2019-06-11T18:13:14+03:00

## API Description

Use these REST APIs for getting the network connectivity status of your Azure API Management deployment. When the API Management service is deployed inside a Virtual Network, it needs to have access to other Azure resources it depends on. This also gives details about the DNS Servers visible to Azure API Management deployment.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets the Connectivity Status to the external resources on which the Api Management service depends from inside the Cloud Service. This also returns the DNS Servers as visible to the CloudService.

*Tags:* `NetworkStatus`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `locationName` - _required_ - Location in which the API Management service is deployed. This is one of the Azure Regions like West US, East US, South Central US.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Gets the Connectivity Status to the external resources on which the Api Management service depends from inside the Cloud Service. This also returns the DNS Servers as visible to the CloudService.

*Tags:* `NetworkStatus`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `api-version` - _required_ - Version of the API to be used with the client request.

## License

**flow**ground :- Telekom iPaaS / azure-com-apimanagement-apimnetworkstatus-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
