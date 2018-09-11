# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:00 09/11/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43499 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41287 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40099 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30268 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 26414 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24594 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 24465 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23485 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20035 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19139 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17272 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16940 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16858 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15383 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14377 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14114 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13731 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13277 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12851 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12707 | `mocha 'test/**/*.spec.js'` | 
| [svg/svgo](https://github.com/svg/svgo) | 10300 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10228 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10183 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9863 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9853 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 9523 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9196 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9052 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8825 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8812 | `mocha tests/*.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8801 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8552 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8454 | `mocha --check-leaks -R dot` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9863 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9853 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 9523 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9428 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9220 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9196 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9052 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8825 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8812 | `mocha tests/*.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8801 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8553 | `mocha test/src` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8552 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8529 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8454 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8346 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8211 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8185 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8093 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7982 | `mocha --opts mocha.opts` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7927 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7753 | `./node_modules/.bin/mocha test` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7751 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [dthree/cash](https://github.com/dthree/cash) | 7561 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7457 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7440 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7340 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7326 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7302 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7167 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7099 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 7086 | `mocha --compilers js:babel-core/register` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7074 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6944 | `mocha $HARMONY_OPTS` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 6819 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js'` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6763 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6681 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6537 | `mocha --exit --require babel-core/register` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6530 | `npm run jshint && mocha test/` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6434 | `mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6307 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6301 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6257 | `npm run test:mocha:src` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6054 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6004 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5977 | `mocha tests/node.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5934 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5860 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5818 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5759 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5751 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5751 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5737 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5541 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5421 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5420 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5410 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5401 | `standard && mocha` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5183 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5149 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5130 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5112 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5111 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5070 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4992 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4857 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4846 | `mocha test` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4791 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4768 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4766 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4745 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4700 | `mocha --reporter spec -t 8000` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4691 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4665 | `./node_modules/.bin/mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4574 | `mocha ./test/runner.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4517 | `mocha --recursive` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4502 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4495 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4481 | `nyc mocha --exit` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4445 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4440 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4343 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4302 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4220 | `mocha -R spec src` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4217 | `mocha -R spec ./test --recursive` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4200 | `nyc mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4162 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4108 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4082 | `mocha --timeout=15000 tests/*.test.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4052 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4049 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4044 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4042 | `mocha --require test/babel-hook test/*.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4038 | `npm run lint ; mocha && mocha test/individual` | 
| [tj/ejs](https://github.com/tj/ejs) | 4000 | `mocha --require should --reporter spec` | 
| [teambit/bit](https://github.com/teambit/bit) | 3949 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3947 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3925 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3920 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3909 | `mocha --check-leaks --reporter spec --bail` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3901 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3881 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [erming/shout](https://github.com/erming/shout) | 3803 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3765 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3740 | `nyc mocha "test/**/*.test.js"` | 
| [primus/primus](https://github.com/primus/primus) | 3680 | `npm run build && mocha test/*.test.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3679 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3676 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3674 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3593 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3581 | `mocha tests/javascript` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3573 | `NODE_ENV=test mocha --exit` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3568 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3566 | `node_modules/.bin/mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3551 | `mocha --reporter spec --timeout 3000` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3541 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3529 | `NODE_ENV=test mocha test/**/*.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3510 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3495 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3294 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3284 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3249 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3247 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3221 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3186 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3163 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3153 | `./node_modules/.bin/mocha test/test.*.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3132 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3131 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3127 | `mocha test/*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3095 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3094 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3186 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3163 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3153 | `./node_modules/.bin/mocha test/test.*.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3148 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3132 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3131 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3127 | `mocha test/*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3095 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3094 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3093 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3089 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3078 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3064 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3041 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3033 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3025 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3022 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3005 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3033 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3025 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3022 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3005 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2956 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2948 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2939 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2912 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2907 | `mocha -R landing test/index` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2903 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2902 | `mocha -R spec --recursive src/test` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2902 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2883 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2874 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2866 | `eslint . && mocha -t 5000` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2863 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2859 | `npm run mocha && npm run lint` | 
| [github-tools/github](https://github.com/github-tools/github) | 2825 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2810 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2808 | `mocha -R spec spec spec/reporters` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2803 | `mocha test-node` | 
| [mde/ejs](https://github.com/mde/ejs) | 2787 | `mocha --require should --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2774 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2745 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [css/csso](https://github.com/css/csso) | 2735 | `mocha --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2723 | `xo && mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2717 | `mocha test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2707 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2703 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2701 | `mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2696 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2657 | `npm run build && cd test && mocha . --reporter dot` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2656 | `mocha --timeout 100000` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2703 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2701 | `mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2696 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2657 | `npm run build && cd test && mocha . --reporter dot` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2656 | `mocha --timeout 100000` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2656 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2636 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2634 | `mocha --recursive --watch` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2613 | `mocha-phantomjs ./test/index.html` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2604 | `nyc mocha --timeout=10000` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2598 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2575 | `mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2575 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2571 | `nyc mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2547 | `mocha "test/**/*-test.js"` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2487 | `mocha --reporter=spec test/*-test.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2487 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2476 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2469 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2466 | `mocha test/src/**/*.unit.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2456 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2452 | `mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2440 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2418 | `mocha --no-colors --reporter spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2407 | `nyc --reporter=html --reporter=text mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2396 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2358 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2354 | `grunt jshint && mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2350 | `mocha test && npm run lint` | 
| [noble/noble](https://github.com/noble/noble) | 2237 | `mocha -R spec test/*.js` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2237 | `mocha test test/unit/**/*_test.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2232 | `mocha --compilers js:babel-register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2229 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2216 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2185 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2150 | `cross-env BABEL_ENV=test mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2140 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2128 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2124 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2122 | `standard && mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2121 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2070 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2045 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2040 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2024 | `mocha && eslint *.js` | 
| [slate/slate](https://github.com/slate/slate) | 2006 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2001 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2000 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [zeeshanu/dumper.js](https://github.com/zeeshanu/dumper.js) | 1996 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [pahen/madge](https://github.com/pahen/madge) | 1995 | `npm run lint && npm run mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1994 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1991 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1972 | `mocha --require=test/test_helper.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1971 | `mocha -c test/index.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1966 | `mocha --reporter spec --timeout 5000` | 
| [share/sharedb](https://github.com/share/sharedb) | 1961 | `./node_modules/.bin/mocha && npm run jshint` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1948 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1945 | `npm run lint && mocha -R dot && npm run cover` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1940 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1938 | `mocha` | 
| [then/promise](https://github.com/then/promise) | 1938 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1933 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1931 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1923 | `mocha --require ./test/common --growl test/expect.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1915 | `mocha test/*.test.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1908 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1895 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1883 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1878 | `mocha tests.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1877 | `npm run mocha && npm run karma` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1851 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1849 | `mocha --reporter spec && npm run test-typescript` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1842 | `mocha --compilers js:babel-register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1840 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1837 | `mocha && npm run lint` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1835 | `mocha --reporter spec test/*.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1821 | `mocha tests --require @babel/register` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1820 | `mocha test` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1815 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1812 | `npm run lint && mocha --reporter spec test/*.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1810 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1806 | `mocha --timeout 5000` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1802 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1801 | `mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1798 | `mocha test/**/*.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1779 | `npm run lint && npm run mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1761 | `mocha test -u bdd -R spec` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1757 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1753 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1737 | `mocha test/**/*_test.js --bail` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1735 | `mocha ./test/basic.js -t 5000` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1735 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1733 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1728 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1717 | `./node_modules/.bin/mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1715 | `mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1710 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1707 | `npm run lint && mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1706 | `mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1699 | `npm run lint && npm run mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1696 | `mocha test --timeout 600000` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1688 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1685 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1681 | `mocha test/* --reporter spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1680 | `mocha compiled_tests/` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1671 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1578 | `./node_modules/mocha/bin/mocha -R spec` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1577 | `mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1567 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1564 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1556 | `./node_modules/.bin/mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1548 | `mocha --check-leaks --reporter spec --bail` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1547 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1544 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1538 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1535 | `node_modules/.bin/mocha --recursive` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1532 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [retejs/rete](https://github.com/retejs/rete) | 1531 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1523 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1578 | `./node_modules/mocha/bin/mocha -R spec` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1577 | `mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1567 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1564 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1564 | `mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1562 | `mocha --reporter spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1556 | `./node_modules/.bin/mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1548 | `mocha --check-leaks --reporter spec --bail` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1547 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1544 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1538 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1535 | `node_modules/.bin/mocha --recursive` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1532 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [retejs/rete](https://github.com/retejs/rete) | 1531 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1523 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1512 | `nyc mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1511 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1511 | `mocha -u tdd` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1502 | `nyc mocha --timeout=20000 test.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1502 | `mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1486 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1480 | `mocha test/**/*.spec.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1486 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1480 | `mocha test/**/*.spec.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1465 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [samccone/drool](https://github.com/samccone/drool) | 1458 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1442 | `mocha test.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1316 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1315 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1309 | `NODE_PATH=. mocha **/*.spec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1304 | `mocha-phantomjs tests/index.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1302 | `mocha spec/exec.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1293 | `npm run lint && npm run mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1292 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1291 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1289 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1286 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1285 | `mocha --timeout 60000 test/` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1285 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1277 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1271 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1267 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1267 | `mocha --check-leaks --reporter spec --bail test/` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1266 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1266 | `mocha --recursive test/bin` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1262 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1262 | `mocha test/*.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1387 | `npm run lint && mocha && karma start --single-run` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1386 | `./node_modules/mocha/bin/mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1385 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1382 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1380 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1378 | `npm run build && mocha -r should` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1376 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1366 | `NODE_ENV=test mocha tests/*.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1365 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1363 | `cross-env NODE_ENV=test nyc mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1360 | `mocha --opts test/opts/mocha.opts` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1357 | `mocha tests/test-*` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1348 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1348 | `istanbul cover _mocha test -- --timeout 20000` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1345 | `standard && istanbul cover _mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1342 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1338 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1337 | `mocha --recursive` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1331 | `mocha --reporter dot` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1331 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1327 | `./node_modules/.bin/mocha test` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1321 | `mocha -R spec ./test/unit/**` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1318 | `mocha ./test/test*.js --reporter spec` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1316 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1315 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1309 | `NODE_PATH=. mocha **/*.spec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1304 | `mocha-phantomjs tests/index.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1302 | `mocha spec/exec.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1293 | `npm run lint && npm run mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1292 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1291 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1289 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1286 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1285 | `mocha --timeout 60000 test/` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1285 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1277 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1271 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1267 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1267 | `mocha --check-leaks --reporter spec --bail test/` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1266 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1266 | `mocha --recursive test/bin` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1262 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1262 | `mocha test/*.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1260 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1258 | `mocha tests` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1251 | `npm run prepublishOnly && mocha test/test.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1218 | `mocha test/test.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1214 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [normalize/mz](https://github.com/normalize/mz) | 1214 | `mocha --reporter spec` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1212 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1211 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1211 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1210 | `mocha --compilers js:babel-core/register` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1208 | `node ./node_modules/mocha/bin/mocha tests` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1207 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1198 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1198 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1195 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1193 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1186 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1210 | `mocha --compilers js:babel-core/register` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1208 | `node ./node_modules/mocha/bin/mocha tests` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1208 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1207 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1206 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1198 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1198 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1195 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1195 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1193 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1186 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1177 | `webpack && npm run lint && npm run mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1175 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1169 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1164 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1163 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1158 | `npm run lint && mocha --require @babel/register` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1155 | `mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1153 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1151 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1150 | `mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1146 | `npm run mocha:istanbul` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1132 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1128 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1127 | `istanbul cover _mocha test/*.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1123 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1118 | `mocha --timeout 20000` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1118 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1110 | `mocha test/*` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1108 | `mocha` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1107 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1107 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1107 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [electron/asar](https://github.com/electron/asar) | 1101 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1095 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1068 | `mocha --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1067 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1066 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1062 | `mocha test/tests.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1061 | `standard && mocha -b` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1058 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1053 | `mocha test --compilers js:babel-core/register` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1053 | `mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1046 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1041 | `npm-run-all test:jest test:server:mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1040 | `mocha && standard` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1037 | `mocha --reporter spec --timeout 3000` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1036 | `eslint src test && mocha --compilers babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1034 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 1030 | `mocha test` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1062 | `mocha test/tests.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1061 | `standard && mocha -b` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1058 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1053 | `mocha test --compilers js:babel-core/register` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1053 | `mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1046 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1041 | `npm-run-all test:jest test:server:mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1040 | `mocha && standard` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1037 | `mocha --reporter spec --timeout 3000` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1034 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 1030 | `mocha test` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1027 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1026 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 980 | `npm run rollup-cjs && mocha test/test.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 976 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 975 | `mocha --reporter spec` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 970 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 969 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [wilk/microjob](https://github.com/wilk/microjob) | 965 | `node --experimental-worker node_modules/.bin/_mocha ./test` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 960 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 959 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 956 | `mocha --reporter spec --bail --check-leaks test/` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 951 | `mocha "client.test" --compilers js:babel-register` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 949 | `mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 948 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 858 | `eslint test && mocha --compilers js:babel/register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 851 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 848 | `istanbul cover _mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 846 | `mocha --check-leaks -t 20000` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 845 | `mocha --reporter spec` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 844 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 836 | `mocha --reporter spec --bail --check-leaks test/` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 829 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 828 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 826 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 825 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 825 | `mocha && ember test` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 823 | `mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 822 | `mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 821 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 818 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 817 | `mocha --async-only` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 816 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 816 | `mocha --exit --use_strict src/*.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 814 | `mocha tests/*.test.js --reporter spec` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 810 | `mocha` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 810 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 810 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 808 | `cake build && mocha ./test/mocha/*.coffee` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 806 | `mocha --harmony --full-trace --check-leaks` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 803 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 802 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 801 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 801 | `mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 800 | `npm run build && istanbul test _mocha test/test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 799 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 798 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 798 | `mocha -u tdd` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 798 | `./node_modules/.bin/mocha test/**/*` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 798 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 797 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 796 | `npm run mocha-test test/integration` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 796 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 795 | `mocha --colors --reporter spec test.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 794 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 792 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 782 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 781 | `xo && mocha -R spec` | 
| [developit/decko](https://github.com/developit/decko) | 779 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 778 | `mocha` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 777 | `mocha -r should --reporter spec test/*.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 777 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 776 | `mocha test` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 773 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 773 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 766 | `mocha --ui tdd --require ./test/__setup` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 765 | `mocha --recursive -s 15 test/` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 764 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 763 | `mocha -R spec src/**/*_test.js` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 756 | `mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 753 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 753 | `mocha` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 753 | `nyc mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 753 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 752 | `mocha test` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 756 | `mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 753 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 753 | `mocha` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 753 | `nyc mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 753 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 752 | `mocha test` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 750 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 746 | `npm run lint && npm run mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 744 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 742 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 742 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 740 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 740 | `babel-node node_modules/.bin/_mocha -- test` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 738 | `mocha tests/*.mocha.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 737 | `mocha --reporter spec` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 735 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 733 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 733 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 731 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 731 | `npm run-script jshint && npm run-script mocha` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 708 | `mocha ./test/test.js --timeout 1000000` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 707 | `mocha` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 703 | `mocha $(find test -name '*.test.js')` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 703 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 699 | `npm run test-mocha && npm run test-karma` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 698 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 696 | `./node_modules/.bin/mocha -t 60000` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 661 | `mocha` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 657 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 655 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 654 | `mocha --recursive --compilers js:babel-core/register` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 653 | `mocha --require babel-register src/**/*.spec.js src/*.spec.js` | 
| [pburtchaell/react-notification](https://github.com/pburtchaell/react-notification) | 644 | `node_modules/.bin/mocha --compilers js:babel-core/register --reporter spec --recursive --timeout 5000 test/setup.js test/**/*.js` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 644 | `./node_modules/.bin/mocha --bail` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 696 | `mocha --reporter spec` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 692 | `mocha --compilers js:babel-core/register` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 691 | `jenkins-mocha ./tests/*.js` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 689 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 685 | `mocha` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 684 | `mocha --reporter spec --bail --check-leaks test/` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 684 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 683 | `mocha` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 659 | `./node_modules/.bin/mocha` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 658 | `mocha --reporter spec` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 657 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 657 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 656 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 655 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 654 | `mocha --recursive --compilers js:babel-core/register` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 654 | `mocha` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 653 | `./node_modules/.bin/mocha test/integration` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 652 | `mocha --require babel-register` | 
| [shime/livedown](https://github.com/shime/livedown) | 651 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 649 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 647 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 647 | `_mocha -u bdd --colors test/` | 