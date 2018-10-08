# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:00 10/08/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43790 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41430 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40469 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30411 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 27118 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24700 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 24664 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23779 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20289 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19311 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17519 | `npm run test:lint && npm run test:mocha` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17105 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17065 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15672 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14406 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14260 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14034 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13423 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13028 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12743 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12474 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12263 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12218 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11730 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11577 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11550 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10777 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10460 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10371 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10354 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10158 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10125 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10113 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 9692 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9473 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9460 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9302 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9259 | `mocha -b -r esm` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 9177 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9086 | `grunt mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8964 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 8930 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8905 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8619 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8559 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8477 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8358 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8292 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8252 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8119 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7946 | `npm run eslint && npm run mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7907 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7775 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7559 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7477 | `npm run build && istanbul cover _mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7445 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7442 | `mocha` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7428 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [aui/art-template](https://github.com/aui/art-template) | 7426 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7365 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7307 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6848 | `mocha; jshint *.js lib` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6829 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6708 | `mocha --exit --require @babel/register` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6662 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6592 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6380 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6352 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6284 | `npm run test:mocha:src` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6094 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6060 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6021 | `mocha tests/node.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5900 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5828 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5821 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5807 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5777 | `mocha && eslint lib/**` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5759 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5512 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5498 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5483 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5416 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5276 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5230 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5512 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5498 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5483 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5416 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5276 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5230 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5189 | `mocha src/**/*Tests.js --harmony` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5173 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5156 | `mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5146 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5031 | `gulp lint && mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4926 | `mocha test` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4874 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4816 | `gulp build; mocha;` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4801 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4794 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4768 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4760 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4700 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4682 | `./node_modules/.bin/mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4644 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4574 | `npm run lint && npm run mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4571 | `mocha ./test/runner.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4555 | `nyc mocha --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4545 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4454 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4447 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4421 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4417 | `nyc mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4338 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4288 | `mocha -R spec src` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4206 | `mocha -R spec ./test --recursive` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4192 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4191 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4189 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4147 | `mocha --timeout=15000 tests/*.test.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 4114 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4103 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4093 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4083 | `npm run lint ; mocha && mocha test/individual` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4059 | `mocha --require test/babel-hook test/*.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4048 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [tj/ejs](https://github.com/tj/ejs) | 4019 | `mocha --require should --reporter spec` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3986 | `mocha --check-leaks --reporter spec --bail` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3954 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3903 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3870 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3810 | `nyc mocha "test/**/*.test.js"` | 
| [erming/shout](https://github.com/erming/shout) | 3799 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3773 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3730 | `NODE_ENV=test mocha --exit` | 
| [expressjs/session](https://github.com/expressjs/session) | 3730 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3641 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3599 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3579 | `mocha tests/javascript` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3576 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3570 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3552 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3552 | `mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3522 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3476 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3461 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3381 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3327 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3312 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3476 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3471 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3461 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3444 | `mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3381 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3363 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3327 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3312 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3199 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3181 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3173 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3168 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3146 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3145 | `mocha test/*.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3142 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3139 | `mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3139 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3134 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3123 | `mocha test/index.js && npm run demo` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3093 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3089 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3066 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3060 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3056 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3039 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2995 | `eslint . && mocha -t 5000` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2989 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2986 | `mocha -R landing test/index` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2982 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2995 | `eslint . && mocha -t 5000` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2989 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2986 | `mocha -R landing test/index` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2982 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2963 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2918 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2911 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2907 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2895 | `mocha` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2894 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2890 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2878 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2855 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [mde/ejs](https://github.com/mde/ejs) | 2847 | `mocha --require should --reporter spec` | 
| [github-tools/github](https://github.com/github-tools/github) | 2832 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2829 | `istanbul cover _mocha` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2826 | `mocha test-node` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2825 | `mocha -R spec spec spec/reporters` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2822 | `mocha --require babel-register --recursive spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2820 | `mocha` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2816 | `node_modules/.bin/mocha --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2792 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2773 | `mocha --require should --reporter spec` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2770 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2765 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [css/csso](https://github.com/css/csso) | 2745 | `mocha --reporter dot` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2732 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2724 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2705 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2691 | `npm run build && cd test && mocha . --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2724 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2705 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2691 | `npm run build && cd test && mocha . --reporter dot` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2671 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2666 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2663 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2653 | `mocha --timeout 100000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2642 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2626 | `nyc mocha --timeout=10000` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2616 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2611 | `mocha-phantomjs ./test/index.html` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2594 | `nyc mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2575 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2570 | `mocha "test/**/*-test.js"` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2281 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [gajus/swing](https://github.com/gajus/swing) | 2243 | `mocha --compilers js:babel-register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2227 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2221 | `mocha test test/unit/**/*_test.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2170 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2144 | `standard && mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2140 | `nyc npm run _mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2354 | `grunt jshint && mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2346 | `mocha && eslint .` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2312 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2291 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2286 | `mocha -R spec test/*.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2284 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2281 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [gajus/swing](https://github.com/gajus/swing) | 2243 | `mocha --compilers js:babel-register` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2235 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2231 | `mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2227 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2170 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2161 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2152 | `cross-env BABEL_ENV=test mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2140 | `nyc npm run _mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2130 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2126 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2118 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2113 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2097 | `mocha test/runner.js --reporter spec` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2096 | `mocha` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2093 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2066 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2065 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2061 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2056 | `mocha && eslint *.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2051 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [pahen/madge](https://github.com/pahen/madge) | 2042 | `npm run lint && npm run mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2024 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2011 | `mocha --compilers js:babel-core/register __tests__` | 
| [slate/slate](https://github.com/slate/slate) | 1999 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1995 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1994 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1982 | `./node_modules/.bin/mocha && npm run jshint` | 
| [kach/nearley](https://github.com/kach/nearley) | 1947 | `mocha test/*.test.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1945 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1945 | `npm run lint && mocha -R dot && npm run cover` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1937 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1931 | `mocha --require ./test/common --growl test/expect.js` | 
| [retejs/rete](https://github.com/retejs/rete) | 1925 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1924 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1921 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1915 | `npm run mocha && npm run karma` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1910 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1894 | `mocha --compilers js:babel-register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1888 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1884 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1894 | `mocha --compilers js:babel-register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1888 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1884 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1877 | `mocha tests.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1869 | `mocha --reporter spec && npm run test-typescript` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1854 | `mocha && npm run lint` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1852 | `mocha --reporter spec test/*.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1843 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1843 | `mocha tests --require @babel/register` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1830 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1825 | `mocha test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1822 | `mocha --reporter spec --grep .` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1819 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1816 | `mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1815 | `mocha test/**/*.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1815 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1808 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1803 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1802 | `mocha test -u bdd -R spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1787 | `npm run lint && npm run mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1759 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1755 | `mocha ./test/basic.js -t 5000` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1681 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1673 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1672 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1671 | `mocha test/setup.js test/spec/*.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1669 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1663 | `xo && mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1655 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1644 | `mocha spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1638 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1633 | `mocha tests/test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1625 | `mocha tests.js` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1621 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1618 | `mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1611 | `standard "./src/*.js" && mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1609 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1607 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1592 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1585 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1577 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1577 | `mocha --check-leaks --reporter spec --bail` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1571 | `mocha --reporter spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1565 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1556 | `mocha test.js` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1555 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1544 | `npm run test:lint && npm run test:mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1618 | `mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1611 | `standard "./src/*.js" && mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1609 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1607 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1592 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1585 | `./node_modules/mocha/bin/mocha -R spec` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1582 | `mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1577 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1577 | `mocha --check-leaks --reporter spec --bail` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1571 | `mocha --reporter spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1565 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1411 | `npm run lint && mocha && karma start --single-run` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1407 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1403 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1398 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1398 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1392 | `mocha -R spec ./test/unit/**` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1384 | `npm run build && mocha -r should` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1383 | `mocha tests/test-*` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1380 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1372 | `mocha --opts test/opts/mocha.opts` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1367 | `standard && istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1365 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1362 | `mocha --reporter dot` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1359 | `cross-env NODE_ENV=test nyc mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1349 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1348 | `npm run lint && npm run mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1486 | `mocha test/**/*.spec.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1481 | `mocha -R spec` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1477 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1464 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1434 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1434 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [noble/bleno](https://github.com/noble/bleno) | 1430 | `mocha -R spec test/*.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1425 | `mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1422 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1417 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1411 | `npm run lint && mocha && karma start --single-run` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1407 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1403 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1398 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1398 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1392 | `mocha -R spec ./test/unit/**` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1392 | `istanbul cover _mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1384 | `npm run build && mocha -r should` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1383 | `mocha tests/test-*` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1382 | `./node_modules/mocha/bin/mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1382 | `mocha ./test/test*.js --reporter spec` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1380 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1372 | `mocha --opts test/opts/mocha.opts` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1367 | `standard && istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1365 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1362 | `mocha --reporter dot` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1359 | `cross-env NODE_ENV=test nyc mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1349 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1348 | `npm run lint && npm run mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1346 | `mocha --recursive` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1338 | `./node_modules/.bin/mocha test` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1338 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1335 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1335 | `mocha` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1327 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1320 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1320 | `NODE_PATH=. mocha **/*.spec.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1314 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1307 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1306 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1304 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1303 | `mocha-phantomjs tests/index.html` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1299 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1299 | `mocha` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1296 | `mocha spec/exec.js` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1295 | `mocha --recursive test/bin` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1292 | `mocha --timeout 60000 test/` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1289 | `mocha --check-leaks --reporter spec --bail test/` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1283 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1282 | `mocha --recursive test` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1283 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1282 | `mocha --recursive test` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1278 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1275 | `mocha test/*.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1274 | `npm run prepublishOnly && mocha test/test.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1270 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1265 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1265 | `mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1263 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1262 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1253 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1252 | `mocha tests` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1250 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1249 | `mocha` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1246 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1243 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1246 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1243 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1242 | `mocha src/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1239 | `npm run lint && npm run mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1236 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1233 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1231 | `istanbul test _mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1229 | `mocha --compilers js:babel-core/register` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1227 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1223 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1221 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1215 | `mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1214 | `mocha test/test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1212 | `mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1210 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [variety/variety](https://github.com/variety/variety) | 1210 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1209 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1208 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1208 | `node ./node_modules/mocha/bin/mocha tests` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1208 | `webpack && npm run lint && npm run mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1198 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1198 | `mocha test` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1197 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1196 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1188 | `npm run lint && mocha --require @babel/register` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1184 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1183 | `npm run mocha:istanbul` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1183 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [router5/router5](https://github.com/router5/router5) | 1177 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1169 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1168 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1167 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1156 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1152 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1143 | `mocha --timeout 20000` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1136 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1135 | `istanbul cover _mocha test/*.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1134 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1133 | `xo && mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1132 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1118 | `mocha test/*` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1118 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1113 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1112 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1110 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1106 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1103 | `mocha --reporter spec --bail --check-leaks test/` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1097 | `webpack && mocha test/unit` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1088 | `mocha --check-leaks -t 20000` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1086 | `mocha --reporter spec --bail --check-leaks test/` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1085 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1072 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1071 | `mocha --recursive --bail --reporter spec test` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1070 | `standard && mocha -b` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1068 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1064 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1063 | `mocha test/tests.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 1053 | `mocha && standard` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1050 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1055 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1053 | `mocha && standard` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1050 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1041 | `eslint src test && mocha --compilers babel-register` | 
| [tomas/needle](https://github.com/tomas/needle) | 1039 | `mocha test` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1035 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1034 | `mocha --reporter spec --timeout 3000` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1033 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1031 | `npm run convertto:es5 && npm run mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1030 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1015 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1008 | `mocha --check-leaks -R dot` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1007 | `mocha --recursive test/unit/` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 999 | `mocha --colors ./test/*.spec.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 993 | `mocha -R list` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 992 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 991 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 985 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 985 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 985 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 980 | `mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 980 | `mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 974 | `npm run rollup-cjs && mocha test/test.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 973 | `mocha --reporter spec` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 970 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 966 | `mocha test` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 964 | `mocha --reporter spec --bail --check-leaks test/` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 963 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 959 | `mocha "client.test" --compilers js:babel-register` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 957 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 953 | `mocha` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 953 | `mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 952 | `mocha --compilers js:babel-register test/*.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 949 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 948 | `npm run lint && mocha -R spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 943 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 942 | `mocha --timeout 5000` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 929 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 929 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 929 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 929 | `mocha spec/*.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 923 | `mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 920 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 917 | `mocha -t 600000` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 917 | `mocha test` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 914 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 911 | `./node_modules/.bin/mocha --reporter spec` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 893 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 892 | `mocha --recursive ./test/*_spec.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 891 | `mocha` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 890 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 889 | `node_modules/.bin/mocha` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 888 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 886 | `./node_modules/.bin/mocha --globals angular,require` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 886 | `mocha test --compilers js:babel-register` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 880 | `npm run lint && npm run mocha:no-functional` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 878 | `istanbul cover -- _mocha --reporter spec` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 877 | `mocha -t 5000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 877 | `standard && standard ./bin/* && mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 875 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 871 | `mocha --timeout 200000` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 870 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 869 | `node_modules/.bin/mocha test/spec` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 878 | `istanbul cover -- _mocha --reporter spec` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 877 | `standard && standard ./bin/* && mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 875 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 871 | `mocha --timeout 200000` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 870 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 869 | `node_modules/.bin/mocha test/spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 866 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 866 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 862 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 858 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 858 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 857 | `eslint test && mocha --compilers js:babel/register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 854 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 852 | `mocha test/index.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 851 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 850 | `istanbul cover _mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 849 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 848 | `mocha --reporter spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 845 | `mocha --check-leaks -t 20000` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 843 | `mocha --compilers js:@babel/register --reporter spec test/**/*.test.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 842 | `npm run lint && mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 842 | `mocha test` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 842 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 840 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 836 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 834 | `mocha --reporter spec --bail --check-leaks test/` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 833 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 832 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 831 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 830 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 827 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 827 | `mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 826 | `mocha && ember test` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 825 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 823 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 821 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 821 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 820 | `npm run build && istanbul test _mocha test/test.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 819 | `./node_modules/.bin/mocha test/**/*` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 816 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 815 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 815 | `mocha --harmony --full-trace --check-leaks` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 814 | `mocha --async-only` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 812 | `mocha --opts mocha.opts` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 811 | `mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 809 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 809 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 808 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 806 | `mocha --colors --reporter spec test.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 801 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 799 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 797 | `npm run mocha-test test/integration` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 796 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 796 | `mocha -R spec tests/` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 793 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 792 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 792 | `mocha -u tdd` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 792 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 790 | `mocha -r should --reporter spec test/*.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 788 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 787 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [developit/decko](https://github.com/developit/decko) | 784 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 788 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 787 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 785 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [developit/decko](https://github.com/developit/decko) | 784 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 782 | `xo && mocha -R spec` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 779 | `mocha test` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 778 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 775 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 772 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 769 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 769 | `nyc mocha` | 