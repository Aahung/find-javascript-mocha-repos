# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:16 10/16/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43887 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41502 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40577 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30444 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24735 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 24729 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23877 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20364 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19397 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17580 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17193 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17120 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15765 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14431 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14302 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14121 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13469 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13110 | `mocha --globals document test` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10850 | `mocha test/index.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10405 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10376 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10201 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [tj/co](https://github.com/tj/co) | 10190 | `mocha --harmony` | 
| [websockets/ws](https://github.com/websockets/ws) | 9744 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9537 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9489 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 9355 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9332 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9275 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9109 | `grunt mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9033 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 8960 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8941 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [websockets/ws](https://github.com/websockets/ws) | 9744 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9537 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9489 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 9355 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9332 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9275 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9109 | `grunt mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9033 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 8960 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8941 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8643 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8573 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8486 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8377 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8310 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8263 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8125 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7966 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7952 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7798 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7561 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7486 | `npm run build && istanbul cover _mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7476 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7468 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [aui/art-template](https://github.com/aui/art-template) | 7454 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7443 | `mocha` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7403 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7355 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [almende/vis](https://github.com/almende/vis) | 7201 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7152 | `xo && mocha test/*.js --timeout 100000` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7029 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6994 | `mocha $HARMONY_OPTS` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6912 | `mocha; jshint *.js lib` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6850 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6756 | `mocha --exit --require @babel/register` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6737 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6618 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6420 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6371 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6294 | `npm run test:mocha:src` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6163 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6079 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6057 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6041 | `mocha tests/node.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5908 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5858 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5846 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5833 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5831 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5786 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5564 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5534 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5513 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5416 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5323 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5267 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5193 | `mocha src/**/*Tests.js --harmony` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5188 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5186 | `mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5154 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5052 | `gulp lint && mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4971 | `mocha test` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4879 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4832 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4821 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4801 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4775 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4769 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4707 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4698 | `./node_modules/.bin/mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4673 | `mocha --recursive` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4622 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4593 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4592 | `nyc mocha --exit` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4569 | `mocha ./test/runner.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4471 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4459 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4458 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4446 | `nyc mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4346 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4307 | `mocha -R spec src` | 
| [teambit/bit](https://github.com/teambit/bit) | 4225 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4224 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4206 | `mocha -R spec ./test --recursive` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4203 | `node_modules/.bin/mocha test/tests.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4197 | `nyc mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4175 | `mocha --timeout=15000 tests/*.test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4160 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4100 | `npm run lint ; mocha && mocha test/individual` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4082 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [tj/ejs](https://github.com/tj/ejs) | 4023 | `mocha --require should --reporter spec` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4016 | `mocha --check-leaks --reporter spec --bail` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3869 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3832 | `nyc mocha "test/**/*.test.js"` | 
| [erming/shout](https://github.com/erming/shout) | 3796 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3781 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3778 | `NODE_ENV=test mocha --exit` | 
| [expressjs/session](https://github.com/expressjs/session) | 3750 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3781 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3778 | `NODE_ENV=test mocha --exit` | 
| [expressjs/session](https://github.com/expressjs/session) | 3750 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3747 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [primus/primus](https://github.com/primus/primus) | 3692 | `npm run build && mocha test/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3678 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3667 | `npm run jshint && npm run mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3654 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3616 | `NODE_ENV=test mocha test/**/*.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3606 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3583 | `mocha tests/javascript` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3581 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3577 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3573 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3556 | `mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3554 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3532 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3460 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3444 | `mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3402 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3340 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3327 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3263 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3207 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3263 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3207 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3187 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3179 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3168 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3165 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3161 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3160 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3160 | `mocha test/*.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3156 | `./node_modules/.bin/mocha test/test.*.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3149 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3141 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3114 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3101 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3093 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3079 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3073 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3073 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3060 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3050 | `eslint . && mocha -t 5000` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3035 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [mde/ejs](https://github.com/mde/ejs) | 2868 | `mocha --require should --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2862 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2837 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2834 | `mocha test-node` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2814 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2814 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2804 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2787 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2772 | `mocha --require should --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2756 | `mocha --reporter dot` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2745 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2714 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2702 | `npm run build && cd test && mocha . --reporter dot` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2688 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2683 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2772 | `mocha --require should --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2756 | `mocha --reporter dot` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2745 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2730 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2714 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2702 | `npm run build && cd test && mocha . --reporter dot` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2683 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2679 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2659 | `mocha --timeout 100000` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2633 | `nyc mocha --timeout=10000` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2624 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2619 | `mocha-phantomjs ./test/index.html` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2601 | `nyc mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2679 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2659 | `mocha --timeout 100000` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2633 | `nyc mocha --timeout=10000` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2624 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2619 | `mocha-phantomjs ./test/index.html` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2601 | `nyc mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2577 | `mocha "test/**/*-test.js"` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2548 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2532 | `mocha test/unit --require mochahook` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2530 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2529 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2511 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2168 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2157 | `cross-env BABEL_ENV=test mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2140 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2127 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2124 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2121 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2115 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2103 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2096 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2077 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2070 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2064 | `mocha && eslint *.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2052 | `npm run lint && npm run mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2030 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2366 | `mocha -R spec` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2365 | `mocha && eslint .` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2314 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2305 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2296 | `mocha -R spec test/*.js` | 
| [retejs/rete](https://github.com/retejs/rete) | 2296 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2286 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2285 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [Qix-/color](https://github.com/Qix-/color) | 2273 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2249 | `mocha --compilers js:babel-register` | 
| [pahen/madge](https://github.com/pahen/madge) | 2052 | `npm run lint && npm run mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2030 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2020 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2001 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [slate/slate](https://github.com/slate/slate) | 1998 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1997 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1993 | `./node_modules/.bin/mocha && npm run jshint` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1982 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1978 | `mocha --require=test/test_helper.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1976 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1975 | `mocha --reporter spec --timeout 5000` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1971 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [kach/nearley](https://github.com/kach/nearley) | 1955 | `mocha test/*.test.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1952 | `npm run lint && mocha -R dot && npm run cover` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1936 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1936 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1934 | `mocha --require ./test/common --growl test/expect.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1927 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1921 | `npm run mocha && npm run karma` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1917 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1911 | `mocha --compilers js:babel-register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1896 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1885 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1879 | `mocha --reporter spec && npm run test-typescript` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1877 | `mocha tests.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1858 | `mocha --reporter spec test/*.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1858 | `mocha tests --require @babel/register` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1845 | `mocha` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1843 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1833 | `mocha test` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1831 | `mocha test/**/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1828 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1821 | `mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1819 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1816 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1808 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1793 | `npm run lint && npm run mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1767 | `mocha ./test/basic.js -t 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1793 | `npm run lint && npm run mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1767 | `mocha ./test/basic.js -t 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1763 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1750 | `mocha test` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1736 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1733 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1732 | `mocha compiled_tests/` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1728 | `mocha test/**/*_test.js --bail` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1725 | `npm run lint && npm run mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1722 | `./node_modules/.bin/mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1722 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1717 | `npm run lint && mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1716 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1709 | `mocha test --timeout 600000` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1706 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1703 | `mocha test/* --reporter spec` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1702 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1692 | `mocha test/*.js` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1690 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1688 | `mocha test/setup.js test/spec/*.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1678 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1673 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1672 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1667 | `xo && mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1655 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1617 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1607 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1596 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1590 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1587 | `./node_modules/mocha/bin/mocha -R spec` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1586 | `mocha --check-leaks --reporter spec --bail` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1581 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1571 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1571 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1555 | `./node_modules/.bin/mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1552 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1545 | `npm run test:lint && npm run test:mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1541 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1539 | `TEST=all mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1538 | `mocha --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1534 | `nyc mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1530 | `node_modules/.bin/mocha --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1524 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1521 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1534 | `nyc mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1530 | `node_modules/.bin/mocha --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1524 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1521 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1517 | `mocha -u tdd` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1489 | `mocha test/**/*.spec.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1482 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1473 | `mocha --timeout 10000 ./tests/lib.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1470 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1459 | `mocha test/unit` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1456 | `NODE_ENV=test mocha tests/*.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1454 | `mocha test/tests.js --timeout=10000` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1452 | `mocha --check-leaks --require @babel/register` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1447 | `mocha test.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1445 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1444 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1276 | `mocha test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1271 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1270 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1267 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1265 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1265 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1258 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1258 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1253 | `mocha tests` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1252 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1249 | `mocha src/test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1247 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1243 | `mocha --compilers js:babel-core/register` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1242 | `npm run lint && npm run mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1240 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1322 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1314 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1313 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1312 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1310 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1308 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1305 | `mocha-phantomjs tests/index.html` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1304 | `mocha` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1303 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1300 | `mocha --recursive test/bin` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1297 | `mocha spec/exec.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1296 | `npm run prepublishOnly && mocha test/test.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1293 | `mocha --check-leaks --reporter spec --bail test/` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1292 | `mocha --recursive test` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1292 | `mocha --timeout 60000 test/` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1291 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1283 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1276 | `mocha test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1271 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1270 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1267 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1265 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1265 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1258 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1258 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1253 | `mocha tests` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1252 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1252 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1251 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1249 | `mocha src/test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1247 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1243 | `mocha --compilers js:babel-core/register` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1242 | `npm run lint && npm run mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1240 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1240 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1237 | `istanbul test _mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1233 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1229 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1229 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1225 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1222 | `webpack && npm run lint && npm run mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1216 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1214 | `mocha test/test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1214 | `mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1213 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1211 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1210 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1209 | `node ./node_modules/mocha/bin/mocha tests` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1206 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1205 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1204 | `npm run lint && mocha --require @babel/register` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1200 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1198 | `npm run mocha:istanbul` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1198 | `mocha test` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1191 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1186 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1183 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [router5/router5](https://github.com/router5/router5) | 1183 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1177 | `mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1174 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1159 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1156 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1147 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1142 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1137 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1137 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1136 | `mocha $(find test -name '*.test.js') --exit` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1135 | `istanbul cover _mocha test/*.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1135 | `xo && mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1133 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1131 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1128 | `mocha --timeout 30000 --recursive ./tests` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1112 | `mocha test --compilers js:babel-core/register` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1110 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1110 | `mocha --reporter spec --bail --check-leaks test/` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1108 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1108 | `webpack && mocha test/unit` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1100 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1094 | `npm-run-all test:jest test:server:mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1091 | `mocha --reporter spec --bail --check-leaks test/` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1089 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1089 | `mocha` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1088 | `mocha --check-leaks -t 20000` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1086 | `mocha` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1085 | `mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1080 | `mocha --compilers js:babel-register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1086 | `mocha` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1085 | `mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1080 | `mocha --compilers js:babel-register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1073 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1073 | `mocha --recursive --bail --reporter spec test` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1072 | `standard && mocha -b` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1071 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1068 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1066 | `mocha test/tests.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 1059 | `mocha && standard` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1059 | `mocha` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1054 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1045 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1045 | `eslint src test && mocha --compilers babel-register` | 
| [tomas/needle](https://github.com/tomas/needle) | 1043 | `mocha test` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1038 | `npm run convertto:es5 && npm run mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1037 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1035 | `mocha --recursive -r tests/setup tests` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1034 | `mocha --reporter spec --timeout 3000` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1034 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1027 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1026 | `mocha --async-only` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1025 | `mocha $(find test -name '*.test.js')` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1024 | `mocha --reporter spec test --recursive` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1021 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 930 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 930 | `mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 923 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 920 | `mocha -t 600000` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 920 | `./node_modules/.bin/mocha --reporter spec` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 910 | `./node_modules/.bin/mocha -R spec` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 909 | `nyc --check-coverage mocha test/*.test.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 906 | `nyc mocha specs` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 905 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 905 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 903 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 902 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 974 | `npm run rollup-cjs && mocha test/test.js` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 973 | `mocha test` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 973 | `mocha --reporter spec` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 970 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 969 | `mocha --reporter spec --bail --check-leaks test/` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 963 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 962 | `mocha "client.test" --compilers js:babel-register` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 960 | `mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 958 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 955 | `mocha --compilers js:babel-register test/*.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 933 | `mocha spec/*.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 932 | `mocha tests` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 930 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 930 | `mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 926 | `mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 923 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 920 | `mocha -t 600000` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 920 | `./node_modules/.bin/mocha --reporter spec` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 910 | `./node_modules/.bin/mocha -R spec` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 910 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 909 | `nyc --check-coverage mocha test/*.test.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 907 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 906 | `nyc mocha specs` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 905 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 905 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 905 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 904 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 903 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 902 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 902 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 902 | `mocha --recursive ./test/*_spec.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 896 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 895 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 887 | `node_modules/.bin/mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 887 | `mocha test --compilers js:babel-register` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 886 | `./node_modules/.bin/mocha --globals angular,require` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 884 | `standard && standard ./bin/* && mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 883 | `istanbul cover -- _mocha --reporter spec` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 879 | `npm run lint && npm run mocha:no-functional` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 877 | `mocha -t 5000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 875 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 873 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 870 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 869 | `node_modules/.bin/mocha test/spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 866 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 869 | `node_modules/.bin/mocha test/spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 866 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 866 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 858 | `mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 858 | `eslint test && mocha --compilers js:babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 856 | `mocha test/index.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 856 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 855 | `mocha --reporter list` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 855 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 851 | `mocha --reporter spec` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 851 | `mocha test` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 850 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 850 | `istanbul cover _mocha` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 836 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 833 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 833 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 833 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 833 | `mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 832 | `mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 827 | `mocha && ember test` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 825 | `./node_modules/.bin/mocha test/**/*` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 824 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 822 | `mocha --recursive` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 821 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 821 | `npm run build && istanbul test _mocha test/test.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 817 | `mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 817 | `mocha --harmony --full-trace --check-leaks` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 817 | `mocha --opts mocha.opts` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 815 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 815 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 830 | `mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 827 | `mocha && ember test` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 825 | `./node_modules/.bin/mocha test/**/*` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 824 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 822 | `mocha --recursive` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 821 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 821 | `npm run build && istanbul test _mocha test/test.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 817 | `mocha --harmony --full-trace --check-leaks` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 817 | `mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 817 | `mocha --opts mocha.opts` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 817 | `mocha --async-only` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 815 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 815 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 815 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 815 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 814 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 802 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 799 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 798 | `npm run mocha-test test/integration` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 797 | `mocha -R spec tests/` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 796 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 796 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 795 | `mocha -r should --reporter spec test/*.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 793 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 790 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 790 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [developit/decko](https://github.com/developit/decko) | 789 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 790 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [developit/decko](https://github.com/developit/decko) | 789 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 788 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 785 | `mocha test` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 784 | `xo && mocha -R spec` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 780 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 777 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 776 | `mocha` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 772 | `nyc mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 772 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 772 | `nyc mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 772 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 770 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 769 | `mocha --recursive -s 15 test/` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 766 | `mocha test` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 764 | `mocha --ui tdd --require ./test/__setup` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 764 | `mocha` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 763 | `mocha -R spec src/**/*_test.js` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 754 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 752 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 749 | `mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 749 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 747 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 747 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 746 | `babel-node node_modules/.bin/_mocha -- test` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 746 | `npm run lint && npm run mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 745 | `nyc mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 745 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 744 | `mocha test/mocha.js` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 743 | `mocha --harmony tests/**` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 745 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 744 | `mocha test/mocha.js` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 743 | `mocha --harmony tests/**` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 740 | `mocha tests/*.mocha.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 739 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 739 | `npm run-script jshint && npm run-script mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 738 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 738 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 735 | `mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 734 | `npm run lint && mocha` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 733 | `npm run bundle && mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 733 | `mocha --reporter spec build/test/index.js` | 