# ![LOGO](logo.png) Azure SQL Server API spec **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure SQL Server API spec API (version 2014-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/sql-connectionPolicies/2014-04-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:01+03:00

## API Description

The Azure SQL Server management API provides a RESTful set of web services that interact with Azure SQL Server services to manage your databases. The API enables users update server connection policy.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets the server's secure connection policy.

*Tags:* `ConnectionPolicies`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `connectionPolicyName` - _required_ - The name of the connection policy.
    Possible values: default.

### Creates or updates the server's connection policy.

*Tags:* `ConnectionPolicies`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `connectionPolicyName` - _required_ - The name of the connection policy.
    Possible values: default.

## License

**flow**ground :- Telekom iPaaS / azure-com-sql-connection-policies-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
