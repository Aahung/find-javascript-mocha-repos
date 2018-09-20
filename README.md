# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:13 09/20/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43599 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41344 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40242 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30315 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 26608 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24642 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 24557 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19210 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17364 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17364 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16999 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16941 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15466 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14392 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14156 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13825 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13338 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12947 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12731 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12427 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12250 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12117 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11651 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11461 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11408 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10673 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10359 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10295 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10207 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10128 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10084 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9076 | `grunt mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8883 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 8875 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8837 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8681 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8580 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8550 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8463 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8357 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8236 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8225 | `mocha --compilers js:babel-register test/test.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8052 | `mocha --opts mocha.opts` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7940 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7772 | `./node_modules/.bin/mocha test` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8236 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8225 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8106 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8052 | `mocha --opts mocha.opts` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7940 | `npm run eslint && npm run mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7808 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7772 | `./node_modules/.bin/mocha test` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7467 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7442 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7383 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7361 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7358 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7209 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7175 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5627 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5455 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5444 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5437 | `standard && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5421 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5199 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5183 | `mocha src/**/*Tests.js --harmony` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5171 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5147 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5147 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5105 | `mocha` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6266 | `npm run test:mocha:src` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6052 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6045 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5998 | `mocha tests/node.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5940 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5929 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5876 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5783 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5768 | `mocha && eslint lib/**` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5762 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5761 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5627 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5455 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5444 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5437 | `standard && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5421 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5199 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5183 | `mocha src/**/*Tests.js --harmony` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5171 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5147 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5147 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5105 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5008 | `gulp lint && mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4874 | `mocha test` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4867 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4807 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4779 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4771 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4753 | `mocha -R spec 'tests/app'` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4736 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4703 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4677 | `./node_modules/.bin/mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4578 | `mocha ./test/runner.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4562 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4535 | `npm run lint && npm run mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4521 | `mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4509 | `nyc mocha --exit` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4455 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4449 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4349 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4346 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4231 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4229 | `mocha -R spec src` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4170 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4127 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4111 | `mocha --timeout=15000 tests/*.test.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4100 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4062 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4059 | `npm run lint ; mocha && mocha test/individual` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4052 | `mocha --require test/babel-hook test/*.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4052 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 4012 | `mocha --require should --reporter spec` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4009 | `nyc --require ./test/helpers/register _mocha -- test/tests/index.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 3995 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3987 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3946 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3936 | `mocha --check-leaks --reporter spec --bail` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3904 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3876 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [erming/shout](https://github.com/erming/shout) | 3803 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3773 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3770 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3699 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3691 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [primus/primus](https://github.com/primus/primus) | 3689 | `npm run build && mocha test/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3680 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3671 | `npm run jshint && npm run mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3616 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3612 | `NODE_ENV=test mocha --exit` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3585 | `mocha tests/javascript` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3582 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3571 | `node_modules/.bin/mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3561 | `NODE_ENV=test mocha test/**/*.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3554 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3552 | `mocha --reporter spec --timeout 3000` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3535 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3469 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3452 | `mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3438 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3341 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3323 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3303 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3267 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3258 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3267 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3258 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3235 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3189 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3168 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3154 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3154 | `./node_modules/.bin/mocha test/test.*.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3137 | `mocha test/*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3135 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3116 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3111 | `mocha test/index.js && npm run demo` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3107 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3107 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3098 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3081 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3077 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3056 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2922 | `eslint . && mocha -t 5000` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2921 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2912 | `mocha -R spec --recursive src/test` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2909 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2879 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2869 | `npm run mocha && npm run lint` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2844 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2831 | `istanbul cover _mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2829 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2821 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2820 | `mocha -R spec spec spec/reporters` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2814 | `mocha test-node` | 
| [mde/ejs](https://github.com/mde/ejs) | 2809 | `mocha --require should --reporter spec` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2801 | `mocha --require babel-register --recursive spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2795 | `node_modules/.bin/mocha --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2778 | `mocha --require should --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2844 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2831 | `istanbul cover _mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2829 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2821 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2820 | `mocha -R spec spec spec/reporters` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2814 | `mocha test-node` | 
| [mde/ejs](https://github.com/mde/ejs) | 2809 | `mocha --require should --reporter spec` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2801 | `mocha --require babel-register --recursive spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2795 | `node_modules/.bin/mocha --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2778 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2763 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2740 | `mocha test.js` | 
| [css/csso](https://github.com/css/csso) | 2736 | `mocha --reporter dot` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2730 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2728 | `xo && mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2528 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2500 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2497 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2493 | `mocha --reporter=spec test/*-test.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2490 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2479 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2476 | `mocha test/src/**/*.unit.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2472 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2467 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2453 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2418 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2417 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2401 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2375 | `mocha test/ --no-timeouts` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2372 | `node node_modules/mocha/bin/_mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2528 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2500 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2497 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2493 | `mocha --reporter=spec test/*-test.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2490 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2479 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2476 | `mocha test/src/**/*.unit.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2472 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2467 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2453 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2418 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2417 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2401 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2317 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2292 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2283 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2256 | `mocha -R spec test/*.js` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2238 | `mocha test test/unit/**/*_test.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2236 | `mocha --compilers js:babel-register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2229 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2224 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2205 | `mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2118 | `mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2118 | `nyc npm run _mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2101 | `mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2092 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2075 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2056 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2054 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2045 | `mocha && eslint *.js` | 
| [zeeshanu/dumper.js](https://github.com/zeeshanu/dumper.js) | 2034 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2008 | `mocha --compilers js:babel-core/register __tests__` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2008 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2005 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [slate/slate](https://github.com/slate/slate) | 2005 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2004 | `npm run lint && npm run mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1997 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1995 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1978 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1972 | `mocha --require=test/test_helper.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1971 | `mocha -c test/index.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1970 | `mocha --reporter spec --timeout 5000` | 
| [share/sharedb](https://github.com/share/sharedb) | 1970 | `./node_modules/.bin/mocha && npm run jshint` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1962 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1949 | `npm run lint && mocha -R dot && npm run cover` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1945 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1944 | `mocha --bail --reporter spec --check-leaks test/` | 
| [then/promise](https://github.com/then/promise) | 1940 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1932 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1930 | `mocha --require ./test/common --growl test/expect.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1927 | `mocha test/*.test.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1916 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1914 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1886 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1882 | `npm run mocha && npm run karma` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1878 | `mocha tests.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1865 | `mocha --compilers js:babel-register` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1860 | `mocha --reporter spec && npm run test-typescript` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1859 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1853 | `mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1846 | `mocha && npm run lint` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1841 | `mocha --reporter spec test/*.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1832 | `mocha tests --require @babel/register` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1824 | `mocha test` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1823 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1818 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1816 | `npm run lint && mocha --reporter spec test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1811 | `mocha --reporter spec --grep .` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1810 | `mocha test/**/*.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1810 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1807 | `mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1806 | `mocha --timeout 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1787 | `npm run lint && npm run mocha` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1784 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1754 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1742 | `mocha ./test/basic.js -t 5000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1738 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1735 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1735 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1730 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1719 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1716 | `mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1708 | `npm run lint && mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1707 | `mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1705 | `npm run lint && npm run mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1702 | `mocha test --timeout 600000` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1693 | `mocha test` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1689 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1688 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1663 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1656 | `mocha test/setup.js test/spec/*.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1646 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1641 | `mocha && size-limit` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1638 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1636 | `mocha tests/test.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1614 | `eslint --cache . && tsc && mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1612 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1609 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1606 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1600 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1614 | `mocha tests.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1614 | `eslint --cache . && tsc && mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1612 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1609 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1606 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1605 | `standard "./src/*.js" && mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1600 | `mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1598 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1583 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1576 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1576 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1574 | `mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1567 | `mocha --reporter spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1560 | `./node_modules/.bin/mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1583 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1576 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1576 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1574 | `mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1567 | `mocha --reporter spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1560 | `./node_modules/.bin/mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1556 | `mocha --check-leaks --reporter spec --bail` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1556 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1555 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [retejs/rete](https://github.com/retejs/rete) | 1554 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1547 | `npm run test:lint && npm run test:mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1542 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1540 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1536 | `node_modules/.bin/mocha --recursive` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1530 | `nyc mocha --timeout=20000 test.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1488 | `mocha test/**/*.spec.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1478 | `TEST=all mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1451 | `mocha test.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1446 | `mocha --timeout 10000 ./tests/lib.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1473 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1451 | `mocha test.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1446 | `mocha --timeout 10000 ./tests/lib.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1442 | `mocha --check-leaks --require @babel/register` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1440 | `mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1431 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1430 | `mocha -R spec test/*.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1425 | `mocha test/unit` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1423 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1416 | `mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1410 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1407 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1407 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1403 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1401 | `NODE_ENV=test mocha tests/*.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1400 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1398 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1397 | `npm run lint && mocha && karma start --single-run` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1393 | `istanbul cover _mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1389 | `./node_modules/mocha/bin/mocha` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1387 | `mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1385 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1380 | `npm run build && mocha -r should` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1372 | `mocha tests/test-*` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1370 | `mocha --opts test/opts/mocha.opts` | 
| [electron/devtron](https://github.com/electron/devtron) | 1369 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1363 | `cross-env NODE_ENV=test nyc mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1362 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1350 | `istanbul cover _mocha test -- --timeout 20000` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1350 | `standard && istanbul cover _mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1348 | `mocha -R spec ./test/unit/**` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1347 | `mocha --reporter dot` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1346 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1342 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1339 | `mocha --recursive` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1337 | `mocha ./test/test*.js --reporter spec` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1335 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1329 | `./node_modules/.bin/mocha test` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1312 | `npm run lint && npm run mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1305 | `mocha-phantomjs tests/index.html` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1303 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1303 | `mocha spec/exec.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1298 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1296 | `mocha` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1293 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1287 | `mocha --timeout 60000 test/` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1284 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1280 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1279 | `mocha --recursive test/bin` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1275 | `mocha --check-leaks --reporter spec --bail test/` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1272 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1268 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1267 | `mocha test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1268 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1267 | `npm run prepublishOnly && mocha test/test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1267 | `mocha test/*.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1263 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1262 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1260 | `mocha tests` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1255 | `mocha --recursive test` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1250 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1247 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1244 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1242 | `mocha src/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1237 | `npm run lint && npm run mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1236 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1235 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1235 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1232 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1236 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1235 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1235 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1232 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1226 | `istanbul test _mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1218 | `mocha --compilers js:babel-core/register` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1218 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1217 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1216 | `mocha --reporter spec` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1215 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1213 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1212 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1209 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1208 | `node ./node_modules/mocha/bin/mocha tests` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1204 | `mocha test` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1203 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1202 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1201 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1198 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1198 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1193 | `webpack && npm run lint && npm run mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1185 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1181 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1174 | `npm run lint && mocha --require @babel/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1171 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1164 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1161 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1160 | `npm run mocha:istanbul` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1155 | `mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1155 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1154 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1140 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1137 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1134 | `istanbul cover _mocha test/*.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1132 | `mocha --timeout 20000` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1130 | `xo && mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1129 | `mocha $(find test -name '*.test.js') --exit` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1129 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1091 | `webpack && mocha test/unit` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1086 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1084 | `mocha --compilers js:babel-register` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1083 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1083 | `mocha --reporter spec --bail --check-leaks test/` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1080 | `mocha --timeout 30000 --recursive ./tests` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1075 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1074 | `mocha --recursive --bail --reporter spec test` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1074 | `mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1067 | `standard && mocha -b` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1066 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1064 | `mocha test --compilers js:babel-core/register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1064 | `mocha test/tests.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1061 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1084 | `mocha --compilers js:babel-register` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1083 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1083 | `mocha --reporter spec --bail --check-leaks test/` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1080 | `mocha --timeout 30000 --recursive ./tests` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1076 | `mocha --reporter spec --bail --check-leaks test/` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1075 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1074 | `mocha --recursive --bail --reporter spec test` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1074 | `mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1067 | `standard && mocha -b` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1066 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1064 | `mocha test --compilers js:babel-core/register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1064 | `mocha test/tests.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1061 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1054 | `mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1029 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1029 | `mocha $(find test -name '*.test.js')` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1025 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1019 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1018 | `mocha --async-only` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1018 | `npm run convertto:es5 && npm run mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1015 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1014 | `mocha --check-leaks -R dot` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1013 | `mocha --recursive test/unit/` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1008 | `mocha --recursive -r tests/setup tests` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1005 | `mocha --colors ./test/*.spec.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1015 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1014 | `mocha --check-leaks -R dot` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1013 | `mocha --recursive test/unit/` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1008 | `mocha --recursive -r tests/setup tests` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1005 | `mocha --colors ./test/*.spec.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 994 | `mocha -R list` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 994 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 991 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 990 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 981 | `npm run rollup-cjs && mocha test/test.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 981 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 980 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 975 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 975 | `mocha --reporter spec` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 970 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 964 | `mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 963 | `mocha --reporter spec --bail --check-leaks test/` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 963 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 956 | `mocha --compilers js:babel-register test/*.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 946 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 943 | `mocha --timeout 5000` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 941 | `mocha test` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 931 | `mocha spec/*.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 927 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 924 | `mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 928 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 927 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 924 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 919 | `mocha test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 916 | `mocha ./test/index.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 915 | `mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 912 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 911 | `mocha -t 600000` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 904 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 903 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 903 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 903 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 900 | `./node_modules/.bin/mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 899 | `./node_modules/.bin/mocha -R spec` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 897 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 897 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 895 | `nyc mocha specs` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 893 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 893 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 892 | `mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 892 | `nyc --check-coverage mocha test/*.test.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 890 | `node_modules/.bin/mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 889 | `./node_modules/.bin/mocha --globals angular,require` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 889 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 888 | `mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 883 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 882 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 880 | `mocha --recursive ./test/*_spec.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 880 | `istanbul cover -- _mocha --reporter spec` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 876 | `npm run lint && npm run mocha:no-functional` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 876 | `mocha test --compilers js:babel-register` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 876 | `mocha --reporter list` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 876 | `standard && standard ./bin/* && mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 875 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 873 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 873 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 873 | `mocha -t 5000` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 872 | `mocha --timeout 200000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 869 | `node_modules/.bin/mocha test/spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 868 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 867 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 860 | `mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 858 | `eslint test && mocha --compilers js:babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 852 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 851 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 850 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 850 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 848 | `mocha --reporter spec` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 846 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 845 | `mocha --check-leaks -t 20000` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 843 | `mocha test/index.js` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 843 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 841 | `npm run lint && mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 841 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 839 | `mocha --reporter spec --bail --check-leaks test/` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 839 | `mocha test` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 838 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 838 | `mocha --exit --use_strict src/*.test.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 837 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 836 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 829 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 825 | `mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 825 | `mocha && ember test` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 824 | `mocha` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 824 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 823 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 821 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 821 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 783 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 782 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 782 | `xo && mocha -R spec` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 777 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 776 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 775 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 770 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 767 | `mocha --ui tdd --require ./test/__setup` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 765 | `mocha --recursive -s 15 test/` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 765 | `mocha --opts mocha.opts` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 764 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 764 | `mocha -R spec src/**/*_test.js` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 806 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 803 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 802 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 801 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 799 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 798 | `mocha -u tdd` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 798 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 797 | `npm run mocha-test test/integration` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 797 | `mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 796 | `mocha -R spec tests/` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 796 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [edsu/anon](https://github.com/edsu/anon) | 795 | `mocha --colors --reporter spec test.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 794 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 790 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 787 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 786 | `mocha -r should --reporter spec test/*.js` | 
| [developit/decko](https://github.com/developit/decko) | 785 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 783 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 782 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 782 | `xo && mocha -R spec` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 781 | `mocha test` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 779 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 777 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 776 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 775 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 770 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 