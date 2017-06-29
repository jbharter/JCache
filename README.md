# FlashCache
A quick class to provide a lightweight cache wrapper on top of the ConcurrentHashMap class

This is my attempt at a lightweight caching type. There is probably a better built in implementation, but since I like to make things more difficult for myself, I created one on my own! This was created as an extension on the ConcurrentHashMap class, in an effort to provide an upper bound for the number of objects allowed.