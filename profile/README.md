# VOD Downloaders

Welcome to my central hub for VOD downloading related projects. The projects listed below support downloading off of various places like [Dispatcharr](https://github.com/Dispatcharr/Dispatcharr) and [freemediaheckyeah](https://fmhy.net/video) sites.  
These projects are largely written in Rust :crab: as an attempt for [me](https://github.com/ggjorven) to learn more about the language.  

## Projects

The user-facing functionality is spread across these projects:

- [FMHY-Downloader](https://github.com/VOD-Downloaders/FMHY-Downloader) - Docker container with WebUI for downloading VODs off of [FMHY](https://fmhy.net/video) sites. [![Development state](https://img.shields.io/badge/state-beta-mediumseagreen)](https://github.com/VOD-Downloaders/FMHY-Downloader)
- [FMHY-Indexers](https://github.com/VOD-Downloaders/FMHY-Indexers) - Collection of [FMHY](https://fmhy.net/video) indexers to be used in conjunction with [FMHY-Downloader](https://github.com/VOD-Downloaders/FMHY-Downloader). [![Development state](https://img.shields.io/badge/state-beta-mediumseagreen)](https://github.com/VOD-Downloaders/FMHY-Indexers)
- [FMHY-Bridge](https://github.com/VOD-Downloaders/FMHY-Bridge) - Documentation for stream enc- and decryption endpoints for [FMHY-Downloader](https://github.com/VOD-Downloaders/FMHY-Downloader). [![Development state](https://img.shields.io/badge/state-production-steelblue)](https://github.com/VOD-Downloaders/FMHY-Bridge)
- [Dispatcharr-cli](https://github.com/VOD-Downloaders/Dispatcharr-cli) - Command-line interface for downloading VODs off [Dispatcharr](https://github.com/Dispatcharr/Dispatcharr). [![Development state](https://img.shields.io/badge/state-alpha-yellow)](https://github.com/VOD-Downloaders/Dispatcharr-cli)
- [Dispatcharr-plugin](https://github.com/VOD-Downloaders/Dispatcharr-plugin) - Plugin to extend [Dispatcharr](https://github.com/Dispatcharr/Dispatcharr)'s VOD downloading capabilities. [![Development state](https://img.shields.io/badge/state-unstarted-indianred
)](https://github.com/VOD-Downloaders/Dispatcharr-plugin)

## Core

The core functionality is created in these "core" projects which are then used in the plugins or cli tools.

- [Dispatcharr-core](https://github.com/VOD-Downloaders/Dispatcharr-core) - Core functions for downloading off of [Dispatcharr](https://github.com/Dispatcharr/Dispatcharr) sites. [![Development state](https://img.shields.io/badge/state-alpha-yellow
)](https://github.com/VOD-Downloaders/Dispatcharr-core)

## Supporting 

Supporting projects which have been created to help the goal of easy VOD downloading.

- [TMDB-Proxy](https://github.com/VOD-Downloaders/TMDB-Proxy) - Easily deployable proxy of the TMDB API for Vercel. [![Development state](https://img.shields.io/badge/state-beta-mediumseagreen)](https://github.com/VOD-Downloaders/TMDB-Proxy)

## Sources

- [Dispatcharr](https://github.com/Dispatcharr/Dispatcharr) - **Dispatcharr**, Self-hosted IPTV proxy.
- [FMHY's video list](https://fmhy.net/video) - **freemediaheckyeah**, The largest collection of free stuff on the internet!
