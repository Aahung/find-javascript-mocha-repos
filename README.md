# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:35 02/26/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45286 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42580 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42326 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30946 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25887 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25401 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25265 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21641 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20238 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15462 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14754 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14092 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13811 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13386 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12873 | `istanbul cover _mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12850 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12682 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12398 | `nyc grunt mocha-and-karma` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11429 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12682 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12616 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12398 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12373 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11700 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11429 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11276 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10988 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10737 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10674 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10737 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10674 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10474 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9946 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9848 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9742 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9618 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9524 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9474 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9372 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9204 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8987 | `mocha test/src` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8949 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 8891 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8718 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8637 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8595 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8489 | `grunt clean:test && mocha --exit` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8484 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8302 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8294 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8285 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8096 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8090 | `npm run eslint && npm run mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8089 | `mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8069 | `./node_modules/.bin/mocha test` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8018 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7928 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7275 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7148 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7105 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7074 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6991 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6623 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6428 | `npm run test:mocha:src` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6378 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6378 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6312 | `mocha tests/node.js` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6428 | `npm run test:mocha:src` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6378 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6378 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6312 | `mocha tests/node.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6268 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6247 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6206 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6145 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6139 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6121 | `standard && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6066 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5927 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5913 | `mocha && eslint lib/**` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5894 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5885 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [teambit/bit](https://github.com/teambit/bit) | 5832 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5818 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5740 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5675 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5665 | `mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5927 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5913 | `mocha && eslint lib/**` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5894 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5885 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [teambit/bit](https://github.com/teambit/bit) | 5832 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5818 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5740 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5675 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5665 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5614 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5485 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5465 | `mocha -r esm` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5409 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5401 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5394 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5270 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5210 | `mocha src/**/*Tests.js --harmony` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5139 | `gulp lint && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5129 | `mocha --color` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5125 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5101 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5047 | `nyc mocha --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4994 | `gulp build; mocha;` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4987 | `nyc mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4950 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4927 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4911 | `NODE_ENV=test mocha --exit` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4907 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4879 | `mocha -R spec 'tests/app'` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4875 | `mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4863 | `mocha test` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4755 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4742 | `mocha --recursive --colors` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4676 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4587 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4569 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4493 | `mocha --timeout=15000 tests/*.test.js` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4487 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4469 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4439 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4428 | `mocha --check-leaks --reporter spec --bail` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4402 | `node_modules/.bin/mocha test/tests.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4392 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4326 | `npm run lint ; mocha && mocha test/individual` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4245 | `npm run build && cd test && mocha . --reporter dot` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4191 | `mocha -R spec ./test --recursive` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4121 | `nyc mocha "test/**/*.test.js"` | 
| [tj/ejs](https://github.com/tj/ejs) | 4105 | `mocha --require should --reporter spec` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 4073 | `npm run mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 4072 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4054 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3993 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [tj/ejs](https://github.com/tj/ejs) | 4105 | `mocha --require should --reporter spec` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 4073 | `npm run mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 4072 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4054 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 4017 | `./node_modules/mocha/bin/mocha --require babel-core/register test/*` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3993 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3966 | `NODE_ENV=test mocha test/**/*.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3940 | `export TESTING=true; mocha --reporter list` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3897 | `mocha && tsc -p ./test/types` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3855 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [primus/primus](https://github.com/primus/primus) | 3833 | `npm run build && mocha test/*.test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3833 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3825 | `eslint . && mocha -t 5000` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3819 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3682 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3680 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3674 | `npm run jshint && npm run mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3657 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3608 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3603 | `mocha tests/javascript` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3600 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3587 | `nyc mocha && tsc` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3563 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3536 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3531 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3506 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3499 | `mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3496 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3466 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2675 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2595 | `mocha test --exit && npm run lint` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2585 | `TEST=all mocha` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2578 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2571 | `mocha test/src/**/*.unit.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2555 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2534 | `export TESTING=true; mocha --reporter list` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2521 | `mocha test/index.js --reporter dot` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2492 | `nyc --require babel-register npm run _mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2443 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2403 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2388 | `grunt jshint && mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3131 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3117 | `nyc mocha --recursive` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3109 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3098 | `npm run mocha && npm run lint` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3090 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3067 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3058 | `node_modules/.bin/mocha --reporter spec` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3024 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 3011 | `mocha --require @babel/register --recursive spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3004 | `mocha` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 3003 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2986 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2978 | `mocha -R spec --recursive src/test` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2973 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2705 | `mocha test/unit --require mochahook` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2697 | `mocha --timeout 100000` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2675 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2637 | `mocha-phantomjs ./test/index.html` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2627 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2595 | `mocha test --exit && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2583 | `mocha && eslint .` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2578 | `mocha` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2560 | `mocha test` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2555 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2551 | `nyc --reporter=html --reporter=text mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2534 | `export TESTING=true; mocha --reporter list` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2532 | `mocha --reporter=spec test/*-test.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2521 | `mocha test/index.js --reporter dot` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2042 | `mocha --reporter spec --timeout 5000` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 2008 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1989 | `mocha test/**/*.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1981 | `mocha --require ./test/common --growl test/expect.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1967 | `bmocha --reporter spec test/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1966 | `mocha --bail --reporter spec --check-leaks test/` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1939 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1935 | `mocha --reporter spec --grep .` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1934 | `nyc mocha --timeout=20000 test.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1930 | `mocha test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1921 | `mocha test -u bdd -R spec` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1874 | `eslint --cache . && tsc && mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2637 | `mocha-phantomjs ./test/index.html` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2627 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2595 | `mocha test --exit && npm run lint` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2585 | `TEST=all mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2583 | `mocha && eslint .` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2578 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2571 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2560 | `mocha test` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2557 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2555 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2551 | `nyc --reporter=html --reporter=text mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2548 | `mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2534 | `export TESTING=true; mocha --reporter list` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2532 | `mocha --reporter=spec test/*-test.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2521 | `mocha test/index.js --reporter dot` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2470 | `mocha -R spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2454 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2451 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [noble/noble](https://github.com/noble/noble) | 2443 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2423 | `npm run build && mocha --require babel-register` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2403 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2366 | `node node_modules/mocha/bin/_mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 2354 | `npm run lint && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2470 | `mocha -R spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2454 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2451 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [noble/noble](https://github.com/noble/noble) | 2443 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2423 | `npm run build && mocha --require babel-register` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2403 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2388 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2366 | `node node_modules/mocha/bin/_mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 2354 | `npm run lint && npm run mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2324 | `mocha --compilers js:babel-register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2319 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2314 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2313 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2276 | `standard && mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2244 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2242 | `mocha && eslint *.js` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2242 | `npm run lint && mocha tests/**/*.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 2232 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2218 | `mocha test test/unit/**/*_test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2213 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2208 | `mocha --timeout 15000 --bail --exit test/*-test.js test/security/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2206 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2208 | `mocha --timeout 15000 --bail --exit test/*-test.js test/security/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2206 | `mocha test/runner.js --reporter spec` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2196 | `mocha test/test-*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2192 | `cross-env BABEL_ENV=test mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2179 | `mocha --compilers js:babel-register` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2158 | `mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2152 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2150 | `mocha --compilers js:babel-core/register __tests__` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2142 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2140 | `mocha test` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2134 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [htmlhint/HTMLHint](https://github.com/htmlhint/HTMLHint) | 2064 | `mocha` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2058 | `npm run lint && mocha -R dot && npm run cover` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2057 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2056 | `mocha && npm run lint` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2054 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2042 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2028 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 2020 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2015 | `mocha --require=test/test_helper.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 2008 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1989 | `mocha test/**/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1976 | `mocha --reporter spec && npm run test-typescript` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1967 | `bmocha --reporter spec test/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1966 | `mocha --bail --reporter spec --check-leaks test/` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1967 | `bmocha --reporter spec test/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1961 | `npm run lint && mocha --reporter spec test/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1958 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1939 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1934 | `nyc mocha --timeout=20000 test.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1921 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1908 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1898 | `mocha ./test/basic.js -t 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1884 | `mocha tests.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1442 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1438 | `npm run build && mocha -r should` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1426 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1408 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1404 | `npm run mocha:istanbul` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1401 | `mocha --recursive` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1392 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1391 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1388 | `./node_modules/mocha/bin/mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1372 | `cross-env NODE_ENV=test nyc mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1341 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1340 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1686 | `mocha && size-limit` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1672 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1671 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1669 | `NODE_ENV=test mocha tests/*.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1667 | `xo && mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1645 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1636 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1633 | `mocha --reporter spec` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1627 | `mocha --recursive` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1624 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1622 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1622 | `./node_modules/mocha/bin/mocha -R spec` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1621 | `mocha test/unit` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1621 | `mocha test.js` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1614 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1446 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1442 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1438 | `npm run build && mocha -r should` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1426 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [electron/devtron](https://github.com/electron/devtron) | 1423 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1409 | `mocha --check-leaks --reporter spec --bail test/` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1408 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1404 | `npm run mocha:istanbul` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1401 | `mocha --recursive` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1395 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1394 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1392 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1391 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1381 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1455 | `mocha test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1449 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1446 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1442 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1438 | `npm run build && mocha -r should` | 
| [electron/devtron](https://github.com/electron/devtron) | 1423 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1409 | `mocha --check-leaks --reporter spec --bail test/` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1408 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1627 | `mocha --recursive` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1624 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1622 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1622 | `./node_modules/mocha/bin/mocha -R spec` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1621 | `mocha test/unit` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1617 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1615 | `mocha -R spec ./test/unit/**` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1614 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1593 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1592 | `mocha tests/test-*` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1586 | `nyc mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1567 | `mocha --check-leaks --require @babel/register` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1286 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1276 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1266 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1263 | `mocha tests` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1247 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1230 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1220 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1213 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1209 | `mocha test` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1208 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1207 | `mocha test/test.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1207 | `mocha --reporter spec --bail --check-leaks test/` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1206 | `mocha --recursive -r tests/setup tests` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1203 | `npm-run-all test:jest test:server:mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1198 | `mocha --reporter spec test --recursive` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1192 | `xo && mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1191 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1179 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1177 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1177 | `mocha $(find test -name '*.test.js') --exit` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1177 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1168 | `mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1168 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1168 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1161 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1159 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1157 | `istanbul cover _mocha test/*.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1153 | `webpack && mocha test/unit` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1152 | `npm run convertto:es5 && npm run mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1149 | `mocha && standard` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1097 | `node_modules/.bin/mocha && npm run lint` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1095 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1092 | `mocha --compilers js:babel-register` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1082 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 1079 | `mocha test` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1062 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1061 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 1051 | `mocha --recursive ./test/*_spec.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1038 | `mocha --recursive test/unit/` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1029 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1023 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1022 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 1022 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1015 | `mocha --async-only` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1014 | `./node_modules/.bin/mocha -R spec` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1014 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1010 | `mocha --compilers js:babel-register test/*.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1007 | `mocha -R list` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1007 | `mocha --check-leaks -R dot` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 1006 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 999 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 920 | `mocha test/index.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 920 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 916 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 907 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 907 | `npm run lint && npm run mocha:no-functional` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 906 | `mocha -r should --exit test/*.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 901 | `node_modules/.bin/mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 892 | `node_modules/.bin/mocha test/spec` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 892 | `mocha --harmony --full-trace --check-leaks` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 887 | `mocha --reporter list` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 883 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 883 | `mocha --harmony tests/**` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 878 | `npm run lint && mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 876 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 874 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1039 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1038 | `mocha --recursive test/unit/` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1033 | `mocha --reporter spec --bail --check-leaks test/` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1029 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1028 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1027 | `mocha spec/*.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1024 | `mocha --reporter spec --timeout 3000` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1023 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1022 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 1022 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1016 | `npm run lint && mocha -R spec` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1015 | `mocha --async-only` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1014 | `./node_modules/.bin/mocha -R spec` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1014 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 879 | `mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 878 | `mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 876 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 868 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 864 | `eslint test && mocha --compilers js:babel/register` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 862 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 858 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 856 | `mocha -r babel-register --check-leaks test/index.js` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 856 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 855 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 853 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 845 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 845 | `mocha --opts mocha.opts` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 844 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 842 | `mocha test` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 838 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 837 | `mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 832 | `mocha && ember test` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 831 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 830 | `npm run mocha-test test/integration` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 828 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 825 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 821 | `_mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 819 | `mocha --colors --reporter spec test.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 817 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 812 | `mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 808 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 937 | `mocha --timeout 5000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 928 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 920 | `mocha test/index.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 920 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 919 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 917 | `mocha -t 5000` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 897 | `mocha --timeout 200000` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 895 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 892 | `mocha --harmony --full-trace --check-leaks` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 887 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 883 | `mocha --harmony tests/**` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 879 | `mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 878 | `mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 878 | `npm run lint && mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 876 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 874 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 871 | `istanbul cover _mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 865 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 861 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [developit/decko](https://github.com/developit/decko) | 859 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 859 | `mocha --reporter spec --bail --check-leaks test/` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 858 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 857 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 856 | `nyc mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 856 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 845 | `mocha --opts mocha.opts` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 845 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 844 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 842 | `mocha test` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 841 | `mocha --async-only` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 854 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 853 | `mocha` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 853 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 845 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 845 | `mocha --opts mocha.opts` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 845 | `mocha` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 844 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 842 | `mocha test` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 841 | `mocha --async-only` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 838 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 837 | `mocha` | 
| [ebradyjobory/finance.js](https://github.com/ebradyjobory/finance.js) | 835 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 825 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 821 | `mocha test` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 821 | `_mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 821 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 820 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 819 | `mocha --colors --reporter spec test.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 817 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 812 | `mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 808 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 808 | `mocha test` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 808 | `mocha index.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 805 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 804 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 796 | `jenkins-mocha ./tests/*.js` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 795 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [fivdi/onoff](https://github.com/fivdi/onoff) | 781 | `nyc mocha` | 
| [koajs/static](https://github.com/koajs/static) | 780 | `mocha --harmony --reporter spec --exit` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 777 | `babel-node node_modules/.bin/_mocha -- test` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 777 | `npm run-script jshint && npm run-script mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 801 | `mocha` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 801 | `eslint . && mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 798 | `mocha --no-timeouts` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 796 | `nyc mocha` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 796 | `jenkins-mocha ./tests/*.js` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 796 | `npm run lint && npm run mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 795 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 792 | `mocha --recursive -s 15 test/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 767 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 766 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 765 | `npm run lint&&mocha tests/*.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 764 | `./bin/selenium-standalone install && mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 762 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 761 | `mocha 'test/**/*.tests.js'` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 751 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 750 | `mocha tests/*.mocha.js` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 749 | `npm run test-mocha && npm run test-karma` | 
| [electron/apps](https://github.com/electron/apps) | 748 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 739 | `mocha ./test/test.js --timeout 1000000` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 737 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 737 | `mocha` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 736 | `mocha $(find test -name '*.test.js')` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 736 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 735 | `mocha --reporter spec test/` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 731 | `mocha` | 
| [formio/formio](https://github.com/formio/formio) | 728 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 727 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 726 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 726 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [IjzerenHein/autolayout.js](https://github.com/IjzerenHein/autolayout.js) | 668 | `mocha` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 667 | `mocha` | 
| [calmm-js/partial.lenses](https://github.com/calmm-js/partial.lenses) | 666 | `nyc mocha && nyc report -r html mocha` | 
| [coinbase/gdax-node](https://github.com/coinbase/gdax-node) | 665 | `mocha --full-trace --ui tdd --bail --reporter spec tests/*.js` | 
| [substance/data](https://github.com/substance/data) | 665 | `mocha -R spec tests/run.js` | 
| [theoephraim/node-google-spreadsheet](https://github.com/theoephraim/node-google-spreadsheet) | 661 | `node_modules/.bin/mocha` | 
| [joaonuno/tree-model-js](https://github.com/joaonuno/tree-model-js) | 661 | `istanbul cover _mocha` | 
| [Ivshti/linvodb3](https://github.com/Ivshti/linvodb3) | 660 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 658 | `mocha` | 
| [chao/RESTClient](https://github.com/chao/RESTClient) | 656 | `mocha` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 653 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [docpress/docpress](https://github.com/docpress/docpress) | 653 | `nyc mocha` | 
| [spirit/spirit](https://github.com/spirit/spirit) | 652 | `BABEL_ENV=modules NODE_ENV=test mocha -r babel-register -r babel-polyfill -r ./test/bootstrap.js --timeout 5000` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 651 | `./node_modules/.bin/mocha test/integration` | 
| [rkusa/koa-passport](https://github.com/rkusa/koa-passport) | 649 | `mocha` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 683 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 683 | `mocha --bail test/` | 
| [shime/livedown](https://github.com/shime/livedown) | 676 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [mtth/avsc](https://github.com/mtth/avsc) | 676 | `mocha` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 674 | `mocha --require babel-register` | 
| [stevenvachon/broken-link-checker](https://github.com/stevenvachon/broken-link-checker) | 670 | `mocha test/ --reporter spec --check-leaks --bail` | 
| [IjzerenHein/autolayout.js](https://github.com/IjzerenHein/autolayout.js) | 668 | `mocha` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 667 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [calmm-js/partial.lenses](https://github.com/calmm-js/partial.lenses) | 666 | `nyc mocha && nyc report -r html mocha` | 
| [coinbase/gdax-node](https://github.com/coinbase/gdax-node) | 665 | `mocha --full-trace --ui tdd --bail --reporter spec tests/*.js` | 
| [zapty/forever-service](https://github.com/zapty/forever-service) | 527 | `mocha test/*.js` | 
| [techlayer/espresso.js](https://github.com/techlayer/espresso.js) | 521 | `mocha` | 
| [mher/node-celery](https://github.com/mher/node-celery) | 521 | `mocha tests` | 
| [markdalgleish/react-themeable](https://github.com/markdalgleish/react-themeable) | 519 | `babel-istanbul cover _mocha -- --compilers js:babel/register && babel-istanbul check-coverage --branches 100` | 
| [vega/datalib](https://github.com/vega/datalib) | 516 | `npm run lint && TZ=America/Los_Angeles mocha --recursive test/` | 
| [shakiba/svgexport](https://github.com/shakiba/svgexport) | 514 | `mocha` | 
| [shootaroo/jit-grunt](https://github.com/shootaroo/jit-grunt) | 514 | `npm-run-all build -p lint mocha` | 
| [expressjs/serve-favicon](https://github.com/expressjs/serve-favicon) | 512 | `mocha --reporter spec --bail --check-leaks test/` | 
| [atom/etch](https://github.com/atom/etch) | 508 | `npm run standard && npm run mocha` | 
| [Rich-Harris/buble](https://github.com/Rich-Harris/buble) | 506 | `mocha test/test.js` | 