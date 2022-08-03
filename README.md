# weebysnc-oauth
### Minimal C oauth 2.0 authentication ilbrary using libcurl and libmicrohttpd

This library is heavily insipred by https://github.com/slugonamission/OAuth2
but aims to add extra missing functionality like handle browser opening/code retrieval,
access token refresh, state saving, etc.

### Missing functionality

- IMPORTANT Access token refresh functionality
using the refresh token.

- RELEVANT Handling on auth callback different than
application/json

- UNIMPORTANT Better handling on browser opening and
code retrieval (I'd like to use protocol
handlers but implementing on many platforms
seems hard)

- UNIMPORTANT Simplification of the codebase to
remove the use of tiny-json and
(if possible) libmicrohttpd

### Contributing

Any contribution is welcome and should be done through a pull request.
