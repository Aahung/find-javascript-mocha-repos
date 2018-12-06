# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:20 12/06/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44508 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41760 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41369 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30645 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 25263 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 24991 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24434 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20938 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19775 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18046 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17622 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17481 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16452 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14705 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14580 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14577 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13717 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13368 | `mocha --globals document test` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12546 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12323 | `mocha` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12268 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12074 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12054 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11995 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11192 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10862 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10673 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10672 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10473 | `mocha` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10436 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10315 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10307 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [websockets/ws](https://github.com/websockets/ws) | 10139 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10436 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10315 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10307 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [websockets/ws](https://github.com/websockets/ws) | 10139 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9601 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9544 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9380 | `mocha tests/*.js` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9372 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9202 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 9170 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9156 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8762 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8621 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8529 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8409 | `grunt clean:test && mocha --exit` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8378 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8370 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8353 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8188 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7996 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7903 | `./node_modules/.bin/mocha test` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7755 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7751 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7698 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7684 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7679 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [dthree/cash](https://github.com/dthree/cash) | 7580 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7542 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7457 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7371 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7272 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7266 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7235 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7121 | `mocha --exit --require @babel/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7061 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7004 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6829 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6652 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6564 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6470 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6335 | `npm run test:mocha:src` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6294 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6172 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6163 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6076 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6073 | `mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6070 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6021 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6009 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5996 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5824 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5792 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5617 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5615 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5496 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5418 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5409 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5383 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5265 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5241 | `mocha -r esm` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5199 | `mocha src/**/*Tests.js --harmony` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5170 | `mocha test` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5138 | `mocha --color` | 
| [tj/ejs](https://github.com/tj/ejs) | 4060 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4035 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3922 | `export TESTING=true; mocha --reporter list` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3885 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3867 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3862 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3796 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [erming/shout](https://github.com/erming/shout) | 3795 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3763 | `NODE_ENV=test mocha test/**/*.js` | 
| [primus/primus](https://github.com/primus/primus) | 3761 | `npm run build && mocha test/*.test.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3693 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4653 | `nyc mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4568 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4516 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4498 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4480 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4472 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4449 | `mocha -R spec src` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4371 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4356 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4305 | `mocha --timeout=15000 tests/*.test.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4264 | `node_modules/.bin/mocha test/tests.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4217 | `nyc mocha` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4208 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4203 | `mocha -R spec ./test --recursive` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4194 | `mocha --check-leaks --reporter spec --bail` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4183 | `npm run lint ; mocha && mocha test/individual` | 
| [muicss/mui](https://github.com/muicss/mui) | 4100 | `mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4099 | `NODE_ENV=test mocha --exit` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4091 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4060 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4035 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3885 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3922 | `export TESTING=true; mocha --reporter list` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3885 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3867 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3862 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3805 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3796 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [erming/shout](https://github.com/erming/shout) | 3795 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3763 | `NODE_ENV=test mocha test/**/*.js` | 
| [primus/primus](https://github.com/primus/primus) | 3761 | `npm run build && mocha test/*.test.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3693 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3684 | `standard && mocha --timeout 60000 test/test.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3668 | `mocha test/* --reporter spec` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3660 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3457 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3407 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3393 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3388 | `eslint . && mocha -t 5000` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3352 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3305 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3287 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3270 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3262 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3262 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3257 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3248 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3393 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3388 | `eslint . && mocha -t 5000` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3352 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3315 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3305 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3287 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3270 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3262 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3262 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3257 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3248 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3212 | `mocha test/index.js && npm run demo` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3211 | `mocha test/*.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3210 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3192 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3192 | `mocha && tsc -p ./test/types` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3189 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2832 | `istanbul cover _mocha` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2825 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2779 | `mocha --require should --reporter spec` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2775 | `npm run build && cd test && mocha . --reporter dot` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2750 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2741 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2738 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2683 | `mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 2682 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2682 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2681 | `nyc mocha --timeout=10000` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2676 | `mocha --timeout 100000` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2661 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2628 | `mocha-phantomjs ./test/index.html` | 
| [github-tools/github](https://github.com/github-tools/github) | 2865 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2863 | `mocha -R spec spec spec/reporters` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2832 | `istanbul cover _mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2830 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2825 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [css/csso](https://github.com/css/csso) | 2790 | `mocha --reporter dot` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2779 | `mocha --require should --reporter spec` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2775 | `npm run build && cd test && mocha . --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2750 | `xo && mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2750 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2741 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2738 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2699 | `mocha "./test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2683 | `mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 2682 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2682 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2681 | `nyc mocha --timeout=10000` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2676 | `mocha --timeout 100000` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2825 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [css/csso](https://github.com/css/csso) | 2790 | `mocha --reporter dot` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2779 | `mocha --require should --reporter spec` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2775 | `npm run build && cd test && mocha . --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2750 | `xo && mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2750 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2741 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2738 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2721 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2699 | `mocha "./test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2683 | `mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 2682 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2682 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2681 | `nyc mocha --timeout=10000` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2676 | `mocha --timeout 100000` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2661 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2503 | `mocha --reporter=spec test/*-test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2484 | `nyc --reporter=html --reporter=text mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2456 | `mocha test --exit && npm run lint` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2436 | `mocha --no-colors --reporter spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2426 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2424 | `mocha test/index.js --reporter dot` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2421 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2411 | `mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2377 | `grunt jshint && mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2373 | `mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2355 | `mocha -R spec test/*.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1847 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1823 | `mocha compiled_tests/` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1814 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1799 | `mocha --timeout 5000` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1769 | `npm run lint && npm run mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1756 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1746 | `mocha test/setup.js test/spec/*.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1736 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1733 | `eslint --cache . && tsc && mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1732 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1732 | `npm run lint && mocha && npm run typescript` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1882 | `npm run lint && mocha --reporter spec test/*.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1879 | `mocha tests.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1871 | `mocha test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1867 | `mocha --reporter spec --grep .` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1849 | `mocha test -u bdd -R spec` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1847 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1823 | `mocha compiled_tests/` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1821 | `mocha test` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1799 | `mocha --timeout 5000` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1756 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1748 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1746 | `mocha test/setup.js test/spec/*.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1736 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1733 | `eslint --cache . && tsc && mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1732 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1732 | `npm run lint && mocha && npm run typescript` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1729 | `./node_modules/.bin/mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1726 | `mocha test/**/*_test.js --bail` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1726 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1722 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1720 | `mocha test/*.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1719 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1713 | `mocha test --timeout 600000` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1711 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1706 | `mocha tests.js` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1696 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1688 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1678 | `TEST=all mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1678 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1665 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1665 | `xo && mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1656 | `standard "./src/*.js" && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1656 | `mocha spec` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1653 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1648 | `mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1646 | `mocha` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1639 | `mocha test/test-*.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1639 | `mocha tests/test.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1638 | `mocha --check-leaks --reporter spec --bail` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1636 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1616 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1612 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1598 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1595 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1594 | `./node_modules/mocha/bin/mocha -R spec` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1593 | `mocha test.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1570 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1558 | `nyc mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1558 | `NODE_ENV=test mocha tests/*.js` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1552 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1549 | `npm run test:lint && npm run test:mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1546 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1540 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1534 | `node_modules/.bin/mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1532 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1529 | `mocha -u tdd` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1526 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1522 | `mocha ./test/test*.js --reporter spec` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1522 | `mocha test/unit` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1502 | `mocha --check-leaks --require @babel/register` | 
| [samccone/drool](https://github.com/samccone/drool) | 1456 | `mocha test/tests.js --timeout=10000` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1452 | `npm run lint && mocha && karma start --single-run` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1438 | `npm run lint && npm run mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1428 | `standard && istanbul cover _mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1422 | `mocha --opts test/opts/mocha.opts` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1412 | `npm run build && mocha -r should` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1407 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1402 | `istanbul cover _mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1384 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1322 | `mocha` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1320 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1313 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1312 | `mocha-phantomjs tests/index.html` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1307 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1304 | `mocha --timeout 60000 test/` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1302 | `mocha test/*.js` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1300 | `webpack && npm run lint && npm run mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1294 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1288 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1283 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1283 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1283 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1282 | `npm run mocha:istanbul` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1280 | `mocha src/test.js` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1277 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1276 | `npm run lint && npm run mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1274 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1267 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1266 | `npm run lint && mocha --require @babel/register` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1407 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1402 | `istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1392 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1384 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1380 | `mocha --recursive` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1379 | `mocha --recursive test/bin` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1377 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1373 | `npm run prepublishOnly && mocha test/test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1366 | `mocha --recursive test` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1365 | `cross-env NODE_ENV=test nyc mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1364 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1363 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1257 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1249 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1249 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 1245 | `mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1243 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1241 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1240 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1230 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [normalize/mz](https://github.com/normalize/mz) | 1230 | `mocha --reporter spec` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1220 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1219 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1213 | `mocha --timeout 20000` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1328 | `mocha --check-leaks --reporter spec --bail test/` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1325 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1322 | `mocha` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1320 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1319 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1313 | `mocha --compilers js:babel-core/register` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1313 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1312 | `mocha-phantomjs tests/index.html` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1310 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1307 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1304 | `mocha --timeout 60000 test/` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1302 | `mocha test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1301 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1300 | `webpack && npm run lint && npm run mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1297 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1294 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1264 | `mocha tests/` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1263 | `istanbul test _mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1258 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1258 | `mocha tests` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1257 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1249 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1249 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 1245 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1244 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1243 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1241 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1240 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1230 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [normalize/mz](https://github.com/normalize/mz) | 1230 | `mocha --reporter spec` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1228 | `mocha --timeout 30000 --recursive ./tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1220 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1219 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1213 | `mocha --timeout 20000` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1207 | `mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1206 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [electron/asar](https://github.com/electron/asar) | 1177 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1166 | `mocha --recursive -r tests/setup tests` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1165 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1161 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1160 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [electron/asar](https://github.com/electron/asar) | 1177 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1172 | `mocha` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1166 | `mocha --recursive -r tests/setup tests` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1165 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1161 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1160 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1159 | `mocha $(find test -name '*.test.js') --exit` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1155 | `xo && mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1151 | `mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1149 | `istanbul cover _mocha test/*.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1149 | `mocha --reporter spec --bail --check-leaks test/` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1146 | `npm-run-all test:jest test:server:mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1144 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1141 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1116 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1115 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1112 | `mocha && standard` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1112 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1110 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1108 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1101 | `standard && mocha -b` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1098 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1095 | `node_modules/.bin/mocha && npm run lint` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1092 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1087 | `mocha --recursive --bail --reporter spec test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1085 | `mocha --compilers js:babel-register` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1083 | `mocha --reporter spec test --recursive` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1078 | `eslint src test && mocha --compilers babel-register` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1104 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1101 | `standard && mocha -b` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1098 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1095 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1094 | `mocha --check-leaks -t 20000` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1092 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1087 | `mocha --recursive --bail --reporter spec test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1085 | `mocha --compilers js:babel-register` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1083 | `mocha --reporter spec test --recursive` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1078 | `eslint src test && mocha --compilers babel-register` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1075 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1075 | `npm run convertto:es5 && npm run mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1075 | `mocha test/tests.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1014 | `mocha --colors ./test/*.spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1009 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 999 | `mocha -R list` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 996 | `mocha --reporter spec --bail --check-leaks test/` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 994 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 990 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 987 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 979 | `mocha --reporter spec` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 978 | `npm run lint && mocha -R spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 977 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 976 | `mocha test/*.test.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 975 | `mocha --compilers js:babel-register test/*.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 900 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 893 | `node_modules/.bin/mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 887 | `mocha test/index.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 879 | `node_modules/.bin/mocha test/spec` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 875 | `./node_modules/.bin/mocha test/**/*` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 868 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 862 | `mocha --reporter list` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 861 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 969 | `mocha "client.test" --compilers js:babel-register` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 968 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 967 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 966 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 965 | `mocha` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 963 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 957 | `mocha spec/*.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 955 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 952 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 951 | `./node_modules/.bin/mocha --reporter spec` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 949 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 948 | `mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 945 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 943 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 929 | `mocha` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 928 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 926 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 925 | `mocha test --compilers js:babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 922 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 918 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 918 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 912 | `mocha -t 5000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 912 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 911 | `npm run lint && npm run mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 907 | `standard && standard ./bin/* && mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 906 | `istanbul cover -- _mocha --reporter spec` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 941 | `mocha test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 941 | `mocha --timeout 5000` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 940 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 940 | `mocha -t 600000` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 937 | `./node_modules/.bin/mocha -R spec` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 935 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 929 | `mocha` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 928 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 927 | `nyc mocha specs` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 926 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 925 | `mocha test --compilers js:babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 922 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 900 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 899 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 893 | `node_modules/.bin/mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 893 | `npm run lint && npm run mocha:no-functional` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 890 | `mocha test` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 887 | `mocha test/index.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 884 | `mocha --timeout 200000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 882 | `./node_modules/.bin/mocha --globals angular,require` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 879 | `node_modules/.bin/mocha test/spec` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 878 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 875 | `./node_modules/.bin/mocha test/**/*` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 873 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 871 | `mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 868 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 862 | `mocha --reporter list` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 862 | `eslint test && mocha --compilers js:babel/register` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 861 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 859 | `mocha --reporter spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 858 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 857 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 856 | `istanbul cover _mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 856 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 851 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 851 | `mocha --check-leaks -t 20000` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 850 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 849 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 848 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 847 | `npm run lint && mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 847 | `mocha --harmony --full-trace --check-leaks` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 847 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 844 | `nyc mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 843 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 841 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 837 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 837 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 836 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 835 | `mocha -r should --exit test/*.js` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 835 | `mocha --opts mocha.opts` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 835 | `mocha --opts mocha.opts` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 831 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 831 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 831 | `mocha --async-only` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 829 | `mocha && ember test` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 825 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 824 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 824 | `mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 824 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 821 | `mocha test` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [developit/decko](https://github.com/developit/decko) | 819 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 817 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 817 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 819 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 817 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 817 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 816 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 814 | `nyc mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 813 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 812 | `npm run mocha-test test/integration` | 
| [edsu/anon](https://github.com/edsu/anon) | 811 | `mocha --colors --reporter spec test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 811 | `cake build && mocha ./test/mocha/*.coffee` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 811 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 810 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 806 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 803 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 782 | `mocha` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 782 | `mocha --harmony tests/**` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 778 | `mocha test` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 777 | `mocha --recursive -s 15 test/` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 774 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 773 | `npm run lint && npm run mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 770 | `mocha -R spec src/**/*_test.js` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 771 | `nyc mocha` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 770 | `mocha -R spec src/**/*_test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 767 | `mocha tests --timeout 10000` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 766 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 765 | `mocha test/mocha.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 758 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 757 | `jenkins-mocha ./tests/*.js` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 757 | `npm run-script jshint && npm run-script mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 758 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 758 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 757 | `jenkins-mocha ./tests/*.js` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 757 | `npm run-script jshint && npm run-script mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 754 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 754 | `mocha index.test.js` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 754 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 753 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 751 | `./bin/selenium-standalone install && mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 751 | `mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 750 | `mocha --reporter spec build/test/index.js` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 689 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 681 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [formio/formio](https://github.com/formio/formio) | 680 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 677 | `mocha` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 676 | `mocha --compilers js:babel-register` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 676 | `mocha --bail test/` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 674 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 673 | `./node_modules/.bin/mocha tests/*.js` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 671 | `_mocha -u bdd --colors test/` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 671 | `mocha 'test/**/*.tests.js'` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 729 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 729 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 727 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 725 | `mocha ./test/index.js` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 724 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 720 | `mocha $(find test -name '*.test.js')` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 719 | `mocha test` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 718 | `mocha ./test/test.js --timeout 1000000` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 716 | `mocha --reporter spec test/` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 731 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 729 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 729 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 727 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 725 | `mocha ./test/index.js` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 724 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 720 | `mocha $(find test -name '*.test.js')` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 718 | `mocha ./test/test.js --timeout 1000000` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 718 | `mocha --reporter spec --bail --check-leaks test/` | 