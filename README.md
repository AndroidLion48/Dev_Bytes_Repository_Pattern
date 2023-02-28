###DevByteRepository - Solution Code
==================================

DevByte application with the Repository Pattern implemented to cache data for persistent data.

#Introduction
------------

This app demonstrates the Repository pattern,
the recommended best practice for code separation and architecture. Using
repository pattern the data layer is abstracted from the rest of the app.
Repositories act as mediators between different data sources, such as persistent
models, web services, and caches and the rest of the app.  DevByteRepository app displays a list of DevByte videos. DevByte videos are
short videos made by the Google Android developer relations team to introduce
new developer features on Android. 

# Summary

- Caching is a process of storing data fetched from a network on a device's storage. Caching lets your app access data when the device is offline, or if your app needs to access the same data again.

- The best way for your app to store structured data on a device's file system is to use a local SQLite database. Room is an SQLite object-mapping library, meaning that it provides an abstraction layer over SQLite. Using Room is the recommended best practice for implementing offline caching.

- A repository class isolates data sources, such as a Room database and web services, from the rest of the app. The repository class provides a clean API for data access to the rest of the app.

- Using repositories is a recommended best practice for code separation and architecture.

- When you design an offline cache, it's a best practice to separate the app's network, domain, and database objects. This strategy is an example of separation of concerns.