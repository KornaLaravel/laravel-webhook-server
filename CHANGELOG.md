# Changelog

All notable changes to `laravel-webhook-server` will be documented in this file

## 3.8.3 - 2025-02-14

### What's Changed

* Laravel 12.x Compatibility by @laravel-shift in https://github.com/spatie/laravel-webhook-server/pull/162

### New Contributors

* @laravel-shift made their first contribution in https://github.com/spatie/laravel-webhook-server/pull/162

**Full Changelog**: https://github.com/spatie/laravel-webhook-server/compare/3.8.2...3.8.3

## 3.8.2 - 2024-12-16

### What's Changed

* Fix CallWebhookJob behaviour when throwExceptionOnFailure is true by @cristian-fleischer in https://github.com/spatie/laravel-webhook-server/pull/161

### New Contributors

* @cristian-fleischer made their first contribution in https://github.com/spatie/laravel-webhook-server/pull/161

**Full Changelog**: https://github.com/spatie/laravel-webhook-server/compare/3.8.1...3.8.2

## 3.8.1 - 2024-02-12

### What's Changed

* Add support for laravel 11 by @shuvroroy in https://github.com/spatie/laravel-webhook-server/pull/154
* Corrected typos in README.md and webhook-server.php by @OussamaMater in https://github.com/spatie/laravel-webhook-server/pull/151

### New Contributors

* @OussamaMater made their first contribution in https://github.com/spatie/laravel-webhook-server/pull/151

**Full Changelog**: https://github.com/spatie/laravel-webhook-server/compare/3.8.0...3.8.1

## 3.8.0 - 2023-11-27

3.8.0

### What's Changed

* Add event that is being fired upon the webhook's dispatch by @thannaske in https://github.com/spatie/laravel-webhook-server/pull/150

### New Contributors

* @thannaske made their first contribution in https://github.com/spatie/laravel-webhook-server/pull/150

**Full Changelog**: https://github.com/spatie/laravel-webhook-server/compare/3.7.0...3.8.0

## 3.7.0 - 2023-11-20

### What's Changed

- Adds support for mutual TLS by @JonErickson in https://github.com/spatie/laravel-webhook-server/pull/149

### New Contributors

- @JonErickson made their first contribution in https://github.com/spatie/laravel-webhook-server/pull/149

**Full Changelog**: https://github.com/spatie/laravel-webhook-server/compare/3.6.0...3.7.0

## 3.6.0 - 2023-09-25

### What's Changed

- Fix webhook event type for raw body by @DotNetSimon in https://github.com/spatie/laravel-webhook-server/pull/147

**Full Changelog**: https://github.com/spatie/laravel-webhook-server/compare/3.5.0...3.6.0

## 3.5.0 - 2023-09-12

### What's Changed

- Webhook option to allow sending a raw body instead of array -> json. by @DotNetSimon in https://github.com/spatie/laravel-webhook-server/pull/146

### New Contributors

- @DotNetSimon made their first contribution in https://github.com/spatie/laravel-webhook-server/pull/146

**Full Changelog**: https://github.com/spatie/laravel-webhook-server/compare/3.4.3...3.5.0

## 3.4.3 - 2023-03-17

### What's Changed

- Change to protected properties `$response`, `$errorType` and `$errorMessage` in `CallWebhookJob`  by @Kazuto in https://github.com/spatie/laravel-webhook-server/pull/143

**Full Changelog**: https://github.com/spatie/laravel-webhook-server/compare/3.4.2...3.4.3

## 3.4.2 - 2023-01-25

### What's Changed

- Fixes a couple of minor typographical errors. by @cxj in https://github.com/spatie/laravel-webhook-server/pull/141
- support Laravel 10.0 by @hihuangwei in https://github.com/spatie/laravel-webhook-server/pull/142

### New Contributors

- @cxj made their first contribution in https://github.com/spatie/laravel-webhook-server/pull/141
- @hihuangwei made their first contribution in https://github.com/spatie/laravel-webhook-server/pull/142

**Full Changelog**: https://github.com/spatie/laravel-webhook-server/compare/3.4.1...3.4.2

## 3.4.1 - 2023-01-10

### What's Changed

- Add PHP 8.2 Support by @patinthehat in https://github.com/spatie/laravel-webhook-server/pull/138
- Convert all tests to pest by @alexmanase in https://github.com/spatie/laravel-webhook-server/pull/139
- Refactored Request to Method by @JamesFreeman in https://github.com/spatie/laravel-webhook-server/pull/140

### New Contributors

- @patinthehat made their first contribution in https://github.com/spatie/laravel-webhook-server/pull/138
- @alexmanase made their first contribution in https://github.com/spatie/laravel-webhook-server/pull/139
- @JamesFreeman made their first contribution in https://github.com/spatie/laravel-webhook-server/pull/140

**Full Changelog**: https://github.com/spatie/laravel-webhook-server/compare/3.4.0...3.4.1

