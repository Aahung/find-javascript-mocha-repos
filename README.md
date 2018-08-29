# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:00 08/29/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43350 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41214 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39899 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30190 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 26130 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24539 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23349 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19903 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19061 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17138 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16863 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16700 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15283 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14352 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14021 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13615 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13215 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12776 | `./node_modules/.bin/mocha test/` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12664 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12356 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12233 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11896 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11540 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11283 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11253 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10533 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10217 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10170 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10148 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10060 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9989 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9759 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9719 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 9424 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9403 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9154 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9139 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9023 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8760 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8751 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8742 | `mocha tests/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8511 | `mocha test/test.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8494 | `mocha test/src` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8449 | `mocha --check-leaks -R dot` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8407 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8336 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8190 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8091 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8078 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7913 | `npm run eslint && npm run mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7892 | `mocha --opts mocha.opts` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7727 | `./node_modules/.bin/mocha test` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7668 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [dthree/cash](https://github.com/dthree/cash) | 7558 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7442 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7439 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7284 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7267 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7263 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7112 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7071 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 7036 | `mocha --compilers js:babel-core/register` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6968 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6914 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6721 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6556 | `mocha; jshint *.js lib` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6495 | `npm run jshint && mocha test/` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6426 | `mocha --exit --require babel-core/register` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6323 | `mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6279 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6260 | `mocha test/test.js` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6240 | `npm run test:mocha:src` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6052 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5990 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5940 | `mocha tests/node.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5935 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5835 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5736 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5728 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5713 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5690 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5675 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5416 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5370 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5349 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5348 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5347 | `standard && mocha` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5181 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5147 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5102 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5049 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5016 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4981 | `gulp lint && mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 4951 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4466 | `mocha --recursive` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4448 | `nyc mocha --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4448 | `npm run lint && npm run mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4437 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4425 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4333 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4239 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4213 | `mocha -R spec ./test --recursive` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4189 | `mocha -R spec src` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4156 | `nyc mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4149 | `nyc mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4333 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4239 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4213 | `mocha -R spec ./test --recursive` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4189 | `mocha -R spec src` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4156 | `nyc mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4149 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4092 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4039 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4038 | `mocha --timeout=15000 tests/*.test.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4033 | `mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4018 | `npm run lint ; mocha && mocha test/individual` | 
| [tj/ejs](https://github.com/tj/ejs) | 3986 | `mocha --require should --reporter spec` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3868 | `mocha --check-leaks --reporter spec --bail` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3867 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3866 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [teambit/bit](https://github.com/teambit/bit) | 3860 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [erming/shout](https://github.com/erming/shout) | 3806 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3759 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3704 | `nyc mocha "test/**/*.test.js"` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3666 | `npm run jshint && npm run mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 3642 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [expressjs/session](https://github.com/expressjs/session) | 3642 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3578 | `mocha tests/javascript` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3550 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3538 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3532 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3493 | `NODE_ENV=test mocha --exit` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3485 | `NODE_ENV=test mocha test/**/*.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3468 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3445 | `mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3426 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3388 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3426 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3388 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3275 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3263 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3261 | `nyc mocha && tsc` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3235 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3218 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 3202 | `export TESTING=true; mocha --reporter list` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3235 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3218 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 3202 | `export TESTING=true; mocha --reporter list` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3178 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3177 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3151 | `./node_modules/.bin/mocha test/test.*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3147 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3135 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3129 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3104 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3102 | `mocha test/*.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3071 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3068 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3064 | `mocha test/index.js && npm run demo` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3062 | `mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3061 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3054 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3029 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3026 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3023 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3006 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3002 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2975 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2922 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2921 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2902 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2899 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2897 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2887 | `mocha -R spec --recursive src/test` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2879 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2869 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2868 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2861 | `mocha -R landing test/index` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2849 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2839 | `npm run mocha && npm run lint` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2831 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2555 | `nyc mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2554 | `mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2533 | `export TESTING=true; mocha --reporter list` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2529 | `mocha "test/**/*-test.js"` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2521 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2464 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2457 | `mocha test/src/**/*.unit.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2457 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2443 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2417 | `mocha --no-colors --reporter spec` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2401 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2391 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2352 | `grunt jshint && mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2481 | `mocha --reporter=spec test/*-test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2467 | `mocha test` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2464 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2464 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2457 | `mocha test/src/**/*.unit.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2457 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2438 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2399 | `nyc --reporter=html --reporter=text mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2391 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2352 | `grunt jshint && mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2350 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2225 | `mocha --compilers js:babel-register` | 
| [noble/noble](https://github.com/noble/noble) | 2218 | `mocha -R spec test/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2147 | `cross-env BABEL_ENV=test mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2124 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2113 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2112 | `mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2109 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2105 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2074 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2260 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2234 | `mocha test test/unit/**/*_test.js` | 
| [noble/noble](https://github.com/noble/noble) | 2218 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2204 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2167 | `mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2234 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2229 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [gajus/swing](https://github.com/gajus/swing) | 2225 | `mocha --compilers js:babel-register` | 
| [noble/noble](https://github.com/noble/noble) | 2218 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2204 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2167 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2147 | `cross-env BABEL_ENV=test mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2124 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2115 | `standard && mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2113 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2112 | `mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2105 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2074 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2067 | `mocha test/runner.js --reporter spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2066 | `nyc npm run _mocha` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2063 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2032 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2031 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [slate/slate](https://github.com/slate/slate) | 2004 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [slate/slate](https://github.com/slate/slate) | 2004 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1999 | `mocha && eslint *.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1990 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1989 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1982 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 1977 | `npm run lint && npm run mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1976 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1969 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1967 | `mocha --require=test/test_helper.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1951 | `mocha --reporter spec --timeout 5000` | 
| [share/sharedb](https://github.com/share/sharedb) | 1949 | `./node_modules/.bin/mocha && npm run jshint` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1939 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1935 | `mocha --bail --reporter spec --check-leaks test/` | 
| [then/promise](https://github.com/then/promise) | 1931 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1930 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1928 | `npm run lint && mocha -R dot && npm run cover` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1926 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1928 | `npm run lint && mocha -R dot && npm run cover` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1926 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1918 | `mocha --require ./test/common --growl test/expect.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1904 | `mocha test/*.test.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1897 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1886 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1881 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1878 | `mocha tests.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1858 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1849 | `npm run mocha && npm run karma` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1846 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1843 | `mocha --reporter spec && npm run test-typescript` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1825 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1823 | `mocha --reporter spec test/*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1819 | `mocha --compilers js:babel-register` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1815 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1813 | `mocha && npm run lint` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1812 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1811 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1809 | `mocha tests --require babel-core/register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1807 | `mocha test` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1803 | `mocha --timeout 5000` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1803 | `npm run lint && mocha --reporter spec test/*.js` | 
| [zeeshanu/dumper.js](https://github.com/zeeshanu/dumper.js) | 1803 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1791 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1791 | `mocha --reporter spec --grep .` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1776 | `mocha test/**/*.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1772 | `npm run lint && npm run mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1754 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1752 | `mocha test -u bdd -R spec` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1749 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1734 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1731 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1730 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1727 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1721 | `mocha ./test/basic.js -t 5000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1715 | `mocha` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1714 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1709 | `./node_modules/.bin/mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1700 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1700 | `npm run lint && mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1592 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1590 | `eslint --cache . && tsc && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1589 | `mocha tests.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1579 | `standard "./src/*.js" && mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1565 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1551 | `mocha --reporter spec` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1550 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1547 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1547 | `mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1544 | `npm run test:lint && npm run test:mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1540 | `mocha test.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1607 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1595 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1590 | `eslint --cache . && tsc && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1589 | `mocha tests.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1579 | `standard "./src/*.js" && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1577 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1573 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1565 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1552 | `./node_modules/.bin/mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1573 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1565 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1552 | `./node_modules/.bin/mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1551 | `mocha --reporter spec` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1550 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1547 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1547 | `mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1544 | `npm run test:lint && npm run test:mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1540 | `mocha test.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1534 | `mocha --check-leaks --reporter spec --bail` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1534 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1533 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1531 | `node_modules/.bin/mocha --recursive` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1525 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1443 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1428 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1419 | `mocha -R spec test/*.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1417 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1415 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1407 | `mocha --check-leaks --require @babel/register` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1404 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1396 | `mocha test/unit` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1396 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1390 | `TEST=all mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1390 | `istanbul cover _mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1387 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1386 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1385 | `./node_modules/mocha/bin/mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1428 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1419 | `mocha -R spec test/*.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1417 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1415 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1407 | `mocha --check-leaks --require @babel/register` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1404 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1396 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1390 | `TEST=all mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1390 | `istanbul cover _mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1387 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1386 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1385 | `./node_modules/mocha/bin/mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1381 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1372 | `npm run build && mocha -r should` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1365 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1365 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1365 | `npm run lint && mocha && karma start --single-run` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1363 | `cross-env NODE_ENV=test nyc mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1361 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [electron/devtron](https://github.com/electron/devtron) | 1358 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1351 | `mocha --opts test/opts/mocha.opts` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1351 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1342 | `mocha tests/test-*` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1340 | `istanbul cover _mocha test -- --timeout 20000` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1338 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1334 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1328 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1328 | `mocha --recursive` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1327 | `NODE_ENV=test mocha tests/*.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1327 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1317 | `mocha --reporter dot` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1309 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1305 | `mocha -R spec ./test/unit/**` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1305 | `mocha-phantomjs tests/index.html` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1303 | `NODE_PATH=. mocha **/*.spec.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1301 | `mocha spec/exec.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1294 | `mocha ./test/test*.js --reporter spec` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1287 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1284 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1282 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1284 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1282 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1278 | `mocha --timeout 60000 test/` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1275 | `npm run lint && npm run mocha` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1275 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1272 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1272 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1263 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1263 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1261 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1260 | `mocha --check-leaks --reporter spec --bail test/` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1258 | `mocha` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1257 | `mocha test/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1252 | `mocha tests` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1252 | `mocha --recursive test/bin` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1252 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1249 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1241 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1204 | `node ./node_modules/mocha/bin/mocha tests` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1201 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1201 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1198 | `mocha --recursive test` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1197 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1196 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1193 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1193 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1170 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1170 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1168 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1166 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1164 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1164 | `webpack && npm run lint && npm run mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1158 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1198 | `mocha --compilers js:babel-core/register` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1198 | `mocha --recursive test` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1197 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1196 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1193 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1193 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1193 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [variety/variety](https://github.com/variety/variety) | 1191 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1170 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1170 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1168 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1166 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1165 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1164 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1164 | `webpack && npm run lint && npm run mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1127 | `npm run mocha:istanbul` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1125 | `mocha $(find test -name '*.test.js')` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1124 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1122 | `xo && mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1121 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1120 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1119 | `istanbul cover _mocha test/*.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1118 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1107 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1106 | `mocha test/*` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1106 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1106 | `mocha --timeout 20000` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1105 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1102 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1099 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1095 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1091 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1090 | `mocha --check-leaks -t 20000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1091 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1090 | `mocha --check-leaks -t 20000` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1082 | `nodeunit test; mocha test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1082 | `mocha --compilers js:babel-register` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1080 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1077 | `webpack && mocha test/unit` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1072 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1070 | `mocha --recursive --bail --reporter spec test` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1067 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1061 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1061 | `mocha --reporter spec --bail --check-leaks test/` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1061 | `mocha test/tests.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1090 | `mocha --check-leaks -t 20000` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1082 | `nodeunit test; mocha test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1082 | `mocha --compilers js:babel-register` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1080 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1077 | `webpack && mocha test/unit` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1072 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1070 | `mocha --recursive --bail --reporter spec test` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1067 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1061 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1061 | `mocha --reporter spec --bail --check-leaks test/` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1061 | `mocha test/tests.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1058 | `mocha --reporter spec --bail --check-leaks test/` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1038 | `mocha --reporter spec --timeout 3000` | 
| [electron/spectron](https://github.com/electron/spectron) | 1032 | `mocha && standard` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1030 | `eslint src test && mocha --compilers babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1028 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 1027 | `mocha test` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1024 | `npm-run-all test:jest test:server:mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1022 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1021 | `mocha $(find test -name '*.test.js')` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1014 | `mocha --check-leaks -R dot` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1012 | `mocha --recursive test/unit/` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1010 | `mocha test --compilers js:babel-core/register` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1007 | `mocha --async-only` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1007 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1002 | `mocha --colors ./test/*.spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1014 | `mocha --check-leaks -R dot` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1012 | `mocha --recursive test/unit/` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1011 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1010 | `mocha test --compilers js:babel-core/register` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1007 | `mocha --async-only` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1007 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1002 | `mocha --colors ./test/*.spec.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 996 | `npm run convertto:es5 && npm run mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 996 | `mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 994 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 989 | `mocha -R list` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 989 | `mocha -R list` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 986 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 984 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 982 | `mocha --recursive -r tests/setup tests` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 978 | `npm run rollup-cjs && mocha test/test.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 975 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 975 | `mocha --reporter spec` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 973 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 962 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 960 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 959 | `mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 948 | `mocha --reporter spec --bail --check-leaks test/` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 948 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 947 | `mocha --compilers js:babel-register test/*.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 946 | `mocha "client.test" --compilers js:babel-register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 945 | `mocha --timeout 5000` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 944 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 944 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 943 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 940 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 936 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 934 | `npm run lint && mocha -R spec` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 914 | `mocha ./test/index.js` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 912 | `mocha test` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 906 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 901 | `mocha -t 600000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 890 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 889 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 887 | `nyc mocha specs` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 886 | `node_modules/.bin/mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 886 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 904 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 901 | `mocha -t 600000` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 894 | `mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 892 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 890 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 889 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 888 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 887 | `nyc mocha specs` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 886 | `node_modules/.bin/mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 886 | `mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 883 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 882 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 881 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 879 | `./node_modules/.bin/mocha -R spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 879 | `./node_modules/.bin/mocha --reporter spec` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 877 | `mocha --reporter list` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 872 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 870 | `istanbul cover -- _mocha --reporter spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 868 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 867 | `mocha --timeout 200000` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 867 | `mocha -t 5000` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 866 | `npm run lint && npm run mocha:no-functional` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 865 | `nyc --check-coverage mocha test/*.test.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 864 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 863 | `node_modules/.bin/mocha test/spec` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 862 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 861 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 861 | `mocha test --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 861 | `standard && standard ./bin/* && mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 836 | `npm run lint && mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 832 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 832 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 829 | `mocha test/index.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 825 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 823 | `mocha test` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 822 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 822 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 821 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 819 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 836 | `npm run lint && mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 832 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 832 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 829 | `mocha test/index.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 825 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 823 | `mocha test` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 823 | `mocha && ember test` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 822 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 822 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 822 | `mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 821 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 819 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 817 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 816 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 816 | `mocha --async-only` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 815 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 814 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 812 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 812 | `mocha tests/*.test.js --reporter spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 808 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 807 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 800 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 799 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 798 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 796 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 795 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 794 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 793 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 792 | `npm run mocha-test test/integration` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 792 | `npm run build && istanbul test _mocha test/test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 791 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 790 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 789 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [edsu/anon](https://github.com/edsu/anon) | 789 | `mocha --colors --reporter spec test.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 789 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 788 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 767 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 765 | `mocha --ui tdd --require ./test/__setup` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 765 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 764 | `mocha --recursive -s 15 test/` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 764 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 758 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 757 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 754 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 753 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 751 | `mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 751 | `mocha` | 