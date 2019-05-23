# ![LOGO](logo.png) Enterprise License Manager **flow**ground Connector

## Description

A generated **flow**ground connector for the Enterprise License Manager API (version v1).

Generated from: https://api.apis.guru/v2/specs/googleapis.com/licensing/v1/swagger.json<br/>
Generated at: 2019-05-23T12:13:28+03:00

## API Description

Views and manages licenses for your domain.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Assign License.

*Tags:* `licenseAssignments`

#### Input Parameters
* `productId` - _required_ - Name for product
* `skuId` - _required_ - Name for sku
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Revoke License.

*Tags:* `licenseAssignments`

#### Input Parameters
* `productId` - _required_ - Name for product
* `skuId` - _required_ - Name for sku
* `userId` - _required_ - email id or unique Id of the user
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Get license assignment of a particular product and sku for a user

*Tags:* `licenseAssignments`

#### Input Parameters
* `productId` - _required_ - Name for product
* `skuId` - _required_ - Name for sku
* `userId` - _required_ - email id or unique Id of the user
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Assign License. This method supports patch semantics.

*Tags:* `licenseAssignments`

#### Input Parameters
* `productId` - _required_ - Name for product
* `skuId` - _required_ - Name for sku for which license would be revoked
* `userId` - _required_ - email id or unique Id of the user
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Assign License.

*Tags:* `licenseAssignments`

#### Input Parameters
* `productId` - _required_ - Name for product
* `skuId` - _required_ - Name for sku for which license would be revoked
* `userId` - _required_ - email id or unique Id of the user
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List license assignments for given product and sku of the customer.

*Tags:* `licenseAssignments`

#### Input Parameters
* `customerId` - _required_ - CustomerId represents the customer for whom licenseassignments are queried
* `maxResults` - _optional_ - Maximum number of campaigns to return at one time. Must be positive. Optional. Default value is 100.
* `pageToken` - _optional_ - Token to fetch the next page.Optional. By default server will return first page
* `productId` - _required_ - Name for product
* `skuId` - _required_ - Name for sku
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List license assignments for given product of the customer.

*Tags:* `licenseAssignments`

#### Input Parameters
* `customerId` - _required_ - CustomerId represents the customer for whom licenseassignments are queried
* `maxResults` - _optional_ - Maximum number of campaigns to return at one time. Must be positive. Optional. Default value is 100.
* `pageToken` - _optional_ - Token to fetch the next page.Optional. By default server will return first page
* `productId` - _required_ - Name for product
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

## License

**flow**ground :- Telekom iPaaS / googleapis-com-licensing-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
