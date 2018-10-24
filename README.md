# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:20 10/24/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43997 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41550 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40693 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30489 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 24806 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 24766 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23965 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20434 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19457 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17667 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17285 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17174 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15879 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14454 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14354 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14193 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13501 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13147 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12792 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12522 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12308 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12281 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11840 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11722 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11692 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10909 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10579 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10447 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10404 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10279 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [tj/co](https://github.com/tj/co) | 10209 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10181 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [websockets/ws](https://github.com/websockets/ws) | 9787 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9602 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9500 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 9424 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9372 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9296 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9121 | `grunt mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9091 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 8986 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8970 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8670 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8577 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8493 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8380 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8328 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8277 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8139 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8020 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7959 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7818 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7560 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7508 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7503 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7495 | `npm run build && istanbul cover _mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7488 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7445 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7445 | `mocha` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7414 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [almende/vis](https://github.com/almende/vis) | 7228 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7177 | `xo && mocha test/*.js --timeout 100000` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7064 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7014 | `mocha $HARMONY_OPTS` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6965 | `mocha; jshint *.js lib` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6876 | `mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6810 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6802 | `mocha --exit --require @babel/register` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6653 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6457 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6384 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6303 | `npm run test:mocha:src` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6219 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6095 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6059 | `mocha tests/node.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6054 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5936 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5929 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5901 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5880 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5879 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5863 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5788 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5593 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5559 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5529 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5415 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5342 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5297 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5220 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5196 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5195 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5152 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5061 | `gulp lint && mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5002 | `mocha test` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4885 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4866 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4833 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4805 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4780 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4776 | `mocha test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4718 | `./node_modules/.bin/mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4711 | `mocha --reporter spec -t 8000` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4703 | `mocha --recursive` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4652 | `mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4625 | `nyc mocha --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4614 | `npm run lint && npm run mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4570 | `mocha ./test/runner.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4503 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4481 | `nyc mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4466 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4460 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4348 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 4338 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4323 | `mocha -R spec src` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4260 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4215 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4213 | `node_modules/.bin/mocha test/tests.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4205 | `mocha -R spec ./test --recursive` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4200 | `mocha --timeout=15000 tests/*.test.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4198 | `nyc mocha` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4133 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4127 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4107 | `npm run lint ; mocha && mocha test/individual` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4071 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4033 | `mocha --require should --reporter spec` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4031 | `mocha --check-leaks --reporter spec --bail` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3978 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3906 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3867 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3844 | `nyc mocha "test/**/*.test.js"` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3828 | `NODE_ENV=test mocha --exit` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3783 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 3776 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3771 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [primus/primus](https://github.com/primus/primus) | 3714 | `npm run build && mocha test/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3679 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3666 | `npm run jshint && npm run mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3665 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3646 | `NODE_ENV=test mocha test/**/*.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3613 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3587 | `mocha tests/javascript` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3586 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3582 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3561 | `mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3554 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3526 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3475 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3461 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3444 | `mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3399 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3357 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3341 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3319 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3292 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3319 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3292 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3208 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3198 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3191 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3189 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3186 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3170 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3168 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3165 | `mocha test/*.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3158 | `./node_modules/.bin/mocha test/test.*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3157 | `mocha test/index.js && npm run demo` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3146 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3134 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3109 | `mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3105 | `eslint . && mocha -t 5000` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3100 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3097 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3086 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3084 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3080 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3033 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3024 | `mocha -R landing test/index` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3017 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 3008 | `mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2977 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2952 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2927 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2920 | `npm run mocha && npm run lint` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2914 | `mocha -R spec --recursive src/test` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2907 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2904 | `mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2683 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2661 | `mocha --timeout 100000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2652 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2634 | `nyc mocha --timeout=10000` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2632 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2618 | `mocha-phantomjs ./test/index.html` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2615 | `nyc mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2590 | `mocha "test/**/*-test.js"` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2584 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2577 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2546 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2542 | `mocha test/unit --require mochahook` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2532 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2521 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2488 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2486 | `mocha test/src/**/*.unit.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2732 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2721 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tj/should.js](https://github.com/tj/should.js) | 2718 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2715 | `npm run build && cd test && mocha . --reporter dot` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2714 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2697 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2683 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2661 | `mocha --timeout 100000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2652 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2634 | `nyc mocha --timeout=10000` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2632 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2618 | `mocha-phantomjs ./test/index.html` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2615 | `nyc mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2590 | `mocha "test/**/*-test.js"` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2584 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2489 | `mocha test` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2488 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [retejs/rete](https://github.com/retejs/rete) | 2487 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2486 | `mocha test/src/**/*.unit.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2484 | `mocha --reporter=spec test/*-test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2459 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2442 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2421 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2409 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2391 | `mocha test && npm run lint` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2389 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2384 | `mocha test/index.js --reporter dot` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2370 | `grunt jshint && mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2421 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2409 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2391 | `mocha test && npm run lint` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2389 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2384 | `mocha test/index.js --reporter dot` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2382 | `mocha && eslint .` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2370 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2369 | `mocha -R spec` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2314 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 2313 | `mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2310 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2306 | `mocha -R spec test/*.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2201 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2182 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2174 | `nyc npm run _mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2159 | `cross-env BABEL_ENV=test mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2157 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2156 | `standard && mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2138 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2127 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2120 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2114 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2106 | `mocha test/runner.js --reporter spec` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2096 | `mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2094 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2088 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2074 | `mocha && eslint *.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2069 | `npm run lint && npm run mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2040 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2040 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [share/sharedb](https://github.com/share/sharedb) | 2011 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2006 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1998 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [slate/slate](https://github.com/slate/slate) | 1998 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1997 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1996 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1985 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [slate/slate](https://github.com/slate/slate) | 1998 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1997 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1996 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1985 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1980 | `mocha --reporter spec --timeout 5000` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1979 | `mocha --require=test/test_helper.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1969 | `mocha test/*.test.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1963 | `mocha -c test/index.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1959 | `npm run lint && mocha -R dot && npm run cover` | 
| [then/promise](https://github.com/then/promise) | 1950 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1939 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1936 | `mocha --require ./test/common --growl test/expect.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1936 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1929 | `mocha --compilers js:babel-register` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1927 | `npm run mocha && npm run karma` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1926 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1888 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1885 | `mocha --reporter spec && npm run test-typescript` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1877 | `mocha && npm run lint` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1876 | `mocha tests.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1868 | `mocha tests --require @babel/register` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1860 | `mocha --reporter spec test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1847 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1837 | `mocha test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1835 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1830 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1821 | `mocha test -u bdd -R spec` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1821 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1807 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1800 | `mocha --timeout 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1797 | `npm run lint && npm run mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1780 | `mocha test` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1775 | `mocha ./test/basic.js -t 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1767 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1752 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1742 | `mocha compiled_tests/` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1736 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1732 | `npm run lint && npm run mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1732 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1660 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1650 | `mocha spec` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1643 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1636 | `mocha tests/test.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1622 | `standard "./src/*.js" && mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1614 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1610 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1609 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1596 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1591 | `nyc mocha --timeout=20000 test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1588 | `./node_modules/mocha/bin/mocha -R spec` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1584 | `mocha --reporter spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1578 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1578 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1563 | `TEST=all mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1558 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1555 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1547 | `npm run test:lint && npm run test:mocha` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1541 | `nyc mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1530 | `node_modules/.bin/mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1520 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1635 | `mocha --expose-gc --slow 300` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1622 | `standard "./src/*.js" && mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1621 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1614 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1610 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1609 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1600 | `mocha --check-leaks --reporter spec --bail` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1596 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1591 | `nyc mocha --timeout=20000 test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1588 | `./node_modules/mocha/bin/mocha -R spec` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1584 | `mocha --reporter spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1582 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1578 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1448 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1447 | `mocha test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1440 | `mocha -R spec test/*.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1437 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1434 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1426 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1425 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1425 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1422 | `npm run lint && mocha && karma start --single-run` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1420 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1412 | `mocha -R spec ./test/unit/**` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1410 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1408 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1399 | `mocha tests/test-*` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1397 | `istanbul cover _mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1390 | `standard && istanbul cover _mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1382 | `mocha --opts test/opts/mocha.opts` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1488 | `mocha test/**/*.spec.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1486 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1482 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1478 | `mocha -R spec` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1475 | `mocha --timeout 10000 ./tests/lib.js` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1469 | `NODE_ENV=test mocha tests/*.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1467 | `mocha test/unit` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1460 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1457 | `mocha --check-leaks --require @babel/register` | 
| [samccone/drool](https://github.com/samccone/drool) | 1454 | `mocha test/tests.js --timeout=10000` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1448 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1447 | `mocha test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1440 | `mocha -R spec test/*.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1467 | `mocha test/unit` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1460 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1457 | `mocha --check-leaks --require @babel/register` | 
| [samccone/drool](https://github.com/samccone/drool) | 1454 | `mocha test/tests.js --timeout=10000` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1448 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1447 | `mocha test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1440 | `mocha -R spec test/*.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1437 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1434 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1426 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1425 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1425 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1422 | `npm run lint && mocha && karma start --single-run` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1420 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1415 | `mocha ./test/test*.js --reporter spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1412 | `mocha -R spec ./test/unit/**` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1410 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1408 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1399 | `mocha tests/test-*` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1397 | `istanbul cover _mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1395 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1390 | `standard && istanbul cover _mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1388 | `npm run build && mocha -r should` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1387 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1382 | `mocha --opts test/opts/mocha.opts` | 
| [electron/devtron](https://github.com/electron/devtron) | 1376 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1376 | `npm run lint && npm run mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1375 | `mocha --reporter dot` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1366 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1360 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1355 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1354 | `mocha --recursive` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1346 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1343 | `./node_modules/.bin/mocha test` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1340 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1331 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1327 | `NODE_PATH=. mocha **/*.spec.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1325 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1318 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1318 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1313 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1325 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1318 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1318 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1313 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1311 | `npm run prepublishOnly && mocha test/test.js` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1310 | `mocha --recursive test/bin` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1307 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1305 | `mocha-phantomjs tests/index.html` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1304 | `mocha` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1300 | `mocha spec/exec.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1299 | `mocha --recursive test` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1298 | `mocha --check-leaks --reporter spec --bail test/` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1296 | `mocha --timeout 60000 test/` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1296 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1286 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1281 | `mocha test/*.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1280 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1274 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1268 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1265 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1265 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1264 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1262 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1262 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1256 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1256 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1255 | `npm run lint && npm run mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1254 | `mocha tests` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1252 | `mocha src/test.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1252 | `mocha --compilers js:babel-core/register` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1247 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1245 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1194 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1189 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1184 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1180 | `mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1176 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1159 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1157 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1155 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1153 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1200 | `mocha test` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1200 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1200 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1194 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1189 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1184 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1180 | `mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1176 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1159 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1157 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1155 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1153 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [electron/asar](https://github.com/electron/asar) | 1142 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1139 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1138 | `istanbul cover _mocha test/*.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1138 | `mocha $(find test -name '*.test.js') --exit` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1138 | `mocha --timeout 30000 --recursive ./tests` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1138 | `xo && mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1137 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1134 | `mocha` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1090 | `mocha --check-leaks -t 20000` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1089 | `mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1074 | `standard && mocha -b` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1073 | `mocha --recursive --bail --reporter spec test` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1072 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1068 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1067 | `mocha test/tests.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1064 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1062 | `mocha && standard` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1059 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1058 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1068 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1067 | `mocha test/tests.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1064 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1062 | `mocha && standard` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1059 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1058 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1049 | `nyc --reporter=html --reporter=text mocha --recursive -r tests/setup tests` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1049 | `eslint src test && mocha --compilers babel-register` | 
| [tomas/needle](https://github.com/tomas/needle) | 1043 | `mocha test` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1042 | `npm run convertto:es5 && npm run mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1041 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1036 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1036 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1035 | `mocha --reporter spec test --recursive` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1049 | `nyc --reporter=html --reporter=text mocha --recursive -r tests/setup tests` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1049 | `eslint src test && mocha --compilers babel-register` | 
| [tomas/needle](https://github.com/tomas/needle) | 1043 | `mocha test` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1042 | `npm run convertto:es5 && npm run mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1041 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1036 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1036 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1035 | `mocha --reporter spec test --recursive` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1034 | `mocha --reporter spec --timeout 3000` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1029 | `mocha $(find test -name '*.test.js')` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1027 | `mocha --async-only` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1021 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1021 | `mocha` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1012 | `mocha --recursive test/unit/` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1011 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1010 | `mocha --colors ./test/*.spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1008 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 994 | `mocha -R list` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 994 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 992 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 992 | `mocha test` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 988 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 984 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 979 | `mocha --reporter spec --bail --check-leaks test/` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 978 | `mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 973 | `npm run rollup-cjs && mocha test/test.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 973 | `mocha --reporter spec` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 970 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 965 | `mocha "client.test" --compilers js:babel-register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 963 | `mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 961 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 958 | `mocha --compilers js:babel-register test/*.js` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 958 | `mocha --recursive` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 957 | `mocha` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 955 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 954 | `npm run lint && mocha -R spec` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 949 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 947 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 943 | `mocha --timeout 5000` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 935 | `mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 932 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 932 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 935 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 935 | `mocha spec/*.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 932 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 932 | `mocha tests` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 929 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 925 | `mocha -t 600000` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 925 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 920 | `mocha test` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 920 | `./node_modules/.bin/mocha --reporter spec` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 918 | `nyc --check-coverage mocha test/*.test.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 915 | `./node_modules/.bin/mocha -R spec` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 912 | `nyc mocha specs` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 877 | `mocha -t 5000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 871 | `node_modules/.bin/mocha test/spec` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 869 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 868 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 861 | `mocha test/index.js` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 859 | `eslint test && mocha --compilers js:babel/register` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 858 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 855 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 854 | `mocha --reporter list` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 853 | `mocha --reporter spec` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 869 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 868 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 866 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 866 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 859 | `eslint test && mocha --compilers js:babel/register` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 858 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 855 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 854 | `mocha --reporter list` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 853 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 852 | `istanbul cover _mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 851 | `mocha test` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 851 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 859 | `eslint test && mocha --compilers js:babel/register` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 858 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 855 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 854 | `mocha --reporter list` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 853 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 852 | `istanbul cover _mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 851 | `mocha test` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 851 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 847 | `mocha --check-leaks -t 20000` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 845 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 843 | `npm run lint && mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 843 | `mocha` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 842 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 841 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 835 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 828 | `npm run build && istanbul test _mocha test/test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 828 | `mocha && ember test` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 827 | `./node_modules/.bin/mocha test/**/*` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 825 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 824 | `mocha --opts mocha.opts` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 822 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 821 | `mocha --harmony --full-trace --check-leaks` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 819 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 819 | `mocha --async-only` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 818 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 817 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 827 | `./node_modules/.bin/mocha test/**/*` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 825 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 824 | `mocha --opts mocha.opts` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 822 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 821 | `mocha --harmony --full-trace --check-leaks` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 819 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 819 | `mocha --async-only` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 818 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 817 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 815 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 815 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 815 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 774 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 772 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 770 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 770 | `mocha --recursive -s 15 test/` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 768 | `mocha test` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 766 | `mocha -R spec src/**/*_test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 764 | `mocha --ui tdd --require ./test/__setup` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 755 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 