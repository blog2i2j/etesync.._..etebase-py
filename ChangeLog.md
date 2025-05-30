# Changelog

## Version 0.31.8
* Build for Python 3.12

## Version 0.31.7
* Bump etebase dependency to latest

## Version 0.31.6
* Bump multiple dependencies to fix building with Rust 1.64

## Version 0.31.5
* Bump flapigen and cpython deps to potentially fix crashes with Python 3.9 and 3.10

## Version 0.31.4
* Disable musllinux which currently fails build

## Version 0.31.3
* Build for Python 3.10

## Version 0.31.2
* Fix crashes with Python 3.9

## Version 0.31.1
* Fix exposing the Utils class

## Version 0.31.0
* Fix issue with custom urls lacking a trailing slash
* Account: expose the login_key and signup_key variants.
* Update etebase dependency

## Version 0.30.0
* Login: automatically init the account if not init
* Have global and immutable collection types (changes the create and list APIs)
* Update etebase dependency

## Version 0.21.1
* Invitations: expose from_username
* Update etebase dep

## Version 0.21.0
* Use new and shorter fingerprint pretty format
* Update etebase dep

## Version 0.20.2
* CI: statically link Windows C runtime on Windows
* CI: change how we build the wheels to fix Windows link issue

## Version 0.20.1
* Fix errors when setting item and collection metadata

## Version 0.20.0
* Expose access level values
* Rename API_URL to DEFAULT_SERVER_URL and update etebase dep.
* Add an API function to check if it's an etebase server.
* Update etebase dep

## Version 0.2.1
* Update etebase dep

## Version 0.2.0
* ItemManager: implement item revisions fetching.
* Fix `UserProfile` member manager and invitation manager.
* Expose `pretty_fingerprint` for pretty fingerprint printing
* Make `deps`/`fetch_options` parameters optional.
* Expose `randombytes` for generating random data
* Expose `API_URL` and add a default parameter to the Client constructor.
* Base64Url: improve the python bindings of this class

## Version 0.1.0
* Initial commit