## 3.4.0 - 2022-11-16

### What's Changed

- Add proxy option by @andycowan in https://github.com/spatie/laravel-webhook-server/pull/136

### New Contributors

- @andycowan made their first contribution in https://github.com/spatie/laravel-webhook-server/pull/136

**Full Changelog**: https://github.com/spatie/laravel-webhook-server/compare/3.3.0...3.4.0

## 3.3.0 - 2022-11-09

### What's Changed

- Add missing config documentation to readme by @Kazuto in https://github.com/spatie/laravel-webhook-server/pull/134
- Add option for configurable Webhook Job by @Kazuto in https://github.com/spatie/laravel-webhook-server/pull/135

### New Contributors

- @Kazuto made their first contribution in https://github.com/spatie/laravel-webhook-server/pull/134

**Full Changelog**: https://github.com/spatie/laravel-webhook-server/compare/3.2.1...3.3.0

## 3.2.1 - 2022-07-29

### What's Changed

- Allow sub-classes of `CallWebhookJob` to use a `GuzzleHttp\Client` specific for outgoing webhooks by @bezhermoso in https://github.com/spatie/laravel-webhook-server/pull/125

**Full Changelog**: https://github.com/spatie/laravel-webhook-server/compare/3.2.0...3.2.1

## 3.2.0 - 2022-06-24

### What's Changed

- feat: add dispatchIf, dispatchUnless, dispatchSyncIf and dispatchSync… by @regnerisch in https://github.com/spatie/laravel-webhook-server/pull/124

### New Contributors

- @regnerisch made their first contribution in https://github.com/spatie/laravel-webhook-server/pull/124

**Full Changelog**: https://github.com/spatie/laravel-webhook-server/compare/3.1.2...3.2.0

## 3.1.2 - 2022-01-26

- support Laravel 9

## 3.1.1 - 2021-12-10

## What's Changed

- Include Exception with Laravel queue failures by @awarrenlove in https://github.com/spatie/laravel-webhook-server/pull/114

**Full Changelog**: https://github.com/spatie/laravel-webhook-server/compare/3.1.0...3.1.1

## 3.0.0 - 2021-09-10

- support using webhook URLs as part of webhook signatures (#98)

The only breaking change in this release is the addidation of `string $webhookUrl` to the `calculateSignature` method of the `Signer` interface.
If you have a custom `Signer` in your project, add that `$webhookUrl` to the `calculateSignature` method.

## 2.1.1 - 2021-08-27

- add ability to use default queue of connection (#94)

## 2.1.0 - 2021-08-01

- allow setting queue connection (#92)

## 2.0.1 - 2021-07-23

- fix tests

## 2.0.0 - 2021-07-23

- require Laravel 8
- require PHP 8

No changes to the API were made, so you can safely upgrade from v1 to v2

## 1.13.0 - 2021-04-28

- add `dispatchSync`

## 1.12.0 - 2021-04-20

- pass Guzzle TransferStats into resulting Event (#81)

## 1.11.3 - 2021-04-02

- fix for missing default headers when using withHeaders (#79)

## 1.11.2 - 2021-03-17

- dispatch should return the PendingDispatch (#74)

## 1.11.1 - 2020-12-15

- fix exception name for invalid signers (#67)

## 1.11.0 - 2020-11-28

- add support for PHP 8

## 1.10.0 - 2020-10-04

- add `getUuid`

## 1.9.3 - 2020-09-09

- support Guzzle 7

## 1.9.2 - 2020-09-09

- support Laravel 8

## 1.9.1 - 2020-04-10

- do not use body in GET request (#43)

## 1.9.0 - 2020-03-19

- add `doNotSign`

## 1.8.1 - 2020-03-19

- fix `uuid`

## 1.8.0 - 2020-03-18

- add `uuid`

## 1.7.0 - 2020-03-05

- add `dispatchNow` (#39)

## 1.6.0 - 2020-03-02

- add support for Laravel 7

## 1.5.0 - 2019-12-08

- drop support for PHP 7.3

## 1.4.0 - 2019-09-05

- add error info to the dispatched event

## 1.3.1 - 2019-09-05

- remove duplicate line

## 1.3.0 - 2019-09-04

- do not release job on last attempt

## 1.2.0 - 2019-09-04

- add `getResponse`

## 1.1.0 - 2019-09-04

- Add Laravel 6 support

## 1.0.5 - 2019-07-24

- avoid sending unsuccessfull event when the final try of a job succeeds

## 1.0.4 - 2019-06-22

- remove constructor on `WebhookCallFailedEvent` so it inherits properties

## 1.0.3 - 2019-06-19

- add `ContentType` header with value `application/json` by default

## 1.0.2 - 2019-06-16

- move `test-time` to dev dependencies

## 1.0.1 - 2019-06-15

- fixed method names

## 1.0.0 - 2019-06-15

**contains bug, do not use**

- initial release
