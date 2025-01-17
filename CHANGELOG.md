# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.5.2] - 2023-05-04
### Updated
- Switched to using a Firefox user-agent, and added XSRF token GET call.

## [0.5.1] - 2023-02-04
### Updated
- Updated the version of requests-pkcs12 we rely on to avoid deprecation warnings.

## [0.5.0] - 2023-01-17
### Added
- Added the ability to control cookiejar saving. Autosave can be disabled
  and the session cookies can now be saved at any time, not just on close.

## [0.4.0] - 2022-09-12
### Added
- Added the ability to do initial authentication with username/password
  or with Kerberos tickets.
### Deprecated
- Passing the certfile/cert password as their own arguments is now deprecated.
  Use the new `auth_type` argument to pass authentication information.
### New contributors
- Nickolai Zeldovich (zeldovich)

## [0.3.1] - 2022-02-23
### Added
- Added the ability to load a wider variety of Bearer tokens (Tim tickets)

## [0.3.0] - 2022-01-15
### Added
- Added the ability to use phone-call second factor.
- Added additional constructor argument to select between
  available second factor options.
- Added typing-extensions to dependencies to properly support
  Python 3.6 and Python 3.7

## [0.2.0]
### Added
- First working version of the touchstone auth.