# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:15 11/21/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44328 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41688 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41143 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30582 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 25072 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 24910 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24236 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20743 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19676 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17923 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17503 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17381 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16231 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14532 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14519 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14494 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13635 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13271 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12881 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12599 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12458 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12305 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11995 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11926 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11889 | `mocha --require @babel/register --reporter dot` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 11790 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11102 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10756 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10583 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10531 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10444 | `mocha` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10318 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10278 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10262 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [websockets/ws](https://github.com/websockets/ws) | 10015 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9853 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9567 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9479 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9349 | `mocha -b -r esm` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9261 | `mocha tests/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9179 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 9103 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9064 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8726 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8602 | `mocha test/test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8230 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8163 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7872 | `./node_modules/.bin/mocha test` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7650 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7643 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7620 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7620 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7516 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7451 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7312 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7280 | `npm run xo && npm run mocha` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7188 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7173 | `mocha; jshint *.js lib` | 
| [almende/vis](https://github.com/almende/vis) | 7312 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7280 | `npm run xo && npm run mocha` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7188 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7173 | `mocha; jshint *.js lib` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7071 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7043 | `mocha $HARMONY_OPTS` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7002 | `mocha --exit --require @babel/register` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6977 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6772 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6586 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6459 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6435 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6327 | `npm run test:mocha:src` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6171 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6140 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6128 | `mocha tests/node.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6044 | `mocha` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6021 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5983 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5957 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5947 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5939 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5813 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5724 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5599 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5574 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5423 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5413 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5382 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5328 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5235 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5188 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5141 | `mocha --color` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5109 | `mocha test` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5078 | `gulp lint && mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4995 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4898 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4873 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4826 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4817 | `mocha --recursive` | 
| [santinic/how2](https://github.com/santinic/how2) | 4804 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4803 | `mocha -R spec 'tests/app'` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4769 | `./node_modules/.bin/mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4754 | `mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4732 | `nyc mocha --exit` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4725 | `mocha --reporter spec -t 8000` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4681 | `npm run lint && npm run mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 4658 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4626 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4599 | `nyc mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 4091 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4084 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4015 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3931 | `nyc mocha "test/**/*.test.js"` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3915 | `export TESTING=true; mocha --reporter list` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3849 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3833 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3797 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3791 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3749 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [primus/primus](https://github.com/primus/primus) | 3742 | `npm run build && mocha test/*.test.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3725 | `NODE_ENV=test mocha test/**/*.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3685 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3666 | `npm run jshint && npm run mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3662 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3619 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3615 | `mocha test/* --reporter spec` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3612 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3592 | `mocha tests/javascript` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3588 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3567 | `mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3555 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3506 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3477 | `node_modules/.bin/mocha test/lib/` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3461 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3461 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3448 | `mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3448 | `mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3418 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3391 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3380 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3326 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3285 | `eslint . && mocha -t 5000` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3270 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3259 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3250 | `mocha` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3239 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3232 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3223 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3211 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3040 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3020 | `eslint . && nyc mocha --recursive` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3001 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2958 | `npm run mocha && npm run lint` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2939 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2907 | `mocha test.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2900 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2899 | `node_modules/.bin/mocha --reporter spec` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2897 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2884 | `mocha --require @babel/register --recursive spec` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2883 | `mocha` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2882 | `mocha test-node` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2875 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2874 | `mocha` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 2859 | `mocha && tsc -p ./test/types` | 
| [github-tools/github](https://github.com/github-tools/github) | 2855 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2829 | `istanbul cover _mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3020 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3001 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2958 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2948 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2939 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2930 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2921 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2907 | `mocha test.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2900 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2899 | `node_modules/.bin/mocha --reporter spec` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2897 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2884 | `mocha --require @babel/register --recursive spec` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2883 | `mocha` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2882 | `mocha test-node` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2875 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2874 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2868 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace) | 2864 | `mocha` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 2859 | `mocha && tsc -p ./test/types` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2856 | `mocha -R spec spec spec/reporters` | 
| [github-tools/github](https://github.com/github-tools/github) | 2855 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2829 | `istanbul cover _mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2806 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [css/csso](https://github.com/css/csso) | 2785 | `mocha --reporter dot` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2778 | `mocha --require should --reporter spec` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2778 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2757 | `npm run build && cd test && mocha . --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2749 | `xo && mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2732 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2729 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tj/should.js](https://github.com/tj/should.js) | 2726 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2712 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2684 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2673 | `mocha --timeout 100000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2669 | `mocha --recursive --watch` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2668 | `mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2663 | `nyc mocha --timeout=10000` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2648 | `mocha "./test/**/*-test.js"` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2645 | `nyc mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 2643 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2622 | `mocha-phantomjs ./test/index.html` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2603 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2588 | `mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2587 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2583 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2561 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2536 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2469 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2469 | `nyc --reporter=html --reporter=text mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2427 | `mocha test && npm run lint` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2425 | `mocha --no-colors --reporter spec` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2423 | `mocha && eslint .` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2415 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2415 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2408 | `mocha test/index.js --reporter dot` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2394 | `mocha -R spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2373 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2350 | `mocha` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2253 | `mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2232 | `nyc npm run _mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2227 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2222 | `mocha test test/unit/**/*_test.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2211 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2202 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2187 | `standard && mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2184 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2170 | `cross-env BABEL_ENV=test mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2157 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1500 | `mocha test/unit` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1490 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1490 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1478 | `mocha -R spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1466 | `mocha -R spec ./test/unit/**` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1450 | `mocha test.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1449 | `mocha` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1447 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive --exit` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1443 | `npm run lint && mocha && karma start --single-run` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1441 | `mocha tests/test-*` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1440 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1433 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1415 | `standard && istanbul cover _mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1411 | `mocha --opts test/opts/mocha.opts` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1403 | `npm run build && mocha -r should` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1380 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2157 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2137 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2134 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2133 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2132 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2128 | `mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2126 | `mocha && eslint *.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2121 | `npm run lint && npm run mocha` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2112 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2095 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2080 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2071 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2067 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [share/sharedb](https://github.com/share/sharedb) | 2049 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2026 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2017 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2011 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2002 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [slate/slate](https://github.com/slate/slate) | 1996 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1996 | `mocha test/*.test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1991 | `mocha --reporter spec --timeout 5000` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1991 | `mocha --require=test/test_helper.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1987 | `mocha --compilers js:babel-register` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1985 | `npm run lint && mocha -R dot && npm run cover` | 
| [then/promise](https://github.com/then/promise) | 1968 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1963 | `mocha -c test/index.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1930 | `mocha && npm run lint` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1928 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1909 | `mocha tests --require @babel/register` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1896 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1885 | `mocha --reporter spec test/*.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1877 | `mocha tests.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1865 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1860 | `mocha test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1856 | `mocha --reporter spec --grep .` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1853 | `mocha test` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1848 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1838 | `mocha test -u bdd -R spec` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1853 | `mocha test` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1848 | `mocha` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1848 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1838 | `mocha test -u bdd -R spec` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1813 | `npm run lint && npm run mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1812 | `mocha ./test/basic.js -t 5000` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1800 | `mocha --timeout 5000` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1796 | `mocha compiled_tests/` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1788 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1762 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1796 | `mocha compiled_tests/` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1788 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1762 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1758 | `npm run lint && npm run mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1736 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1730 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1729 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1728 | `npm run lint && mocha && npm run typescript` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1727 | `./node_modules/.bin/mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1726 | `mocha test/**/*_test.js --bail` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1723 | `mocha test/setup.js test/spec/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1697 | `eslint --cache . && tsc && mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1692 | `npm run jshint && mocha --recursive` | 
| [zeit/ms](https://github.com/zeit/ms) | 1683 | `mocha tests.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1670 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1666 | `mocha && size-limit` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1664 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1664 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1657 | `nyc mocha --timeout=20000 test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1654 | `mocha spec` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1646 | `standard "./src/*.js" && mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1641 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1637 | `mocha tests/test.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1637 | `mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1636 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1636 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1636 | `TEST=all mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1527 | `NODE_ENV=test mocha tests/*.js` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1525 | `mocha -u tdd` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1515 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1494 | `mocha test/**/*.spec.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1490 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1482 | `mocha --timeout 10000 ./tests/lib.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1481 | `mocha ./test/test*.js --reporter spec` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1478 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1466 | `mocha -R spec ./test/unit/**` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1463 | `mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1455 | `mocha -R spec test/*.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1455 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1482 | `mocha --timeout 10000 ./tests/lib.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1481 | `mocha ./test/test*.js --reporter spec` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1478 | `mocha -R spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1466 | `mocha -R spec ./test/unit/**` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1463 | `mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1455 | `mocha -R spec test/*.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1455 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1454 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1450 | `mocha test.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1449 | `mocha` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1447 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive --exit` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1443 | `npm run lint && mocha && karma start --single-run` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1441 | `mocha tests/test-*` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1440 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1440 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1433 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1433 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1022 | `mocha --recursive test/unit/` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1015 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1013 | `mocha --colors ./test/*.spec.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 995 | `mocha -R list` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 989 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 979 | `mocha --reporter spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 975 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 972 | `npm run rollup-cjs && mocha test/test.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 971 | `npm run lint && mocha -R spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 970 | `mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 968 | `mocha --compilers js:babel-register test/*.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 966 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 962 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1466 | `mocha -R spec ./test/unit/**` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1463 | `mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1455 | `mocha -R spec test/*.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1455 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1454 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [samccone/drool](https://github.com/samccone/drool) | 1452 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1450 | `mocha test.js` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1447 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive --exit` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1441 | `mocha tests/test-*` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1440 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1440 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1433 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1433 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1214 | `mocha test/test.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1204 | `mocha --timeout 30000 --recursive ./tests` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1204 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1201 | `mocha` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 1194 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1191 | `mocha --timeout 20000` | 
| [poooi/poi](https://github.com/poooi/poi) | 1169 | `mocha --recursive --harmony --require ./test/babelhook` | 
| [electron/asar](https://github.com/electron/asar) | 1167 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1163 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1156 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1150 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1148 | `istanbul cover _mocha test/*.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1148 | `mocha` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1147 | `mocha --recursive -r tests/setup tests` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1143 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1137 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1131 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1124 | `webpack && mocha test/unit` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1123 | `mocha test/*` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1123 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1120 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1115 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1106 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1105 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1101 | `mocha && standard` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1115 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1110 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1106 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1105 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1101 | `mocha && standard` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1094 | `mocha --check-leaks -t 20000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1091 | `standard && mocha -b` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1087 | `mocha --recursive --bail --reporter spec test` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1086 | `mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1084 | `mocha --compilers js:babel-register` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1084 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1028 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1013 | `mocha --colors ./test/*.spec.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 995 | `mocha -R list` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 992 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 989 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1047 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1043 | `mocha --async-only` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1043 | `mocha test` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1037 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1036 | `mocha $(find test -name '*.test.js')` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1033 | `mocha --reporter spec --timeout 3000` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1028 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1022 | `mocha --recursive test/unit/` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 855 | `mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 853 | `mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 850 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 841 | `mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 839 | `nyc mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 839 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 834 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 832 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 832 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 832 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 831 | `mocha --opts mocha.opts` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 828 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 827 | `mocha && ember test` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 823 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 823 | `mocha -r should --reporter spec test/*.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 823 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 816 | `mocha test` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 975 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 972 | `npm run rollup-cjs && mocha test/test.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 971 | `npm run lint && mocha -R spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 970 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 970 | `mocha "client.test" --compilers js:babel-register` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 968 | `mocha --compilers js:babel-register test/*.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 968 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 966 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 965 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 965 | `mocha` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 962 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 954 | `mocha test/*.test.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 950 | `mocha spec/*.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 949 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 954 | `mocha test/*.test.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 950 | `mocha spec/*.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 949 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 947 | `mocha --recursive ./test/*_spec.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 946 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 942 | `mocha tests` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 942 | `mocha --timeout 5000` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 939 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 939 | `./node_modules/.bin/mocha --reporter spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 938 | `mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 938 | `mocha` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 936 | `./node_modules/.bin/mocha -R spec` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 936 | `mocha test` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 925 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 919 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 918 | `nyc mocha specs` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 917 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 917 | `mocha test --compilers js:babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 916 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 915 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 907 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 907 | `mocha -t 5000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 906 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 884 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 881 | `mocha --timeout 200000` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 880 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 879 | `mocha test/index.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 874 | `node_modules/.bin/mocha test/spec` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 874 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 872 | `mocha test` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 867 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 862 | `eslint test && mocha --compilers js:babel/register` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 889 | `npm run lint && npm run mocha:no-functional` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 884 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 881 | `mocha --timeout 200000` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 880 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 879 | `mocha test/index.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 874 | `node_modules/.bin/mocha test/spec` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 874 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 872 | `mocha test` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 867 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 862 | `eslint test && mocha --compilers js:babel/register` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 859 | `mocha` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 858 | `npm run lint && npm run mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 857 | `mocha --reporter list` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 857 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 856 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 855 | `istanbul cover _mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 855 | `mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 853 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 851 | `./node_modules/.bin/mocha test/**/*` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 850 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 843 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 843 | `npm run build && istanbul test _mocha test/test.js` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 841 | `mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 840 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 837 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 834 | `mocha --harmony --full-trace --check-leaks` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 832 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 832 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 831 | `mocha --opts mocha.opts` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 830 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 829 | `mocha --async-only` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 827 | `mocha && ember test` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 823 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 823 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 822 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 827 | `mocha && ember test` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 823 | `mocha -r should --reporter spec test/*.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 823 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 822 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 817 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 817 | `mocha -r babel-register --check-leaks test/index.js` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 816 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 816 | `mocha test` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 816 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 812 | `mocha --colors --reporter spec test.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 811 | `npm run mocha-test test/integration` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 810 | `cake build && mocha ./test/mocha/*.coffee` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 809 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 811 | `npm run mocha-test test/integration` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 810 | `cake build && mocha ./test/mocha/*.coffee` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 809 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 808 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 807 | `mocha` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 806 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 806 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 805 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 805 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 804 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 801 | `nyc mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 796 | `mocha -R spec tests/` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 795 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 794 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 791 | `xo && mocha -R spec` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 790 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 789 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 787 | `mocha --no-timeouts` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 781 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 750 | `mocha` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 750 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 746 | `jenkins-mocha ./tests/*.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 744 | `mocha tests/*.mocha.js` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 744 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 743 | `mocha --reporter spec build/test/index.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 740 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [fossasia/labyrinth](https://github.com/fossasia/labyrinth) | 738 | `./node_modules/.bin/mocha` | 
| [koajs/static](https://github.com/koajs/static) | 738 | `mocha --harmony --reporter spec --exit` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 754 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 754 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 754 | `npm run-script jshint && npm run-script mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 753 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 751 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 751 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 750 | `mocha` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 750 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 746 | `_mocha` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 746 | `jenkins-mocha ./tests/*.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 744 | `mocha tests/*.mocha.js` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 744 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 743 | `mocha --reporter spec build/test/index.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 731 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 730 | `mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 729 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 729 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [susam/texme](https://github.com/susam/texme) | 728 | `standard && mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 727 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 726 | `mocha` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 722 | `npm run test-mocha && npm run test-karma` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 721 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 719 | `mocha $(find test -name '*.test.js')` | 
| [danielstjules/buddy.js](https://github.com/danielstjules/buddy.js) | 628 | `mocha -R spec spec/unit spec/integration` | 
| [phodal/sherlock](https://github.com/phodal/sherlock) | 626 | `mocha --reporter spec` | 
| [hparra/gulp-rename](https://github.com/hparra/gulp-rename) | 623 | `mocha` | 
| [docpress/docpress](https://github.com/docpress/docpress) | 622 | `nyc mocha` | 
| [jaredhanson/passport-google-oauth](https://github.com/jaredhanson/passport-google-oauth) | 620 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [stevenvachon/broken-link-checker](https://github.com/stevenvachon/broken-link-checker) | 619 | `mocha test/ --reporter spec --check-leaks --bail` | 
| [blueberryapps/react-bluekit](https://github.com/blueberryapps/react-bluekit) | 619 | `mocha --compilers js:babel/register --recursive` | 
| [gameclosure/devkit](https://github.com/gameclosure/devkit) | 618 | `mocha --reporter spec --recursive -C ./tests` | 
| [apollographql/eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) | 616 | `tav --ci && mocha test/index.js` | 
| [rkusa/koa-passport](https://github.com/rkusa/koa-passport) | 615 | `mocha` | 
| [robrich/gulp-if](https://github.com/robrich/gulp-if) | 615 | `mocha && jshint .` | 
| [w0rm/gulp-svgstore](https://github.com/w0rm/gulp-svgstore) | 613 | `gulp build && mocha test.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 706 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 705 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 703 | `mocha test` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 699 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 696 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 696 | `eslint . && mocha` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 696 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 692 | `mocha` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 691 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 