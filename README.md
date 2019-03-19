# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:56:39 03/19/19 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45579 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42918 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42470 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 31000 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 26067 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25672 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25338 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21958 | `npm-run-all lint build --parallel test:mocha test:karma test:ts` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20358 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18946 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18377 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18206 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 18022 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15685 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15275 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14810 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14173 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12833 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12774 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12493 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12385 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11819 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11636 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11401 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 11091 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [websockets/ws](https://github.com/websockets/ws) | 10856 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10804 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10524 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 10089 | `mocha tests/*.js` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 10089 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9920 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9774 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9691 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9635 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9512 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9411 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9376 | `mocha --opts mocha.opts` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 9115 | `mocha test/*/**` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 9108 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9040 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8751 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8680 | `mocha --compilers js:babel-register test/test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8642 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8525 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8436 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 9108 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9040 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8751 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8680 | `mocha --compilers js:babel-register test/test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8642 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8600 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8525 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8436 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8322 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8298 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8278 | `mocha` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8202 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8131 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8120 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8118 | `./node_modules/.bin/mocha test` | 
| [aui/art-template](https://github.com/aui/art-template) | 7991 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7755 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7753 | `mocha --exit --require @babel/register` | 
| [almende/vis](https://github.com/almende/vis) | 7707 | `mocha --compilers js:babel-core/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7695 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7684 | `mocha; jshint *.js lib` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7643 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7598 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7452 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7383 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7260 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7174 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7155 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7099 | `mocha test/test.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6280 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6274 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6220 | `standard && mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6166 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 6150 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6068 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 6026 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5966 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5939 | `mocha && eslint lib/**` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5922 | `mocha` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5899 | `npm run lint && mocha tests/**/*.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5855 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5781 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5749 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5640 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5567 | `mocha test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5535 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5516 | `mocha -r esm` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6068 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 6026 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5966 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5939 | `mocha && eslint lib/**` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5922 | `mocha` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5899 | `npm run lint && mocha tests/**/*.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5855 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5781 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5749 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5640 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5567 | `mocha test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5535 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5516 | `mocha -r esm` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5483 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5440 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5397 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5212 | `mocha src/**/*Tests.js --harmony` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5203 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5170 | `npm run lint && npm run mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5153 | `gulp lint && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5124 | `mocha --color` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5119 | `nyc mocha --exit` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 5112 | `NODE_ENV=test mocha --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5090 | `nyc mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 5012 | `gulp build; mocha;` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4995 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4934 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4921 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4898 | `mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4892 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4873 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4842 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4765 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4721 | `mocha -R spec src` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 4631 | `./node_modules/mocha/bin/mocha --require @babel/register test/*` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4600 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4593 | `mocha ./test/runner.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4564 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4544 | `mocha --timeout=15000 tests/*.test.js` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4530 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4494 | `mocha --check-leaks --reporter spec --bail` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4492 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4446 | `mocha test/tests.js` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 4436 | `npm run mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4398 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4389 | `npm run lint && mocha && mocha test/individual && if [ "$TRAVIS_PULL_REQUEST" = "false" ]; then snyk test; fi` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4285 | `npm run build && cd test && mocha . --reporter dot` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4248 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4187 | `mocha -R spec ./test --recursive` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4166 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 4133 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [tj/ejs](https://github.com/tj/ejs) | 4129 | `mocha --require should --reporter spec` | 
| [expressjs/session](https://github.com/expressjs/session) | 4133 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [tj/ejs](https://github.com/tj/ejs) | 4129 | `mocha --require should --reporter spec` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4097 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 4050 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 4014 | `NODE_ENV=test mocha test/**/*.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3980 | `mocha && tsc -p ./test/types` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3952 | `eslint . && mocha -t 5000` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3939 | `export TESTING=true; mocha --reporter list` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3853 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3851 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [primus/primus](https://github.com/primus/primus) | 3846 | `npm run build && mocha test/*.test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3839 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3829 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3609 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3606 | `mocha tests/javascript` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3597 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3564 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3501 | `node_modules/.bin/mocha test/lib/` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3497 | `node ./test/import-test.js && mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3473 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3469 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3461 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3460 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3446 | `mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3423 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3409 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3380 | `mocha test/index.js && npm run demo` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3300 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3242 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3202 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3197 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3183 | `mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3169 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3160 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3135 | `nyc mocha --recursive` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3122 | `npm run mocha && npm run lint` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3093 | `node_modules/.bin/mocha --reporter spec` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3380 | `mocha test/index.js && npm run demo` | 
| [mde/ejs](https://github.com/mde/ejs) | 3339 | `mocha --require should --reporter spec` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3315 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3302 | `mocha test/*.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3300 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3295 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3242 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3202 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3197 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3192 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3183 | `mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3169 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3160 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3153 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3135 | `nyc mocha --recursive` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3122 | `npm run mocha && npm run lint` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3093 | `node_modules/.bin/mocha --reporter spec` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3074 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 3070 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3067 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3064 | `mocha test-node` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 3064 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 3043 | `mocha --require @babel/register --recursive spec` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3032 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3032 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2998 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2989 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2988 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2985 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2852 | `istanbul cover _mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2847 | `mocha "./test/**/*-test.js"` | 
| [css/csso](https://github.com/css/csso) | 2840 | `mocha --reporter dot` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2806 | `mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2789 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2787 | `mocha --require should --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2775 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2774 | `xo && mocha` | 
| [nosqlclient/nosqlclient](https://github.com/nosqlclient/nosqlclient) | 2766 | `cross-env TEST_BROWSER_DRIVER=chrome BABEL_ENV=coverage COVERAGE=1 COVERAGE_OUT_LCOVONLY=1 COVERAGE_APP_FOLDER=$PWD/ meteor test --once --driver-package meteortesting:mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2762 | `nyc mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2748 | `nyc mocha --timeout=10000` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2738 | `mocha test/unit --require mochahook` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2733 | `mocha --recursive --watch` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2725 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2712 | `mocha --timeout 100000` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2706 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [kach/nearley](https://github.com/kach/nearley) | 2120 | `mocha test/*.test.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2101 | `mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2092 | `mocha && npm run lint` | 
| [htmlhint/HTMLHint](https://github.com/htmlhint/HTMLHint) | 2077 | `mocha` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 2077 | `mocha --recursive` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2071 | `npm run lint && mocha -R dot && npm run cover` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2066 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [then/promise](https://github.com/then/promise) | 2031 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2031 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 2005 | `nyc mocha --timeout=20000 test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1985 | `mocha --require ./test/common --growl test/expect.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1980 | `bmocha --reporter spec test/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1975 | `mocha --bail --reporter spec --check-leaks test/` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2219 | `mocha test/runner.js --reporter spec` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2218 | `mocha test test/unit/**/*_test.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2199 | `mocha test` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2192 | `cross-env BABEL_ENV=test mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2181 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2176 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2170 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2137 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2131 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2121 | `npm run mocha && npm run karma` | 
| [kach/nearley](https://github.com/kach/nearley) | 2120 | `mocha test/*.test.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2113 | `mocha tests --require @babel/register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2101 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2483 | `mocha -R spec` | 
| [noble/noble](https://github.com/noble/noble) | 2473 | `mocha -R spec test/*.js` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2458 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2455 | `mocha --no-colors --reporter spec` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2446 | `npm run build && mocha --require babel-register` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2425 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [pahen/madge](https://github.com/pahen/madge) | 2402 | `npm run lint && npm run mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2393 | `grunt jshint && mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2382 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2350 | `mocha test/**/*.coffee` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2336 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [gajus/swing](https://github.com/gajus/swing) | 2335 | `mocha --compilers js:babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2322 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2289 | `standard && mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 2284 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2267 | `mocha test/test-*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2265 | `mocha` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2258 | `npm run lint && mocha tests/**/*.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2244 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2228 | `mocha --timeout 15000 --bail --exit test/*-test.js test/security/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2192 | `cross-env BABEL_ENV=test mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2181 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2171 | `mocha --compilers js:babel-core/register __tests__` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2170 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2163 | `mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2137 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [kach/nearley](https://github.com/kach/nearley) | 2120 | `mocha test/*.test.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2092 | `mocha && npm run lint` | 
| [htmlhint/HTMLHint](https://github.com/htmlhint/HTMLHint) | 2077 | `mocha` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 2077 | `mocha --recursive` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2071 | `npm run lint && mocha -R dot && npm run cover` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2066 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2031 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2020 | `mocha --require=test/test_helper.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 2005 | `nyc mocha --timeout=20000 test.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1997 | `mocha --reporter spec && npm run test-typescript` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1985 | `mocha --require ./test/common --growl test/expect.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1975 | `mocha --bail --reporter spec --check-leaks test/` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1974 | `npm run lint && mocha --reporter spec test/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1965 | `mocha -c test/index.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1959 | `mocha --reporter spec --grep .` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1951 | `mocha test -u bdd -R spec` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1948 | `mocha test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1942 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1936 | `mocha ./test/basic.js -t 5000` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1919 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1892 | `mocha ./test/test*.js --reporter spec` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1960 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1959 | `mocha --reporter spec --grep .` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1951 | `mocha test -u bdd -R spec` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1948 | `mocha test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1942 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1919 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1892 | `mocha ./test/test*.js --reporter spec` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1885 | `mocha tests.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1882 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1870 | `npm run lint && npm run mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1861 | `mocha test/setup.js test/spec/*.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1860 | `npm run lint && npm run mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1917 | `eslint --cache . && tslint --project . && node build && mocha && tsc` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1892 | `mocha ./test/test*.js --reporter spec` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1882 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1862 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1861 | `mocha test/setup.js test/spec/*.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1860 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1828 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1826 | `mocha test` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1826 | `mocha test` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1824 | `mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1794 | `mocha --timeout 5000` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1792 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1781 | `npm run lint && mocha && npm run typescript` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1778 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1770 | `mocha --check-leaks --reporter spec --bail` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1767 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1766 | `mocha test/*.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1766 | `mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1817 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1803 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1794 | `mocha --timeout 5000` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1792 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1781 | `npm run lint && mocha && npm run typescript` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1778 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1770 | `mocha --check-leaks --reporter spec --bail` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1767 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1766 | `mocha test/*.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1766 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1749 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1749 | `./node_modules/.bin/mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1747 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1742 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1739 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1738 | `mocha test --timeout 600000` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1731 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1730 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1730 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1728 | `mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1724 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1723 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1716 | `mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1715 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1701 | `NODE_ENV=test mocha tests/*.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1697 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1695 | `npm run jshint && mocha --recursive` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1488 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1478 | `mocha -R spec` | 
| [samccone/drool](https://github.com/samccone/drool) | 1464 | `mocha test/tests.js --timeout=10000` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1453 | `npm run mocha:istanbul` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1450 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1449 | `webpack && npm run lint && npm run mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1448 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1447 | `npm run build && mocha -r should` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1447 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1433 | `mocha --check-leaks --reporter spec --bail test/` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1433 | `mocha --recursive test/bin` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1556 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [fbeline/design-patterns-JS](https://github.com/fbeline/design-patterns-JS) | 1553 | `mocha test --compilers js:babel-core/register` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1553 | `mocha --recursive test` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1550 | `npm run test:lint && npm run test:mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1549 | `mocha -u tdd` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1548 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1547 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1545 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1538 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1531 | `mocha --timeout 10000 ./tests/lib.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1530 | `npm run prepublishOnly && mocha test/test.js` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1530 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [noble/bleno](https://github.com/noble/bleno) | 1529 | `mocha -R spec test/*.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1528 | `mocha test/**/*.spec.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1518 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1513 | `mocha --reporter dot` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1505 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1495 | `mocha --opts test/opts/mocha.opts` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1488 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1478 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1478 | `mocha -R spec` | 
| [samccone/drool](https://github.com/samccone/drool) | 1464 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1456 | `mocha test.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1453 | `npm run mocha:istanbul` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1450 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1449 | `webpack && npm run lint && npm run mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1448 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1447 | `npm run build && mocha -r should` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1433 | `mocha --check-leaks --reporter spec --bail test/` | 
| [electron/devtron](https://github.com/electron/devtron) | 1427 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1426 | `istanbul cover _mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1416 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1410 | `mocha --compilers js:babel-core/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1410 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1405 | `mocha --recursive` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1401 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1395 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1393 | `NODE_PATH=. mocha **/*.spec.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1391 | `./node_modules/mocha/bin/mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1391 | `./node_modules/.bin/mocha test` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1383 | `mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1383 | `npm run lint && mocha --require @babel/register` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1379 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1376 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1302 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1267 | `mocha tests` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1258 | `mocha test` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1241 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1224 | `mocha --recursive -r tests/setup tests` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1222 | `mocha --reporter spec test --recursive` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1222 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1217 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1330 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1325 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1325 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1321 | `mocha-phantomjs tests/index.html` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1306 | `mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1305 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1304 | `istanbul test _mocha` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1302 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [variety/variety](https://github.com/variety/variety) | 1293 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1284 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [normalize/mz](https://github.com/normalize/mz) | 1269 | `mocha --reporter spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1267 | `mocha tests` | 
| [electron/asar](https://github.com/electron/asar) | 1259 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1258 | `mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1258 | `mocha test` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1256 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1241 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1224 | `mocha --recursive -r tests/setup tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1223 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1222 | `mocha --reporter spec test --recursive` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1222 | `mocha --reporter spec --bail --check-leaks test/` | 
| [normalize/mz](https://github.com/normalize/mz) | 1269 | `mocha --reporter spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1267 | `mocha tests` | 
| [electron/asar](https://github.com/electron/asar) | 1259 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1258 | `mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1258 | `mocha test` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1256 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1241 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1227 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1224 | `mocha --recursive -r tests/setup tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1223 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1222 | `mocha --reporter spec test --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1232 | `node ./node_modules/mocha/bin/mocha tests` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1227 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1224 | `mocha --recursive -r tests/setup tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1223 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1222 | `mocha --reporter spec test --recursive` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1222 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1217 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1214 | `mocha test` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1214 | `npm-run-all test:jest test:server:mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1209 | `mocha test/test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1205 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1197 | `xo && mocha` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1189 | `npm run lint && npm run mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1128 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1122 | `mocha` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1117 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1115 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1113 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1112 | `mocha --recursive --bail --reporter spec test` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1109 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1099 | `mocha --check-leaks -t 20000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1099 | `node_modules/.bin/mocha && npm run lint` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1094 | `mocha --compilers js:babel-register` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1090 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1089 | `mocha test/tests.js` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 988 | `mocha -t 600000 --exit` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 987 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 987 | `mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 985 | `mocha --reporter spec` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 984 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 984 | `mocha` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 983 | `mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 982 | `npm run rollup-cjs && mocha test/test.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 977 | `./node_modules/.bin/mocha --reporter spec` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 975 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 972 | `./node_modules/.bin/mocha test/**/*` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 968 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 967 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 965 | `mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 955 | `istanbul cover -- _mocha --reporter spec` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1128 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1122 | `mocha` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1117 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1115 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1115 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1113 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1112 | `mocha --recursive --bail --reporter spec test` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1109 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1099 | `mocha --check-leaks -t 20000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1099 | `node_modules/.bin/mocha && npm run lint` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1096 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1094 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1089 | `mocha test/tests.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [odota/core](https://github.com/odota/core) | 1079 | `NODE_ENV=test mocha --exit` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1077 | `mocha --async-only` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1067 | `mocha test/*.test.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1067 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1059 | `mocha $(find test -name '*.test.js')` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1032 | `./node_modules/.bin/mocha -R spec` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1030 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 1029 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1029 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1025 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1022 | `mocha --async-only` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1020 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1013 | `mocha --compilers js:babel-register test/*.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1010 | `mocha -R list` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1007 | `mocha --check-leaks -R dot` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 996 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 994 | `mocha "client.test" --compilers js:babel-register` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 988 | `mocha -t 600000 --exit` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 987 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 987 | `mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 984 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 982 | `npm run rollup-cjs && mocha test/test.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 977 | `./node_modules/.bin/mocha --reporter spec` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 975 | `nyc mocha specs` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 962 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 955 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 955 | `istanbul cover -- _mocha --reporter spec` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 952 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 951 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 942 | `mocha test/index.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 937 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 936 | `mocha --timeout 5000` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 994 | `mocha "client.test" --compilers js:babel-register` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 988 | `mocha -t 600000 --exit` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 987 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 987 | `mocha tests` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 985 | `mocha --reporter spec` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 984 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 984 | `mocha` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 983 | `mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 982 | `npm run rollup-cjs && mocha test/test.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 975 | `nyc mocha specs` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 975 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 973 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 942 | `mocha test/index.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 937 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 937 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 936 | `mocha --timeout 5000` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 934 | `mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 952 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 951 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 942 | `mocha test/index.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 937 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 937 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 936 | `mocha --timeout 5000` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 934 | `mocha` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 913 | `mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 907 | `npm run build && istanbul test _mocha test/test.js` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 906 | `npm run lint && mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 905 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [nimiq-network/core](https://github.com/nimiq-network/core) | 904 | `NODE_ENV=test mocha --exit` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 901 | `node_modules/.bin/mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 901 | `mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 898 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 898 | `mocha --timeout 200000` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 892 | `mocha --reporter list` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 780 | `babel-node node_modules/.bin/_mocha -- test` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 780 | `mocha 'test/**/*.tests.js'` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 777 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 775 | `mocha -R spec src/**/*_test.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 773 | `./bin/selenium-standalone install && mocha` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 755 | `mocha --reporter spec --bail --check-leaks test/` | 
| [CharlesStover/reactn](https://github.com/CharlesStover/reactn) | 754 | `mocha -r chai/register-expect -r @babel/register -r ts-node/register "tests/**/*.spec.ts?(x)"` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 753 | `npm run test-mocha && npm run test-karma` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 753 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 846 | `mocha test` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 846 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 845 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 843 | `ts-mocha test/` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 842 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 841 | `mocha --async-only` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 840 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 837 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 836 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 836 | `npm run mocha-test test/integration` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 836 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 832 | `_mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 832 | `mocha && ember test` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 829 | `cake build && mocha ./test/mocha/*.coffee` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 826 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 826 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 825 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 822 | `eslint . && mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 820 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 820 | `mocha --colors --reporter spec test.js` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 820 | `mocha index.test.js` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 818 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 818 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 815 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 815 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 812 | `mocha test` | 