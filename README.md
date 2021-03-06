# ⚛ futureRX

> 🚀 The futuristic stack to create universal React applications with MobX as state manager. With supporting async data fetching out of the box on server side rendering.

WARNING: This is a proof of concept running on bleeding edge libraries, it has not been running in production yet. If you do [contact me](http://twitter.com/iam4x).

This project aim frontend applications which are using an external API to work with data. This boilerplate does not include an API with it to fetch/persist data.

## Libraries used

> **nodejs ^6.2** / **npm ^3.9**

  * #### react
    * [mobx](https://github.com/mobxjs/mobx)
    * [mobx-store](https://github.com/AriaFallah/mobx-store)
    * [react ^15](https://facebook.github.io/react/)
    * [react-router ^2.0.0](https://github.com/rackt/react-router)
    * [react-hot-loader ^3.0.0-beta](https://github.com/gaearon/react-hot-loader)
    * [why-did-you-update](https://github.com/garbles/why-did-you-update)

  * #### server side rendering
    * [koa ^2.0.0](http://koajs.com/)

  * #### tools
    * [webpack ^2.1.0-beta](http://webpack.github.io/)
    * [webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware)
    * [webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware)
    * [babeljs ^6.9](https://babeljs.io/)
    * [flowtype (via babel-plugin-typecheck)](https://github.com/codemix/babel-plugin-typecheck)
    * [browser-sync](https://www.browsersync.io)

## Setup

* `$ git clone https://github.com/iam4x/futureRX.git [myApp]`
* `$ cd [myApp] && npm install`

## Run

  * ### dev
    * `$ npm run dev` OR
    * `$ PORT=xxxx npm run dev`
    * (Append `?debugRender` to your URL to enable `why-did-you-update`)

  * ### test
    * `$ npm test` OR
    * `$ npm test -- --watch`

  * ### build
    * `$ NODE_ENV=production npm run build`
    * `$ NODE_ENV=production node server`

### TODO

* [ ] allow override of listening ports (config)
* [ ] test with ava and airbnb-enzyme
* [ ] inline styles (with postcss-modules)
* [ ] webpack build config
* [ ] production server optimization
* [ ] refactor server code

### Learn more

* [Official ReactJS website](http://facebook.github.io/react/)
* [Official ReactJS wiki](https://github.com/facebook/react/wiki)
* [Learn ES6](https://babeljs.io/docs/learn-es6/)
* [ES6 Features](https://github.com/lukehoban/es6features#readme)
