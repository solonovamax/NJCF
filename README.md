# NJCF
Not Just a Command Framework - a Java command framework for the popular JDA library.

This is currently still in development. No feature is guaranteed to remain the same for the final release,
nor is it guaranteed to be implemented; any feature list is a list of possible future features.

## About

NFCF is a framework for bots to use that already has many of the common features such as
databases, permission handling, command handling and more. 
Its goal is to make it easier to produce complex bots. 

This framework is a basic bot framework whose goal is to make it easier for developers to produce bigger and better bots,
with not as much effort.

## Features

- Command handling system.
  - Handling for command names and aliases
  - Parses command arguments and creates representing objects
    - You can define your own parsers for your own types
  - Automatically asks users for arguments if not provided
  - Built in help and ping commands
  - Throttle handling
- Database management
  - SQLite support
  - MySQL support
  - MongoDB support
  - Allows for easy persistent storage of properties for users and guilds
  - Manages all database communication and provides various entities, such as guild, user and member entities
- Easy audio integration
  - quickly play audio from various services
    - YouTube
    - SoundCloud
    - Spotify
    - Mp3 Files
- Automatically uses caching and threading to optimize performance
  - This is black magic, I have no clue how any of it works


