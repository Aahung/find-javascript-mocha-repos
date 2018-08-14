# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:03 08/14/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43164 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41121 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39649 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30101 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 25726 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24454 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23153 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19712 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18941 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16781 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16533 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15149 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14322 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13935 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13449 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13115 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12691 | `./node_modules/.bin/mocha test/` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12630 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12306 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12236 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11779 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11475 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11127 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11123 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10434 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10103 | `set NODE_ENV=test && mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10097 | `mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10090 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [tj/co](https://github.com/tj/co) | 10020 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9944 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9634 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9592 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9370 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 9339 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9074 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9029 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8988 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8706 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8683 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8635 | `mocha tests/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8490 | `mocha test/test.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8449 | `mocha test/src` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8432 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8317 | `grunt clean:test && mocha --exit` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8237 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8165 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8059 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7966 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7894 | `npm run eslint && npm run mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7773 | `mocha --opts mocha.opts` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7692 | `./node_modules/.bin/mocha test` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7565 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [dthree/cash](https://github.com/dthree/cash) | 7551 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7437 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7420 | `npm run build && istanbul cover _mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7223 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7198 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7191 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7036 | `xo && mocha test/*.js --timeout 100000` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7012 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [almende/vis](https://github.com/almende/vis) | 6971 | `mocha --compilers js:babel-core/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6885 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6824 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6660 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6448 | `npm run jshint && mocha test/` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6403 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6332 | `mocha --exit --require babel-core/register` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6247 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6216 | `npm run test:mocha:src` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6190 | `mocha test/test.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6081 | `mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6052 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5964 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5897 | `mocha tests/node.js` | 
| [shipshapecode/shepherd](https://github.com/shipshapecode/shepherd) | 5814 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5806 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5717 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5688 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5607 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5606 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5602 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5410 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5320 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5276 | `standard && mocha` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5176 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5150 | `mocha --color` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5149 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5085 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4969 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4952 | `gulp lint && mocha` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4949 | `mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4840 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4741 | `gulp build; mocha;` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4739 | `mocha test` | 
| [santinic/how2](https://github.com/santinic/how2) | 4733 | `mocha test` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4732 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4730 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4694 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4612 | `./node_modules/.bin/mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4567 | `mocha ./test/runner.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4539 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4463 | `mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4432 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4416 | `nyc mocha --exit` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4416 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4402 | `npm run lint && npm run mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4402 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4326 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4213 | `mocha -R spec ./test --recursive` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4172 | `npm run lint && npm run mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4142 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4134 | `mocha -R spec src` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4092 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4062 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4022 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4013 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4006 | `mocha --require test/babel-hook test/*.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3995 | `mocha --timeout=15000 tests/*.test.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3994 | `npm run lint ; mocha && mocha test/individual` | 
| [tj/ejs](https://github.com/tj/ejs) | 3977 | `mocha --require should --reporter spec` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3894 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3881 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3861 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3846 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3832 | `mocha --check-leaks --reporter spec --bail` | 
| [erming/shout](https://github.com/erming/shout) | 3804 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [teambit/bit](https://github.com/teambit/bit) | 3781 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3778 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3746 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3703 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3670 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3668 | `standard && mocha --timeout 60000 test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3655 | `npm run build && mocha test/*.test.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3653 | `nyc mocha "test/**/*.test.js"` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3670 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3668 | `standard && mocha --timeout 60000 test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3655 | `npm run build && mocha test/*.test.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3653 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 3612 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3584 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3577 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3562 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3549 | `node_modules/.bin/mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3542 | `mocha --reporter spec --timeout 3000` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3524 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3517 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3507 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3463 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3460 | `node_modules/.bin/mocha test/lib/` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3455 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3438 | `mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3432 | `NODE_ENV=test mocha test/**/*.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3401 | `NODE_ENV=test mocha --exit` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3394 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3339 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3237 | `nyc mocha && tsc` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3236 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3232 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3219 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3173 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3168 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3154 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3143 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3140 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3129 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3115 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3064 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3059 | `mocha test/*.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3058 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3047 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3044 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3040 | `mocha test/index.js && npm run demo` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3037 | `mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3025 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3019 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3009 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2990 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2976 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2887 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2877 | `mocha -R spec --recursive src/test` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2877 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2869 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2864 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2847 | `mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2827 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2822 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2819 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2807 | `npm run mocha && npm run lint` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2792 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2791 | `mocha -R landing test/index` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2773 | `mocha` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2752 | `mocha test-node` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2745 | `mocha -R spec spec spec/reporters` | 
| [css/csso](https://github.com/css/csso) | 2721 | `mocha --reporter dot` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2792 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2791 | `mocha -R landing test/index` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2773 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2770 | `mocha --require should --reporter spec` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2757 | `mocha --require babel-register --recursive spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2752 | `mocha test-node` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2745 | `mocha -R spec spec spec/reporters` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2726 | `node_modules/.bin/mocha --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2721 | `mocha --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2705 | `xo && mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2700 | `mocha --require should --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2700 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2672 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [json5/json5](https://github.com/json5/json5) | 2656 | `nyc --reporter=html --reporter=text mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2648 | `mocha --timeout 100000` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2648 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2510 | `mocha "test/**/*-test.js"` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2510 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2470 | `mocha --reporter=spec test/*-test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2458 | `mocha test` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2445 | `mocha test/unit --require mochahook` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2443 | `mocha test/src/**/*.unit.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2443 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2436 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2415 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2408 | `mocha --no-colors --reporter spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2386 | `nyc --reporter=html --reporter=text mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2380 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2351 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2350 | `grunt jshint && mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2339 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2124 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2108 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2104 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2090 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2073 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2050 | `nyc npm run _mocha` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2048 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2047 | `mocha test/runner.js --reporter spec` | 
| [slate/slate](https://github.com/slate/slate) | 2004 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 1933 | `npm run lint && npm run mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1930 | `mocha --bail --reporter spec --check-leaks test/` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1923 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [then/promise](https://github.com/then/promise) | 1919 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1912 | `npm run lint && mocha -R dot && npm run cover` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1911 | `mocha --require ./test/common --growl test/expect.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1911 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [kach/nearley](https://github.com/kach/nearley) | 1887 | `mocha test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1864 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [noble/noble](https://github.com/noble/noble) | 2190 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2181 | `mocha --compilers js:babel-register` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2144 | `cross-env BABEL_ENV=test mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2139 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2124 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2108 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2104 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2101 | `standard && mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2090 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2074 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2050 | `nyc npm run _mocha` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2048 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2047 | `mocha test/runner.js --reporter spec` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2015 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [slate/slate](https://github.com/slate/slate) | 2004 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1986 | `mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1982 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1973 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1960 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1943 | `mocha --reporter spec --timeout 5000` | 
| [share/sharedb](https://github.com/share/sharedb) | 1937 | `./node_modules/.bin/mocha && npm run jshint` | 
| [pahen/madge](https://github.com/pahen/madge) | 1933 | `npm run lint && npm run mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1930 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1926 | `mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1923 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [then/promise](https://github.com/then/promise) | 1919 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1912 | `npm run lint && mocha -R dot && npm run cover` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1911 | `mocha --require ./test/common --growl test/expect.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1911 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [kach/nearley](https://github.com/kach/nearley) | 1887 | `mocha test/*.test.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1878 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1875 | `mocha tests.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1864 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [kach/nearley](https://github.com/kach/nearley) | 1887 | `mocha test/*.test.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1878 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1875 | `mocha tests.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1864 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1839 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1838 | `mocha --reporter spec && npm run test-typescript` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1832 | `npm run mocha && npm run karma` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1826 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1811 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1809 | `mocha --reporter spec test/*.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1811 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1809 | `mocha --reporter spec test/*.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1800 | `mocha test` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1800 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1799 | `mocha && npm run lint` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1795 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1794 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1791 | `npm run lint && mocha --reporter spec test/*.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1791 | `mocha tests --compilers js:babel-core/register` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1780 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1780 | `mocha --compilers js:babel-register` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1779 | `mocha --reporter spec --grep .` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1760 | `npm run lint && npm run mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1758 | `mocha test/**/*.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1754 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1740 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1735 | `mocha test -u bdd -R spec` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1732 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1727 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1727 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1724 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1712 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1704 | `./node_modules/.bin/mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1701 | `mocha ./test/basic.js -t 5000` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1697 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1690 | `npm run lint && mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1688 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1685 | `mocha test --timeout 600000` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1680 | `mocha test/*.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1680 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1672 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1665 | `npm run lint && npm run mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1660 | `mocha test/* --reporter spec` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1658 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1651 | `mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1643 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1643 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1642 | `mocha compiled_tests/` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1633 | `mocha spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1631 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1627 | `mocha tests/test.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1625 | `mocha && size-limit` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1624 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1559 | `standard "./src/*.js" && mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1559 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1551 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1545 | `npm run test:lint && npm run test:mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1542 | `mocha --reporter spec` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1531 | `mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1529 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1524 | `mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1524 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1523 | `node_modules/.bin/mocha --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1520 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1516 | `mocha --check-leaks --reporter spec --bail` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1515 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1510 | `nyc npm run mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1526 | `mocha test.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1524 | `mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1524 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1520 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1516 | `mocha --check-leaks --reporter spec --bail` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1510 | `nyc npm run mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1504 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1501 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1498 | `nyc mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1485 | `mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1481 | `mocha -R spec` | 
| [retejs/rete](https://github.com/retejs/rete) | 1481 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1504 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1501 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1498 | `nyc mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1485 | `mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1481 | `mocha -R spec` | 
| [retejs/rete](https://github.com/retejs/rete) | 1481 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1474 | `mocha test/**/*.spec.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1455 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1452 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1418 | `mocha --timeout 10000 ./tests/lib.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1412 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1411 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1407 | `mocha -R spec test/*.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1402 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1387 | `istanbul cover _mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1383 | `mocha --check-leaks --require @babel/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1380 | `./node_modules/mocha/bin/mocha` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1378 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1375 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1374 | `mocha test/unit` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1373 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1364 | `npm run build && mocha -r should` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1359 | `TEST=all mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1358 | `cross-env NODE_ENV=test nyc mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1349 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1349 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1340 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1337 | `mocha --opts test/opts/mocha.opts` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1336 | `istanbul cover _mocha test -- --timeout 20000` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1324 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1324 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1321 | `./node_modules/.bin/mocha test` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1327 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1324 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1324 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1321 | `./node_modules/.bin/mocha test` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1321 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1321 | `mocha tests/test-*` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1321 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1320 | `mocha --recursive` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1310 | `standard && istanbul cover _mocha` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1309 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1306 | `mocha-phantomjs tests/index.html` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1303 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1298 | `mocha --reporter dot` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1296 | `mocha spec/exec.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1286 | `NODE_PATH=. mocha **/*.spec.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1285 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1280 | `NODE_ENV=test mocha tests/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1273 | `mocha --timeout 60000 test/` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1272 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1266 | `mocha ./test/test*.js --reporter spec` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1263 | `mocha -R spec ./test/unit/**` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1261 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1261 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1260 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1257 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1253 | `mocha` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1250 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1249 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1249 | `mocha test/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1248 | `mocha tests` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1246 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1244 | `npm run lint && npm run mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1244 | `mocha --check-leaks --reporter spec --bail test/` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1239 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1230 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1221 | `mocha src/test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1218 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1218 | `mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1217 | `npm run prepublishOnly && mocha test/test.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1217 | `istanbul test _mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1216 | `mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1215 | `mocha --recursive test/bin` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1214 | `mocha test/test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1208 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1206 | `npm run lint && npm run mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1200 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1200 | `node ./node_modules/mocha/bin/mocha tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1200 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [normalize/mz](https://github.com/normalize/mz) | 1200 | `mocha --reporter spec` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1200 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1200 | `node ./node_modules/mocha/bin/mocha tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1200 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [normalize/mz](https://github.com/normalize/mz) | 1200 | `mocha --reporter spec` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1195 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1190 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1188 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1188 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [variety/variety](https://github.com/variety/variety) | 1187 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1186 | `mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1182 | `mocha --recursive test` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1181 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1178 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1170 | `mocha --compilers js:babel-core/register` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1169 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1145 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1145 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1134 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1132 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1131 | `webpack && npm run lint && npm run mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1128 | `mocha` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1127 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1123 | `mocha $(find test -name '*.test.js')` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1121 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1120 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1118 | `npm run lint && mocha --require @babel/register` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1117 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1114 | `istanbul cover _mocha test/*.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1112 | `npm run mocha:istanbul` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1123 | `mocha $(find test -name '*.test.js')` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1122 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1121 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1120 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1118 | `npm run lint && mocha --require @babel/register` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1117 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1114 | `istanbul cover _mocha test/*.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1112 | `npm run mocha:istanbul` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1110 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1105 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1105 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1104 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1104 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [router5/router5](https://github.com/router5/router5) | 1104 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1102 | `mocha test/*` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1093 | `mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1090 | `mocha --check-leaks -t 20000` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1090 | `mocha --timeout 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1081 | `mocha --compilers js:babel-register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1075 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [electron/asar](https://github.com/electron/asar) | 1075 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1074 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1071 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1068 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1066 | `webpack && mocha test/unit` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1064 | `mocha --recursive --bail --reporter spec test` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1059 | `mocha test/tests.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1056 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1054 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1046 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1045 | `mocha --reporter spec --bail --check-leaks test/` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1043 | `mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1043 | `standard && mocha -b` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1040 | `mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1038 | `mocha --reporter spec --timeout 3000` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1037 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 1027 | `mocha && standard` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1023 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [tomas/needle](https://github.com/tomas/needle) | 1022 | `mocha test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 944 | `mocha "client.test" --compilers js:babel-register` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 941 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 939 | `mocha --compilers js:babel-register test/*.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 938 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 936 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 926 | `npm run lint && mocha -R spec` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 923 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 916 | `mocha ./test/index.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 915 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 915 | `mocha tests` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 914 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 911 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 909 | `mocha test` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 907 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 905 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 905 | `mocha spec/*.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 901 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 888 | `mocha test` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 887 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 886 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 885 | `node_modules/.bin/mocha` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 885 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 884 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 884 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 879 | `nyc mocha specs` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 874 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 874 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 870 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 870 | `./node_modules/.bin/mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 868 | `./node_modules/.bin/mocha -R spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 867 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 865 | `mocha --timeout 200000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 865 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 865 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 864 | `npm run lint && npm run mocha:no-functional` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 863 | `mocha -t 5000` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 862 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 860 | `node_modules/.bin/mocha test/spec` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 860 | `mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 859 | `istanbul cover -- _mocha --reporter spec` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 857 | `standard && standard ./bin/* && mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 857 | `eslint test && mocha --compilers js:babel/register` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 855 | `mocha test --compilers js:babel-register` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 852 | `nyc --check-coverage mocha test/*.test.js` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 852 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 847 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 846 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 842 | `mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 842 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 840 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 840 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 840 | `istanbul cover _mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 840 | `mocha --check-leaks -t 20000` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 838 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 837 | `mocha --recursive ./test/*_spec.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 836 | `mocha --reporter list` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 836 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 831 | `npm run lint && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 831 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 830 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 830 | `mocha --reporter spec --bail --check-leaks test/` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 822 | `mocha && ember test` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 819 | `mocha test/index.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 818 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 816 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 813 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 813 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 813 | `mocha test` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 812 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 812 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 810 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 807 | `mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 793 | `mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 790 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 790 | `mocha --harmony --full-trace --check-leaks` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 788 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 788 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 787 | `npm run mocha-test test/integration` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 786 | `npm run build && istanbul test _mocha test/test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 786 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [edsu/anon](https://github.com/edsu/anon) | 785 | `mocha --colors --reporter spec test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 784 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 783 | `mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 782 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 782 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 781 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 778 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 777 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 776 | `xo && mocha -R spec` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 775 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 793 | `mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 790 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 790 | `mocha --harmony --full-trace --check-leaks` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 788 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 787 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 787 | `npm run mocha-test test/integration` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 786 | `npm run build && istanbul test _mocha test/test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 786 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 786 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 785 | `mocha --colors --reporter spec test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 784 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 783 | `mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 782 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 782 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 781 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 778 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 777 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 776 | `xo && mocha -R spec` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 775 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 771 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [developit/decko](https://github.com/developit/decko) | 770 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 768 | `mocha test` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 766 | `mocha --no-timeouts` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 764 | `mocha --ui tdd --require ./test/__setup` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 763 | `mocha -R spec src/**/*_test.js` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 761 | `mocha` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 758 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 757 | `mocha --recursive -s 15 test/` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 757 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 755 | `mocha -r should --reporter spec test/*.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 755 | `./node_modules/.bin/mocha test/**/*` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 752 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 750 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 750 | `mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 743 | `mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 741 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 740 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 740 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 740 | `npm run lint && npm run mocha` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 739 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 739 | `mocha --exit --use_strict src/*.test.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 739 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 738 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 737 | `mocha test` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 737 | `mocha --reporter spec` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 737 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 736 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 735 | `mocha tests/*.mocha.js` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 733 | `nyc mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 729 | `mocha test.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 728 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 728 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 728 | `mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 727 | `babel-node node_modules/.bin/_mocha -- test` | 