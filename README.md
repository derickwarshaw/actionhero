# actionhero.js

## The Reusable, Scalable, and Quick node.js API Server

![https://raw.github.com/actionhero/actionhero/master/public/logo/actionhero-small.png](https://raw.github.com/actionhero/actionhero/master/public/logo/actionhero-small.png)

***
**[NPM](https://npmjs.org/package/actionhero) | [Docs](http://actionherojs.com/docs/overview) | [Public Site](http://www.actionherojs.com) | [GitHub](https://github.com/actionhero/actionhero) | [Mailing List](https://groups.google.com/forum/?fromgroups=#!forum/actionhero-js) | [Chat](http://slack.actionherojs.com) | [Client](https://github.com/actionhero/actionhero-client)**
***

[![NPM Version](https://img.shields.io/npm/v/actionhero.svg?style=flat-square)](https://www.npmjs.com/package/actionhero)[![Node Version](https://img.shields.io/node/v/actionhero.svg?style=flat-square)](https://npmjs.org/package/actionhero)[![NPM](https://img.shields.io/npm/dm/actionhero.svg?style=flat-square)](https://npmjs.org/package/actionhero)[![Build Status](https://img.shields.io/travis/actionhero/actionhero/master.svg?style=flat-square)](http://travis-ci.org/actionhero/actionhero)[![Dependency Status](https://david-dm.org/actionhero/actionhero.svg?style=flat-square)](https://david-dm.org/actionhero/actionhero)[![Chat](http://slack.actionherojs.com/badge.svg)](http://slack.actionherojs.com)[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/l0oky/awesome-actionhero) [![Greenkeeper badge](https://badges.greenkeeper.io/actionhero/actionhero.svg)](https://greenkeeper.io/)


## Who is the ActionHero?
ActionHero is a multi-transport API Server with integrated cluster capabilities and delayed tasks. The goal of actionhero is to create an easy-to-use toolkit for making **reusable** & **scalable** APIs.  Clients connected to an actionhero server can [**consume the api**](http://www.actionherojs.com/docs/core/#actions), [**consume static content**](http://www.actionherojs.com/docs/core/#file-server), and [**communicate with each other**](http://www.actionherojs.com/docs/core/#chat).  ActionHero is cluster-ready, with built in support for background tasks, 0-downtime deploys, and more.

Currently actionhero supports the following out of the box...

- [Web Clients](http://www.actionherojs.com/docs/servers/#web): HTTP, HTTPS
- [Socket Clients](http://www.actionherojs.com/docs/servers/#socket): TCP (telnet), TLS
- [Web Socket Clients](http://www.actionherojs.com/docs/servers/#websocket): HTTP, HTTPS

[... and you can also make your own servers and transports.](http://www.actionherojs.com/docs/servers)

## Quick Start
```bash
# mkdir new_project; cd new_project
npm install actionhero
./node_modules/.bin/actionhero generate
npm start
```

Or deploy a web API server now:

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/actionhero/actionhero)

## Want more?

- [Getting Started](http://www.actionherojs.com/docs/overview/#getting-started)
- [Running actionhero](http://www.actionherojs.com/docs/overview/#install-and-quickstart)
- [Read the documentation](http://www.actionherojs.com/docs/overview/)
- [Find community-based resources](https://github.com/l0oky/awesome-actionhero)
- [See a Sample Project (simple)](https://github.com/actionhero/actionhero-tutorial)
- [See a Sample Project (elaborate)](https://github.com/actionhero/actionhero-angular-bootstrap-cors-csrf)
- [View the release history](https://github.com/actionhero/actionhero/releases/)

## Documentation
ActionHero's documentation can be found @ [http://www.actionherojs.com/docs/overview/](http://www.actionherojs.com/docs/overview/).  If you want to contribute to these docs, visit the [site](https://github.com/actionhero/actionhero/tree/master/site) folder of this project with more instructions.

## Who?

* The primary creator of the actionhero framework is [Evan Tahler](http://evantahler.com), but many others [have helped](https://github.com/actionhero/actionhero/graphs/contributors)
* If you want to contribute to actionhero, contribute to the conversation on [github](https://github.com/actionhero/actionhero)

###
