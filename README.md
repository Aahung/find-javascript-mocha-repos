# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:11:37 09/06/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43447 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41259 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40024 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30232 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 26313 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24574 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23435 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19977 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19104 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17224 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16916 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16812 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15342 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14369 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14075 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13693 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13263 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12822 | `./node_modules/.bin/mocha test/` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12693 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12380 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12240 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12003 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11588 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11344 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11315 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10584 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10262 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10206 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10172 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10090 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10020 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9805 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 9487 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9423 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9198 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9178 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9046 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8797 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8789 | `mocha tests/*.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8783 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8531 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8522 | `mocha test/test.js` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8494 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8449 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8345 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8205 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8154 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8084 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7949 | `mocha --opts mocha.opts` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7921 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7746 | `./node_modules/.bin/mocha test` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7728 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [dthree/cash](https://github.com/dthree/cash) | 7560 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7454 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7442 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7319 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7306 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7294 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7146 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7088 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 7073 | `mocha --compilers js:babel-core/register` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7028 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6932 | `mocha $HARMONY_OPTS` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 6797 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js'` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6754 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6625 | `mocha; jshint *.js lib` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6509 | `npm run jshint && mocha test/` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6494 | `mocha --exit --require babel-core/register` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6392 | `mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6295 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6287 | `mocha test/test.js` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6248 | `npm run test:mocha:src` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6054 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6000 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5963 | `mocha tests/node.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5935 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5851 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5793 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5748 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5745 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5733 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5714 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 