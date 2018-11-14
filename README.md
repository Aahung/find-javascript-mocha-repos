# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:46 11/14/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44232 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30554 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 25006 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 24878 | `npm run lint && npm run mocha-node-test` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19603 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17847 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17439 | `mocha` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14509 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14463 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17847 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17439 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17337 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16119 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14509 | `nyc --reporter=html --reporter=text mocha` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14470 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14463 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13604 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13228 | `mocha --globals document test` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12574 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12294 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11959 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11878 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11836 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11068 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10717 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10544 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10472 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10440 | `mocha` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10268 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10262 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10239 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10268 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10262 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10239 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [websockets/ws](https://github.com/websockets/ws) | 9935 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9773 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 9666 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9556 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9450 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9328 | `mocha -b -r esm` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9235 | `mocha tests/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9166 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 9075 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9038 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8713 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8600 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8506 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8386 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8337 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8300 | `mocha --compilers js:babel-register test/test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8186 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8161 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7971 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7861 | `./node_modules/.bin/mocha test` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7595 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7591 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7591 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7577 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [aui/art-template](https://github.com/aui/art-template) | 7575 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [dthree/cash](https://github.com/dthree/cash) | 7567 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7512 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7446 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7282 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7262 | `npm run xo && npm run mocha` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7142 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7120 | `mocha; jshint *.js lib` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7028 | `mocha $HARMONY_OPTS` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6985 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6961 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6956 | `mocha --exit --require @babel/register` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6738 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6555 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6423 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6369 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6317 | `npm run test:mocha:src` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6127 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6117 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6110 | `mocha tests/node.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6062 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6027 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5970 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5923 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5921 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5805 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5687 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5580 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5561 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5412 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5397 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5369 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5299 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5223 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5186 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5142 | `mocha --color` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5083 | `mocha test` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5070 | `gulp lint && mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4970 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4893 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4866 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4818 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4800 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4792 | `mocha -R spec 'tests/app'` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4791 | `mocha --recursive` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4752 | `./node_modules/.bin/mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4724 | `mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4718 | `mocha --reporter spec -t 8000` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4706 | `nyc mocha --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4665 | `npm run lint && npm run mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4595 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4572 | `mocha ./test/runner.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 4572 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4349 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4342 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4256 | `mocha --timeout=15000 tests/*.test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4240 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4231 | `node_modules/.bin/mocha test/tests.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4211 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4203 | `mocha -R spec ./test --recursive` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4165 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4134 | `npm run lint ; mocha && mocha test/individual` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4124 | `mocha --check-leaks --reporter spec --bail` | 
| [muicss/mui](https://github.com/muicss/mui) | 4083 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4081 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4042 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4007 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3977 | `NODE_ENV=test mocha --exit` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3911 | `export TESTING=true; mocha --reporter list` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3910 | `nyc mocha "test/**/*.test.js"` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3868 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3836 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3817 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [erming/shout](https://github.com/erming/shout) | 3793 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3790 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3728 | `npm run build && mocha test/*.test.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3719 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3705 | `NODE_ENV=test mocha test/**/*.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3687 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3666 | `npm run jshint && npm run mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3650 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3607 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3606 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3603 | `node_modules/.bin/mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3591 | `mocha tests/javascript` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3572 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3564 | `mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3554 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3553 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3548 | `mocha test/* --reporter spec` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3489 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3462 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3442 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3442 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3402 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3381 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3362 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3321 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3252 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3240 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3239 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3230 | `eslint . && mocha -t 5000` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3230 | `mocha` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3225 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3224 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3040 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3007 | `eslint . && nyc mocha --recursive` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3002 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2992 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2950 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2938 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2926 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2918 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2892 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2891 | `node_modules/.bin/mocha --reporter spec` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2890 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2871 | `mocha --require babel-register --recursive spec` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2870 | `mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2860 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2860 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2846 | `mocha -R spec spec spec/reporters` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2829 | `istanbul cover _mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2952 | `mocha --require should --reporter spec` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2950 | `npm run mocha && npm run lint` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2939 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2926 | `mocha -R spec --recursive src/test` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2894 | `mocha test.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2892 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2891 | `node_modules/.bin/mocha --reporter spec` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2890 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2871 | `mocha --require babel-register --recursive spec` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2870 | `mocha` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2869 | `mocha test-node` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2860 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2860 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2857 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [github-tools/github](https://github.com/github-tools/github) | 2850 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2846 | `mocha -R spec spec spec/reporters` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2829 | `istanbul cover _mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2415 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2410 | `mocha && eslint .` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2390 | `mocha -R spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2344 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2294 | `npm run build && mocha --require babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2289 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2288 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [gajus/swing](https://github.com/gajus/swing) | 2268 | `mocha --compilers js:babel-register` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2263 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2227 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2223 | `mocha test test/unit/**/*_test.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2491 | `mocha --reporter=spec test/*-test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2468 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2464 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2423 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2415 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2410 | `mocha && eslint .` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2408 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2390 | `mocha -R spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2344 | `mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2331 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2324 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2500 | `mocha test` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2491 | `mocha --reporter=spec test/*-test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2468 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2464 | `nyc --reporter=html --reporter=text mocha` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 2426 | `mocha && tsc -p ./test/types` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2423 | `mocha --no-colors --reporter spec` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2421 | `mocha test && npm run lint` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2415 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2410 | `mocha && eslint .` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2408 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2404 | `mocha test/index.js --reporter dot` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2390 | `mocha -R spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2374 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2219 | `nyc npm run _mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2197 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2184 | `standard && mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2182 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2161 | `mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2152 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2132 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2131 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2129 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2128 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2126 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2227 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2223 | `mocha test test/unit/**/*_test.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2219 | `nyc npm run _mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2205 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2197 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2184 | `standard && mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2182 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2168 | `cross-env BABEL_ENV=test mocha` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2161 | `mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2134 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2132 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2131 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2129 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2128 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2126 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2112 | `mocha && eslint *.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2101 | `npm run lint && npm run mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2095 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2070 | `mocha --compilers js:babel-core/register __tests__` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2050 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2018 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2011 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2003 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2002 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [slate/slate](https://github.com/slate/slate) | 1996 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1987 | `mocha --reporter spec --timeout 5000` | 
| [kach/nearley](https://github.com/kach/nearley) | 1987 | `mocha test/*.test.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1984 | `mocha --require=test/test_helper.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1975 | `npm run lint && mocha -R dot && npm run cover` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1974 | `mocha --compilers js:babel-register` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1967 | `npm run mocha && npm run karma` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1945 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1944 | `mocha --require ./test/common --growl test/expect.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1936 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1927 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1917 | `mocha && npm run lint` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1899 | `mocha --reporter spec && npm run test-typescript` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1896 | `mocha tests --require @babel/register` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1894 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1877 | `mocha tests.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1864 | `mocha test/**/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1860 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1854 | `mocha test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1848 | `mocha --reporter spec --grep .` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1845 | `mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1881 | `mocha --reporter spec test/*.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1877 | `mocha tests.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1864 | `mocha test/**/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1860 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1854 | `mocha test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1848 | `mocha --reporter spec --grep .` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1845 | `mocha` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1843 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1837 | `mocha test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1831 | `mocha test -u bdd -R spec` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1817 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1811 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1809 | `npm run lint && npm run mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1800 | `mocha --timeout 5000` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1796 | `mocha ./test/basic.js -t 5000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1727 | `mocha test/**/*_test.js --bail` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1727 | `./node_modules/.bin/mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1727 | `npm run lint && mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1721 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1717 | `mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1714 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1714 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1710 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1709 | `mocha test --timeout 600000` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1693 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1688 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1684 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1674 | `mocha tests.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1664 | `mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1664 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1655 | `mocha spec` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1688 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1685 | `eslint --cache . && tsc && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1674 | `mocha tests.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1664 | `mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1664 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1662 | `mocha && size-limit` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1657 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1655 | `mocha spec` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1641 | `standard "./src/*.js" && mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1638 | `mocha --expose-gc --slow 300` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1578 | `mocha test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1577 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1550 | `nyc mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1548 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1546 | `npm run test:lint && npm run test:mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1532 | `node_modules/.bin/mocha --recursive` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1528 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1527 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1523 | `mocha -u tdd` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1510 | `NODE_ENV=test mocha tests/*.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1492 | `mocha test/unit` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1489 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace) | 1486 | `mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1481 | `mocha --check-leaks --require @babel/register` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1479 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1475 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1467 | `mocha ./test/test*.js --reporter spec` | 
| [noble/bleno](https://github.com/noble/bleno) | 1455 | `mocha -R spec test/*.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1454 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1453 | `mocha -R spec ./test/unit/**` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1451 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [samccone/drool](https://github.com/samccone/drool) | 1451 | `mocha test/tests.js --timeout=10000` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1450 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1450 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1449 | `mocha test.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1442 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1451 | `mocha test/tests.js --timeout=10000` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1450 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1450 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1449 | `mocha test.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1442 | `mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1437 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1433 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1432 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1431 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1431 | `npm run lint && mocha && karma start --single-run` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1429 | `mocha tests/test-*` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1411 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1408 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1408 | `standard && istanbul cover _mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1407 | `npm run lint && npm run mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1403 | `mocha --opts test/opts/mocha.opts` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1402 | `npm run build && mocha -r should` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1400 | `istanbul cover _mocha` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1348 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1348 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1343 | `NODE_PATH=. mocha **/*.spec.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1342 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1339 | `npm run prepublishOnly && mocha test/test.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1337 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1333 | `mocha --recursive test` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1331 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1326 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1315 | `mocha --check-leaks --reporter spec --bail test/` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1310 | `mocha spec/exec.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1308 | `mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1308 | `mocha-phantomjs tests/index.html` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1300 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1288 | `mocha test/*.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1286 | `mocha --compilers js:babel-core/register` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1286 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1282 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1276 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1274 | `mocha` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1274 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1271 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1269 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1269 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1265 | `mocha src/test.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1265 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1261 | `webpack && npm run lint && npm run mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1261 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1260 | `npm run lint && npm run mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1257 | `mocha tests` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1250 | `npm run mocha:istanbul` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1250 | `istanbul test _mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1239 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1238 | `npm run lint && mocha --require @babel/register` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1237 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1235 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [variety/variety](https://github.com/variety/variety) | 1231 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1228 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1225 | `mocha tests/` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1223 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1222 | `mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1220 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1215 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1215 | `mocha test/test.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1205 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1204 | `mocha test` | 
| [router5/router5](https://github.com/router5/router5) | 1204 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1197 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1191 | `mocha --timeout 30000 --recursive ./tests` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1181 | `mocha --timeout 20000` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1180 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1168 | `mocha --recursive` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1163 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1162 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1161 | `mocha` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1168 | `mocha --recursive` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1163 | `mocha` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 1163 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1162 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1161 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1152 | `mocha $(find test -name '*.test.js') --exit` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1151 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1144 | `istanbul cover _mocha test/*.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1144 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1144 | `xo && mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1141 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1138 | `mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1094 | `mocha --check-leaks -t 20000` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1085 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1084 | `mocha --recursive --bail --reporter spec test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1084 | `mocha --compilers js:babel-register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1078 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1076 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1073 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1071 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1071 | `mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1069 | `eslint src test && mocha --compilers babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1069 | `mocha test/tests.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1090 | `standard && mocha -b` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1085 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1084 | `mocha --recursive --bail --reporter spec test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1084 | `mocha --compilers js:babel-register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1078 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1076 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1073 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1071 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1071 | `mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1069 | `eslint src test && mocha --compilers babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1069 | `mocha test/tests.js` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1060 | `mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1059 | `mocha --reporter spec test --recursive` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1060 | `mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1059 | `mocha --reporter spec test --recursive` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1058 | `npm run convertto:es5 && npm run mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 1050 | `mocha test` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1048 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1043 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1039 | `mocha --async-only` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1036 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1036 | `mocha $(find test -name '*.test.js')` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1012 | `mocha --colors ./test/*.spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1009 | `mocha --check-leaks -R dot` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1008 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 995 | `mocha -R list` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 995 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 993 | `mocha --reporter spec --bail --check-leaks test/` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 991 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 987 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 942 | `mocha tests` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 942 | `mocha --timeout 5000` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 937 | `mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 936 | `mocha --recursive ./test/*_spec.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 935 | `mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 932 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 930 | `./node_modules/.bin/mocha -R spec` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 926 | `mocha test` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 921 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 920 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 919 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 918 | `nyc mocha specs` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 941 | `mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 937 | `mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 936 | `mocha --recursive ./test/*_spec.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 935 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 934 | `mocha -t 600000` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 932 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 932 | `./node_modules/.bin/mocha --reporter spec` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 926 | `mocha test` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 923 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 921 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 921 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 920 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 919 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 918 | `nyc mocha specs` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 918 | `nyc mocha specs` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 916 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 915 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 914 | `mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 912 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 912 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 896 | `mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 896 | `istanbul cover -- _mocha --reporter spec` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 892 | `node_modules/.bin/mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 890 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 896 | `mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 896 | `istanbul cover -- _mocha --reporter spec` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 892 | `node_modules/.bin/mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 890 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 888 | `npm run lint && npm run mocha:no-functional` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 884 | `./node_modules/.bin/mocha --globals angular,require` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 878 | `mocha test/index.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 878 | `mocha --timeout 200000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 873 | `node_modules/.bin/mocha test/spec` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 869 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 867 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 867 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 865 | `mocha test` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 862 | `eslint test && mocha --compilers js:babel/register` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 861 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 857 | `mocha --reporter list` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 856 | `mocha --reporter spec` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 856 | `mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 855 | `istanbul cover _mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 855 | `mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 849 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 848 | `mocha --check-leaks -t 20000` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 847 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 847 | `./node_modules/.bin/mocha test/**/*` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 844 | `npm run lint && mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 844 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 842 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 841 | `npm run lint && npm run mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 840 | `npm run build && istanbul test _mocha test/test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 840 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 840 | `mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 838 | `nyc mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 835 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 835 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 833 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 828 | `mocha --harmony --full-trace --check-leaks` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 828 | `mocha && ember test` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 828 | `mocha --async-only` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 826 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 824 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 823 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 820 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 818 | `mocha -r should --reporter spec test/*.js` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 818 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 817 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 815 | `mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 814 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 814 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 812 | `mocha test` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 812 | `mocha test` | 
| [edsu/anon](https://github.com/edsu/anon) | 810 | `mocha --colors --reporter spec test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 810 | `cake build && mocha ./test/mocha/*.coffee` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 809 | `npm run mocha-test test/integration` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 807 | `mocha` | 
| [developit/decko](https://github.com/developit/decko) | 806 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 806 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 805 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 804 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 804 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 803 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 803 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 796 | `mocha -R spec tests/` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 786 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 785 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 784 | `mocha --no-timeouts` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 775 | `mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 772 | `mocha --recursive -s 15 test/` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 769 | `mocha -R spec src/**/*_test.js` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 775 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 773 | `mocha test` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 772 | `mocha --recursive -s 15 test/` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 769 | `mocha -R spec src/**/*_test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 765 | `mocha --ui tdd --require ./test/__setup` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 765 | `mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 763 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 762 | `npm run lint && npm run mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 762 | `npm run lint && mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 760 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 759 | `babel-node node_modules/.bin/_mocha -- test` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 765 | `mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 763 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 762 | `npm run lint && npm run mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 762 | `npm run lint && mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 760 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 759 | `nyc mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 759 | `babel-node node_modules/.bin/_mocha -- test` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 756 | `mocha --harmony tests/**` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 754 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 753 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 753 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 753 | `mocha test/mocha.js` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 752 | `npm run-script jshint && npm run-script mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 751 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 750 | `mocha` | 
| [danielstjules/buddy.js](https://github.com/danielstjules/buddy.js) | 627 | `mocha -R spec spec/unit spec/integration` | 
| [hparra/gulp-rename](https://github.com/hparra/gulp-rename) | 623 | `mocha` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 623 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [docpress/docpress](https://github.com/docpress/docpress) | 620 | `nyc mocha` | 
| [gameclosure/devkit](https://github.com/gameclosure/devkit) | 619 | `mocha --reporter spec --recursive -C ./tests` | 
| [jaredhanson/passport-google-oauth](https://github.com/jaredhanson/passport-google-oauth) | 619 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [blueberryapps/react-bluekit](https://github.com/blueberryapps/react-bluekit) | 616 | `mocha --compilers js:babel/register --recursive` | 
| [gauntface/simple-push-demo](https://github.com/gauntface/simple-push-demo) | 614 | `gulp && npm run lint && node ./test/helpers/download-browsers.js && mocha` | 
| [rkusa/koa-passport](https://github.com/rkusa/koa-passport) | 613 | `mocha` | 
| [robrich/gulp-if](https://github.com/robrich/gulp-if) | 613 | `mocha && jshint .` | 
| [stevenvachon/broken-link-checker](https://github.com/stevenvachon/broken-link-checker) | 611 | `mocha test/ --reporter spec --check-leaks --bail` | 
| [cgross/generator-cg-angular](https://github.com/cgross/generator-cg-angular) | 609 | `mocha` | 
| [VictorBjelkholm/autochecker](https://github.com/VictorBjelkholm/autochecker) | 606 | `mocha` | 