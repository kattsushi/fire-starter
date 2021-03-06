![FireLoop](https://storage.googleapis.com/fireloop/fireloop-gh-header.svg)

---

<h4 align="center" font-size="20px">

```javascript
  _____.__                                   __                 __                
_/ ____\__|______   ____             _______/  |______ ________/  |_  ___________ 
\   __\|  \_  __ \_/ __ \   ______  /  ___/\   __\__  \\_  __ \   __\/ __ \_  __ \
 |  |  |  ||  | \/\  ___/  /_____/  \___ \  |  |  / __ \|  | \/|  | \  ___/|  | \/
 |__|  |__||__|    \___  >         /____  > |__| (____  /__|   |__|  \___  >__|   
                       \/               \/            \/                 \/       
----------------------------------------------------------------------------------
@mean-expert-official                                       @fireloop/fire-starter
----------------------------------------------------------------------------------

```

</h4>
<hr>

[![All Contributors](https://img.shields.io/badge/all_contributors-3-orange.svg?style=flat-square)](#contributors)
&nbsp; [![Slack](https://fireloop-slack.now.sh/badge.svg)](http://slack.fireloop.io)
&nbsp; [![Build](https://travis-ci.org/mean-expert-official/fire-starter.svg)](https://travis-ci.org/)
&nbsp; <a href="https://heroku.com/deploy"><img src="https://img.shields.io/badge/deploy_to-heroku-79589F.svg" alt="Deploy" data-canonical-src="https://www.herokucdn.com/deploy/button.svg" style="max-width:100%;"></a>

> Starter kit for the <a href="http://fireloop.io"><b>fireloop.io</b></a> platform

## Features
> <b>note:</b> this repo includes experimental ngrx features in the sdk.  the plan is to eventually have the loopback-sdk-builder generate these ngrx files - until then, be aware that running `fireloop sdk` will overwrite the ngrx files in the sdk.

* <a href="http://fireloop.io">fireloop</a>
* <a href="https://angular.io/">angular</a>
* <a href="https://github.com/angular/angular-cli">angular-cli</a>
* <a href="http://loopback.io/doc/index.html">loopback</a>
* <a href="https://github.com/strongloop/loopback-cli">loopback-cli</a>
* <a href="https://github.com/mean-expert-official/loopback-sdk-builder">loopback-sdk-builder</a>
* <a href="https://github.com/mean-expert-official/loopback-component-realtime">loopback-component-realtime</a>
* <a href="https://github.com/ngrx/store">ngrx/store</a>
* <a href="https://github.com/ngrx/effects">ngrx/effects</a>
* <a href="http://v4-alpha.getbootstrap.com/">bootstrap 4</a>
* <a href="https://ng-bootstrap.github.io/#/home">ng-bootstrap</a>
* <a href="https://github.com/formly-js/ng-formly">ng-formly</a>
* <a href="https://limonte.github.io/sweetalert2/">sweetalert2</a>

## Setup
> This stack requires <b>node ^7.0.0</b> and <b>npm ^4.0.0</b>

```console
npm install -g @mean-expert/fireloop @angular/cli loopback-cli nodemon

git clone https://github.com/mean-expert-official/fire-starter.git
```

## Install
> From the root directory (fire-starter), execute:

```console
cd fire-starter

npm run install
```

This will run the install script, which installs all project dependencies in both the `api` and `webapp` directories.

## Development
> Open 2 separate console windows to fire up the api server and webapp dev server separately
1. <b>api server</b>
```console
cd fire-starter/api

npm run dev
```
> the api explorer will be available at <b>`localhost:3000/explorer`</b>

2. <b>webapp dev server</b>
```console
cd fire-starter/webapp

npm run dev
```
> your webapp will be served at <b>`localhost:4200`</b>

With both servers running, you can now begin development with live-reload and file-watching on both the client and server.

## Contributors

Thanks goes to these wonderful people ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
| [<img src="https://avatars0.githubusercontent.com/u/36491?v=3" width="100px;"/><br /><sub>Bram Borggreve</sub>](http://colmena.io/)<br />[💻](https://github.com/beeman/fireloop-starter/commits?author=beeman) | [<img src="https://avatars2.githubusercontent.com/u/6089253?v=3" width="100px;"/><br /><sub>Brannon N. Darby II</sub>](https://github.com/brannon-darby)<br />[💻](https://github.com/beeman/fireloop-starter/commits?author=brannon-darby) | [<img src="https://avatars1.githubusercontent.com/u/12107518?v=3" width="100px;"/><br /><sub>Andres David Jimenez</sub>](https://plus.google.com/+AndresJimenezS/posts)<br />[💻](https://github.com/beeman/fireloop-starter/commits?author=kattsushi) |
| :---: | :---: | :---: |
<!-- ALL-CONTRIBUTORS-LIST:END -->
This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification. Contributions of any kind welcome!

