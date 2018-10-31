# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:19 10/31/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44084 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41585 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40792 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30511 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24810 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24028 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20504 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19508 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17725 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17350 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17233 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15935 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14477 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14385 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14285 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13544 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13183 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12806 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12541 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12341 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12288 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11879 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11769 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11739 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10961 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10631 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10476 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10422 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10340 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [tj/co](https://github.com/tj/co) | 10225 | `mocha --harmony` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9523 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 9484 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9392 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9307 | `mocha -b -r esm` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9138 | `mocha tests/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9130 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 9014 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8982 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8689 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8585 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8498 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8385 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8281 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8146 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8068 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7964 | `npm run eslint && npm run mocha` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8385 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8328 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8281 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8146 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8068 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7964 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7837 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7561 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7533 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7530 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [aui/art-template](https://github.com/aui/art-template) | 7510 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7500 | `npm run build && istanbul cover _mocha` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7494 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7457 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7445 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6892 | `mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6866 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6687 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6493 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6397 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6311 | `npm run test:mocha:src` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6249 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6120 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6069 | `mocha tests/node.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6058 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6311 | `npm run test:mocha:src` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6249 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6120 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6069 | `mocha tests/node.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6058 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5976 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5952 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5934 | `mocha` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5905 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5892 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5882 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5795 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5624 | `standard && mocha` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5246 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5209 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5196 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5151 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5070 | `gulp lint && mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5036 | `mocha test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4896 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4890 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4840 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4809 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4785 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4783 | `mocha -R spec 'tests/app'` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4896 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4890 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4840 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4809 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4785 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4783 | `mocha -R spec 'tests/app'` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4734 | `mocha --recursive` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4731 | `./node_modules/.bin/mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4711 | `mocha --reporter spec -t 8000` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4657 | `mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4646 | `nyc mocha --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4636 | `npm run lint && npm run mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4570 | `mocha ./test/runner.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4529 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4510 | `nyc mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4470 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4466 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [teambit/bit](https://github.com/teambit/bit) | 4438 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4347 | `mocha -R spec src` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4347 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4296 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4256 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4222 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4217 | `mocha --timeout=15000 tests/*.test.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4205 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4202 | `nyc mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4168 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4137 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4114 | `npm run lint ; mocha && mocha test/individual` | 
| [muicss/mui](https://github.com/muicss/mui) | 4077 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4076 | `mocha --require test/babel-hook test/*.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4046 | `mocha --check-leaks --reporter spec --bail` | 
| [tj/ejs](https://github.com/tj/ejs) | 4035 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3992 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3911 | `export TESTING=true; mocha --reporter list` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3876 | `NODE_ENV=test mocha --exit` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3875 | `nyc mocha "test/**/*.test.js"` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3866 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [erming/shout](https://github.com/erming/shout) | 3795 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3793 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3791 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3785 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3714 | `npm run build && mocha test/*.test.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3684 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3682 | `standard && mocha --timeout 60000 test/test.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3667 | `NODE_ENV=test mocha test/**/*.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3664 | `npm run jshint && npm run mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3625 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3595 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3592 | `node_modules/.bin/mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3590 | `mocha tests/javascript` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3586 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3563 | `mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3553 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3446 | `mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3445 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3372 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3352 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3301 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3217 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3215 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3213 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3209 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3176 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3174 | `mocha test/*.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3160 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3201 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3198 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3176 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3174 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3174 | `mocha test/*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3166 | `mocha test/index.js && npm run demo` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3160 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3159 | `./node_modules/.bin/mocha test/test.*.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3152 | `eslint . && mocha -t 5000` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3118 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3117 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3106 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3102 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3094 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3092 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3044 | `mocha -R landing test/index` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3035 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 3023 | `mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2980 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2973 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2857 | `node_modules/.bin/mocha --reporter spec` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2854 | `mocha --require babel-register --recursive spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2853 | `mocha test-node` | 
| [github-tools/github](https://github.com/github-tools/github) | 2844 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2843 | `mocha` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2842 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2840 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2837 | `mocha -R spec spec spec/reporters` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2828 | `istanbul cover _mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2779 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2777 | `mocha --require should --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2770 | `mocha --reporter dot` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2739 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2735 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2721 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2707 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2690 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2662 | `mocha --timeout 100000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2660 | `mocha --recursive --watch` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2557 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2553 | `mocha test/unit --require mochahook` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2532 | `export TESTING=true; mocha --reporter list` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2532 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2531 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2495 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2485 | `mocha --reporter=spec test/*-test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2464 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2451 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2423 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2412 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2390 | `mocha test/index.js --reporter dot` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2373 | `grunt jshint && mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2613 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2580 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2557 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2553 | `mocha test/unit --require mochahook` | 
| [retejs/rete](https://github.com/retejs/rete) | 2543 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2532 | `export TESTING=true; mocha --reporter list` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2532 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2531 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2495 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2492 | `mocha test` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2485 | `mocha --reporter=spec test/*-test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2464 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2451 | `nyc --reporter=html --reporter=text mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2532 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2531 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2495 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2492 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2492 | `mocha test` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2485 | `mocha --reporter=spec test/*-test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2464 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2451 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2423 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2412 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2401 | `mocha test && npm run lint` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2398 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2394 | `mocha && eslint .` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2390 | `mocha test/index.js --reporter dot` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2377 | `mocha -R spec` | 
| [Qix-/color](https://github.com/Qix-/color) | 2323 | `mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2316 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2315 | `mocha -R spec test/*.js` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2315 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2289 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2287 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2266 | `npm run build && mocha --require babel-register` | 
| [gajus/swing](https://github.com/gajus/swing) | 2259 | `mocha --compilers js:babel-register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2225 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2223 | `mocha test test/unit/**/*_test.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2047 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2046 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [share/sharedb](https://github.com/share/sharedb) | 2024 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2010 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [slate/slate](https://github.com/slate/slate) | 1997 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1981 | `mocha --reporter spec --timeout 5000` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1980 | `mocha --require=test/test_helper.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1974 | `mocha test/*.test.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1962 | `npm run lint && mocha -R dot && npm run cover` | 
| [then/promise](https://github.com/then/promise) | 1955 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1939 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1937 | `mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1931 | `npm run mocha && npm run karma` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1928 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1927 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1887 | `mocha --reporter spec && npm run test-typescript` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1881 | `mocha tests --require @babel/register` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1876 | `mocha tests.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1887 | `mocha --reporter spec && npm run test-typescript` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1881 | `mocha tests --require @babel/register` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1876 | `mocha tests.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1851 | `mocha test/**/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1851 | `npm run lint && mocha --reporter spec test/*.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1844 | `mocha` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1844 | `mocha test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1837 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1833 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1826 | `mocha test -u bdd -R spec` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1807 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1801 | `npm run lint && npm run mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1800 | `mocha --timeout 5000` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1807 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1801 | `npm run lint && npm run mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1800 | `mocha --timeout 5000` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1796 | `mocha test` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1781 | `mocha ./test/basic.js -t 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1771 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1755 | `mocha compiled_tests/` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1737 | `npm run lint && npm run mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1736 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1734 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1727 | `mocha test/**/*_test.js --bail` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1723 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1704 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1700 | `mocha test/*.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1698 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1686 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1681 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1679 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1661 | `eslint --cache . && tsc && mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1660 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1656 | `mocha tests.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1656 | `mocha && size-limit` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1653 | `mocha spec` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1650 | `mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1636 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1636 | `mocha tests/test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1635 | `mocha --expose-gc --slow 300` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1600 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1588 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1585 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1572 | `mocha test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1559 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1545 | `mocha --recursive` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1544 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1530 | `node_modules/.bin/mocha --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1525 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1523 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1572 | `mocha test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1559 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1556 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1547 | `nyc mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1545 | `mocha --recursive` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1544 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1530 | `node_modules/.bin/mocha --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1525 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1521 | `mocha -u tdd` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1320 | `npm run prepublishOnly && mocha test/test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1316 | `mocha --recursive test` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1314 | `mocha --recursive test/bin` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1313 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1312 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1296 | `mocha --timeout 60000 test/` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1289 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1284 | `mocha test/*.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1270 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1270 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1265 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1265 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1264 | `mocha test --compilers js:babel-core/register` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1261 | `mocha --compilers js:babel-core/register` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1259 | `mocha src/test.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1257 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1499 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1492 | `mocha test/**/*.spec.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1486 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1480 | `NODE_ENV=test mocha tests/*.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1478 | `mocha -R spec` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1478 | `mocha --timeout 10000 ./tests/lib.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1477 | `mocha test/unit` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1471 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1468 | `mocha --check-leaks --require @babel/register` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1458 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1453 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1447 | `mocha test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1445 | `mocha -R spec test/*.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1443 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1439 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1433 | `mocha ./test/test*.js --reporter spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1432 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1429 | `mocha -R spec ./test/unit/**` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1427 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1426 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1426 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1424 | `npm run lint && mocha && karma start --single-run` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1418 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1413 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1410 | `mocha tests/test-*` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1407 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1402 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1296 | `mocha --timeout 60000 test/` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1289 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1288 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1284 | `mocha test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1278 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1270 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1270 | `mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1265 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1265 | `mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1264 | `mocha test --compilers js:babel-core/register` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1261 | `mocha --compilers js:babel-core/register` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1260 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1257 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1256 | `mocha tests` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1256 | `npm run lint && npm run mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1249 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1248 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1246 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1246 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1240 | `istanbul test _mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1239 | `webpack && npm run lint && npm run mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1232 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1230 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1229 | `npm run mocha:istanbul` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1224 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1223 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1222 | `npm run lint && mocha --require @babel/register` | 
| [normalize/mz](https://github.com/normalize/mz) | 1218 | `mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1216 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1216 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1215 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1213 | `mocha test/test.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1211 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1210 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1208 | `mocha tests/` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1205 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1199 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1196 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1183 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1177 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1162 | `mocha --timeout 20000` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1160 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1150 | `mocha --timeout 30000 --recursive ./tests` | 
| [electron/asar](https://github.com/electron/asar) | 1146 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1145 | `mocha $(find test -name '*.test.js') --exit` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1141 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1140 | `istanbul cover _mocha test/*.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1140 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1139 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 1139 | `mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1138 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1126 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1122 | `mocha test/*` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1120 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1119 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1117 | `mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1117 | `npm-run-all test:jest test:server:mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1117 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1115 | `webpack && mocha test/unit` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1111 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1110 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1126 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1122 | `mocha test/*` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1120 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1119 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1117 | `mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1117 | `npm-run-all test:jest test:server:mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1117 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1115 | `webpack && mocha test/unit` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1113 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1111 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1110 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1105 | `mocha --reporter spec --bail --check-leaks test/` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1095 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1093 | `mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1091 | `mocha --check-leaks -t 20000` | 
| [tomas/needle](https://github.com/tomas/needle) | 1044 | `mocha test` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1039 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1036 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1034 | `mocha --reporter spec --timeout 3000` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1032 | `mocha` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1032 | `mocha $(find test -name '*.test.js')` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1016 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1010 | `mocha --colors ./test/*.spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1008 | `mocha --check-leaks -R dot` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1008 | `mocha --check-leaks -R dot` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1004 | `mocha test` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 996 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 996 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 994 | `mocha -R list` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 990 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 984 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 981 | `mocha --reporter spec --bail --check-leaks test/` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1021 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1016 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1015 | `mocha --recursive test/unit/` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1010 | `mocha --colors ./test/*.spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1008 | `mocha --check-leaks -R dot` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1004 | `mocha test` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 996 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 974 | `mocha --reporter spec` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 972 | `npm run rollup-cjs && mocha test/test.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 969 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 967 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 967 | `mocha "client.test" --compilers js:babel-register` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 964 | `npm run lint && mocha -R spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 963 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 960 | `mocha --compilers js:babel-register test/*.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 960 | `mocha` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 955 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 953 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 946 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 943 | `mocha --timeout 5000` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 939 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 937 | `mocha spec/*.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 934 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 934 | `mocha tests` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 928 | `mocha -t 600000` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 927 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 937 | `mocha spec/*.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 936 | `mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 934 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 934 | `mocha tests` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 928 | `mocha -t 600000` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 927 | `./node_modules/.bin/mocha --reporter spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 927 | `mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 925 | `mocha test/*.test.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 921 | `mocha test` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 918 | `./node_modules/.bin/mocha -R spec` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 917 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 916 | `mocha --recursive ./test/*_spec.js` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 915 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 914 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 913 | `nyc mocha specs` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 910 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 910 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 909 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 909 | `mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 908 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 905 | `mocha test --compilers js:babel-register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 902 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 901 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 894 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 894 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 893 | `mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 890 | `istanbul cover -- _mocha --reporter spec` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 888 | `node_modules/.bin/mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 887 | `standard && standard ./bin/* && mocha` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 887 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 885 | `./node_modules/.bin/mocha --globals angular,require` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 884 | `npm run lint && npm run mocha:no-functional` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 879 | `mocha -t 5000` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 877 | `mocha --timeout 200000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 866 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 864 | `mocha test/index.js` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 858 | `mocha --reporter list` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 858 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 857 | `mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 856 | `mocha --reporter spec` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 855 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 854 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 853 | `istanbul cover _mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 848 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 844 | `npm run lint && mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 844 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 844 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 841 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 853 | `istanbul cover _mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 848 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 847 | `mocha --check-leaks -t 20000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 845 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 844 | `npm run lint && mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 844 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 844 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 841 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 840 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 839 | `mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 838 | `mocha --reporter spec --bail --check-leaks test/` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 837 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 834 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 810 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 809 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 808 | `mocha --colors --reporter spec test.js` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 804 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 803 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 802 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 801 | `npm run mocha-test test/integration` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 801 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 801 | `npm run lint && npm run mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 797 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 796 | `mocha -R spec tests/` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 794 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 794 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 792 | `mocha -u tdd` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 802 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 802 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 801 | `npm run mocha-test test/integration` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 801 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 801 | `npm run lint && npm run mocha` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 800 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 797 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 796 | `mocha -R spec tests/` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 794 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 792 | `mocha -u tdd` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 789 | `xo && mocha -R spec` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 789 | `mocha test` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 785 | `nyc mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 792 | `mocha -u tdd` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 789 | `xo && mocha -R spec` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 789 | `mocha test` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 785 | `nyc mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 782 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 782 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 781 | `mocha --no-timeouts` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 780 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 779 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 775 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 766 | `mocha --ui tdd --require ./test/__setup` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 758 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 756 | `npm run lint && npm run mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 754 | `npm run lint && mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 754 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 753 | `nyc mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 751 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 751 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 750 | `mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 749 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 735 | `npm run bundle && mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 735 | `mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 735 | `mocha --reporter spec build/test/index.js` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 735 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 734 | `mocha --reporter spec` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 732 | `./bin/selenium-standalone install && mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 731 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 730 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 729 | `jenkins-mocha ./tests/*.js` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 727 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [koajs/static](https://github.com/koajs/static) | 727 | `mocha --harmony --reporter spec --exit` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 726 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 725 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 726 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 725 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 725 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 717 | `mocha $(find test -name '*.test.js')` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 714 | `npm run test-mocha && npm run test-karma` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 713 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 710 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 