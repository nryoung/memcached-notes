Overview
========

Directly from the NewOverivew page:

    Free & open source, high-performance, distributed memory object caching system, generic in nature, but intended for use in speeding up dynamic web applications by alleviating database load.

Memcached keeps objects (of any kind) in memory for a certain period of time. This allows for fast retrievals from memory instead of accessing data from the Database every time.

Components that make up memcached:

* Client software, which has a list of memcache servers. Also, has a hashing algorithm so it knows which server to choose based on the 'key' of the input.
* Server software, which stores the key/value pairs into an internal hash table. Also, has algorithms to know when to throw out or 'expire' data in cache.


If it is still not apparent what memcached _is_ then checkout this awesome story put together by the memcached team:

    https://code.google.com/p/memcached/wiki/TutorialCachingStory
