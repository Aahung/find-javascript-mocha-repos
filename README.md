# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:08 10/17/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43905 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41511 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40599 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30450 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 24742 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 24734 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23892 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20372 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19407 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17595 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17206 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17125 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15785 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14436 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14308 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14129 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13472 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13115 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12769 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12507 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12270 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12263 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11790 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11668 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11621 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10859 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10527 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10405 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10381 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10209 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [tj/co](https://github.com/tj/co) | 10191 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10155 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [websockets/ws](https://github.com/websockets/ws) | 9751 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9551 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9491 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 9362 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9343 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9280 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9113 | `grunt mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9038 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 8964 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8946 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8647 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8575 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8485 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8379 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8311 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8264 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8129 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7972 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7955 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7802 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7562 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7486 | `npm run build && istanbul cover _mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7481 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7479 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [aui/art-template](https://github.com/aui/art-template) | 7457 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7444 | `mocha` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7408 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7364 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [almende/vis](https://github.com/almende/vis) | 7202 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7154 | `xo && mocha test/*.js --timeout 100000` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7030 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6994 | `mocha $HARMONY_OPTS` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6920 | `mocha; jshint *.js lib` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6855 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6761 | `mocha --exit --require @babel/register` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6753 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6620 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6427 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6373 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6295 | `npm run test:mocha:src` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6170 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6081 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6057 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6043 | `mocha tests/node.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5914 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5859 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5850 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5841 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5839 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5786 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5566 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5539 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5514 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5416 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5329 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5273 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5194 | `mocha src/**/*Tests.js --harmony` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5189 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5186 | `mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5154 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5052 | `gulp lint && mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4977 | `mocha test` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4879 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4837 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4821 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4802 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4775 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4772 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4707 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4701 | `./node_modules/.bin/mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4675 | `mocha --recursive` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4631 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4600 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4593 | `nyc mocha --exit` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4569 | `mocha ./test/runner.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4475 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4461 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4458 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4454 | `nyc mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4346 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4310 | `mocha -R spec src` | 
| [teambit/bit](https://github.com/teambit/bit) | 4242 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4230 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4207 | `node_modules/.bin/mocha test/tests.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4205 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4198 | `nyc mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4175 | `mocha --timeout=15000 tests/*.test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4165 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4120 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4101 | `npm run lint ; mocha && mocha test/individual` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4091 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4063 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4027 | `mocha --require should --reporter spec` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4017 | `mocha --check-leaks --reporter spec --bail` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3961 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3906 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3869 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3834 | `nyc mocha "test/**/*.test.js"` | 
| [erming/shout](https://github.com/erming/shout) | 3795 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3782 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3780 | `NODE_ENV=test mocha --exit` | 
| [expressjs/session](https://github.com/expressjs/session) | 3751 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3749 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [primus/primus](https://github.com/primus/primus) | 3703 | `npm run build && mocha test/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3678 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3667 | `npm run jshint && npm run mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3654 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3618 | `NODE_ENV=test mocha test/**/*.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3607 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3584 | `mocha tests/javascript` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3581 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3577 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3575 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3558 | `mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3554 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3535 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3470 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3460 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3444 | `mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3403 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3383 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3328 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3284 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3265 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3284 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3265 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3207 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3189 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3181 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3172 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3167 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3164 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3163 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3159 | `mocha test/*.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3156 | `./node_modules/.bin/mocha test/test.*.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3154 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3142 | `mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3138 | `mocha test/index.js && npm run demo` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3119 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3102 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3097 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3079 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3076 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3074 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3065 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3054 | `eslint . && mocha -t 5000` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3035 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3006 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3005 | `mocha -R landing test/index` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2997 | `mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2967 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2940 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2923 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2909 | `npm run mocha && npm run lint` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2908 | `mocha -R spec --recursive src/test` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2900 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2895 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2884 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 2875 | `mocha --require should --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2863 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2838 | `mocha --require babel-register --recursive spec` | 
| [github-tools/github](https://github.com/github-tools/github) | 2837 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2836 | `mocha test-node` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2832 | `mocha -R spec spec spec/reporters` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2831 | `istanbul cover _mocha` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2830 | `node_modules/.bin/mocha --reporter spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2828 | `mocha` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2816 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2814 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2805 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2789 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2772 | `mocha --require should --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2756 | `mocha --reporter dot` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2746 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2731 | `xo && mocha` | 
| [tj/should.js](https://github.com/tj/should.js) | 2717 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2715 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2703 | `npm run build && cd test && mocha . --reporter dot` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2689 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2689 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2679 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2659 | `mocha --timeout 100000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2651 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2633 | `nyc mocha --timeout=10000` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2625 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2619 | `mocha-phantomjs ./test/index.html` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2603 | `nyc mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2578 | `mocha "test/**/*-test.js"` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2575 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2306 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [retejs/rete](https://github.com/retejs/rete) | 2303 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [noble/noble](https://github.com/noble/noble) | 2297 | `mocha -R spec test/*.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 2292 | `mocha` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2286 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2285 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2251 | `mocha --compilers js:babel-register` | 
| [gajus/swing](https://github.com/gajus/swing) | 2247 | `mocha --compilers js:babel-register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2228 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2189 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2170 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [noble/noble](https://github.com/noble/noble) | 2297 | `mocha -R spec test/*.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 2292 | `mocha` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2286 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2285 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2251 | `mocha --compilers js:babel-register` | 
| [gajus/swing](https://github.com/gajus/swing) | 2247 | `mocha --compilers js:babel-register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2228 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2221 | `mocha test test/unit/**/*_test.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2189 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2170 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2189 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2170 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2157 | `cross-env BABEL_ENV=test mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2155 | `nyc npm run _mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2150 | `standard && mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2141 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2130 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2123 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2121 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2115 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2104 | `mocha test/runner.js --reporter spec` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2096 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2083 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2080 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2065 | `mocha && eslint *.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2052 | `npm run lint && npm run mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2023 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2001 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [slate/slate](https://github.com/slate/slate) | 1998 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1996 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1953 | `npm run lint && mocha -R dot && npm run cover` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1937 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1935 | `mocha --require ./test/common --growl test/expect.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1921 | `npm run mocha && npm run karma` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1917 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1914 | `mocha --compilers js:babel-register` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1885 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1927 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1921 | `npm run mocha && npm run karma` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1917 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1914 | `mocha --compilers js:babel-register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1899 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1885 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1880 | `mocha --reporter spec && npm run test-typescript` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1877 | `mocha tests.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1865 | `mocha && npm run lint` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1859 | `mocha tests --require @babel/register` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1858 | `mocha --reporter spec test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1830 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1821 | `mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1819 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1816 | `mocha test -u bdd -R spec` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1816 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1808 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1795 | `npm run lint && npm run mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1767 | `mocha ./test/basic.js -t 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1763 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1753 | `mocha test` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1750 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1736 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1733 | `mocha compiled_tests/` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1733 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1728 | `mocha test/**/*_test.js --bail` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1725 | `npm run lint && npm run mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1722 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1717 | `npm run lint && mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1716 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1708 | `mocha test --timeout 600000` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1706 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1704 | `mocha test/* --reporter spec` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1702 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1692 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1692 | `mocha test/*.js` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1688 | `mocha test/setup.js test/spec/*.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1681 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1558 | `mocha test.js` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1555 | `./node_modules/.bin/mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1553 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1545 | `npm run test:lint && npm run test:mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1541 | `mocha --recursive` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1541 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1538 | `TEST=all mocha` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1534 | `nyc mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1530 | `node_modules/.bin/mocha --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1525 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1517 | `mocha -u tdd` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1634 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1634 | `mocha tests/test.js` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1633 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [zeit/ms](https://github.com/zeit/ms) | 1632 | `mocha tests.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1630 | `mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1619 | `standard "./src/*.js" && mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1618 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1607 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1596 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1592 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1588 | `mocha --check-leaks --reporter spec --bail` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1587 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1581 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1579 | `nyc mocha --timeout=20000 test.js` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1578 | `mocha --reporter spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1573 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1558 | `mocha test.js` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1555 | `./node_modules/.bin/mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1553 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1545 | `npm run test:lint && npm run test:mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1541 | `mocha --recursive` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1541 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1538 | `TEST=all mocha` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1534 | `nyc mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1530 | `node_modules/.bin/mocha --recursive` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1447 | `mocha test.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1447 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1444 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1437 | `mocha -R spec test/*.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1432 | `mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1426 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1424 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1422 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1419 | `npm run lint && mocha && karma start --single-run` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1414 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1409 | `mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1407 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1402 | `mocha ./test/test*.js --reporter spec` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1395 | `istanbul cover _mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1391 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1473 | `mocha --timeout 10000 ./tests/lib.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1471 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1461 | `mocha test/unit` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1459 | `NODE_ENV=test mocha tests/*.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1454 | `mocha test/tests.js --timeout=10000` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1454 | `mocha --check-leaks --require @babel/register` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1447 | `mocha test.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1447 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1444 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1437 | `mocha -R spec test/*.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1432 | `mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1426 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1424 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1422 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1419 | `npm run lint && mocha && karma start --single-run` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1414 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1409 | `mocha -R spec ./test/unit/**` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1409 | `mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1407 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1406 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1402 | `mocha ./test/test*.js --reporter spec` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1395 | `istanbul cover _mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1391 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1389 | `mocha tests/test-*` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1388 | `npm run build && mocha -r should` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1383 | `standard && istanbul cover _mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1380 | `mocha --opts test/opts/mocha.opts` | 
| [electron/devtron](https://github.com/electron/devtron) | 1372 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1372 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1369 | `mocha --reporter dot` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1351 | `mocha --recursive` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1341 | `./node_modules/.bin/mocha test` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1339 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1337 | `mocha` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1329 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1324 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1323 | `NODE_PATH=. mocha **/*.spec.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1316 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1313 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1305 | `mocha-phantomjs tests/index.html` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1304 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1304 | `mocha` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1298 | `mocha spec/exec.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1324 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1323 | `NODE_PATH=. mocha **/*.spec.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1316 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1314 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1313 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1313 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1311 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1305 | `mocha-phantomjs tests/index.html` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1304 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1304 | `mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1300 | `mocha --recursive test/bin` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1298 | `npm run prepublishOnly && mocha test/test.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1298 | `mocha spec/exec.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1294 | `mocha --timeout 60000 test/` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1293 | `mocha --check-leaks --reporter spec --bail test/` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1293 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1292 | `mocha --recursive test` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1283 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1272 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1270 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1268 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1265 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1259 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1259 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1253 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1253 | `mocha tests` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1252 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1252 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1249 | `mocha src/test.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1246 | `mocha --compilers js:babel-core/register` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1246 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1242 | `npm run lint && npm run mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1241 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1241 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1237 | `istanbul test _mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1237 | `istanbul test _mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1233 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1230 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1229 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1225 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1222 | `webpack && npm run lint && npm run mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1216 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [normalize/mz](https://github.com/normalize/mz) | 1215 | `mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1214 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1214 | `mocha test/test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1211 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1210 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1209 | `node ./node_modules/mocha/bin/mocha tests` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1207 | `npm run lint && mocha --require @babel/register` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1205 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1177 | `mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1175 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1159 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1156 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1148 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1142 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1137 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1137 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1136 | `istanbul cover _mocha test/*.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1136 | `mocha $(find test -name '*.test.js') --exit` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1136 | `xo && mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1136 | `xo && mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1133 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1132 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1130 | `mocha --timeout 30000 --recursive ./tests` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1118 | `mocha test/*` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1117 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1116 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1116 | `mocha test --compilers js:babel-core/register` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1116 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1110 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1110 | `mocha --reporter spec --bail --check-leaks test/` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1108 | `webpack && mocha test/unit` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1100 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1095 | `npm-run-all test:jest test:server:mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1118 | `mocha test/*` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1117 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1116 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1116 | `mocha test --compilers js:babel-core/register` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1116 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1110 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1110 | `mocha --reporter spec --bail --check-leaks test/` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1109 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1108 | `webpack && mocha test/unit` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1100 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1095 | `npm-run-all test:jest test:server:mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1091 | `nyc mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1090 | `mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1089 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1088 | `mocha --check-leaks -t 20000` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1087 | `mocha` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1086 | `mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1080 | `mocha --compilers js:babel-register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1073 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1073 | `mocha --recursive --bail --reporter spec test` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1072 | `standard && mocha -b` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1071 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1068 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1067 | `mocha test/tests.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 1059 | `mocha && standard` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1059 | `mocha` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1009 | `mocha --colors ./test/*.spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1008 | `mocha --check-leaks -R dot` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1002 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 997 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 994 | `mocha -R list` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 992 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 989 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 986 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 984 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 976 | `mocha test` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 974 | `npm run rollup-cjs && mocha test/test.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 970 | `mocha --reporter spec --bail --check-leaks test/` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 970 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 963 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 962 | `mocha "client.test" --compilers js:babel-register` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 961 | `mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 958 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 955 | `mocha --compilers js:babel-register test/*.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 955 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 951 | `npm run lint && mocha -R spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 947 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 943 | `mocha --timeout 5000` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 940 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 933 | `mocha spec/*.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 930 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 930 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 930 | `mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 925 | `mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 924 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 920 | `mocha -t 600000` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 919 | `mocha test` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 919 | `./node_modules/.bin/mocha --reporter spec` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 911 | `nyc --check-coverage mocha test/*.test.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 911 | `./node_modules/.bin/mocha -R spec` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 910 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 907 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 906 | `nyc mocha specs` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 906 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 906 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 905 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 904 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 903 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 903 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 902 | `mocha --recursive ./test/*_spec.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 901 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 897 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 895 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 893 | `mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 892 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 890 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 889 | `mocha test --compilers js:babel-register` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 887 | `node_modules/.bin/mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 886 | `./node_modules/.bin/mocha --globals angular,require` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 884 | `standard && standard ./bin/* && mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 874 | `mocha --timeout 200000` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 874 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 870 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 869 | `node_modules/.bin/mocha test/spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 866 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 866 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 858 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 858 | `mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 858 | `eslint test && mocha --compilers js:babel/register` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 857 | `mocha test/index.js` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 856 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 855 | `mocha --reporter list` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 838 | `nyc mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 838 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 836 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 835 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 835 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 834 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 833 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 833 | `mocha` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 833 | `mocha --recursive` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 827 | `mocha && ember test` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 825 | `./node_modules/.bin/mocha test/**/*` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 824 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 822 | `npm run build && istanbul test _mocha test/test.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 821 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 819 | `mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 818 | `mocha --harmony --full-trace --check-leaks` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 817 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 817 | `mocha --opts mocha.opts` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 838 | `nyc mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 838 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 838 | `mocha` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 836 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 835 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 835 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 834 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 833 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 833 | `mocha` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 833 | `mocha --recursive` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 827 | `mocha && ember test` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 825 | `./node_modules/.bin/mocha test/**/*` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 824 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 822 | `npm run build && istanbul test _mocha test/test.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 821 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 819 | `mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 818 | `mocha --harmony --full-trace --check-leaks` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 817 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 817 | `mocha --opts mocha.opts` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 817 | `mocha --async-only` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 816 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 815 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 815 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 814 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 809 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 807 | `mocha --colors --reporter spec test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 807 | `cake build && mocha ./test/mocha/*.coffee` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 805 | `mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 803 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 799 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 798 | `npm run mocha-test test/integration` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 797 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 797 | `mocha -R spec tests/` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 796 | `mocha -r should --reporter spec test/*.js` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 796 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 794 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 793 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 792 | `mocha -u tdd` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 792 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 790 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [developit/decko](https://github.com/developit/decko) | 789 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 788 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 785 | `mocha test` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 784 | `xo && mocha -R spec` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 781 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 780 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 778 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 776 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 774 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 772 | `nyc mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 770 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 