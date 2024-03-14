# Changelog

## [Unreleased]

## 2.1.0 - 2024-03-14
- Added optional parameter force_fcm_v1 for PushClient initialization. If True, it will send Android notifications via FCM V1.

## 2.0.0 - 2021-03-17
- Changed requests library to use Sessions
- Used chunks for checking push receipts as per expo docs
- Changing to 2.0.0 to indicate the breaking change in 1.0.2

## 1.0.3 - 2021-03-08
- Fixed typo in previous release causing crash sending push tickets

## 1.0.2 - 2021-03-07
- Renamed variables / classes to confirm with the expo documentation
- This version will require code modifications (renaming of some classes)
- Breaking change, should have been renamed to v2.0.0

## 1.0.1 - 2021-02-15
- Add support for push receipt InvalidCredentials error

## 1.0.0 - 2020-11-17
- Add chunking to multiple publishing
- Configurable timeout
- PushResponse returns message ID
- Implemenet push/getReceipts

## 0.3.0 - 2019-08-22
## 0.3.1 - 2019-08-22

## [0.2.0] - 2018-07-13
### Added
- Support for `channel_id` (https://github.com/expo/exponent-server-sdk-python/pull/14 thanks @raphaelrk)
