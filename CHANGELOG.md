# Change Log

## [2.0.2] - 2022-01-10
- Fixed version number comparisons for when a version segment reaches two digits

## [2.0.1] - 2021-09-17
- Fixed console status reporting of whether or not errors were found

## [2.0.0] - 2021-08-30
- Significant changes to the CLI arguments with the tool to reduce complexity for users
- Removed need for scanning schema files for performing testing of a service

## [1.1.8] - 2021-06-18
- Corrected conditional requirements to properly account for all values specified

## [1.1.7] - 2020-03-21
- Resynched common validation code with the Service Validator

## [1.1.6] - 2020-03-13
- Added support for `IfPopulated` expressions
- Added support for `@Redfish.ActionInfo` on actions

## [1.1.5] - 2020-01-17
- Added htmlLogScraper.py to generate a CSV style report

## [1.1.4] - 2019-07-19
- Downgraded several messages not related to interop profile conformance to be informational
- Fixes to handling of conditional requirements to not produce false errors

## [1.1.3] - 2019-06-21
- Added support for new URIs requirement added to 1.1.0 of the profile specification
- Made fixes to the handling of the `CompareProperty` term
- Made fix to the handling of `IfImplemented` to not treat it as mandatory
- Made fix to tracking of Service Root requirements
- Made enhancements to debug log output

## [1.1.2] - 2019-05-31
- Updated schema pack to 2019.1

## [1.1.1] - 2019-05-10
- Made fixes to version comparison testing

## [1.1.0] - 2019-04-12
- Added missing @odata.context initialization for Message Registries

## [1.0.9] - 2019-02-08
- Updated schema pack to 2018.3
- Fixed handling of the Redfish.Revisions term

## [1.0.8] - 2018-10-19
- Fixed how single entry comparisons were performed

## [1.0.7] - 2018-09-21
- Various bug fixes
- Added tool versioning
- Added profile names and hashes to test output

## [1.0.6] - 2018-09-07
- More updates to leverage common code with the Redfish-Service-Validator tool

## [1.0.5] - 2018-08-17
- Refactored project to leverage common service traversal code used in the Redfish-Service-Validator tool

## [1.0.4] - 2018-07-06
- Added support for validating requirements described by profiles listed in "RequiredProfiles"

## [1.0.3] - 2018-04-13
- Added prevention of invalid properties from being checked further

## [1.0.2] - 2018-03-16
- Fixed usage of the Protocol property to allow for it to be missing in the profile
- Added checking for invalid properties in payloads

## [1.0.1] - 2018-03-02
- Change "comply" to "conform" in various output messages

## [1.0.0] - 2018-01-26
- Initial release; conformant with version 1.0.0 of DSP0272
