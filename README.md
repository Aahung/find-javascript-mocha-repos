# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:21 11/23/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44361 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41694 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41179 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30596 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 25091 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 24922 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24272 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20779 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19693 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14530 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14513 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13654 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13289 | `mocha --globals document test` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12475 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12000 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11947 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11110 | `mocha test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12886 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12608 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12475 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12305 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12000 | `nyc grunt mocha-and-karma` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 11956 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11947 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11901 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11110 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10769 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10599 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10552 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10451 | `mocha` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10339 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10286 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10264 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [websockets/ws](https://github.com/websockets/ws) | 10026 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9872 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9572 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9490 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9353 | `mocha -b -r esm` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9275 | `mocha tests/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9186 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 9117 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9082 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8736 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8601 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8518 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8393 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8349 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8348 | `mocha --compilers js:babel-register test/test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8247 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8165 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7981 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7876 | `./node_modules/.bin/mocha test` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7661 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7660 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7627 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7625 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7615 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [dthree/cash](https://github.com/dthree/cash) | 7576 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7516 | `npm run build && istanbul cover _mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4468 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4398 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4350 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4274 | `mocha --timeout=15000 tests/*.test.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4212 | `nyc mocha` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4184 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4153 | `mocha --check-leaks --reporter spec --bail` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4084 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4049 | `mocha --require should --reporter spec` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4018 | `NODE_ENV=test mocha --exit` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4017 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6473 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6439 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6327 | `npm run test:mocha:src` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6197 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6143 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6133 | `mocha tests/node.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6050 | `mocha` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6026 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5987 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5966 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5953 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5939 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5814 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5725 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5604 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5578 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5434 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5414 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5384 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5335 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5236 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5189 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5141 | `mocha --color` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5115 | `mocha test` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5079 | `gulp lint && mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5009 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4898 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4876 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4833 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4823 | `mocha --recursive` | 
| [santinic/how2](https://github.com/santinic/how2) | 4805 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4805 | `mocha -R spec 'tests/app'` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4773 | `./node_modules/.bin/mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4759 | `mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4742 | `nyc mocha --exit` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4726 | `mocha --reporter spec -t 8000` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4696 | `npm run lint && npm run mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 4686 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4631 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4606 | `nyc mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4569 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4498 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4468 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4430 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4408 | `mocha -R spec src` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4398 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4350 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4290 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4274 | `mocha --timeout=15000 tests/*.test.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4246 | `node_modules/.bin/mocha test/tests.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4212 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4204 | `mocha -R spec ./test --recursive` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4184 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4153 | `mocha --check-leaks --reporter spec --bail` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4152 | `npm run lint ; mocha && mocha test/individual` | 
| [muicss/mui](https://github.com/muicss/mui) | 4096 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4084 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4049 | `mocha --require should --reporter spec` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4018 | `NODE_ENV=test mocha --exit` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4017 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3940 | `nyc mocha "test/**/*.test.js"` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3916 | `export TESTING=true; mocha --reporter list` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3853 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3838 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3799 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3791 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3759 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [primus/primus](https://github.com/primus/primus) | 3744 | `npm run build && mocha test/*.test.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3729 | `NODE_ENV=test mocha test/**/*.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3685 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3667 | `npm run jshint && npm run mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3665 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3624 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3620 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3615 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3610 | `node_modules/.bin/mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3592 | `mocha tests/javascript` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3591 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3569 | `mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3560 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3555 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3510 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3477 | `node_modules/.bin/mocha test/lib/` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3464 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3461 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3448 | `mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3423 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3394 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3385 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3328 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3305 | `eslint . && mocha -t 5000` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3279 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3264 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3254 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3245 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3241 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3238 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3229 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3217 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3194 | `mocha test/index.js && npm run demo` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3185 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3185 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3185 | `mocha test/*.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3166 | `./node_modules/.bin/mocha test/test.*.js` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3162 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2949 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2941 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2934 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2922 | `mocha` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 2917 | `mocha && tsc -p ./test/types` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2915 | `mocha test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2902 | `node_modules/.bin/mocha --reporter spec` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2889 | `mocha --require @babel/register --recursive spec` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2885 | `mocha` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2883 | `mocha test-node` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2878 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2874 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [github-tools/github](https://github.com/github-tools/github) | 2859 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2830 | `istanbul cover _mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2810 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [css/csso](https://github.com/css/csso) | 2786 | `mocha --reporter dot` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2784 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2778 | `mocha --require should --reporter spec` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2431 | `mocha test && npm run lint` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2427 | `mocha --no-colors --reporter spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2418 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2341 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2328 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2313 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2294 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2287 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2287 | `mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2270 | `mocha --compilers js:babel-register` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2565 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2538 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2534 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2509 | `mocha test/src/**/*.unit.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2494 | `mocha --reporter=spec test/*-test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2473 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2470 | `nyc --reporter=html --reporter=text mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2431 | `mocha test && npm run lint` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2427 | `mocha --no-colors --reporter spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2418 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2416 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2410 | `mocha test/index.js --reporter dot` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2538 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2534 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2511 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2509 | `mocha test/src/**/*.unit.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2494 | `mocha --reporter=spec test/*-test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2473 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2470 | `nyc --reporter=html --reporter=text mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2431 | `mocha test && npm run lint` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2427 | `mocha --no-colors --reporter spec` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2426 | `mocha && eslint .` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2418 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2416 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2410 | `mocha test/index.js --reporter dot` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2396 | `mocha -R spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2470 | `nyc --reporter=html --reporter=text mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2431 | `mocha test && npm run lint` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2427 | `mocha --no-colors --reporter spec` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2426 | `mocha && eslint .` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2418 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2416 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2410 | `mocha test/index.js --reporter dot` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2396 | `mocha -R spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2374 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2351 | `mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2341 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2328 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2313 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2302 | `npm run build && mocha --require babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2294 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2287 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2287 | `mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2270 | `mocha --compilers js:babel-register` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2237 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2234 | `nyc npm run _mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2230 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2222 | `mocha test test/unit/**/*_test.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2215 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2214 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2188 | `standard && mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2187 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2171 | `cross-env BABEL_ENV=test mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2159 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2138 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2137 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2136 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2095 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2084 | `mocha --compilers js:babel-core/register __tests__` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2076 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2072 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [share/sharedb](https://github.com/share/sharedb) | 2052 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2028 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2003 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1997 | `mocha test/*.test.js` | 
| [slate/slate](https://github.com/slate/slate) | 1996 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1993 | `mocha --reporter spec --timeout 5000` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1992 | `mocha --require=test/test_helper.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1992 | `mocha --compilers js:babel-register` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1948 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1946 | `mocha --require ./test/common --growl test/expect.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1942 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1937 | `mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1930 | `mocha && npm run lint` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1928 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1907 | `mocha --reporter spec && npm run test-typescript` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1888 | `mocha --reporter spec test/*.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1877 | `mocha tests.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1871 | `mocha test/**/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1868 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1863 | `mocha test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1858 | `mocha --reporter spec --grep .` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1854 | `mocha test` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1849 | `mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1847 | `mocha` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1896 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1888 | `mocha --reporter spec test/*.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1877 | `mocha tests.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1871 | `mocha test/**/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1868 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1863 | `mocha test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1858 | `mocha --reporter spec --grep .` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1854 | `mocha test` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1849 | `mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1847 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1839 | `mocha test -u bdd -R spec` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1813 | `npm run lint && npm run mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1811 | `mocha ./test/basic.js -t 5000` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1803 | `mocha compiled_tests/` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1800 | `mocha --timeout 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1789 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1764 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1758 | `npm run lint && npm run mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1736 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1730 | `npm run lint && mocha && npm run typescript` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1729 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1728 | `mocha test/setup.js test/spec/*.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1726 | `mocha test/**/*_test.js --bail` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1736 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1732 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1730 | `npm run lint && mocha && npm run typescript` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1729 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1728 | `mocha test/setup.js test/spec/*.js` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1727 | `./node_modules/.bin/mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1726 | `mocha test/**/*_test.js --bail` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1721 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1721 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1714 | `mocha test/*.js` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1710 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1709 | `mocha test --timeout 600000` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1709 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1702 | `eslint --cache . && tsc && mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1692 | `npm run jshint && mocha --recursive` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1691 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1692 | `npm run jshint && mocha --recursive` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1691 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1688 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1684 | `mocha tests.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1674 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1666 | `mocha && size-limit` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1666 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1664 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1660 | `nyc mocha --timeout=20000 test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1654 | `mocha spec` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1647 | `standard "./src/*.js" && mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1641 | `TEST=all mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1641 | `mocha --expose-gc --slow 300` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1640 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1638 | `mocha tests/test.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1637 | `mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1631 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1624 | `mocha --check-leaks --reporter spec --bail` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1623 | `mocha test/test-*.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1613 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1612 | `mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1608 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1605 | `mocha --reporter spec` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1591 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1590 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1585 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1582 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1591 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1590 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1585 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1582 | `mocha test.js` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1550 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1549 | `nyc mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1549 | `mocha --recursive` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1546 | `npm run test:lint && npm run test:mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1541 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1534 | `NODE_ENV=test mocha tests/*.js` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1533 | `node_modules/.bin/mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1528 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1525 | `mocha -u tdd` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1516 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1505 | `mocha test/unit` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1498 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1495 | `mocha --check-leaks --require @babel/register` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1494 | `mocha test/**/*.spec.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1492 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1490 | `mocha ./test/test*.js --reporter spec` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1484 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1478 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1477 | `mocha -R spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1467 | `mocha -R spec ./test/unit/**` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1467 | `mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1460 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [noble/bleno](https://github.com/noble/bleno) | 1457 | `mocha -R spec test/*.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1456 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [samccone/drool](https://github.com/samccone/drool) | 1452 | `mocha test/tests.js --timeout=10000` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1451 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive --exit` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1451 | `mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1450 | `mocha test.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1444 | `npm run lint && mocha && karma start --single-run` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1443 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1442 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1441 | `mocha tests/test-*` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1439 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1434 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1418 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1415 | `npm run lint && npm run mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1415 | `standard && istanbul cover _mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1413 | `mocha --opts test/opts/mocha.opts` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1404 | `npm run build && mocha -r should` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1400 | `mocha --reporter dot` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1400 | `istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1387 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1385 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1377 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1370 | `mocha --recursive` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1346 | `NODE_PATH=. mocha **/*.spec.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1344 | `mocha --recursive test` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1336 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1334 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1313 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1303 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1302 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1299 | `mocha --compilers js:babel-core/register` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1298 | `mocha test/*.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1295 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1295 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1339 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1336 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1334 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1330 | `mocha test --compilers js:babel-core/register` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1324 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1320 | `mocha` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1319 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1318 | `mocha --check-leaks --reporter spec --bail test/` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1313 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1311 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1311 | `mocha-phantomjs tests/index.html` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1303 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1302 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1299 | `mocha --compilers js:babel-core/register` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1299 | `mocha --timeout 60000 test/` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1298 | `mocha test/*.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1295 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1295 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1283 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1280 | `webpack && npm run lint && npm run mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1276 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1276 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1275 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1273 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1273 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1272 | `mocha src/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1269 | `npm run lint && npm run mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1265 | `mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1265 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1263 | `npm run mocha:istanbul` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1260 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1259 | `istanbul test _mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1257 | `mocha tests` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1248 | `mocha --recursive` | 
| [normalize/mz](https://github.com/normalize/mz) | 1224 | `mocha --reporter spec` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1218 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1216 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1215 | `mocha test/test.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 1208 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1206 | `mocha --timeout 30000 --recursive ./tests` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1205 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1201 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1197 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1195 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1218 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1216 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1215 | `mocha test/test.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 1208 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1206 | `mocha --timeout 30000 --recursive ./tests` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1205 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1201 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1197 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1195 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1115 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1110 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [electron/spectron](https://github.com/electron/spectron) | 1101 | `mocha && standard` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1099 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1098 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1094 | `mocha --check-leaks -t 20000` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1092 | `mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1092 | `standard && mocha -b` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1090 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1087 | `mocha --recursive --bail --reporter spec test` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1087 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1084 | `mocha --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1082 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1140 | `mocha --reporter spec --bail --check-leaks test/` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1135 | `npm-run-all test:jest test:server:mocha` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1130 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1125 | `mocha --reporter spec --bail --check-leaks test/` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1124 | `mocha test/*` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1124 | `webpack && mocha test/unit` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1123 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1123 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1115 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1110 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1107 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1107 | `mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1037 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1036 | `mocha $(find test -name '*.test.js')` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1033 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1033 | `mocha --reporter spec --timeout 3000` | 
| [odota/core](https://github.com/odota/core) | 1033 | `NODE_ENV=test mocha --exit` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1013 | `mocha --colors ./test/*.spec.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 996 | `mocha -R list` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 996 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 993 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 989 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 979 | `mocha --reporter spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 977 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 972 | `npm run rollup-cjs && mocha test/test.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 971 | `npm run lint && mocha -R spec` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 971 | `mocha "client.test" --compilers js:babel-register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 970 | `mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 969 | `mocha --compilers js:babel-register test/*.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 967 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 966 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 965 | `mocha` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 963 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 970 | `mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 970 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 969 | `mocha --compilers js:babel-register test/*.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 967 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 966 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 965 | `mocha` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 963 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 956 | `mocha test/*.test.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 950 | `mocha --recursive ./test/*_spec.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 950 | `mocha spec/*.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 949 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 947 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 918 | `mocha test --compilers js:babel-register` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 914 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 907 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 907 | `mocha -t 5000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 907 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 904 | `standard && standard ./bin/* && mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 898 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 893 | `node_modules/.bin/mocha` | 
| [nimiq-network/core](https://github.com/nimiq-network/core) | 893 | `NODE_ENV=test mocha --exit` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 890 | `npm run lint && npm run mocha:no-functional` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 923 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 921 | `mocha` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 920 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 918 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 918 | `mocha test --compilers js:babel-register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 917 | `nyc mocha specs` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 916 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 914 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 907 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 907 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 907 | `mocha -t 5000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 904 | `standard && standard ./bin/* && mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 896 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 893 | `node_modules/.bin/mocha` | 
| [nimiq-network/core](https://github.com/nimiq-network/core) | 893 | `NODE_ENV=test mocha --exit` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 884 | `./node_modules/.bin/mocha --globals angular,require` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 883 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 883 | `mocha test` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 882 | `mocha test/index.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 882 | `mocha --timeout 200000` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 881 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 874 | `node_modules/.bin/mocha test/spec` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 874 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 840 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 839 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 837 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 835 | `mocha --harmony --full-trace --check-leaks` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 834 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 832 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 832 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 832 | `mocha --opts mocha.opts` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 828 | `mocha -r should --reporter spec test/*.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 828 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 828 | `mocha && ember test` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 825 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 823 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 818 | `mocha test` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 817 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 817 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 817 | `mocha -r babel-register --check-leaks test/index.js` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 839 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 837 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 835 | `mocha --harmony --full-trace --check-leaks` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 834 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 832 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 832 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 832 | `mocha --opts mocha.opts` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 830 | `mocha --async-only` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 828 | `mocha -r should --reporter spec test/*.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 828 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 828 | `mocha && ember test` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 825 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 823 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 823 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 821 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 837 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 835 | `mocha --harmony --full-trace --check-leaks` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 834 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 832 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 832 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 832 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 832 | `mocha --opts mocha.opts` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 830 | `mocha --async-only` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 828 | `mocha -r should --reporter spec test/*.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 828 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 828 | `mocha && ember test` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 825 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 823 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 823 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 821 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 780 | `mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 778 | `mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 775 | `mocha --recursive -s 15 test/` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 773 | `npm run lint && mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 769 | `mocha -R spec src/**/*_test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 766 | `mocha --ui tdd --require ./test/__setup` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 765 | `npm run lint && npm run mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 764 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 762 | `babel-node node_modules/.bin/_mocha -- test` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 792 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 791 | `xo && mocha -R spec` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 790 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 788 | `mocha --no-timeouts` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 780 | `mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 778 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 777 | `mocha test` | 