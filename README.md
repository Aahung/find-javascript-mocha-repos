# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:06 07/19/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29898 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 24873 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24317 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23901 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18746 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16613 | `mocha` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14263 | `nyc --reporter=html --reporter=text mocha` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16613 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16318 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14882 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14263 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13775 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13138 | `mocha --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12984 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12585 | `mocha 'test/**/*.spec.js'` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12558 | `./node_modules/.bin/mocha test/` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 12545 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12226 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12213 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11567 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11354 | `nyc grunt mocha-and-karma` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10902 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10883 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10254 | `mocha test/index.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9956 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 9939 | `mocha --harmony` | 
| [svg/svgo](https://github.com/svg/svgo) | 9935 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9934 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9867 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9488 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9337 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9290 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 9120 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8974 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8916 | `grunt mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8829 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8554 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [amark/gun](https://github.com/amark/gun) | 8494 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8447 | `mocha test/test.js` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8414 | `mocha tests/*.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8408 | `mocha --check-leaks -R dot` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8358 | `mocha test/src` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8267 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8124 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8022 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7916 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7846 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7813 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7625 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7541 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7522 | `mocha --opts mocha.opts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7438 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7388 | `npm run build && istanbul cover _mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7371 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 7129 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7092 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7062 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6944 | `xo && mocha test/*.js --timeout 100000` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6885 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [almende/vis](https://github.com/almende/vis) | 6881 | `mocha --compilers js:babel-core/register` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5823 | `mocha tests/node.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5732 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5683 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5645 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5512 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5497 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5408 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5371 | `mocha --timeout 10000 && npm run lint` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5370 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5225 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5172 | `mocha src/**/*Tests.js --harmony` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5162 | `standard && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5940 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5930 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5823 | `mocha tests/node.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5796 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5732 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5683 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5645 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5512 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5497 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5408 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5371 | `mocha --timeout 10000 && npm run lint` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5370 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5225 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5172 | `mocha src/**/*Tests.js --harmony` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5162 | `standard && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5155 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5034 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4928 | `gulp lint && mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4861 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4853 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4836 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4834 | `mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4725 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4721 | `mocha test` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4711 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4691 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4688 | `mocha --reporter spec -t 8000` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4670 | `mocha test` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4568 | `mocha ./test/runner.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4556 | `./node_modules/.bin/mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4439 | `mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4429 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4407 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4379 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4329 | `nyc mocha --exit` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4327 | `mocha --recursive && make test` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4323 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4303 | `npm run lint && npm run mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4132 | `nyc mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4069 | `npm run lint && npm run mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4061 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4036 | `nyc mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 3995 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3990 | `mocha --require test/babel-hook test/*.js` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3961 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3949 | `node_modules/.bin/mocha test/tests.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 3947 | `mocha --require should --reporter spec` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3945 | `npm run lint ; mocha && mocha test/individual` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3921 | `mocha --timeout=15000 tests/*.test.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3889 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3882 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3810 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [erming/shout](https://github.com/erming/shout) | 3803 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3742 | `mocha --check-leaks --reporter spec --bail` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3725 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3724 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3674 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3669 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3650 | `standard && mocha --timeout 60000 test/test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3633 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [primus/primus](https://github.com/primus/primus) | 3623 | `npm run build && mocha test/*.test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3610 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3593 | `nyc mocha "test/**/*.test.js"` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3572 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3562 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [teambit/bit](https://github.com/teambit/bit) | 3559 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [expressjs/session](https://github.com/expressjs/session) | 3554 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3530 | `mocha --reporter spec --timeout 3000` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3526 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3521 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3499 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3478 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3456 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3447 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3434 | `mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3428 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3423 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3370 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3355 | `NODE_ENV=test mocha test/**/*.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3256 | `NODE_ENV=test mocha --exit` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3253 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3188 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3181 | `nyc mocha && tsc` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3170 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3167 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3145 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3135 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3134 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3122 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3111 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3098 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3061 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3043 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3021 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3013 | `mocha test/*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3000 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2996 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2989 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2982 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2975 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2973 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2942 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2862 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2856 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2831 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2826 | `mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2821 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2820 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2816 | `istanbul cover _mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2802 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2800 | `mocha --opts mocha.opts` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2794 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [github-tools/github](https://github.com/github-tools/github) | 2791 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2773 | `npm run mocha && npm run lint` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2772 | `mocha --require should --reporter spec` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2752 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2726 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2721 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2720 | `mocha --require babel-register --recursive spec` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2703 | `mocha -R landing test/index` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2721 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2720 | `mocha --require babel-register --recursive spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2718 | `mocha test-node` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2703 | `mocha -R landing test/index` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2697 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2692 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2687 | `node_modules/.bin/mocha --reporter spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2637 | `mocha --timeout 100000` | 
| [mde/ejs](https://github.com/mde/ejs) | 2630 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2626 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2619 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2608 | `mocha-phantomjs ./test/index.html` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2605 | `mocha --recursive --watch` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2604 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2587 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [json5/json5](https://github.com/json5/json5) | 2576 | `nyc --reporter=html --reporter=text mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2570 | `nyc mocha --timeout=10000` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2558 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2587 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [json5/json5](https://github.com/json5/json5) | 2576 | `nyc --reporter=html --reporter=text mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2570 | `nyc mocha --timeout=10000` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2558 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2554 | `npm run build && cd test && mocha . --reporter dot` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2543 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2536 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2495 | `nyc mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2474 | `mocha "test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2474 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2466 | `mocha --reporter=spec test/*-test.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2447 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2344 | `nyc --reporter=html --reporter=text mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2344 | `grunt jshint && mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2341 | `mocha --no-colors --reporter spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2330 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2300 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2273 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2268 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2263 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2262 | `mocha test && npm run lint` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2230 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2225 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2223 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2216 | `mocha test/index.js --reporter dot` | 
| [gajus/swing](https://github.com/gajus/swing) | 2213 | `mocha --compilers js:babel-register` | 
| [noble/noble](https://github.com/noble/noble) | 2160 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2139 | `mocha --compilers js:babel-register` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2132 | `cross-env BABEL_ENV=test mocha` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2125 | `mocha test/ --no-timeouts` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2105 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2096 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1900 | `mocha --require ./test/common --growl test/expect.js` | 
| [then/promise](https://github.com/then/promise) | 1895 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1894 | `npm run lint && mocha -R dot && npm run cover` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1886 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1874 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1873 | `mocha tests.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 1863 | `npm run lint && npm run mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 1860 | `mocha test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1852 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1792 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1790 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1788 | `mocha -R spec spec spec/reporters` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1787 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1773 | `mocha test` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1773 | `mocha && npm run lint` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1772 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1767 | `mocha --reporter spec test/*.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1766 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1757 | `mocha tests --compilers js:babel-core/register` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1756 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1754 | `mocha --reporter spec --grep .` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1743 | `npm run lint && npm run mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1735 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1730 | `mocha test/**/*.js` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1725 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1696 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1683 | `npm run lint && mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1675 | `mocha test --timeout 600000` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1673 | `mocha ./test/basic.js -t 5000` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1673 | `xo && mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1667 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1664 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1661 | `mocha test/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1649 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1645 | `npm run lint && npm run mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1633 | `mocha test/* --reporter spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1629 | `mocha --expose-gc --slow 300` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1626 | `mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1625 | `mocha tests/test.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1622 | `mocha && size-limit` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1649 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1645 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1645 | `npm run lint && npm run mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1641 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1633 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1632 | `mocha spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1629 | `mocha --expose-gc --slow 300` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1626 | `mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1625 | `mocha tests/test.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1622 | `mocha && size-limit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1603 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1599 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1596 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1595 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1576 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1576 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1564 | `./node_modules/mocha/bin/mocha -R spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1546 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1539 | `npm run test:lint && npm run test:mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1537 | `mocha --reporter spec` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1537 | `eslint --cache . && tsc && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1536 | `mocha tests.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1529 | `standard "./src/*.js" && mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1518 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1507 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1507 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1499 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1499 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1496 | `mocha --check-leaks --reporter spec --bail` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1495 | `mocha -u tdd` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1493 | `mocha test` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1492 | `mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1490 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1486 | `node_modules/.bin/mocha --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1485 | `nyc mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1481 | `mocha -R spec` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1477 | `nyc npm run mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1463 | `mocha --recursive` | 
| [samccone/drool](https://github.com/samccone/drool) | 1452 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1448 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1481 | `mocha -R spec` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1477 | `nyc npm run mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1467 | `mocha test/**/*.spec.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1463 | `mocha --recursive` | 
| [samccone/drool](https://github.com/samccone/drool) | 1452 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1448 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1438 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1394 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1390 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1386 | `mocha -R spec test/*.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1381 | `istanbul cover _mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1374 | `./node_modules/mocha/bin/mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 1362 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1358 | `cross-env NODE_ENV=test nyc mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1353 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1353 | `mocha --check-leaks --require @babel/register` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1353 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [electron/devtron](https://github.com/electron/devtron) | 1336 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1334 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1333 | `mocha test/unit` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1320 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1319 | `mocha --opts test/opts/mocha.opts` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1318 | `mocha` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1314 | `mocha` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1314 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1314 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1313 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1312 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1310 | `./node_modules/.bin/mocha test` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1310 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1306 | `mocha-phantomjs tests/index.html` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1305 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1320 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1319 | `mocha --opts test/opts/mocha.opts` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1318 | `mocha` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1314 | `mocha` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1314 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1314 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1313 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1312 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1310 | `./node_modules/.bin/mocha test` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1310 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1306 | `mocha-phantomjs tests/index.html` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1305 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1304 | `mocha --recursive` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1300 | `eslint src && mocha && karma start --single-run` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1297 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1293 | `TEST=all mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1292 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1292 | `mocha spec/exec.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1282 | `mocha tests/test-*` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1279 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1278 | `mocha --reporter dot` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1270 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1263 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1261 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1261 | `mocha --timeout 60000 test/` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1251 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1251 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1245 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1244 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1243 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1242 | `mocha test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1239 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1239 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1238 | `mocha tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1236 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1227 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1219 | `NODE_ENV=test mocha tests/*.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1217 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1211 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1209 | `mocha src/test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1208 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1206 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1204 | `mocha -R spec ./test/unit/**` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1201 | `mocha ./test/test*.js --reporter spec` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1201 | `mocha --check-leaks --reporter spec --bail test/` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1200 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1198 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1198 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1196 | `node ./node_modules/mocha/bin/mocha tests` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1194 | `mocha test` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1188 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1186 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1186 | `mocha --recursive test/bin` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1176 | `npm run prepublishOnly && mocha test/test.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1174 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1171 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1168 | `mocha` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1166 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1165 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1163 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1163 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1162 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1161 | `mocha --recursive test` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1153 | `istanbul test _mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1150 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1153 | `istanbul test _mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1150 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1149 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1145 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1145 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1140 | `mocha --compilers js:babel-core/register` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1140 | `NODE_PATH=. mocha **/*.spec.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1135 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1122 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1107 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1107 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1106 | `istanbul cover _mocha test/*.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1103 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1103 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1103 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1099 | `mocha test/*` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1098 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1094 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1090 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1089 | `mocha --check-leaks -t 20000` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1085 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [router5/router5](https://github.com/router5/router5) | 1085 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1083 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1080 | `mocha` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1079 | `mocha --compilers js:babel-register` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1078 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [electron/asar](https://github.com/electron/asar) | 1056 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1055 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1055 | `npm run mocha:istanbul` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1049 | `mocha --recursive --bail --reporter spec test` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1047 | `webpack && mocha test/unit` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1038 | `mocha --reporter spec --timeout 3000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1032 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1031 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1028 | `mocha --reporter spec --bail --check-leaks test/` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1025 | `mocha --timeout 20000` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1025 | `standard && mocha -b` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1022 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1019 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1019 | `mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1017 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1042 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1039 | `mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1038 | `mocha --reporter spec --timeout 3000` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1037 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1032 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1031 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1028 | `mocha --reporter spec --bail --check-leaks test/` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1025 | `mocha --timeout 20000` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1025 | `standard && mocha -b` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1022 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1019 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1017 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [electron/spectron](https://github.com/electron/spectron) | 1012 | `mocha && standard` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1012 | `mocha --check-leaks -R dot` | 
| [tomas/needle](https://github.com/tomas/needle) | 1011 | `mocha test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1009 | `eslint src test && mocha --compilers babel-register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1008 | `mocha $(find test -name '*.test.js')` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 949 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 939 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit/**/*-test.js` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 931 | `mocha -R spec` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 931 | `mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 930 | `mocha test --compilers js:babel-core/register` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 929 | `mocha --compilers js:babel-register test/*.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 919 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 966 | `npm run lint && npm run flow && NODE_ENV=test nyc mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 966 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 965 | `mocha --reporter spec` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 963 | `npm run convertto:es5 && npm run mocha` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 949 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 941 | `mocha "client.test" --compilers js:babel-register` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 939 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit/**/*-test.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 941 | `mocha "client.test" --compilers js:babel-register` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 939 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit/**/*-test.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 934 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 931 | `mocha -R spec` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 931 | `mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 930 | `mocha test --compilers js:babel-core/register` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 929 | `mocha --compilers js:babel-register test/*.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 928 | `mocha --reporter spec --bail --check-leaks test/` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 925 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 919 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 918 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 919 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 918 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 917 | `npm run lint && mocha -R spec` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 915 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 912 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 911 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 908 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 907 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 905 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 902 | `mocha tests` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 900 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 891 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 891 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 889 | `mocha spec/*.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 885 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 883 | `mocha -t 600000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 879 | `node_modules/.bin/mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 879 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 876 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 868 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 864 | `nyc mocha specs` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 864 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 864 | `npm run lint && npm run mocha:no-functional` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 864 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 863 | `mocha --timeout 200000` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 861 | `mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 856 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 855 | `eslint test && mocha --compilers js:babel/register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 854 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 853 | `mocha -t 5000` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 852 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 849 | `./node_modules/.bin/mocha -R spec` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 849 | `mocha test --compilers js:babel-register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 848 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 849 | `./node_modules/.bin/mocha -R spec` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 849 | `mocha test --compilers js:babel-register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 848 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 846 | `standard && standard ./bin/* && mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 846 | `./node_modules/.bin/mocha --reporter spec` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 846 | `istanbul cover -- _mocha --reporter spec` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 843 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 842 | `mocha test` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 838 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 836 | `istanbul cover _mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 836 | `mocha --check-leaks -t 20000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 834 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 833 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 824 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 824 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 823 | `mocha --reporter list` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 821 | `mocha --reporter spec --bail --check-leaks test/` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 819 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 815 | `npm run lint && mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 814 | `nyc --check-coverage mocha test/*.test.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 812 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 812 | `mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 811 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 811 | `mocha --recursive ./test/*_spec.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 812 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 812 | `mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 811 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 811 | `mocha --recursive ./test/*_spec.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 807 | `mocha test/index.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 807 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 806 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 806 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 806 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 804 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 804 | `mocha --require babel-register` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 803 | `cake build && mocha ./test/mocha/*.coffee` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 803 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 800 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 799 | `mocha --async-only` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 798 | `mocha test` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 770 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 768 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [developit/decko](https://github.com/developit/decko) | 767 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 767 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 766 | `mocha --ui tdd --require ./test/__setup` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 763 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 763 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 756 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 753 | `mocha --recursive -s 15 test/` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 753 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 753 | `mocha test` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 752 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 751 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 751 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 777 | `mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 776 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 776 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 776 | `xo && mocha -R spec` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 776 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 775 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 772 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 771 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 770 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 768 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [developit/decko](https://github.com/developit/decko) | 767 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 767 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 766 | `mocha --ui tdd --require ./test/__setup` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 763 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 763 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 740 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 738 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 736 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 735 | `mocha -r should --reporter spec test/*.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 735 | `mocha test` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 735 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 735 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 732 | `npm run lint && npm run mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 732 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 730 | `mocha tests/*.mocha.js` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 730 | `mocha test.js` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 729 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 743 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 740 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 738 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 736 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 735 | `mocha -r should --reporter spec test/*.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 735 | `mocha test` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 735 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 735 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 732 | `npm run lint && npm run mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 732 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 730 | `mocha tests/*.mocha.js` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 730 | `mocha test.js` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 729 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 726 | `mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 725 | `mocha` | 
| [scality/S3](https://github.com/scality/S3) | 724 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 723 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 723 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 722 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 722 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 721 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 721 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 719 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 718 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 717 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 717 | `babel-node node_modules/.bin/_mocha -- test` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 716 | `npm run bundle && mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 715 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 