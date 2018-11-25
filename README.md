# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:08 11/25/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44375 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41701 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41191 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30596 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24927 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24291 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20811 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19707 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17944 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17534 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17405 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16278 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14574 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14534 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14524 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13661 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13299 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12888 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12610 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12485 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12308 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12003 | `nyc grunt mocha-and-karma` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 11996 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11955 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11908 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11118 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10776 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10603 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10566 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10452 | `mocha` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10348 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10291 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10271 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [websockets/ws](https://github.com/websockets/ws) | 10044 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9887 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9575 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9498 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9357 | `mocha -b -r esm` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9286 | `mocha tests/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9189 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 9133 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9092 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8738 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8605 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8519 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8398 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8351 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8351 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8258 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8166 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7986 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7883 | `./node_modules/.bin/mocha test` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7669 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7668 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7641 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7635 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7622 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [dthree/cash](https://github.com/dthree/cash) | 7578 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7522 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7453 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7328 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7289 | `npm run xo && npm run mocha` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7211 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7198 | `mocha; jshint *.js lib` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7114 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7049 | `mocha $HARMONY_OPTS` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7036 | `mocha --exit --require @babel/register` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6984 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6791 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6601 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6486 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6440 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6327 | `npm run test:mocha:src` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6208 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6146 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6140 | `mocha tests/node.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6070 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6054 | `mocha` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6033 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5991 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5973 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5954 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5938 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5815 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5733 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5607 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5585 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5438 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5415 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5390 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5339 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5241 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5189 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5141 | `mocha --color` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5121 | `mocha test` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5079 | `gulp lint && mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4773 | `./node_modules/.bin/mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4748 | `nyc mocha --exit` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4726 | `mocha --reporter spec -t 8000` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4698 | `npm run lint && npm run mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 4695 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4638 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4611 | `nyc mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4567 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4499 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4467 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4440 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4410 | `mocha -R spec src` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4408 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4350 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4567 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4499 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4467 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4440 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4410 | `mocha -R spec src` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4408 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4350 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4300 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4277 | `mocha --timeout=15000 tests/*.test.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4247 | `node_modules/.bin/mocha test/tests.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4214 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4204 | `mocha -R spec ./test --recursive` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4185 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4160 | `mocha --check-leaks --reporter spec --bail` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4156 | `npm run lint ; mocha && mocha test/individual` | 
| [muicss/mui](https://github.com/muicss/mui) | 4098 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4084 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4050 | `mocha --require should --reporter spec` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4025 | `NODE_ENV=test mocha --exit` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4021 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3942 | `nyc mocha "test/**/*.test.js"` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3916 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3866 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3856 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3840 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3800 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3792 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3763 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [primus/primus](https://github.com/primus/primus) | 3746 | `npm run build && mocha test/*.test.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3733 | `NODE_ENV=test mocha test/**/*.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3686 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3667 | `npm run jshint && npm run mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3666 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3629 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3621 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3615 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3611 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3615 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3611 | `node_modules/.bin/mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3596 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3592 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3570 | `mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3562 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3555 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3514 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3477 | `node_modules/.bin/mocha test/lib/` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3472 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3461 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3450 | `mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3431 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3394 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3386 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3195 | `mocha test/index.js && npm run demo` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3187 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3170 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3154 | `mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3145 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3133 | `mocha -R landing test/index` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3128 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3128 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3117 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3108 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 3078 | `mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3041 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3025 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3021 | `eslint . && nyc mocha --recursive` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3008 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace) | 2990 | `mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3154 | `mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3145 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3133 | `mocha -R landing test/index` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3128 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3128 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3117 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3108 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 3078 | `mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3041 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3025 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3021 | `eslint . && nyc mocha --recursive` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3008 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 2991 | `mocha --require should --reporter spec` | 
| [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace) | 2990 | `mocha` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2963 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2950 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2942 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2934 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2922 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2919 | `mocha test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2902 | `node_modules/.bin/mocha --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2902 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2901 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2887 | `mocha test-node` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2886 | `mocha` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2880 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2879 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2878 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2863 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2856 | `mocha -R spec spec spec/reporters` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2832 | `istanbul cover _mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2810 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2513 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2509 | `mocha test/src/**/*.unit.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2498 | `mocha --reporter=spec test/*-test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2475 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2470 | `nyc --reporter=html --reporter=text mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2429 | `mocha && eslint .` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2426 | `mocha --no-colors --reporter spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2421 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2416 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2396 | `mocha -R spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2372 | `node node_modules/mocha/bin/_mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2352 | `mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2372 | `node node_modules/mocha/bin/_mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2352 | `mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2344 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2329 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2314 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2306 | `npm run build && mocha --require babel-register` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2298 | `mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2289 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [gajus/swing](https://github.com/gajus/swing) | 2270 | `mocha --compilers js:babel-register` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2238 | `nyc --require babel-register npm run _mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2230 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1992 | `mocha --require=test/test_helper.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1963 | `mocha -c test/index.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1951 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1946 | `mocha --require ./test/common --growl test/expect.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1937 | `mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1931 | `mocha && npm run lint` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1929 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1917 | `mocha tests --require @babel/register` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1907 | `mocha --reporter spec && npm run test-typescript` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1898 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1877 | `mocha tests.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1870 | `npm run lint && mocha --reporter spec test/*.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1856 | `mocha test` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2242 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2238 | `nyc --require babel-register npm run _mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2230 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2221 | `mocha test test/unit/**/*_test.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2220 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2215 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2191 | `standard && mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2190 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2171 | `cross-env BABEL_ENV=test mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2161 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2140 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2139 | `mocha test/runner.js --reporter spec` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2137 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2132 | `mocha && eslint *.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2132 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2129 | `mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 2128 | `npm run lint && npm run mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2084 | `mocha --compilers js:babel-core/register __tests__` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2080 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2030 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2019 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2015 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2004 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1999 | `mocha test/*.test.js` | 
| [slate/slate](https://github.com/slate/slate) | 1996 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1994 | `mocha --compilers js:babel-register` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1993 | `mocha --reporter spec --timeout 5000` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1992 | `npm run lint && mocha -R dot && npm run cover` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1992 | `mocha --require=test/test_helper.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1983 | `npm run mocha && npm run karma` | 
| [then/promise](https://github.com/then/promise) | 1969 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1917 | `mocha tests --require @babel/register` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1898 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1892 | `mocha --reporter spec test/*.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1873 | `mocha test/**/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1863 | `mocha test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1859 | `mocha --reporter spec --grep .` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1856 | `mocha test` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1850 | `mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1847 | `mocha` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1877 | `mocha tests.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1873 | `mocha test/**/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1870 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1863 | `mocha test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1859 | `mocha --reporter spec --grep .` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1856 | `mocha test` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1850 | `mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1847 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1841 | `mocha test -u bdd -R spec` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1814 | `npm run lint && npm run mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1812 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1811 | `mocha ./test/basic.js -t 5000` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1807 | `mocha compiled_tests/` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1764 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1760 | `npm run lint && npm run mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1736 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1735 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1730 | `npm run lint && mocha && npm run typescript` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1730 | `mocha test/setup.js test/spec/*.js` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1729 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1727 | `./node_modules/.bin/mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1726 | `mocha test/**/*_test.js --bail` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1723 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1721 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1717 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1714 | `mocha test/*.js` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1710 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1710 | `mocha test --timeout 600000` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1709 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1706 | `eslint --cache . && tsc && mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1692 | `npm run jshint && mocha --recursive` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1691 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1688 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1685 | `mocha tests.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1675 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1670 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1666 | `mocha && size-limit` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1664 | `nyc mocha --timeout=20000 test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1654 | `mocha spec` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1647 | `standard "./src/*.js" && mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1647 | `TEST=all mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1641 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1641 | `mocha --expose-gc --slow 300` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1637 | `mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1636 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1633 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1626 | `mocha --check-leaks --reporter spec --bail` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1625 | `mocha test/test-*.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1613 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1613 | `mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1609 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1606 | `mocha --reporter spec` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1591 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1591 | `./node_modules/mocha/bin/mocha -R spec` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1586 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1609 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1606 | `mocha --reporter spec` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1591 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1591 | `./node_modules/mocha/bin/mocha -R spec` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1586 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1583 | `mocha test.js` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1550 | `nyc mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1550 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1549 | `mocha --recursive` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1546 | `npm run test:lint && npm run test:mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1546 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1538 | `NODE_ENV=test mocha tests/*.js` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1533 | `node_modules/.bin/mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1528 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1525 | `mocha -u tdd` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1518 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1506 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1506 | `mocha test/unit` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1496 | `mocha --check-leaks --require @babel/register` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1496 | `mocha test/**/*.spec.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1495 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1493 | `mocha ./test/test*.js --reporter spec` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1485 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1479 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1477 | `mocha -R spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1468 | `mocha -R spec ./test/unit/**` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1468 | `mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1461 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [noble/bleno](https://github.com/noble/bleno) | 1459 | `mocha -R spec test/*.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1457 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1453 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive --exit` | 
| [samccone/drool](https://github.com/samccone/drool) | 1453 | `mocha test/tests.js --timeout=10000` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1451 | `mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1450 | `mocha test.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1446 | `npm run lint && mocha && karma start --single-run` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1444 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1444 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1443 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1442 | `mocha tests/test-*` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1435 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1418 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1417 | `npm run lint && npm run mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1417 | `standard && istanbul cover _mocha` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1416 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1414 | `mocha --opts test/opts/mocha.opts` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1411 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1405 | `npm run build && mocha -r should` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1401 | `mocha --reporter dot` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1400 | `istanbul cover _mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1377 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1373 | `mocha --recursive` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1362 | `cross-env NODE_ENV=test nyc mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1357 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1357 | `./node_modules/.bin/mocha test` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1355 | `npm run prepublishOnly && mocha test/test.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1346 | `NODE_PATH=. mocha **/*.spec.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1339 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1337 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1312 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1311 | `mocha-phantomjs tests/index.html` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1302 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1300 | `mocha --timeout 60000 test/` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1298 | `mocha test/*.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1283 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1283 | `webpack && npm run lint && npm run mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1277 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1276 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1276 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1274 | `mocha src/test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1274 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1273 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1269 | `npm run lint && npm run mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1268 | `npm run mocha:istanbul` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1267 | `mocha` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1267 | `mocha --recursive` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1265 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1264 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1287 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1283 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1277 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1276 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1276 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1274 | `mocha src/test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1274 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1269 | `npm run lint && npm run mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1268 | `npm run mocha:istanbul` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1267 | `mocha --recursive` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1265 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1264 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1259 | `istanbul test _mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1257 | `mocha tests` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1267 | `mocha` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1267 | `mocha --recursive` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1265 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1264 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1259 | `istanbul test _mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1257 | `mocha tests` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1247 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1246 | `npm run lint && mocha --require @babel/register` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1245 | `mocha tests/` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1244 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1238 | `mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1237 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1237 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1236 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1235 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1234 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1214 | `mocha test/test.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 1209 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1208 | `mocha --timeout 30000 --recursive ./tests` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1205 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1201 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1198 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1197 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [electron/asar](https://github.com/electron/asar) | 1172 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1164 | `mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1164 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1157 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1156 | `mocha $(find test -name '*.test.js') --exit` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1155 | `mocha` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1153 | `mocha --recursive -r tests/setup tests` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1153 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1150 | `istanbul cover _mocha test/*.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1147 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1145 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1144 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1150 | `istanbul cover _mocha test/*.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1147 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1145 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1144 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1141 | `mocha --reporter spec --bail --check-leaks test/` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1137 | `npm-run-all test:jest test:server:mocha` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1130 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1128 | `mocha --reporter spec --bail --check-leaks test/` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1127 | `mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1124 | `mocha test/*` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1124 | `webpack && mocha test/unit` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1123 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1115 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1066 | `npm run convertto:es5 && npm run mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1055 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [tomas/needle](https://github.com/tomas/needle) | 1053 | `mocha test` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1048 | `mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1047 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1045 | `mocha --async-only` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1037 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1034 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1033 | `mocha --reporter spec --timeout 3000` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 979 | `mocha --reporter spec` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 974 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 973 | `npm run lint && mocha -R spec` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 972 | `npm run rollup-cjs && mocha test/test.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 971 | `mocha "client.test" --compilers js:babel-register` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 967 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 965 | `mocha` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 963 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 960 | `mocha test/*.test.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 952 | `mocha spec/*.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 950 | `mocha --recursive ./test/*_spec.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 945 | `mocha tests` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 945 | `mocha tests` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 943 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 942 | `./node_modules/.bin/mocha --reporter spec` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 942 | `mocha --timeout 5000` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 939 | `mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 938 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 937 | `mocha -t 600000` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 937 | `mocha test` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 937 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 936 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 936 | `./node_modules/.bin/mocha -R spec` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 929 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 926 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 925 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 922 | `mocha` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 920 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 919 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 919 | `mocha test --compilers js:babel-register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 918 | `nyc mocha specs` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 918 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 914 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 909 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 908 | `mocha -t 5000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 907 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 904 | `standard && standard ./bin/* && mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 899 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 899 | `istanbul cover -- _mocha --reporter spec` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 896 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 893 | `node_modules/.bin/mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 890 | `npm run lint && npm run mocha:no-functional` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 888 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 886 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 884 | `mocha test` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 884 | `./node_modules/.bin/mocha --globals angular,require` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 882 | `mocha test/index.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 882 | `mocha --timeout 200000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 876 | `npm run lint && npm run mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 875 | `node_modules/.bin/mocha test/spec` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 874 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 868 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 862 | `eslint test && mocha --compilers js:babel/register` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 860 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 858 | `mocha --reporter list` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 858 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 857 | `mocha --reporter spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 856 | `istanbul cover _mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 855 | `mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 854 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 854 | `./node_modules/.bin/mocha test/**/*` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 850 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 847 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 846 | `npm run lint && mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 844 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 844 | `npm run build && istanbul test _mocha test/test.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 842 | `mocha --reporter spec --bail --check-leaks test/` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 842 | `mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 840 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 839 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 838 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 821 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 819 | `mocha test` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 817 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 817 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 817 | `mocha -r babel-register --check-leaks test/index.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 816 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 812 | `mocha --colors --reporter spec test.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 811 | `npm run mocha-test test/integration` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 811 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 808 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 807 | `mocha` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 807 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 807 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 806 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 804 | `nyc mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 808 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 807 | `mocha` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 807 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 807 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 806 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 804 | `nyc mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 804 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 799 | `mocha` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 798 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 796 | `mocha -R spec tests/` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 795 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 792 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 770 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 770 | `mocha -R spec src/**/*_test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 767 | `mocha --ui tdd --require ./test/__setup` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 765 | `npm run lint && npm run mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 764 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 762 | `babel-node node_modules/.bin/_mocha -- test` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 762 | `mocha --harmony tests/**` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 761 | `nyc mocha` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 761 | `_mocha` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 759 | `mocha test/mocha.js` | 
| [fossasia/labyrinth](https://github.com/fossasia/labyrinth) | 757 | `./node_modules/.bin/mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 753 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 752 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 751 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 781 | `mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 778 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 777 | `mocha test` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 776 | `mocha --recursive -s 15 test/` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 774 | `npm run lint && mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 770 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [sass-eyeglass/eyeglass](https://github.com/sass-eyeglass/eyeglass) | 682 | `mocha test/**/test_*.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 680 | `npm run lint && mocha test` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 677 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 677 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 675 | `mocha --bail test/` | 
| [formio/formio](https://github.com/formio/formio) | 674 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 666 | `mocha 'test/**/*.tests.js'` | 