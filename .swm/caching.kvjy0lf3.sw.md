---
id: kvjy0lf3
title: Caching
file_version: 1.1.3
app_version: 1.12.1
---

## Animation Cache

`AnimationCacheProvider` is a protocol that describes an Animation Cache. Animation Cache is used when loading `Animation` models. Using an Animation Cache can increase performance when loading an animation multiple times.

Lottie comes with a prebuilt LRU Animation Cache.

### LRUAnimationCache

An Animation Cache that will store animations up to `cacheSize`. Once `cacheSize` is reached, the least recently used animation will be ejected. The default size of the cache is 100.

LRUAnimationCache has a global `sharedCache` that is used to store the animations.

You may also call `LRUAnimationCache.sharedCache.clearCache()` to clear the cache.

<br/>

This file was generated by Swimm. [Click here to view it in the app](https://swimm-web-app.web.app/repos/Z2l0aHViJTNBJTNBbG90dGllLWlvcyUzQSUzQXVzZXJ0ZXN0aW5nLXN3aW1t/docs/kvjy0lf3).
