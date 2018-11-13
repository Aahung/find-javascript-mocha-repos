# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:38 11/13/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44219 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41649 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40993 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30553 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 25000 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 24873 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24154 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20641 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19591 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17835 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17435 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17331 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16107 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14506 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14455 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14449 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13598 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13222 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12861 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12570 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12416 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12293 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11952 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11855 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11825 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11065 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10711 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10536 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10465 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10435 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10258 | `mocha --harmony` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10257 | `mocha` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10238 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [websockets/ws](https://github.com/websockets/ws) | 9924 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9765 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 9661 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9554 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9440 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9326 | `mocha -b -r esm` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9227 | `mocha tests/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9164 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 9069 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9034 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8711 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8599 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8505 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8385 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8338 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8300 | `mocha --compilers js:babel-register test/test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8183 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8159 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7970 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7860 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7587 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7584 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7575 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7570 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [aui/art-template](https://github.com/aui/art-template) | 7568 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [dthree/cash](https://github.com/dthree/cash) | 7567 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7512 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7446 | `mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6418 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6352 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6315 | `npm run test:mocha:src` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6126 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6105 | `mocha tests/node.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6103 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6062 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6022 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5967 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5918 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5917 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5805 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5683 | `standard && mocha` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6022 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5967 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5938 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5918 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5917 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5805 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5683 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5576 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5557 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5412 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5392 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5368 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5576 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5557 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5412 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5392 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5368 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5294 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5220 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5185 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5143 | `mocha --color` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5079 | `mocha test` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5070 | `gulp lint && mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4961 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4893 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4862 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4817 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4799 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4790 | `mocha -R spec 'tests/app'` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4785 | `mocha --recursive` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4752 | `./node_modules/.bin/mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4719 | `mocha --reporter spec -t 8000` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4703 | `nyc mocha --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4672 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4660 | `npm run lint && npm run mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4590 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4572 | `mocha ./test/runner.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 4561 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4557 | `nyc mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4490 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4467 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4374 | `mocha -R spec src` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4373 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4349 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4338 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4253 | `mocha --timeout=15000 tests/*.test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4230 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4230 | `node_modules/.bin/mocha test/tests.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4210 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4203 | `mocha -R spec ./test --recursive` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4161 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4130 | `npm run lint ; mocha && mocha test/individual` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4114 | `mocha --check-leaks --reporter spec --bail` | 
| [muicss/mui](https://github.com/muicss/mui) | 4083 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4082 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4041 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4005 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3972 | `NODE_ENV=test mocha --exit` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3912 | `export TESTING=true; mocha --reporter list` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3904 | `nyc mocha "test/**/*.test.js"` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3868 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [expressjs/session](https://github.com/expressjs/session) | 3817 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [erming/shout](https://github.com/erming/shout) | 3793 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3787 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3728 | `npm run build && mocha test/*.test.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3715 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3700 | `NODE_ENV=test mocha test/**/*.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3684 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3666 | `npm run jshint && npm run mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3647 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3605 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3604 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3600 | `node_modules/.bin/mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3591 | `mocha tests/javascript` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3569 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3552 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3516 | `mocha test/* --reporter spec` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3486 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3477 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3447 | `mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3436 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3397 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3379 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3321 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3321 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3248 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3239 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3234 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3229 | `mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3223 | `eslint . && mocha -t 5000` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3222 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3221 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3198 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3192 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3181 | `mocha test/index.js && npm run demo` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3179 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3177 | `mocha test/*.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3161 | `./node_modules/.bin/mocha test/test.*.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3156 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3149 | `mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3139 | `mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3136 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2951 | `npm run mocha && npm run lint` | 
| [mde/ejs](https://github.com/mde/ejs) | 2946 | `mocha --require should --reporter spec` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2939 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2937 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2925 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2918 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2892 | `mocha test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2889 | `node_modules/.bin/mocha --reporter spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2867 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2867 | `mocha --require babel-register --recursive spec` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2867 | `mocha` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2859 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2856 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [github-tools/github](https://github.com/github-tools/github) | 2848 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2846 | `mocha -R spec spec spec/reporters` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2829 | `istanbul cover _mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2867 | `mocha --require babel-register --recursive spec` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2867 | `mocha` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2859 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2856 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [github-tools/github](https://github.com/github-tools/github) | 2848 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2846 | `mocha -R spec spec spec/reporters` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2829 | `istanbul cover _mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2794 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2779 | `mocha --require should --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2778 | `mocha --reporter dot` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2766 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2744 | `xo && mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2740 | `npm run build && cd test && mocha . --reporter dot` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2726 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2720 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2779 | `mocha --require should --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2778 | `mocha --reporter dot` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2766 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2744 | `xo && mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2740 | `npm run build && cd test && mocha . --reporter dot` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2726 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2720 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2703 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2667 | `mocha --timeout 100000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2666 | `mocha --recursive --watch` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2659 | `mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2659 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2657 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2638 | `nyc mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2636 | `mocha "test/**/*-test.js"` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2622 | `mocha-phantomjs ./test/index.html` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2106 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [pahen/madge](https://github.com/pahen/madge) | 2098 | `npm run lint && npm run mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2095 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2068 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2060 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2048 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [share/sharedb](https://github.com/share/sharedb) | 2040 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2017 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2002 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [slate/slate](https://github.com/slate/slate) | 1996 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1985 | `mocha test/*.test.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1984 | `mocha --require=test/test_helper.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1944 | `mocha --require ./test/common --growl test/expect.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2291 | `npm run build && mocha --require babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2289 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2288 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [gajus/swing](https://github.com/gajus/swing) | 2267 | `mocha --compilers js:babel-register` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2260 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2226 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2223 | `mocha test test/unit/**/*_test.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2204 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2130 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2129 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2128 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2127 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2111 | `mocha && eslint *.js` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2106 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2068 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2060 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2048 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [share/sharedb](https://github.com/share/sharedb) | 2040 | `./node_modules/.bin/mocha && npm run jshint` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2011 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2004 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2002 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [slate/slate](https://github.com/slate/slate) | 1996 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1987 | `mocha --reporter spec --timeout 5000` | 
| [kach/nearley](https://github.com/kach/nearley) | 1985 | `mocha test/*.test.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1984 | `mocha --require=test/test_helper.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1973 | `npm run lint && mocha -R dot && npm run cover` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1970 | `mocha --compilers js:babel-register` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1965 | `npm run mocha && npm run karma` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [then/promise](https://github.com/then/promise) | 1958 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1945 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1944 | `mocha --require ./test/common --growl test/expect.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1938 | `mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1937 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1936 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1927 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1916 | `mocha && npm run lint` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1898 | `mocha --reporter spec && npm run test-typescript` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1895 | `mocha tests --require @babel/register` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1894 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1880 | `mocha --reporter spec test/*.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1877 | `mocha tests.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1864 | `mocha test/**/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1860 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1852 | `mocha test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1846 | `mocha --reporter spec --grep .` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1845 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1846 | `mocha --reporter spec --grep .` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1845 | `mocha` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1839 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1832 | `mocha test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1831 | `mocha test -u bdd -R spec` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1818 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1811 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1809 | `npm run lint && npm run mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1801 | `mocha --timeout 5000` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1795 | `mocha ./test/basic.js -t 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1781 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1778 | `mocha compiled_tests/` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1750 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1747 | `npm run lint && npm run mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1735 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1727 | `mocha test/**/*_test.js --bail` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1726 | `./node_modules/.bin/mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1725 | `npm run lint && mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1721 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1717 | `mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1714 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1713 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1712 | `mocha test/setup.js test/spec/*.js` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1710 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1709 | `mocha test/*.js` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1708 | `mocha test --timeout 600000` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1693 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1687 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1682 | `eslint --cache . && tsc && mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1682 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1673 | `mocha tests.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1664 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1662 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1661 | `mocha && size-limit` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1656 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1655 | `mocha spec` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1640 | `standard "./src/*.js" && mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1638 | `mocha --expose-gc --slow 300` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1636 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1636 | `mocha tests/test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1636 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1636 | `mocha tests/test.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1628 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1623 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1622 | `TEST=all mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1617 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1615 | `mocha --check-leaks --reporter spec --bail` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1611 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1609 | `mocha` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1604 | `mocha test/test-*.js` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1598 | `mocha --reporter spec` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1593 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1589 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1587 | `./node_modules/mocha/bin/mocha -R spec` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1577 | `mocha test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1576 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1549 | `nyc mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1549 | `mocha --recursive` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1548 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1546 | `npm run test:lint && npm run test:mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1533 | `node_modules/.bin/mocha --recursive` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1431 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1431 | `npm run lint && mocha && karma start --single-run` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1428 | `mocha tests/test-*` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1426 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1409 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1408 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1408 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1407 | `standard && istanbul cover _mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1403 | `mocha --opts test/opts/mocha.opts` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1401 | `npm run build && mocha -r should` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1400 | `istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1393 | `mocha --reporter dot` | 
| [electron/devtron](https://github.com/electron/devtron) | 1385 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1372 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1369 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1215 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1214 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [router5/router5](https://github.com/router5/router5) | 1204 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1197 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1187 | `mocha --timeout 30000 --recursive ./tests` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1178 | `mocha --timeout 20000` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1163 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1160 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 1158 | `mocha` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1154 | `mocha --recursive` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1285 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1279 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1274 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1274 | `mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1270 | `mocha --compilers js:babel-core/register` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1269 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1265 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1260 | `webpack && npm run lint && npm run mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1259 | `npm run lint && npm run mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1258 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1257 | `mocha tests` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1253 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1248 | `istanbul test _mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1238 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1236 | `npm run lint && mocha --require @babel/register` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1235 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1232 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [variety/variety](https://github.com/variety/variety) | 1231 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1228 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [normalize/mz](https://github.com/normalize/mz) | 1222 | `mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1220 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1215 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1214 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1178 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1177 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1187 | `mocha --timeout 30000 --recursive ./tests` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1182 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1178 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1177 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1163 | `mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1161 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1160 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 1158 | `mocha` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1154 | `mocha --recursive` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1154 | `mocha --recursive` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1151 | `mocha $(find test -name '*.test.js') --exit` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1150 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1144 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1143 | `istanbul cover _mocha test/*.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1143 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1141 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1137 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1137 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1133 | `mocha --reporter spec --bail --check-leaks test/` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1128 | `npm-run-all test:jest test:server:mocha` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1124 | `mocha --recursive -r tests/setup tests` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1123 | `mocha test/*` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1120 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1120 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1100 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1099 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1097 | `mocha && standard` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1093 | `mocha --check-leaks -t 20000` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1088 | `standard && mocha -b` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1083 | `mocha --recursive --bail --reporter spec test` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1078 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1075 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1073 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1071 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1071 | `mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1069 | `mocha test/tests.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1069 | `mocha test/tests.js` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1068 | `eslint src test && mocha --compilers babel-register` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1060 | `mocha --reporter spec test --recursive` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1058 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1056 | `npm run convertto:es5 && npm run mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 1049 | `mocha test` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1047 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1043 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1038 | `mocha --async-only` | 
| [tomas/needle](https://github.com/tomas/needle) | 1049 | `mocha test` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1047 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1043 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1038 | `mocha --async-only` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1036 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1034 | `mocha --reporter spec --timeout 3000` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1033 | `mocha $(find test -name '*.test.js')` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1031 | `mocha test` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1025 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1022 | `mocha --recursive test/unit/` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1020 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1012 | `mocha --colors ./test/*.spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1009 | `mocha --check-leaks -R dot` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1004 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 995 | `mocha -R list` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 995 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 991 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 989 | `mocha --reporter spec --bail --check-leaks test/` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 988 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 987 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 943 | `mocha --timeout 5000` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 942 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 941 | `mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 935 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 934 | `mocha -t 600000` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 932 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 931 | `./node_modules/.bin/mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 927 | `./node_modules/.bin/mocha -R spec` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 920 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 919 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 918 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 918 | `nyc mocha specs` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 919 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 918 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 916 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 915 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 914 | `mocha test --compilers js:babel-register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 914 | `mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 912 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 911 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 907 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 906 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 934 | `mocha -t 600000` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 932 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 932 | `mocha --recursive ./test/*_spec.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 931 | `./node_modules/.bin/mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 927 | `./node_modules/.bin/mocha -R spec` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 925 | `mocha test` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 920 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 919 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 918 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 918 | `nyc mocha specs` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 918 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 918 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 916 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 915 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 914 | `mocha test --compilers js:babel-register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 914 | `mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 912 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 911 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 907 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 906 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 892 | `node_modules/.bin/mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 892 | `mocha -t 5000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 884 | `./node_modules/.bin/mocha --globals angular,require` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 892 | `node_modules/.bin/mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 892 | `mocha -t 5000` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 889 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 887 | `npm run lint && npm run mocha:no-functional` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 884 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 878 | `mocha --timeout 200000` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 877 | `mocha test/index.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 870 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 856 | `mocha --reporter spec` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 856 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 856 | `mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 855 | `istanbul cover _mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 848 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 846 | `./node_modules/.bin/mocha test/**/*` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 845 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 844 | `npm run lint && mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 844 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 842 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 840 | `npm run build && istanbul test _mocha test/test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 840 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 840 | `npm run lint && npm run mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 839 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 835 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 831 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 830 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 830 | `mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 830 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 846 | `./node_modules/.bin/mocha test/**/*` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 845 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 844 | `npm run lint && mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 844 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 842 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 840 | `npm run build && istanbul test _mocha test/test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 840 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 840 | `npm run lint && npm run mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 839 | `mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 838 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 835 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 831 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 830 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 830 | `mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 830 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 829 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 829 | `mocha --opts mocha.opts` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 823 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 823 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 820 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 818 | `mocha -r should --reporter spec test/*.js` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 818 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 817 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 815 | `mocha` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 813 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 811 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 811 | `mocha test` | 
| [edsu/anon](https://github.com/edsu/anon) | 810 | `mocha --colors --reporter spec test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 810 | `cake build && mocha ./test/mocha/*.coffee` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 808 | `npm run mocha-test test/integration` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 801 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 796 | `mocha -R spec tests/` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 794 | `nyc mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 794 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 792 | `xo && mocha -R spec` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 791 | `mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 786 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 706 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 705 | `mocha --compilers js:babel-core/register` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 704 | `mocha --reporter spec --bail --check-leaks test/` | 
| [fossasia/labyrinth](https://github.com/fossasia/labyrinth) | 702 | `./node_modules/.bin/mocha` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 698 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 696 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 688 | `mocha` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 687 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 685 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 727 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 726 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 726 | `mocha` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 709 | `_mocha` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 666 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 666 | `mocha` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 665 | `mocha` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 664 | `mocha --require babel-register src/**/*.spec.js src/*.spec.js` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 662 | `_mocha -u bdd --colors test/` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 662 | `mocha --recursive --compilers js:babel-core/register` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 661 | `mocha --require babel-register` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 660 | `mocha` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 658 | `mocha --reporter spec` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 656 | `mocha` | 
| [shime/livedown](https://github.com/shime/livedown) | 655 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 650 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [coinbase/gdax-node](https://github.com/coinbase/gdax-node) | 648 | `mocha --full-trace --ui tdd --bail --reporter spec tests/*.js` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 736 | `npm run bundle && mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 735 | `mocha` | 
| [koajs/static](https://github.com/koajs/static) | 734 | `mocha --harmony --reporter spec --exit` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 734 | `mocha --reporter spec` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 733 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 731 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 730 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 730 | `mocha` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 730 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 729 | `mocha` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 727 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 727 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 726 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 726 | `mocha` | 