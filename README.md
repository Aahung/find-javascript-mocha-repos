# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:40 03/29/19 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45734 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 43074 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42525 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 31031 | `nyc mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 26550 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25834 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 22084 | `npm-run-all lint build --parallel test:mocha test:karma test:ts` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20422 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 19068 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18473 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18258 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 18178 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15793 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15335 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14827 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14220 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13675 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13124 | `mocha 'test/**/*.spec.js'` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 13076 | `istanbul cover _mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12933 | `mocha --reporter spec test/*-test.js` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12853 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12523 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12392 | `mocha` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 14032 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13675 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13124 | `mocha 'test/**/*.spec.js'` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 13076 | `istanbul cover _mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12933 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12917 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12853 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12523 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12392 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11893 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11747 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11494 | `set NODE_ENV=test && mocha` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 11158 | `mocha` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8330 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8289 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8171 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7861 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7813 | `mocha --exit --require @babel/register` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7658 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7452 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7341 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7197 | `npm run jshint && mocha test/` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7183 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7475 | `mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7452 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7341 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7197 | `npm run jshint && mocha test/` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7183 | `mocha $HARMONY_OPTS` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6680 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6527 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6457 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6379 | `mocha tests/node.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6361 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7861 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7813 | `mocha --exit --require @babel/register` | 
| [almende/vis](https://github.com/almende/vis) | 7753 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7750 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7742 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7658 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7604 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7475 | `mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7452 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7341 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7197 | `npm run jshint && mocha test/` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7183 | `mocha $HARMONY_OPTS` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7159 | `mocha test/test.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6181 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 6101 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6067 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 6023 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5954 | `mocha && eslint lib/**` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5924 | `npm run lint && mocha tests/**/*.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5922 | `mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5874 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5805 | `mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5798 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5655 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5607 | `mocha test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5586 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5567 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5447 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 6101 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6067 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 6023 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5954 | `mocha && eslint lib/**` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5924 | `npm run lint && mocha tests/**/*.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5922 | `mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5874 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5805 | `mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5798 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5655 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5607 | `mocha test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5586 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5567 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5545 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5447 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5396 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5262 | `mocha --recursive` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5212 | `mocha src/**/*Tests.js --harmony` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5204 | `npm run lint && npm run mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 5202 | `NODE_ENV=test mocha --exit` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5171 | `nyc mocha --exit` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5159 | `gulp lint && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5125 | `mocha --color` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5123 | `nyc mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 5022 | `gulp build; mocha;` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 5011 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4939 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4929 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4913 | `mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4898 | `mocha --recursive --colors` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4895 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4890 | `mocha test` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4775 | `mocha -R spec src` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4770 | `mocha --reporter spec -t 8000` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 4739 | `./node_modules/mocha/bin/mocha --require @babel/register test/*` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 4623 | `npm run mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4614 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4612 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4595 | `mocha ./test/runner.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4571 | `mocha --timeout=15000 tests/*.test.js` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4538 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4532 | `mocha --check-leaks --reporter spec --bail` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4497 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4465 | `mocha test/tests.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4315 | `npm run build && cd test && mocha . --reporter dot` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4257 | `nyc mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4192 | `nyc mocha "test/**/*.test.js"` | 
| [muicss/mui](https://github.com/muicss/mui) | 4179 | `mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 4166 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [tj/ejs](https://github.com/tj/ejs) | 4140 | `mocha --require should --reporter spec` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 4092 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 4038 | `NODE_ENV=test mocha test/**/*.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 4021 | `mocha && tsc -p ./test/types` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3844 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3799 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3773 | `mocha test/* --reporter spec` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4111 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 4038 | `NODE_ENV=test mocha test/**/*.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 4021 | `mocha && tsc -p ./test/types` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 4019 | `eslint . && mocha -t 5000` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3941 | `export TESTING=true; mocha --reporter list` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3863 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3860 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3854 | `npm run build && mocha test/*.test.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3852 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3844 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [antvis/g6](https://github.com/antvis/g6) | 3836 | `torch --compile --renderer --opts test/mocha.opts --recursive ./test/unit` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3800 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [erming/shout](https://github.com/erming/shout) | 3799 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3651 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3645 | `nyc mocha && tsc` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3628 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3623 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3596 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3590 | `mocha -R landing test/index --exit` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3566 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3561 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3505 | `node_modules/.bin/mocha test/lib/` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3502 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3484 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3482 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3464 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3451 | `mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3397 | `mocha test/index.js && npm run demo` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3470 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3451 | `mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3397 | `mocha test/index.js && npm run demo` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3329 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3322 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3305 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3250 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3214 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3201 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3198 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3077 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 3060 | `mocha --require @babel/register --recursive spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3051 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3042 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 3035 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2999 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2996 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2932 | `mocha -R spec spec spec/reporters` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2928 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2911 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2854 | `istanbul cover _mocha` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3051 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3042 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 3035 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 3001 | `mocha -R spec --recursive src/test` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2999 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2996 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2932 | `mocha -R spec spec spec/reporters` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2928 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2928 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2911 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2854 | `istanbul cover _mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2487 | `mocha -R spec` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2464 | `npm run build && mocha --require @babel/register` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2462 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2399 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2394 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2370 | `node node_modules/mocha/bin/_mocha` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2365 | `mocha test/**/*.coffee` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2356 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2347 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2600 | `mocha test/src/**/*.unit.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2580 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2579 | `mocha test` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2573 | `mocha test/index.js --reporter dot` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2571 | `mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2568 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2559 | `nyc --require babel-register npm run _mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2540 | `mocha --reporter=spec test/*-test.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 2540 | `mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2536 | `export TESTING=true; mocha --reporter list` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2487 | `mocha -R spec` | 
| [noble/noble](https://github.com/noble/noble) | 2485 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2464 | `npm run build && mocha --require @babel/register` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2462 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2458 | `mocha --no-colors --reporter spec` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1531 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1524 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [trufflesuite/ganache](https://github.com/trufflesuite/ganache) | 1520 | `npm run test-mocha && npm run test-jest` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1458 | `webpack && npm run lint && npm run mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1457 | `mocha test.js` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1450 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1445 | `mocha --check-leaks --reporter spec --bail test/` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1437 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1413 | `mocha --recursive` | 
| [then/promise](https://github.com/then/promise) | 2037 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2036 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 2025 | `mocha test/**/*.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 2011 | `mocha tests.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 2006 | `mocha --reporter spec && npm run test-typescript` | 
| [slate/slate](https://github.com/slate/slate) | 1993 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1979 | `mocha --bail --reporter spec --check-leaks test/` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1978 | `npm run lint && mocha --reporter spec test/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1965 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1963 | `mocha --reporter spec --grep .` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1958 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1957 | `eslint --cache . && tslint --project . && node build && mocha && tsc` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1956 | `mocha test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1942 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1935 | `mocha ./test/test*.js --reporter spec` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1890 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1887 | `mocha tests.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1826 | `mocha test` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1794 | `mocha --timeout 5000` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1781 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1750 | `./node_modules/.bin/mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1742 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1724 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1633 | `./node_modules/mocha/bin/mocha -R spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1623 | `mocha` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1583 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1582 | `mocha --check-leaks --require @babel/register` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1573 | `npm run lint && mocha && karma start --single-run` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1569 | `mocha --recursive test` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1567 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1565 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1564 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1563 | `mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1545 | `standard && nyc _mocha --exit` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1532 | `mocha test/**/*.spec.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1524 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1457 | `mocha test.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1623 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1606 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1583 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1574 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1547 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1546 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1543 | `npm run prepublishOnly && mocha test/test.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1533 | `mocha --timeout 10000 ./tests/lib.js` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1531 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1522 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1569 | `mocha --recursive test` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1567 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1565 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1564 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1563 | `mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1547 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1546 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1545 | `standard && nyc _mocha --exit` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1533 | `mocha --timeout 10000 ./tests/lib.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1532 | `mocha test/**/*.spec.js` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1531 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1524 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1522 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1502 | `mocha --opts test/opts/mocha.opts` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1498 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1646 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1641 | `mocha tests/test.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1638 | `mocha tests/test-*` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1636 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1633 | `./node_modules/mocha/bin/mocha -R spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1625 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1623 | `mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1621 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1606 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1603 | `npm run lint && npm run mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1595 | `nyc mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1533 | `mocha --timeout 10000 ./tests/lib.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1532 | `mocha test/**/*.spec.js` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1531 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1524 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1522 | `mocha --reporter dot` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1522 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1507 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1502 | `mocha --opts test/opts/mocha.opts` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1500 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1498 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [samccone/drool](https://github.com/samccone/drool) | 1463 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1457 | `mocha test.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1455 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1450 | `npm run build && mocha -r should` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1450 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1445 | `mocha --check-leaks --reporter spec --bail test/` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1434 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1433 | `istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1432 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1430 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1424 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1423 | `mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1437 | `mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1434 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1433 | `istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1432 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1430 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1424 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1423 | `mocha --compilers js:babel-core/register` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1413 | `mocha --recursive` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1412 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1406 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1404 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1398 | `npm run lint && mocha --require @babel/register` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1398 | `mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1397 | `NODE_PATH=. mocha **/*.spec.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1393 | `./node_modules/.bin/mocha test` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1390 | `./node_modules/mocha/bin/mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1369 | `mocha --timeout 20000` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1368 | `mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1365 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1363 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1359 | `mocha --timeout 30000 --recursive ./tests` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1357 | `mocha --timeout 60000 test/` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1355 | `mocha` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1347 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1346 | `lerna run test && mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1344 | `npm run lint && npm run mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1343 | `mocha test/*.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1341 | `mocha src/test.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1340 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1339 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1333 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1398 | `npm run lint && mocha --require @babel/register` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1398 | `mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1397 | `NODE_PATH=. mocha **/*.spec.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1393 | `./node_modules/.bin/mocha test` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1390 | `./node_modules/mocha/bin/mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1384 | `mocha tests/` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1381 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1379 | `cross-env NODE_ENV=test nyc mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1372 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1369 | `mocha --timeout 20000` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1368 | `mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1365 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1363 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1359 | `mocha --timeout 30000 --recursive ./tests` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1357 | `mocha --timeout 60000 test/` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1355 | `mocha` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1347 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1346 | `lerna run test && mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1344 | `npm run lint && npm run mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1343 | `mocha test/*.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1341 | `mocha src/test.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1340 | `mocha spec/exec.js` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1339 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1333 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1327 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1326 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1320 | `mocha-phantomjs tests/index.html` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1319 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1307 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1307 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1307 | `mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1297 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1289 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [normalize/mz](https://github.com/normalize/mz) | 1275 | `mocha --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1274 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1272 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1269 | `mocha tests` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1263 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1261 | `mocha` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1234 | `mocha --recursive -r tests/setup tests` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1231 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1223 | `mocha --reporter spec --bail --check-leaks test/` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1222 | `npm-run-all test:jest test:server:mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1219 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1219 | `npm run lint && npm run mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1211 | `mocha test/test.js` | 
| [ulid/javascript](https://github.com/ulid/javascript) | 1200 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha -- -R spec` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1184 | `npm run convertto:es5 && npm run mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1178 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1172 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1236 | `node ./node_modules/mocha/bin/mocha tests` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1234 | `mocha --recursive -r tests/setup tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1224 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1223 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1219 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1219 | `npm run lint && npm run mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1213 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1213 | `mocha test` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1200 | `xo && mocha` | 
| [ulid/javascript](https://github.com/ulid/javascript) | 1200 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha -- -R spec` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1043 | `mocha --recursive test/unit/` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1043 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1035 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1034 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1032 | `mocha --reporter spec --bail --check-leaks test/` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 1031 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1024 | `mocha --reporter spec --timeout 3000` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1021 | `mocha --async-only` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1017 | `mocha --compilers js:babel-register test/*.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1012 | `mocha -R list` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 999 | `mocha "client.test" --compilers js:babel-register` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 995 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 990 | `mocha -t 600000 --exit` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 990 | `mocha` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 988 | `mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 986 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 986 | `./node_modules/.bin/mocha test/**/*` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 985 | `mocha --reporter spec` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1139 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1136 | `mocha test/*` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1129 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1126 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1117 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1111 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1111 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1108 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1103 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1100 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1099 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1024 | `mocha --reporter spec --timeout 3000` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1021 | `mocha --async-only` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1017 | `mocha --compilers js:babel-register test/*.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1012 | `mocha -R list` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 1009 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 995 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 995 | `mocha tests` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 990 | `mocha -t 600000 --exit` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 990 | `mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 989 | `mocha` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 1038 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1036 | `./node_modules/.bin/mocha -R spec` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1035 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1034 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1033 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1032 | `mocha --reporter spec --bail --check-leaks test/` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 1031 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1024 | `mocha --reporter spec --timeout 3000` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1021 | `mocha --async-only` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1017 | `mocha --compilers js:babel-register test/*.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1012 | `mocha -R list` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 832 | `_mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 832 | `mocha && ember test` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 826 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 824 | `mocha index.test.js` | 
| [edsu/anon](https://github.com/edsu/anon) | 820 | `mocha --colors --reporter spec test.js` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 813 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 810 | `mocha test` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 802 | `nyc mocha --exit` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 800 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [befinal/node-tenpay](https://github.com/befinal/node-tenpay) | 469 | `mocha` | 
| [CacheControl/json-rules-engine](https://github.com/CacheControl/json-rules-engine) | 467 | `mocha && npm run lint --silent` | 
| [philbooth/complexity-report](https://github.com/philbooth/complexity-report) | 466 | `./node_modules/mocha/bin/mocha --ui tdd --reporter spec --colors test` | 
| [conventional-changelog-archived-repos/validate-commit-msg](https://github.com/conventional-changelog-archived-repos/validate-commit-msg) | 465 | `istanbul cover -x test/**/*.test.js node_modules/mocha/bin/_mocha -- -R spec test/**/*.test.js` | 
| [evanmoran/oj](https://github.com/evanmoran/oj) | 460 | `mocha --reporter spec test/*.coffee` | 
| [getsentry/raven-node](https://github.com/getsentry/raven-node) | 460 | `NODE_ENV=test istanbul cover _mocha  -- --reporter dot && NODE_ENV=test coffee ./test/run.coffee` | 
| [Kong/httpsnippet](https://github.com/Kong/httpsnippet) | 460 | `mocha --no-timeouts` | 
| [alexcasalboni/aws-lambda-power-tuning](https://github.com/alexcasalboni/aws-lambda-power-tuning) | 459 | `mocha` | 
| [bcoe/thumbd](https://github.com/bcoe/thumbd) | 457 | `nyc mocha` | 
| [mantoni/eslint_d.js](https://github.com/mantoni/eslint_d.js) | 455 | `mocha --file ./node_modules/mocha-referee-sinon` | 
| [zurb/inky](https://github.com/zurb/inky) | 455 | `mocha --compilers js:babel-register` | 
| [fed135/Kalm](https://github.com/fed135/Kalm) | 454 | `mocha tests/unit --recursive && mocha tests/integration` | 
| [xtuc/async-reactor](https://github.com/xtuc/async-reactor) | 447 | `npm run build && mocha --compilers js:babel-register --require jsdom-global/register` | 
| [debitoor/dot-prop-immutable](https://github.com/debitoor/dot-prop-immutable) | 447 | `mocha` | 
| [square/field-kit](https://github.com/square/field-kit) | 446 | `gulp build && karma start --single-run && mocha --harmony -t 600000 test/selenium/index.js` | 
| [Specro/Philter](https://github.com/Specro/Philter) | 446 | `mocha --reporter spec -c` | 
| [macacajs/macaca-cli](https://github.com/macacajs/macaca-cli) | 444 | `nyc --reporter=lcov --reporter=text mocha` | 
| [ajacksified/Mediator.js](https://github.com/ajacksified/Mediator.js) | 444 | `mocha` | 
| [tappleby/redux-batched-subscribe](https://github.com/tappleby/redux-batched-subscribe) | 443 | `mocha --compilers js:babel/register --recursive src/**/*-test.js` | 
| [tmijs/tmi.js](https://github.com/tmijs/tmi.js) | 442 | `istanbul cover node_modules/mocha/bin/_mocha -- --require should --exit` | 
| [tvfe/wxpage](https://github.com/tvfe/wxpage) | 439 | `mocha test/index` | 
| [e-oj/Fawn](https://github.com/e-oj/Fawn) | 439 | `mocha tests/all.tests.js` | 
| [tonyg/js-nacl](https://github.com/tonyg/js-nacl) | 437 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [xuset/planktos](https://github.com/xuset/planktos) | 436 | `npm run -s pre-test && mocha test/testCli.js && karma start` | 
| [yvanwangl/AccountSystem](https://github.com/yvanwangl/AccountSystem) | 436 | `atool-test-mocha ./src/**/*-test.js` | 
| [gulp-community/gulp-cached](https://github.com/gulp-community/gulp-cached) | 436 | `mocha` | 
| [koajs/mount](https://github.com/koajs/mount) | 435 | `NODE_ENV=test mocha --reporter spec` | 
| [coreybutler/node-mac](https://github.com/coreybutler/node-mac) | 432 | `mocha` | 
| [lazd/gulp-replace](https://github.com/lazd/gulp-replace) | 432 | `mocha` | 
| [ngryman/jquery.finger](https://github.com/ngryman/jquery.finger) | 431 | `grunt mocha` | 
| [bencevans/node-sonos](https://github.com/bencevans/node-sonos) | 431 | `npm run lint && mocha test/sonos.test.js --exit --timeout 10000` | 
| [paldepind/union-type](https://github.com/paldepind/union-type) | 431 | `mocha --compilers js:babel/register` | 
| [Mermade/widdershins](https://github.com/Mermade/widdershins) | 431 | `node $nflags node_modules/mocha/bin/_mocha` | 
| [catamphetamine/react-phone-number-input](https://github.com/catamphetamine/react-phone-number-input) | 423 | `mocha --bail --require babel-core/register --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js"` | 
| [braintree/credit-card-type](https://github.com/braintree/credit-card-type) | 422 | `mocha test/**/*.js` | 
| [allegro/node-worker-nodes](https://github.com/allegro/node-worker-nodes) | 421 | `mocha --trace-warnings -r tests/utils/setup.js {lib,tests}/**/*.spec.js` | 
| [mikaelbr/awesome-es2015-proxy](https://github.com/mikaelbr/awesome-es2015-proxy) | 421 | `mocha examples/test-tools/` | 
| [koajs/cors](https://github.com/koajs/cors) | 420 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [gcanti/flow-static-land](https://github.com/gcanti/flow-static-land) | 419 | `mocha --compilers js:babel-register` | 
| [mbrevoort/node-reggie](https://github.com/mbrevoort/node-reggie) | 417 | `mocha` | 
| [pat310/google-trends-api](https://github.com/pat310/google-trends-api) | 417 | `mocha --compilers js:babel-core/register --colors ./test/*.spec.js` | 
| [Meituan-Dianping/koa-restql](https://github.com/Meituan-Dianping/koa-restql) | 429 | `export NODE_ENV=test; export DEBUG=; ./node_modules/.bin/mocha --reporter spec --harmony --bail --no-timeouts` | 
| [yury-dymov/json-api-normalizer](https://github.com/yury-dymov/json-api-normalizer) | 428 | `cross-env mocha --compilers js:@babel/register` | 
| [se-panfilov/vue-notifications](https://github.com/se-panfilov/vue-notifications) | 428 | `cross-env BABEL_ENV=test && mocha --compilers js:babel-core/register ./test/**/*.spec.js` | 
| [philholden/subdivide](https://github.com/philholden/subdivide) | 428 | `npm run test:mocha` | 
| [vstirbu/fsm-as-promised](https://github.com/vstirbu/fsm-as-promised) | 428 | `mocha` | 
| [tedeh/jayson](https://github.com/tedeh/jayson) | 427 | `mocha` | 
| [Azure/azure-rest-api-specs](https://github.com/Azure/azure-rest-api-specs) | 427 | `mocha -t 500000 --reporter min` | 
| [alexguan/node-zookeeper-client](https://github.com/alexguan/node-zookeeper-client) | 427 | `mocha --recursive --reporter spec test/*` | 
| [AdamBrodzinski/RedScript](https://github.com/AdamBrodzinski/RedScript) | 426 | `mocha -R spec` | 
| [dthree/wat](https://github.com/dthree/wat) | 426 | `./node_modules/istanbul/lib/cli.js cover -x '**/**/markterm.js' _mocha -- -R spec` | 
| [randylien/generator-react-gulp-browserify](https://github.com/randylien/generator-react-gulp-browserify) | 425 | `mocha` | 
| [LucyBot-Inc/api-spec-converter](https://github.com/LucyBot-Inc/api-spec-converter) | 425 | `mocha && npm run browserify && karma start --single-run && git checkout -- dist` | 
| [GitbookIO/gitbook-cli](https://github.com/GitbookIO/gitbook-cli) | 424 | `mocha --reporter spec --recursive --bail` | 
| [trailsjs/sails-permissions](https://github.com/trailsjs/sails-permissions) | 423 | `gulp && mocha --reporter spec --compilers js:babel/register` | 
| [catamphetamine/react-phone-number-input](https://github.com/catamphetamine/react-phone-number-input) | 423 | `mocha --bail --require babel-core/register --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js"` | 
| [googlearchive/node-big-rig](https://github.com/googlearchive/node-big-rig) | 423 | `eslint . && mocha test/*.js --timeout 60000` | 
| [functionscope/Node-Excel-Export](https://github.com/functionscope/Node-Excel-Export) | 422 | `mocha test/main` | 
| [braintree/credit-card-type](https://github.com/braintree/credit-card-type) | 422 | `mocha test/**/*.js` | 
| [allegro/node-worker-nodes](https://github.com/allegro/node-worker-nodes) | 421 | `mocha --trace-warnings -r tests/utils/setup.js {lib,tests}/**/*.spec.js` | 
| [holidayextras/jsonapi-server](https://github.com/holidayextras/jsonapi-server) | 421 | `nyc mocha` | 
| [lbdremy/solr-node-client](https://github.com/lbdremy/solr-node-client) | 421 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js && ./node_modules/mocha/bin/mocha -R spec test/*-test.js --client.bigint=true` | 
| [hulkholden/n64js](https://github.com/hulkholden/n64js) | 421 | `mocha --compilers js:babel-core/register --recursive` | 
| [mikaelbr/awesome-es2015-proxy](https://github.com/mikaelbr/awesome-es2015-proxy) | 421 | `mocha examples/test-tools/` | 
| [koajs/cors](https://github.com/koajs/cors) | 420 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [gcanti/flow-static-land](https://github.com/gcanti/flow-static-land) | 419 | `mocha --compilers js:babel-register` | 
| [DrBoolean/pointfree-fantasy](https://github.com/DrBoolean/pointfree-fantasy) | 419 | `mocha test` | 
| [pcardune/handlebars-loader](https://github.com/pcardune/handlebars-loader) | 417 | `mocha` | 
| [mbrevoort/node-reggie](https://github.com/mbrevoort/node-reggie) | 417 | `mocha` | 
| [pat310/google-trends-api](https://github.com/pat310/google-trends-api) | 417 | `mocha --compilers js:babel-core/register --colors ./test/*.spec.js` | 
| [smysnk/gulp-rev-all](https://github.com/smysnk/gulp-rev-all) | 416 | `mocha test.js` | 
| [JakeSidSmith/react-fastclick](https://github.com/JakeSidSmith/react-fastclick) | 415 | `npm run lint-src && npm run lint-tests && npm run mocha` | 
| [dora-js/dora](https://github.com/dora-js/dora) | 415 | `babel-node $(npm bin)/babel-istanbul cover $(npm bin)/_mocha -- --no-timeouts` | 
| [algolia/expect-jsx](https://github.com/algolia/expect-jsx) | 415 | `mocha --opts mocha.opts && eslint .` | 
| [jviotti/queryl](https://github.com/jviotti/queryl) | 415 | `nyc --reporter=lcov mocha tests && stryker run` | 
| [erikras/multireducer](https://github.com/erikras/multireducer) | 414 | `npm run lint && mocha --compilers js:babel-core/register --recursive` | 
| [jaywcjlove/validator.js](https://github.com/jaywcjlove/validator.js) | 414 | `mocha --require @babel/register --reporter dot` | 
| [fex-team/alogs](https://github.com/fex-team/alogs) | 414 | `mocha-phantomjs test/test.html -s webSecurityEnabled=false` | 
| [olahol/react-ab](https://github.com/olahol/react-ab) | 406 | `./node_modules/.bin/mocha` | 
| [mklabs/tiny-lr](https://github.com/mklabs/tiny-lr) | 406 | `npm run eslint && npm run mocha` | 
| [CrowdHailer/fn.js](https://github.com/CrowdHailer/fn.js) | 406 | `mocha ./tests` | 
| [acuminous/yadda](https://github.com/acuminous/yadda) | 405 | `mocha` | 
| [mtkopone/zelect](https://github.com/mtkopone/zelect) | 404 | `./node_modules/.bin/mocha-phantomjs ./test.html` | 
| [flipxfx/download-git-repo](https://github.com/flipxfx/download-git-repo) | 401 | `mocha` | 
| [gajus/contents](https://github.com/gajus/contents) | 401 | `mocha --require @babel/register` | 
| [tscanlin/tocbot](https://github.com/tscanlin/tocbot) | 400 | `npm run lint && mocha test/index.js` | 
| [flipxfx/download-git-repo](https://github.com/flipxfx/download-git-repo) | 401 | `mocha` | 
| [gajus/contents](https://github.com/gajus/contents) | 401 | `mocha --require @babel/register` | 
| [tscanlin/tocbot](https://github.com/tscanlin/tocbot) | 400 | `npm run lint && mocha test/index.js` | 
| [couchbase/couchnode](https://github.com/couchbase/couchnode) | 399 | `mocha` | 
| [rzimmerman/kal](https://github.com/rzimmerman/kal) | 399 | `node_modules/mocha/bin/mocha -r should -R spec tests/* --compilers kal:compiled/kal` | 
| [dfilatov/vidom](https://github.com/dfilatov/vidom) | 399 | `browserify spec/boot.js -t babelify -o spec/boot.build.js && phantomjs ./node_modules/mocha-phantomjs-core/mocha-phantomjs-core.js spec/runner.html spec "{\"useColors\":true}"` | 
| [PrismarineJS/node-minecraft-protocol](https://github.com/PrismarineJS/node-minecraft-protocol) | 398 | `mocha --recursive --reporter spec` | 
| [lincolnloop/amygdala](https://github.com/lincolnloop/amygdala) | 398 | `mocha --reporter spec --ui bdd` | 
| [RisingStack/graffiti-mongoose](https://github.com/RisingStack/graffiti-mongoose) | 398 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [FormidableLabs/spectacle-editor](https://github.com/FormidableLabs/spectacle-editor) | 398 | `cross-env NODE_ENV=test mocha --recursive --compilers js:babel-register --require ./test/setup.js "test/**/*.spec.js"` | 
| [gajus/contents](https://github.com/gajus/contents) | 401 | `mocha --require @babel/register` | 
| [flipxfx/download-git-repo](https://github.com/flipxfx/download-git-repo) | 401 | `mocha` | 
| [tscanlin/tocbot](https://github.com/tscanlin/tocbot) | 400 | `npm run lint && mocha test/index.js` | 
| [couchbase/couchnode](https://github.com/couchbase/couchnode) | 399 | `mocha` | 
| [dfilatov/vidom](https://github.com/dfilatov/vidom) | 399 | `browserify spec/boot.js -t babelify -o spec/boot.build.js && phantomjs ./node_modules/mocha-phantomjs-core/mocha-phantomjs-core.js spec/runner.html spec "{\"useColors\":true}"` | 
| [rzimmerman/kal](https://github.com/rzimmerman/kal) | 399 | `node_modules/mocha/bin/mocha -r should -R spec tests/* --compilers kal:compiled/kal` | 
| [PrismarineJS/node-minecraft-protocol](https://github.com/PrismarineJS/node-minecraft-protocol) | 398 | `mocha --recursive --reporter spec` | 
| [lincolnloop/amygdala](https://github.com/lincolnloop/amygdala) | 398 | `mocha --reporter spec --ui bdd` | 
| [RisingStack/graffiti-mongoose](https://github.com/RisingStack/graffiti-mongoose) | 398 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [FormidableLabs/spectacle-editor](https://github.com/FormidableLabs/spectacle-editor) | 398 | `cross-env NODE_ENV=test mocha --recursive --compilers js:babel-register --require ./test/setup.js "test/**/*.spec.js"` | 
| [OpenBookPrices/country-data](https://github.com/OpenBookPrices/country-data) | 396 | `mocha` | 
| [jamesknelson/gulp-rev-replace](https://github.com/jamesknelson/gulp-rev-replace) | 396 | `mocha` | 
| [PhilWaldmann/openrecord](https://github.com/PhilWaldmann/openrecord) | 396 | `npm run lint && npm run mocha -- --bail` | 
| [rewonc/pastalog](https://github.com/rewonc/pastalog) | 396 | `mocha test/build/index.js --debug` | 
| [pazguille/aload](https://github.com/pazguille/aload) | 395 | `npm run build && NODE_ENV=test istanbul cover _mocha -- ./test/*.spec.js` | 
| [couchbase/couchnode](https://github.com/couchbase/couchnode) | 399 | `mocha` | 
| [dfilatov/vidom](https://github.com/dfilatov/vidom) | 399 | `browserify spec/boot.js -t babelify -o spec/boot.build.js && phantomjs ./node_modules/mocha-phantomjs-core/mocha-phantomjs-core.js spec/runner.html spec "{\"useColors\":true}"` | 
| [rzimmerman/kal](https://github.com/rzimmerman/kal) | 399 | `node_modules/mocha/bin/mocha -r should -R spec tests/* --compilers kal:compiled/kal` | 
| [PrismarineJS/node-minecraft-protocol](https://github.com/PrismarineJS/node-minecraft-protocol) | 398 | `mocha --recursive --reporter spec` | 
| [lincolnloop/amygdala](https://github.com/lincolnloop/amygdala) | 398 | `mocha --reporter spec --ui bdd` | 
| [RisingStack/graffiti-mongoose](https://github.com/RisingStack/graffiti-mongoose) | 398 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [FormidableLabs/spectacle-editor](https://github.com/FormidableLabs/spectacle-editor) | 398 | `cross-env NODE_ENV=test mocha --recursive --compilers js:babel-register --require ./test/setup.js "test/**/*.spec.js"` | 
| [OpenBookPrices/country-data](https://github.com/OpenBookPrices/country-data) | 396 | `mocha` | 
| [jamesknelson/gulp-rev-replace](https://github.com/jamesknelson/gulp-rev-replace) | 396 | `mocha` | 
| [PhilWaldmann/openrecord](https://github.com/PhilWaldmann/openrecord) | 396 | `npm run lint && npm run mocha -- --bail` | 
| [rewonc/pastalog](https://github.com/rewonc/pastalog) | 396 | `mocha test/build/index.js --debug` | 
| [pazguille/aload](https://github.com/pazguille/aload) | 395 | `npm run build && NODE_ENV=test istanbul cover _mocha -- ./test/*.spec.js` | 
| [chill117/proxy-lists](https://github.com/chill117/proxy-lists) | 395 | `mocha test/unit/ --recursive --reporter spec --ui bdd` | 