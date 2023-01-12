# Change Log

## 1.0.0
- Web API:
    * Add ``highlight_reels()`` and ``highlight_reel_media()``
    * Add ``tagged_user_feed()``
    * Add ``tag_story_feed()`` and ``location_story_feed()``
    * Update query hashes
    * Fix for case sensitivity for tag feed
    * Add ``delete_media()``
    * Add ``proxy_handler`` kwarg to support custom proxy handler such as socks
- App API:
    * :fire: __BREAKING CHANGE__: Change in user agent format for the app version
    * :fire: __BREAKING CHANGE__: Change in argument list for ``search_users()``
    * Add IGTV endpoints
    * Update ``media_n_comments()``, ``search_users()``, ``news()``
    * ``feed_location()`` deprecated
    * Add ``kwargs`` to ``news()`` for paging support
    * Add ``tag_section()`` and ``location_section()`` endpoints
    * Add ``proxy_handler`` kwarg to support custom proxy handler such as socks

- access both the private Instagram app or web API
- CompatPatch patches the objects returned in the private API to match those returned in the public API
- can be used to largely replace the public Instagram API that is now severely restricted
