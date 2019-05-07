# ![LOGO](logo.png) Native Ads Publisher **flow**ground Connector

## Description

A generated **flow**ground connector for the Native Ads Publisher API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/nativeads.com/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:43:07+03:00

## API Description

This is a Native Ads Publisher API it provides same functionality as Native Ads Publisher Account GUI.


## Authorization

This API does not require authorization.

## Actions

### Returns Native Ads Publisher API token

*Tags:* `auth`

### Returns publisher statistics split by date

*Tags:* `reports`

#### Input Parameters
* `token` - _required_ - Native Ads Publisher API authentication token
* `startDate` - _required_ - start date in format YYYY-MM-DD
* `endDate` - _required_ - end date in format YYYY-MM-DD
* `limit` - _required_ - maximum number of results per page
* `page` - _required_ - page number

### Returns publisher statistics split by website

*Tags:* `reports`

#### Input Parameters
* `token` - _required_ - Native Ads Publisher API authentication token
* `startDate` - _required_ - start date in format YYYY-MM-DD
* `endDate` - _required_ - end date in format YYYY-MM-DD
* `limit` - _required_ - maximum number of results per page
* `page` - _required_ - page number

### Returns publisher statistics split by widget

*Tags:* `reports`

#### Input Parameters
* `token` - _required_ - Native Ads Publisher API authentication token
* `startDate` - _required_ - start date in format YYYY-MM-DD
* `endDate` - _required_ - end date in format YYYY-MM-DD
* `limit` - _required_ - maximum number of results per page
* `page` - _required_ - page number

## License

**flow**ground :- Telekom iPaaS / nativeads-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
