# ![LOGO](logo.png) Compute Admin Client **flow**ground Connector

## Description

A generated **flow**ground connector for the Compute Admin Client API (version 2015-12-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-VMExtensions/2015-12-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:37:37+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns a list of all Virtual Machine Extension Images.

> List of all Virtual Machine Extension Images for the current location are returned.

*Tags:* `VMExtensions`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Location of the resource.
* `api-version` - _required_ - Client API Version.

### Deletes a Virtual Machine Extension Image.

> Deletes specified Virtual Machine Extension Image.

*Tags:* `VMExtensions`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Location of the resource.
* `publisher` - _required_ - Name of the publisher.
* `type` - _required_ - Type of extension.
* `version` - _required_ - The version of the resource.
* `api-version` - _required_ - Client API Version.

### Returns requested Virtual Machine Extension Image.

> Returns requested Virtual Machine Extension Image matching publisher, type, version.

*Tags:* `VMExtensions`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Location of the resource.
* `publisher` - _required_ - Name of the publisher.
* `type` - _required_ - Type of extension.
* `version` - _required_ - The version of the resource.
* `api-version` - _required_ - Client API Version.

### Create a Virtual Machine Extension Image.

> Create a Virtual Machine Extension Image with publisher, version.

*Tags:* `VMExtensions`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Location of the resource.
* `publisher` - _required_ - Name of the publisher.
* `type` - _required_ - Type of extension.
* `version` - _required_ - The version of the resource.
* `api-version` - _required_ - Client API Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-vm-extensions-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
