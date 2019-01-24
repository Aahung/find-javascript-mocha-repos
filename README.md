# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:44 01/24/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44982 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42054 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42013 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30846 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25581 | `nyc mocha --timeout=10000 --exit` | 
| [caolan/async](https://github.com/caolan/async) | 25164 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25028 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21355 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20099 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18446 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17996 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17812 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17249 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15202 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14919 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14688 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13933 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13642 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13033 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13004 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12768 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12757 | `istanbul cover _mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12437 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12372 | `mocha --require @babel/register --reporter dot` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12360 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12267 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11487 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11127 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11095 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10869 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10799 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10592 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10437 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10418 | `mocha --harmony` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9746 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9727 | `mocha tests/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9695 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9513 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9432 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9378 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9308 | `grunt mocha` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8898 | `mocha test/src` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8850 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8699 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8687 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8580 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8558 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8447 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8338 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8260 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8190 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8066 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8053 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8013 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7944 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7868 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7856 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7835 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7591 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7588 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [almende/vis](https://github.com/almende/vis) | 7520 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7469 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7460 | `mocha --exit --require @babel/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7455 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7454 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7148 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7112 | `mocha $HARMONY_OPTS` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7112 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7014 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6843 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6840 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6556 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6392 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6269 | `mocha tests/node.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6262 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6228 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6210 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6207 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6114 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6091 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6072 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5976 | `standard && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5933 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5883 | `mocha && eslint lib/**` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5747 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5704 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5697 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5689 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5615 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5542 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5477 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 5426 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5406 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5377 | `mocha -r esm` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5364 | `mocha test` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5335 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4617 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4583 | `mocha ./test/runner.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4569 | `mocha -R spec src` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4546 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4479 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4428 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4377 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4374 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4360 | `node_modules/.bin/mocha test/tests.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4338 | `mocha --check-leaks --reporter spec --bail` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4321 | `NODE_ENV=test mocha --exit` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4302 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4269 | `npm run lint ; mocha && mocha test/individual` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4747 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4617 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4583 | `mocha ./test/runner.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4569 | `mocha -R spec src` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4546 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4479 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4428 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4377 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4374 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4360 | `node_modules/.bin/mocha test/tests.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4338 | `mocha --check-leaks --reporter spec --bail` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4321 | `NODE_ENV=test mocha --exit` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4269 | `npm run lint ; mocha && mocha test/individual` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4234 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4198 | `mocha -R spec ./test --recursive` | 
| [muicss/mui](https://github.com/muicss/mui) | 4139 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 4087 | `mocha --require should --reporter spec` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4074 | `npm run build && cd test && mocha . --reporter dot` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3978 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3978 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3924 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3924 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3883 | `NODE_ENV=test mocha test/**/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3858 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [primus/primus](https://github.com/primus/primus) | 3812 | `npm run build && mocha test/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3797 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3773 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3731 | `mocha && tsc -p ./test/types` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3730 | `mocha test/* --reporter spec` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3725 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3714 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3691 | `eslint . && mocha -t 5000` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3684 | `standard && mocha --timeout 60000 test/test.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3665 | `node_modules/.bin/mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3664 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3658 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3604 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3595 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3562 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3604 | `mocha tests/javascript` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3597 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3595 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3581 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3562 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3491 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3466 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3455 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3450 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3446 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3424 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3407 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3407 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3359 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3353 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3466 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3455 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3450 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3446 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3424 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3418 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3407 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3407 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3379 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3359 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3353 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3345 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3344 | `mocha -R landing test/index --exit` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3314 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3298 | `mocha test/index.js && npm run demo` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3143 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3089 | `nyc mocha --recursive` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3084 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3061 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 3054 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3051 | `npm run mocha && npm run lint` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3028 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3019 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3016 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2989 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2988 | `mocha test-node` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2978 | `mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2963 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2958 | `mocha -R spec --recursive src/test` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2845 | `istanbul cover _mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2826 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2817 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [css/csso](https://github.com/css/csso) | 2816 | `mocha --reporter dot` | 
| [retejs/rete](https://github.com/retejs/rete) | 2791 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2787 | `mocha --require should --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2766 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2757 | `mocha "./test/**/*-test.js"` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2751 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2745 | `mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2710 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2704 | `nyc mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2668 | `mocha test/unit --require mochahook` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2668 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2661 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2630 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2591 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2591 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2550 | `mocha test` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2549 | `mocha test --exit && npm run lint` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2535 | `mocha test/src/**/*.unit.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2533 | `export TESTING=true; mocha --reporter list` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2533 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2528 | `nyc --reporter=html --reporter=text mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2518 | `mocha --reporter=spec test/*-test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2515 | `mocha && eslint .` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2505 | `mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2515 | `mocha && eslint .` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2505 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2500 | `TEST=all mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2488 | `mocha test/index.js --reporter dot` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2472 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2451 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2442 | `mocha -R spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2442 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [Qix-/color](https://github.com/Qix-/color) | 2438 | `mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2426 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2424 | `nyc --require babel-register npm run _mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2405 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2388 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2387 | `npm run build && mocha --require babel-register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2379 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2555 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2550 | `mocha test` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2549 | `mocha test --exit && npm run lint` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2535 | `mocha test/src/**/*.unit.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2533 | `export TESTING=true; mocha --reporter list` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2533 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2528 | `nyc --reporter=html --reporter=text mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2518 | `mocha --reporter=spec test/*-test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2515 | `mocha && eslint .` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2505 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2500 | `TEST=all mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2488 | `mocha test/index.js --reporter dot` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2472 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2451 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2447 | `mocha --no-colors --reporter spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2442 | `mocha -R spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2442 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [Qix-/color](https://github.com/Qix-/color) | 2438 | `mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2098 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2097 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [kach/nearley](https://github.com/kach/nearley) | 2053 | `mocha test/*.test.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2049 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2047 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2039 | `npm run mocha && npm run karma` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2037 | `npm run lint && mocha -R dot && npm run cover` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2035 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2034 | `mocha tests --require @babel/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2024 | `mocha && npm run lint` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2020 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2018 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 2011 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2002 | `mocha --require=test/test_helper.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1997 | `mocha test` | 
| [slate/slate](https://github.com/slate/slate) | 1996 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1983 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1961 | `mocha --bail --reporter spec --check-leaks test/` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1957 | `mocha test/**/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1950 | `mocha --reporter spec && npm run test-typescript` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1948 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1948 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1946 | `bmocha --reporter spec test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1929 | `npm run lint && mocha --reporter spec test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1912 | `mocha --reporter spec --grep .` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1841 | `npm run lint && npm run mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1819 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1809 | `npm run lint && npm run mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1800 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1776 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1752 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1744 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1742 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1738 | `mocha test/*.js` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1730 | `mocha test/test-*.js` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1726 | `mocha test/**/*_test.js --bail` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1726 | `mocha test --timeout 600000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1722 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1715 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1714 | `mocha` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1712 | `mocha --recursive` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1706 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1706 | `mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1759 | `npm run lint && mocha && npm run typescript` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1752 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1744 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1742 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1739 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1738 | `mocha test/*.js` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1737 | `./node_modules/.bin/mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1733 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1730 | `mocha test/test-*.js` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1726 | `mocha test/**/*_test.js --bail` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1726 | `mocha test --timeout 600000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1722 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1715 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1714 | `mocha` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1712 | `mocha --recursive` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1708 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1706 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1706 | `mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1540 | `mocha -u tdd` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1526 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1523 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1515 | `mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1512 | `npm run lint && npm run mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1499 | `mocha --timeout 10000 ./tests/lib.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1497 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [noble/bleno](https://github.com/noble/bleno) | 1496 | `mocha -R spec test/*.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1471 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1460 | `npm run prepublishOnly && mocha test/test.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1455 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1572 | `nyc mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1566 | `mocha -R spec ./test/unit/**` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1557 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1542 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1542 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1540 | `mocha -u tdd` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1537 | `mocha --check-leaks --require @babel/register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1526 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1523 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1515 | `mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1512 | `npm run lint && npm run mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1508 | `npm run lint && mocha && karma start --single-run` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1507 | `mocha test/**/*.spec.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1506 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1504 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1499 | `mocha --timeout 10000 ./tests/lib.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1497 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1493 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1473 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1471 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1465 | `standard && istanbul cover _mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1463 | `mocha --recursive test` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1462 | `mocha --reporter dot` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1461 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1460 | `npm run prepublishOnly && mocha test/test.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1395 | `mocha --recursive` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1379 | `mocha --check-leaks --reporter spec --bail test/` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1373 | `./node_modules/.bin/mocha test` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1365 | `webpack && npm run lint && npm run mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1363 | `NODE_PATH=. mocha **/*.spec.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1358 | `npm run mocha:istanbul` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1358 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1357 | `mocha --compilers js:babel-core/register` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1356 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1356 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1345 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1344 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1343 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1294 | `mocha --timeout 30000 --recursive ./tests` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1293 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1291 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1268 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1266 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1261 | `mocha tests` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1260 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1255 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1252 | `mocha --reporter spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1242 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1241 | `mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1119 | `standard && mocha -b` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1114 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1113 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1105 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1098 | `mocha --recursive --bail --reporter spec test` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1098 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1098 | `node_modules/.bin/mocha && npm run lint` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1097 | `eslint src test && mocha --compilers babel-register` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1096 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1090 | `mocha --compilers js:babel-register` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1083 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [tomas/needle](https://github.com/tomas/needle) | 1066 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1064 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1062 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1057 | `npm run lint && npm run mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1054 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1049 | `mocha $(find test -name '*.test.js')` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1049 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1046 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1018 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 1014 | `mocha --recursive ./test/*_spec.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1012 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1006 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1005 | `mocha -R list` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1004 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 996 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 994 | `mocha --compilers js:babel-register test/*.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 994 | `./node_modules/.bin/mocha -R spec` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 991 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 983 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 983 | `mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 982 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 981 | `mocha "client.test" --compilers js:babel-register` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 977 | `npm run rollup-cjs && mocha test/test.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 974 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 972 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 971 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 966 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 965 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 965 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 963 | `mocha -t 600000` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 962 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 962 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 959 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 948 | `nyc mocha specs` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 948 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 960 | `./node_modules/.bin/mocha --reporter spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 956 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 948 | `nyc mocha specs` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 948 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 947 | `mocha test --compilers js:babel-register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 945 | `mocha` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 941 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 941 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 939 | `mocha test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 939 | `mocha --timeout 5000` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 939 | `mocha test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 939 | `mocha --timeout 5000` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 932 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 931 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 931 | `./node_modules/.bin/mocha test/**/*` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 927 | `istanbul cover -- _mocha --reporter spec` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 925 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 924 | `standard && standard ./bin/* && mocha` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 921 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 918 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 918 | `mocha -t 5000` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 917 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 916 | `mocha spec/*.spec.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 897 | `node_modules/.bin/mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 893 | `mocha --timeout 200000` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 889 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 887 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 885 | `node_modules/.bin/mocha test/spec` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 885 | `mocha -r should --exit test/*.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 884 | `npm run build && istanbul test _mocha test/test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 881 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 854 | `nyc mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 852 | `mocha --check-leaks -t 20000` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 848 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 846 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 845 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 845 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 845 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 844 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [developit/decko](https://github.com/developit/decko) | 841 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 841 | `mocha --async-only` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 838 | `mocha -r babel-register --check-leaks test/index.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 838 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 836 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 834 | `nyc mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 834 | `mocha test` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 832 | `npm run lint && mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 826 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 823 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 820 | `npm run mocha-test test/integration` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 819 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 816 | `mocha --colors --reporter spec test.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 815 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 812 | `_mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 810 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 809 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 804 | `mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 799 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 799 | `mocha test` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 799 | `mocha index.test.js` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 798 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 796 | `mocha --no-timeouts` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 796 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 794 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 788 | `npm run lint && npm run mocha` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 788 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 787 | `nyc mocha` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 785 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 784 | `mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 781 | `mocha --recursive -s 15 test/` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 781 | `mocha tests --timeout 10000` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 815 | `cake build && mocha ./test/mocha/*.coffee` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 810 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 804 | `mocha` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 802 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 800 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 799 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 799 | `mocha test` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 799 | `mocha index.test.js` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 798 | `mocha test/mocha.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 796 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 795 | `xo && mocha -R spec` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 794 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 788 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 787 | `nyc mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 785 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 784 | `mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 781 | `mocha tests --timeout 10000` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 785 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 784 | `mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 781 | `mocha --recursive -s 15 test/` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 777 | `mocha test` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 775 | `mocha -R spec src/**/*_test.js` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 775 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 774 | `eslint . && mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 773 | `babel-node node_modules/.bin/_mocha -- test` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 763 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 763 | `npm run-script jshint && npm run-script mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 761 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 757 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 756 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 756 | `mocha --reporter spec build/test/index.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 753 | `mocha tests/*.mocha.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 736 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 736 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 734 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 734 | `mocha` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 732 | `mocha $(find test -name '*.test.js')` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 730 | `mocha --reporter spec --bail --check-leaks test/` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 730 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 729 | `mocha ./test/test.js --timeout 1000000` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 729 | `mocha --compilers js:babel-core/register` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 724 | `mocha --reporter spec test/` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 722 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 740 | `npm run bundle && mocha` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 738 | `mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 736 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 736 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 734 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 734 | `mocha` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 732 | `mocha $(find test -name '*.test.js')` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 730 | `mocha --reporter spec --bail --check-leaks test/` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 730 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 729 | `mocha ./test/test.js --timeout 1000000` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 729 | `mocha --compilers js:babel-core/register` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 726 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 725 | `./node_modules/.bin/mocha tests/*.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 722 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 721 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 719 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 718 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 715 | `mocha` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 714 | `mocha --reporter spec` | 
| [LouisBarranqueiro/reapop](https://github.com/LouisBarranqueiro/reapop) | 648 | `babel-node ./node_modules/karma/bin/karma start ./build/karma.conf.js --reporters mocha` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 648 | `./node_modules/.bin/mocha --bail` | 
| [kwhitley/apicache](https://github.com/kwhitley/apicache) | 646 | `nyc mocha $(find test -name '*.test.js') --recursive` | 
| [shelljs/shx](https://github.com/shelljs/shx) | 644 | `nyc --reporter=text --reporter=lcov mocha` | 
| [aaronshaf/react-toggle](https://github.com/aaronshaf/react-toggle) | 643 | `nyc mocha --require babel-register --require spec/setup.js spec/**/*.spec.js` | 
| [anandanand84/technicalindicators](https://github.com/anandanand84/technicalindicators) | 641 | `mocha --compilers js:babel-register --require babel-polyfill` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 638 | `nyc mocha test.js` | 
| [floatdrop/gulp-watch](https://github.com/floatdrop/gulp-watch) | 636 | `xo && mocha -r test/util/set-default-options -t 5000 -R spec test/test-*` | 
| [pocketjoso/specificity-graph](https://github.com/pocketjoso/specificity-graph) | 635 | `node_modules/.bin/mocha test` | 
| [hparra/gulp-rename](https://github.com/hparra/gulp-rename) | 632 | `mocha` | 
| [azmenak/react-stripe-checkout](https://github.com/azmenak/react-stripe-checkout) | 632 | `mocha --require babel-register --require .test-setup.js -R spec ./spec.js` | 
| [edankwan/penis.js](https://github.com/edankwan/penis.js) | 631 | `mocha --ui bdd --reporter spec test/` | 
| [Munter/subfont](https://github.com/Munter/subfont) | 628 | `npm run lint && mocha` | 
| [ideal-postcodes/postcodes.io](https://github.com/ideal-postcodes/postcodes.io) | 626 | `NODE_ENV=test npm run test:create && npm run nyc_mocha && NODE_ENV=test npm run test:clear && npm run lint` | 
| [werk85/node-html-to-text](https://github.com/werk85/node-html-to-text) | 625 | `istanbul cover _mocha && eslint .` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 697 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 696 | `mocha` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 695 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [electron/apps](https://github.com/electron/apps) | 693 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 690 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [sass-eyeglass/eyeglass](https://github.com/sass-eyeglass/eyeglass) | 690 | `mocha test/**/test_*.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 688 | `npm run lint && mocha test` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 687 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 671 | `mocha --require babel-register` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [shime/livedown](https://github.com/shime/livedown) | 669 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 669 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 669 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 669 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [substance/data](https://github.com/substance/data) | 666 | `mocha -R spec tests/run.js` | 
| [SavjeeTutorials/SavjeeCoin](https://github.com/SavjeeTutorials/SavjeeCoin) | 665 | `mocha tests/*.test.js` | 
| [mtth/avsc](https://github.com/mtth/avsc) | 664 | `mocha` | 
| [afc163/fanyi](https://github.com/afc163/fanyi) | 663 | `npm run lint && mocha tests/index.js --timeout 0` | 
| [coinbase/gdax-node](https://github.com/coinbase/gdax-node) | 662 | `mocha --full-trace --ui tdd --bail --reporter spec tests/*.js` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 671 | `mocha --require babel-register` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [shime/livedown](https://github.com/shime/livedown) | 669 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 669 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 669 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 669 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [substance/data](https://github.com/substance/data) | 666 | `mocha -R spec tests/run.js` | 
| [SavjeeTutorials/SavjeeCoin](https://github.com/SavjeeTutorials/SavjeeCoin) | 665 | `mocha tests/*.test.js` | 
| [mtth/avsc](https://github.com/mtth/avsc) | 664 | `mocha` | 
| [afc163/fanyi](https://github.com/afc163/fanyi) | 663 | `npm run lint && mocha tests/index.js --timeout 0` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 663 | `mocha` | 
| [coinbase/gdax-node](https://github.com/coinbase/gdax-node) | 662 | `mocha --full-trace --ui tdd --bail --reporter spec tests/*.js` | 
| [Kagami/ffmpeg.js](https://github.com/Kagami/ffmpeg.js) | 661 | `mocha test/test.js` | 