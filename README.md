# ![LOGO](logo.png) Azure Dedicated HSM Resource Provider **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure Dedicated HSM Resource Provider API (version 2018-10-31-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/hardwaresecuritymodules-dedicatedhsm/2018-10-31-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:12+03:00

## API Description

The Azure management API provides a RESTful set of web services that interact with Azure Dedicated HSM RP.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### The List operation gets information about the dedicated HSMs associated with the subscription.

*Tags:* `DedicatedHsms`

#### Input Parameters
* `$top` - _optional_ - Maximum number of results to return.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### The List operation gets information about the dedicated hsms associated with the subscription and within the specified resource group.

*Tags:* `DedicatedHsms`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Resource Group to which the dedicated HSM belongs.
* `$top` - _optional_ - Maximum number of results to return.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes the specified Azure Dedicated HSM.

*Tags:* `DedicatedHsms`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Resource Group to which the dedicated HSM belongs.
* `name` - _required_ - The name of the dedicated HSM to delete
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the specified Azure dedicated HSM.

*Tags:* `DedicatedHsms`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Resource Group to which the dedicated hsm belongs.
* `name` - _required_ - The name of the dedicated HSM.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Update a dedicated HSM in the specified subscription.

*Tags:* `DedicatedHsms`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Resource Group to which the server belongs.
* `name` - _required_ - Name of the dedicated HSM
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Create or Update a dedicated HSM in the specified subscription.

*Tags:* `DedicatedHsms`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Resource Group to which the resource belongs.
* `name` - _required_ - Name of the dedicated Hsm
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-hardwaresecuritymodules-dedicatedhsm-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
