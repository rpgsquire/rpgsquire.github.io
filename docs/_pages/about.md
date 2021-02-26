---
permalink: /about/
title: "About RPG Squire"
---

RPG Squire is an online character management and game-management system for tabletop RPG's, making it easy to create and maintain characters during the entire lifetime of the game.

It is an online web-service - allowing users to access their characters from any computer or device, 

## Technical Details
The Squire Game System (SGS) is a dynamic calculation and management system with a few key distinctions:
* Written in [Go](http://golang.org)
* Available as a WebAssembly binary, so it runs at nearly-native speeds!
   * The Go-framework used to generate the WASM interface is the [maxence-charriere/go-app](https://github.com/maxence-charriere/go-app) system.
* Utilizes a dynamic-content system based on collections of JSON files.
