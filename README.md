# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:50 09/29/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43701 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41390 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40362 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30363 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 26847 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24676 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 24610 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23707 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20208 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19263 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17459 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17056 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17008 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15566 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14399 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14211 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13938 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13377 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12991 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12738 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12452 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12261 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12181 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11704 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11520 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11494 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10718 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10408 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10331 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10260 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10146 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10096 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10027 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9974 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 9641 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9461 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9382 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9277 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9240 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9076 | `grunt mocha` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8963 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8917 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 8905 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8871 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8602 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8548 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8466 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8354 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8262 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8230 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8113 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7941 | `npm run eslint && npm run mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7853 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7768 | `./node_modules/.bin/mocha test` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7475 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7440 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7411 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7398 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7397 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7271 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7228 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [almende/vis](https://github.com/almende/vis) | 7150 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7128 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6963 | `mocha $HARMONY_OPTS` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 6910 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6807 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6801 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6660 | `mocha --exit --require @babel/register` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6622 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6578 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6351 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6335 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6277 | `npm run test:mocha:src` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6051 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6050 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6026 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6012 | `mocha tests/node.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5889 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5816 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5786 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5769 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5768 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5709 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5472 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5470 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5458 | `standard && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5416 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5250 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5202 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5184 | `mocha src/**/*Tests.js --harmony` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5168 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5146 | `mocha --color` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5129 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5018 | `gulp lint && mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4341 | `nyc mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4341 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4206 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4173 | `nyc mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4149 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4132 | `mocha --timeout=15000 tests/*.test.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4079 | `npm run lint ; mocha && mocha test/individual` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4072 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4055 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4053 | `mocha --require test/babel-hook test/*.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 4051 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4048 | `nyc --require ./test/helpers/register _mocha -- test/tests/index.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4017 | `mocha --require should --reporter spec` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3957 | `mocha --check-leaks --reporter spec --bail` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3944 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4443 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4386 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4341 | `nyc mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4341 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4247 | `mocha -R spec src` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4206 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4173 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4162 | `node_modules/.bin/mocha test/tests.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4149 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4132 | `mocha --timeout=15000 tests/*.test.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4079 | `npm run lint ; mocha && mocha test/individual` | 
| [teambit/bit](https://github.com/teambit/bit) | 4051 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4048 | `nyc --require ./test/helpers/register _mocha -- test/tests/index.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4017 | `mocha --require should --reporter spec` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4010 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3957 | `mocha --check-leaks --reporter spec --bail` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3871 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [erming/shout](https://github.com/erming/shout) | 3799 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3794 | `nyc mocha "test/**/*.test.js"` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3769 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3769 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3713 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3708 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [primus/primus](https://github.com/primus/primus) | 3684 | `npm run build && mocha test/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3675 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3665 | `npm run jshint && npm run mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3658 | `NODE_ENV=test mocha --exit` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3622 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3587 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3578 | `mocha tests/javascript` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3578 | `NODE_ENV=test mocha test/**/*.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3570 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3561 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3553 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3552 | `mocha --reporter spec --timeout 3000` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3540 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3514 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3290 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3264 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3238 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3187 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3166 | `mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3134 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3132 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3125 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3120 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3115 | `mocha test/index.js && npm run demo` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3086 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3059 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3048 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3264 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3238 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3187 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3166 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3165 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3148 | `./node_modules/.bin/mocha test/test.*.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3139 | `mocha test/*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3134 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3132 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3125 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3120 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3119 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3115 | `mocha test/index.js && npm run demo` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3086 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3083 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3066 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3059 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3048 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3034 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3033 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3012 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2976 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2975 | `mocha -R landing test/index` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2974 | `eslint . && mocha -t 5000` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2971 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2955 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2908 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2904 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2892 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2889 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2877 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2875 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2875 | `npm run mocha && npm run lint` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2850 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2831 | `istanbul cover _mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2830 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 2824 | `mocha --require should --reporter spec` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2818 | `mocha -R spec spec spec/reporters` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2818 | `mocha test-node` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2816 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2808 | `mocha --require babel-register --recursive spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2801 | `node_modules/.bin/mocha --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2771 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2764 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2759 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2746 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2745 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [css/csso](https://github.com/css/csso) | 2737 | `mocha --reporter dot` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2725 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2723 | `xo && mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2663 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2658 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2653 | `mocha --timeout 100000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2641 | `mocha --recursive --watch` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2636 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2616 | `nyc mocha --timeout=10000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2613 | `mocha-phantomjs ./test/index.html` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2602 | `mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2587 | `nyc mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2573 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2562 | `mocha "test/**/*-test.js"` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2524 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2504 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2502 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2495 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2491 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2465 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2418 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2416 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2399 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2369 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2365 | `mocha test && npm run lint` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2363 | `mocha test/index.js --reporter dot` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2354 | `grunt jshint && mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2354 | `mocha -R spec` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2335 | `mocha && eslint .` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2369 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2365 | `mocha test && npm run lint` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2363 | `mocha test/index.js --reporter dot` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2354 | `grunt jshint && mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2354 | `mocha -R spec` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2335 | `mocha && eslint .` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2310 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2287 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2285 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2278 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [noble/noble](https://github.com/noble/noble) | 2270 | `mocha -R spec test/*.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2237 | `mocha --compilers js:babel-register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2226 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2225 | `mocha --compilers js:babel-register` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2222 | `mocha test test/unit/**/*_test.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 2216 | `mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2159 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2150 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2150 | `cross-env BABEL_ENV=test mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2137 | `standard && mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2130 | `nyc npm run _mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2127 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2126 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2115 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2109 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2096 | `mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2092 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2082 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2059 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2056 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2050 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2045 | `mocha && eslint *.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2030 | `npm run lint && npm run mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2017 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2014 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2006 | `mocha --compilers js:babel-core/register __tests__` | 
| [slate/slate](https://github.com/slate/slate) | 1999 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1993 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1992 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1972 | `./node_modules/.bin/mocha && npm run jshint` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1971 | `mocha --require=test/test_helper.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1968 | `mocha --reporter spec --timeout 5000` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1963 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1959 | `mocha -c test/index.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1938 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [then/promise](https://github.com/then/promise) | 1938 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [kach/nearley](https://github.com/kach/nearley) | 1934 | `mocha test/*.test.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1933 | `mocha` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1930 | `mocha --require ./test/common --growl test/expect.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1924 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1911 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1911 | `npm run mocha && npm run karma` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1885 | `mocha --compilers js:babel-register` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1881 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1876 | `mocha tests.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1871 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1864 | `mocha --reporter spec && npm run test-typescript` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1849 | `mocha && npm run lint` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1843 | `mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1840 | `mocha --reporter spec test/*.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1830 | `mocha tests --require @babel/register` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1822 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1818 | `mocha test` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1818 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1816 | `mocha --reporter spec --grep .` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1816 | `mocha test` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1815 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1814 | `mocha test/**/*.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1809 | `mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1808 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1787 | `mocha test -u bdd -R spec` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1787 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1781 | `npm run lint && npm run mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1787 | `mocha test -u bdd -R spec` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1787 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1781 | `npm run lint && npm run mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1759 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1747 | `mocha ./test/basic.js -t 5000` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1744 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1732 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1730 | `mocha test/**/*_test.js --bail` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1720 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1718 | `./node_modules/.bin/mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1713 | `mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1712 | `npm run lint && npm run mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1708 | `mocha test` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1705 | `mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1704 | `npm run lint && mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1703 | `mocha compiled_tests/` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1700 | `mocha test --timeout 600000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1695 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1690 | `mocha test/*.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1689 | `mocha test/* --reporter spec` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1674 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1674 | `mocha` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1670 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1665 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1662 | `xo && mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1660 | `mocha test/setup.js test/spec/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1631 | `eslint --cache . && tsc && mocha` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1631 | `mocha tests/test.js` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1618 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [zeit/ms](https://github.com/zeit/ms) | 1615 | `mocha tests.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1607 | `mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1606 | `mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1604 | `standard "./src/*.js" && mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1595 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1584 | `./node_modules/mocha/bin/mocha -R spec` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1583 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1579 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1595 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1584 | `./node_modules/mocha/bin/mocha -R spec` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1583 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1579 | `mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1576 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1566 | `mocha --reporter spec` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1565 | `mocha --check-leaks --reporter spec --bail` | 
| [retejs/rete](https://github.com/retejs/rete) | 1564 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1561 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1555 | `./node_modules/.bin/mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1555 | `mocha test.js` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1542 | `npm run test:lint && npm run test:mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1541 | `nyc mocha --timeout=20000 test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1540 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1472 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1453 | `mocha --timeout 10000 ./tests/lib.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1448 | `mocha test.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1441 | `mocha --check-leaks --require @babel/register` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1436 | `mocha test/unit` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1426 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1418 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1418 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1412 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1486 | `mocha test/**/*.spec.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1483 | `mocha -R spec` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1472 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [samccone/drool](https://github.com/samccone/drool) | 1453 | `mocha test/tests.js --timeout=10000` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1453 | `mocha --timeout 10000 ./tests/lib.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1448 | `mocha test.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1441 | `mocha --check-leaks --require @babel/register` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1436 | `mocha test/unit` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1432 | `NODE_ENV=test mocha tests/*.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1431 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1426 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [noble/bleno](https://github.com/noble/bleno) | 1426 | `mocha -R spec test/*.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1421 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1418 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1418 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1412 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1408 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1406 | `npm run lint && mocha && karma start --single-run` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1405 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1399 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1395 | `mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1392 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1391 | `istanbul cover _mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1382 | `npm run build && mocha -r should` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1382 | `./node_modules/mocha/bin/mocha` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1379 | `mocha tests/test-*` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1371 | `mocha -R spec ./test/unit/**` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1369 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1369 | `mocha --opts test/opts/mocha.opts` | 
| [electron/devtron](https://github.com/electron/devtron) | 1363 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1360 | `cross-env NODE_ENV=test nyc mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1358 | `mocha ./test/test*.js --reporter spec` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1355 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1352 | `mocha --reporter dot` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1348 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1347 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1340 | `mocha --recursive` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1338 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1335 | `mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1329 | `npm run lint && npm run mocha` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1327 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1322 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1322 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1318 | `NODE_PATH=. mocha **/*.spec.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1314 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1302 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1301 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1300 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1300 | `mocha-phantomjs tests/index.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1296 | `mocha spec/exec.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1294 | `mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1294 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1293 | `mocha --recursive test/bin` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1292 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1285 | `mocha --check-leaks --reporter spec --bail test/` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1285 | `mocha --timeout 60000 test/` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1283 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1285 | `mocha --check-leaks --reporter spec --bail test/` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1285 | `mocha --timeout 60000 test/` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1283 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1273 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1272 | `mocha --recursive test` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1270 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1270 | `mocha test/*.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1264 | `npm run prepublishOnly && mocha test/test.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1263 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1263 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1262 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1260 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1252 | `mocha tests` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1251 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1236 | `npm run lint && npm run mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1230 | `istanbul test _mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1229 | `mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1224 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1223 | `mocha --compilers js:babel-core/register` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1220 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1218 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1213 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1212 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1211 | `mocha test/test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1211 | `mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1209 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1209 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1207 | `node ./node_modules/mocha/bin/mocha tests` | 
| [variety/variety](https://github.com/variety/variety) | 1205 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1203 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1209 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1209 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1207 | `node ./node_modules/mocha/bin/mocha tests` | 
| [variety/variety](https://github.com/variety/variety) | 1205 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1203 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1199 | `mocha test` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1198 | `webpack && npm run lint && npm run mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1196 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1193 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1192 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1186 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1183 | `npm run lint && mocha --require @babel/register` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1180 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1098 | `mocha --timeout 30000 --recursive ./tests` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1094 | `webpack && mocha test/unit` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1092 | `mocha --reporter spec --bail --check-leaks test/` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1088 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1086 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1085 | `mocha test --compilers js:babel-core/register` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1080 | `mocha --reporter spec --bail --check-leaks test/` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1072 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1070 | `mocha --recursive --bail --reporter spec test` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1069 | `standard && mocha -b` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1061 | `npm-run-all test:jest test:server:mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1055 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1130 | `mocha $(find test -name '*.test.js') --exit` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1130 | `xo && mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1124 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1124 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1118 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [electron/asar](https://github.com/electron/asar) | 1117 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1115 | `mocha test/*` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1110 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1110 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1105 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1105 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1102 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1098 | `mocha --timeout 30000 --recursive ./tests` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1094 | `webpack && mocha test/unit` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1092 | `mocha --reporter spec --bail --check-leaks test/` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1088 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1086 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1085 | `mocha test --compilers js:babel-core/register` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1080 | `mocha --compilers js:babel-register` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1080 | `mocha --reporter spec --bail --check-leaks test/` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1079 | `mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1077 | `mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1072 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1070 | `mocha --recursive --bail --reporter spec test` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1069 | `standard && mocha -b` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1068 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1066 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1063 | `mocha test/tests.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 928 | `mocha` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 927 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 927 | `mocha spec/*.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 926 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 925 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 920 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 914 | `mocha -t 600000` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 903 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 903 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 902 | `./node_modules/.bin/mocha --reporter spec` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 901 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 900 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 899 | `nyc --check-coverage mocha test/*.test.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 899 | `mocha` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 898 | `./node_modules/.bin/mocha -R spec` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 897 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 892 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 892 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 892 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 890 | `node_modules/.bin/mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 887 | `./node_modules/.bin/mocha --globals angular,require` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 885 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 885 | `nyc mocha specs` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 885 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 881 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 881 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 877 | `npm run lint && npm run mocha:no-functional` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 875 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 875 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 875 | `mocha test --compilers js:babel-register` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 875 | `istanbul cover -- _mocha --reporter spec` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 874 | `mocha -t 5000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 874 | `standard && standard ./bin/* && mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 870 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 870 | `mocha --timeout 200000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 869 | `node_modules/.bin/mocha test/spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 866 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 865 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 860 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 857 | `eslint test && mocha --compilers js:babel/register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 854 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 854 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 853 | `mocha --exit --use_strict src/*.test.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 850 | `mocha test/index.js` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 849 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 848 | `mocha --reporter spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 847 | `mocha --reporter list` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 843 | `mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 843 | `mocha test` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 843 | `mocha --compilers js:@babel/register --reporter spec test/**/*.test.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 842 | `npm run lint && mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 842 | `mocha --check-leaks -t 20000` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 841 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 834 | `mocha --reporter spec --bail --check-leaks test/` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 831 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 831 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 831 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 829 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 826 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 825 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 824 | `mocha && ember test` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 823 | `mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 822 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 821 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 805 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 804 | `cake build && mocha ./test/mocha/*.coffee` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 803 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 801 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 800 | `mocha --colors --reporter spec test.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 798 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 798 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 796 | `npm run mocha-test test/integration` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 796 | `mocha -R spec tests/` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 790 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 788 | `mocha -r should --reporter spec test/*.js` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 787 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 784 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 804 | `cake build && mocha ./test/mocha/*.coffee` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 803 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 801 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 800 | `mocha --colors --reporter spec test.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 798 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 798 | `mocha --opts mocha.opts` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 798 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 796 | `npm run mocha-test test/integration` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 796 | `mocha -R spec tests/` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 795 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 790 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 790 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 788 | `mocha -r should --reporter spec test/*.js` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 787 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 784 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 782 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [developit/decko](https://github.com/developit/decko) | 781 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 781 | `xo && mocha -R spec` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 779 | `mocha` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 779 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 779 | `mocha test` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 778 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 773 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 768 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 766 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 764 | `mocha --ui tdd --require ./test/__setup` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 764 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 764 | `mocha --recursive -s 15 test/` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 761 | `mocha test` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 759 | `nyc mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 756 | `mocha` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 753 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 752 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 750 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 749 | `mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 747 | `npm run lint && npm run mocha` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 747 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 746 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 745 | `babel-node node_modules/.bin/_mocha -- test` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 740 | `nyc mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 740 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 739 | `mocha tests/*.mocha.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 738 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 737 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 735 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 735 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 734 | `mocha` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 733 | `npm run-script jshint && npm run-script mocha` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 732 | `npm run bundle && mocha` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 732 | `mocha test.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 731 | `mocha --harmony tests/**` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 730 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 730 | `mocha --reporter spec build/test/index.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 725 | `mocha` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 724 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 724 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 