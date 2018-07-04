# DwebTransports
Transport library for dweb extension.

## Background
This library is part of a general project at the Internet Archive (archive.org) 
to support the decentralized web.

### Node Installation
* Clone this repo. 
* To install dependencies `npm install`
* To build the bundled javascript file `npm run-script build`. The file dist/transports-bundle.js is the output.

###Repos:
* *dweb-transports:* Common API to underlying transports (http, webtorrent, ipfs, yjs)
* *dweb-objects:* Object model for Dweb inc Lists, Authentication, Key/Value, Naming
* *dweb-serviceworker:* Run Transports in ServiceWorker (experimental)
* *dweb-archive:* Decentralized Archive webpage and bootstrapping 
* *dweb-transport:* Original Repo, still includes examples but being split into smaller repos
