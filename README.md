# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:02 11/04/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44120 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41604 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40851 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30529 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 24919 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 24826 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24073 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20545 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19528 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17756 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17365 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17261 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16025 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14482 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14404 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14335 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13564 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13193 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12834 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12554 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12362 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12294 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11899 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11795 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11778 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11001 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10654 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10503 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10421 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10375 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [tj/co](https://github.com/tj/co) | 10232 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10213 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [websockets/ws](https://github.com/websockets/ws) | 9866 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9691 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 9571 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9533 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9405 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9310 | `mocha -b -r esm` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9162 | `mocha tests/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9135 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 9032 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9000 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8696 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8589 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8503 | `mocha --check-leaks -R dot` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7546 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7511 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7499 | `npm run build && istanbul cover _mocha` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7486 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7444 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7258 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7241 | `npm run xo && npm run mocha` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7104 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7063 | `mocha; jshint *.js lib` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7017 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6905 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6881 | `mocha --exit --require @babel/register` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6700 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6509 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6403 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6315 | `npm run test:mocha:src` | 
| [almende/vis](https://github.com/almende/vis) | 7258 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7241 | `npm run xo && npm run mocha` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7104 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7063 | `mocha; jshint *.js lib` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7017 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6905 | `mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6895 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6881 | `mocha --exit --require @babel/register` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6700 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6509 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6403 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6018 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5968 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5959 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5900 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5891 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5797 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5644 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5568 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5549 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5413 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5366 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5352 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5568 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5549 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5413 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5366 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5352 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5262 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5215 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5196 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5150 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5071 | `gulp lint && mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5057 | `mocha test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4912 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4891 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4849 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4809 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4784 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4783 | `mocha test` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4745 | `mocha --recursive` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4741 | `./node_modules/.bin/mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4713 | `mocha --reporter spec -t 8000` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4662 | `nyc mocha --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4658 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4643 | `npm run lint && npm run mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4570 | `mocha ./test/runner.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4541 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4519 | `nyc mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 4473 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4472 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4465 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4354 | `mocha -R spec src` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4348 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4324 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4279 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4232 | `mocha --timeout=15000 tests/*.test.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4225 | `node_modules/.bin/mocha test/tests.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4204 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4201 | `nyc mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4190 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4145 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4117 | `npm run lint ; mocha && mocha test/individual` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4080 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4035 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3994 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3910 | `export TESTING=true; mocha --reporter list` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3902 | `NODE_ENV=test mocha --exit` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3889 | `nyc mocha "test/**/*.test.js"` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3867 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3805 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3805 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3797 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [erming/shout](https://github.com/erming/shout) | 3794 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3785 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3714 | `npm run build && mocha test/*.test.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3690 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3683 | `standard && mocha --timeout 60000 test/test.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3676 | `NODE_ENV=test mocha test/**/*.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3665 | `npm run jshint && npm run mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3631 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3595 | `node_modules/.bin/mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3594 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3592 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3588 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3565 | `mocha --reporter spec --timeout 3000` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3475 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3463 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3453 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3445 | `mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3417 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3383 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3361 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3350 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3306 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3226 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3220 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3213 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3210 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3206 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3183 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3176 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3175 | `mocha test/*.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3171 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3169 | `mocha test/index.js && npm run demo` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3167 | `eslint . && mocha -t 5000` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3158 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3149 | `mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3123 | `mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3121 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3118 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3102 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3099 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3093 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3055 | `mocha -R landing test/index` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3038 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3102 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3099 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3093 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3055 | `mocha -R landing test/index` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3047 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3038 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 3030 | `mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2983 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2980 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2938 | `npm run mocha && npm run lint` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2935 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 2923 | `mocha --require should --reporter spec` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2921 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2919 | `mocha -R spec --recursive src/test` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2860 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2860 | `mocha --require babel-register --recursive spec` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2859 | `mocha test.js` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2850 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2846 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [github-tools/github](https://github.com/github-tools/github) | 2845 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2845 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2844 | `mocha -R spec spec spec/reporters` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2834 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2827 | `istanbul cover _mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2782 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2777 | `mocha --require should --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2769 | `mocha --reporter dot` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2747 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2736 | `xo && mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2731 | `npm run build && cd test && mocha . --reporter dot` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2724 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2584 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2561 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2558 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2538 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2532 | `export TESTING=true; mocha --reporter list` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2519 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2498 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2493 | `mocha test/src/**/*.unit.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2487 | `mocha --reporter=spec test/*-test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2454 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2423 | `mocha --no-colors --reporter spec` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2519 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2498 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2496 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2493 | `mocha test/src/**/*.unit.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2487 | `mocha --reporter=spec test/*-test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2464 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2454 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2423 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2412 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2406 | `mocha test && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2402 | `mocha && eslint .` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2398 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2396 | `mocha test/index.js --reporter dot` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2380 | `mocha -R spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2374 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2370 | `node node_modules/mocha/bin/_mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2423 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2412 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2406 | `mocha test && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2402 | `mocha && eslint .` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2398 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2396 | `mocha test/index.js --reporter dot` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2380 | `mocha -R spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2374 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2370 | `node node_modules/mocha/bin/_mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2329 | `mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2320 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2320 | `mocha -R spec test/*.js` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2315 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2288 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2286 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2272 | `npm run build && mocha --require babel-register` | 
| [gajus/swing](https://github.com/gajus/swing) | 2261 | `mocha --compilers js:babel-register` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2231 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2226 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2222 | `mocha test test/unit/**/*_test.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2195 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2195 | `nyc npm run _mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2170 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2162 | `cross-env BABEL_ENV=test mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2160 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2143 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2130 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2126 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2126 | `mocha` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2121 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2108 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2102 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2101 | `mocha && eslint *.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2086 | `npm run lint && npm run mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2052 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2050 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [share/sharedb](https://github.com/share/sharedb) | 2033 | `./node_modules/.bin/mocha && npm run jshint` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2029 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2014 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2003 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2001 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1998 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [slate/slate](https://github.com/slate/slate) | 1996 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1980 | `mocha --require=test/test_helper.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1966 | `mocha -c test/index.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1962 | `npm run lint && mocha -R dot && npm run cover` | 
| [then/promise](https://github.com/then/promise) | 1955 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1941 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1939 | `mocha --require ./test/common --growl test/expect.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1939 | `mocha --compilers js:babel-register` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1938 | `mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1935 | `npm run mocha && npm run karma` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1929 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1926 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1893 | `mocha && npm run lint` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1890 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1888 | `mocha --reporter spec && npm run test-typescript` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1883 | `mocha tests --require @babel/register` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1876 | `mocha tests.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1869 | `mocha --reporter spec test/*.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1856 | `mocha test/**/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1854 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1846 | `mocha test` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1843 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1841 | `mocha --reporter spec --grep .` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1776 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1758 | `mocha compiled_tests/` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1735 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1734 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1727 | `mocha test/**/*_test.js --bail` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1722 | `./node_modules/.bin/mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1721 | `npm run lint && mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1707 | `mocha test/setup.js test/spec/*.js` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1706 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1703 | `mocha test/*.js` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1734 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1727 | `mocha test/**/*_test.js --bail` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1722 | `./node_modules/.bin/mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1721 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1721 | `npm run lint && mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1713 | `mocha test/* --reporter spec` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1709 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1708 | `mocha test --timeout 600000` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1707 | `mocha test/setup.js test/spec/*.js` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1706 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1703 | `mocha test/*.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1701 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1689 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1682 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1682 | `mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1636 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1636 | `mocha tests/test.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1634 | `standard "./src/*.js" && mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1623 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1620 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1611 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1611 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1610 | `mocha --check-leaks --reporter spec --bail` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1592 | `TEST=all mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1589 | `mocha --reporter spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1588 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1587 | `./node_modules/mocha/bin/mocha -R spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1583 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1603 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1592 | `TEST=all mocha` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1589 | `mocha test/test-*.js` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1588 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1587 | `./node_modules/mocha/bin/mocha -R spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1583 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1573 | `mocha test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1566 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 1561 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1556 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1546 | `mocha --recursive` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1546 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1533 | `node_modules/.bin/mocha --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1525 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1524 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1521 | `mocha -u tdd` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1506 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1471 | `mocha --check-leaks --require @babel/register` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1461 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1451 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1448 | `mocha test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1446 | `mocha -R spec test/*.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1444 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1441 | `mocha ./test/test*.js --reporter spec` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1439 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1435 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1429 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1429 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1422 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1421 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1414 | `mocha tests/test-*` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1407 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1406 | `standard && istanbul cover _mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1403 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1403 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1398 | `istanbul cover _mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1395 | `npm run build && mocha -r should` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1394 | `npm run lint && npm run mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1393 | `mocha --opts test/opts/mocha.opts` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1388 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1384 | `mocha --reporter dot` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1381 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1365 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1360 | `cross-env NODE_ENV=test nyc mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1359 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1356 | `mocha --recursive` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1351 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1346 | `./node_modules/.bin/mocha test` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1340 | `mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1337 | `NODE_PATH=. mocha **/*.spec.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1334 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1334 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1331 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1328 | `npm run prepublishOnly && mocha test/test.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1325 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1308 | `mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1306 | `mocha --check-leaks --reporter spec --bail test/` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1305 | `mocha-phantomjs tests/index.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1303 | `mocha spec/exec.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1302 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1297 | `mocha --timeout 60000 test/` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1294 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1293 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1280 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1280 | `mocha test --compilers js:babel-core/register` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1273 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1270 | `mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1265 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1264 | `mocha --compilers js:babel-core/register` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1263 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1249 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1247 | `webpack && npm run lint && npm run mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1233 | `npm run mocha:istanbul` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1232 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1231 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1228 | `npm run lint && mocha --require @babel/register` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1225 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1225 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1221 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1221 | `mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1216 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1214 | `mocha test/test.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1212 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1210 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1209 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1231 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1228 | `npm run lint && mocha --require @babel/register` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1225 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1225 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1221 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1221 | `mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1216 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1214 | `mocha test/test.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1212 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1210 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1210 | `mocha tests/` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1209 | `mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1205 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1200 | `mocha test` | 
| [router5/router5](https://github.com/router5/router5) | 1197 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1183 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1171 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1164 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1161 | `mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1160 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1156 | `mocha --timeout 30000 --recursive ./tests` | 
| [electron/asar](https://github.com/electron/asar) | 1153 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1147 | `mocha $(find test -name '*.test.js') --exit` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1144 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1142 | `xo && mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1141 | `mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1139 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1138 | `istanbul cover _mocha test/*.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1132 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1123 | `mocha test/*` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1120 | `mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1118 | `npm-run-all test:jest test:server:mocha` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1116 | `webpack && mocha test/unit` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 1114 | `mocha` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1113 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1113 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1111 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1111 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1124 | `mocha --reporter spec --bail --check-leaks test/` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1123 | `mocha test/*` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1120 | `mocha` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1120 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1118 | `npm-run-all test:jest test:server:mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1117 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1116 | `webpack && mocha test/unit` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 1114 | `mocha` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1113 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1113 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1111 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1111 | `mocha --reporter spec --bail --check-leaks test/` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1095 | `mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1094 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1093 | `mocha --check-leaks -t 20000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1087 | `mocha --recursive` | 
| [electron/spectron](https://github.com/electron/spectron) | 1085 | `mocha && standard` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1083 | `mocha --compilers js:babel-register` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1083 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1081 | `standard && mocha -b` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1080 | `mocha --recursive --bail --reporter spec test` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1080 | `mocha --recursive -r tests/setup tests` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1078 | `nodeunit test; mocha test` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1071 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1069 | `mocha test/tests.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1067 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1067 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1067 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1067 | `mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1059 | `eslint src test && mocha --compilers babel-register` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 989 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 989 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 984 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 974 | `mocha --reporter spec` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 972 | `npm run rollup-cjs && mocha test/test.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 969 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 969 | `mocha "client.test" --compilers js:babel-register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 967 | `mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 966 | `npm run lint && mocha -R spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 965 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 962 | `mocha --compilers js:babel-register test/*.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 957 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 953 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 946 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 944 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 943 | `mocha --timeout 5000` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 938 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 937 | `mocha spec/*.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 936 | `mocha tests` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 935 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 932 | `mocha -t 600000` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 931 | `mocha test/*.test.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 929 | `./node_modules/.bin/mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 923 | `./node_modules/.bin/mocha -R spec` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 921 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 921 | `mocha test` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 917 | `nyc mocha specs` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 917 | `mocha --recursive ./test/*_spec.js` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 916 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 915 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 913 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 911 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 910 | `mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 909 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 909 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 907 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 906 | `mocha test --compilers js:babel-register` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 902 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 902 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 899 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 893 | `mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 893 | `istanbul cover -- _mocha --reporter spec` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 892 | `standard && standard ./bin/* && mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 859 | `mocha test` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 859 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 857 | `mocha` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 857 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 856 | `mocha --reporter spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 856 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 854 | `istanbul cover _mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 853 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 846 | `mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 845 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 844 | `npm run lint && mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 843 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 857 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 856 | `mocha --reporter spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 856 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 854 | `istanbul cover _mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 853 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 846 | `mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 845 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 844 | `npm run lint && mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 843 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 841 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 841 | `./node_modules/.bin/mocha test/**/*` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 840 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 840 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 838 | `mocha --reporter spec --bail --check-leaks test/` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 838 | `mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 825 | `mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 825 | `mocha --harmony --full-trace --check-leaks` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 824 | `mocha --async-only` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 821 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 820 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 820 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 816 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 816 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 814 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 811 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 810 | `cake build && mocha ./test/mocha/*.coffee` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 810 | `npm run lint && npm run mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 809 | `mocha --colors --reporter spec test.js` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 808 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 807 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 807 | `mocha -r should --reporter spec test/*.js` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 821 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 820 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 820 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 816 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 816 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 814 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 811 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 810 | `cake build && mocha ./test/mocha/*.coffee` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 810 | `npm run lint && npm run mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 809 | `mocha --colors --reporter spec test.js` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 808 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 807 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 807 | `mocha -r should --reporter spec test/*.js` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [developit/decko](https://github.com/developit/decko) | 805 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 796 | `mocha -R spec tests/` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 794 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 792 | `mocha -u tdd` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 789 | `xo && mocha -R spec` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 785 | `mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 784 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 781 | `mocha --no-timeouts` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 780 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 789 | `xo && mocha -R spec` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 786 | `nyc mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 785 | `mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 784 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 781 | `mocha --no-timeouts` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 780 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 775 | `mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 740 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 739 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 735 | `mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 735 | `mocha --reporter spec build/test/index.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 734 | `mocha --reporter spec` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 732 | `./bin/selenium-standalone install && mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 731 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 731 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 730 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 729 | `jenkins-mocha ./tests/*.js` | 
| [koajs/static](https://github.com/koajs/static) | 728 | `mocha --harmony --reporter spec --exit` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 727 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 