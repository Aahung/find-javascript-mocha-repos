# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:09 12/13/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44589 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41808 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41462 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30687 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 25015 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24513 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21020 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19816 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18094 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17680 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17535 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16589 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14786 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14642 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14599 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13753 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13409 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12919 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12665 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12581 | `istanbul cover _mocha` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12486 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12330 | `mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12120 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12097 | `nyc grunt mocha-and-karma` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12049 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11233 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10912 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10739 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10707 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10488 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10329 | `mocha --harmony` | 
| [websockets/ws](https://github.com/websockets/ws) | 10193 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9617 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9570 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9437 | `mocha tests/*.js` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9382 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9212 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 9206 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9193 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8775 | `mocha test/src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6480 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6341 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6184 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6173 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6084 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6039 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6019 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5936 | `mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5637 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5626 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5520 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5416 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [dthree/cash](https://github.com/dthree/cash) | 7581 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7551 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7459 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7385 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7305 | `mocha; jshint *.js lib` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7305 | `mocha` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7281 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7184 | `mocha --exit --require @babel/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7068 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7023 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6863 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6674 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6598 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6184 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6173 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6106 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6084 | `mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6033 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6019 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5936 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5832 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5814 | `standard && mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5637 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5626 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5561 | `npm run lint && mocha tests/*/*/*.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5520 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4848 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4825 | `mocha -R spec 'tests/app'` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4817 | `./node_modules/.bin/mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4814 | `mocha test` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4792 | `nyc mocha --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4783 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4753 | `npm run lint && npm run mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4706 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4670 | `nyc mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4637 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4573 | `mocha ./test/runner.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4544 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4521 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4476 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4470 | `mocha -R spec src` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4424 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5137 | `mocha --color` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5103 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5090 | `gulp lint && mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 4935 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4907 | `gulp build; mocha;` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4902 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4897 | `mocha --recursive` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4848 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4825 | `mocha -R spec 'tests/app'` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4817 | `./node_modules/.bin/mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4814 | `mocha test` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4792 | `nyc mocha --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4783 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4753 | `npm run lint && npm run mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4728 | `mocha --reporter spec -t 8000` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4706 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4670 | `nyc mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4637 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4573 | `mocha ./test/runner.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4544 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4521 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4476 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4470 | `mocha -R spec src` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4424 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4358 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4327 | `mocha --timeout=15000 tests/*.test.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4275 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4238 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4224 | `nyc mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4210 | `mocha --check-leaks --reporter spec --bail` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4203 | `mocha -R spec ./test --recursive` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4192 | `npm run lint ; mocha && mocha test/individual` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4140 | `NODE_ENV=test mocha --exit` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4093 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4067 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4040 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3976 | `nyc mocha "test/**/*.test.js"` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3924 | `export TESTING=true; mocha --reporter list` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3901 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3884 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3864 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3822 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3809 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3794 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3781 | `NODE_ENV=test mocha test/**/*.js` | 
| [primus/primus](https://github.com/primus/primus) | 3769 | `npm run build && mocha test/*.test.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3707 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3683 | `standard && mocha --timeout 60000 test/test.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3678 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3670 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3667 | `npm run jshint && npm run mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3573 | `mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3554 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3479 | `node_modules/.bin/mocha test/lib/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3470 | `nyc mocha && tsc` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3458 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3452 | `mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3425 | `eslint . && mocha -t 5000` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3409 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3396 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3357 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3332 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3315 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3309 | `mocha && tsc -p ./test/types` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3279 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3274 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3267 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3261 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3223 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3212 | `mocha test/*.js` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3212 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3173 | `./node_modules/.bin/mocha test/test.*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3165 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3161 | `mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3158 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3153 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3212 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3203 | `mocha -R landing test/index --exit` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3192 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3173 | `./node_modules/.bin/mocha test/test.*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3165 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3161 | `mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3158 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3153 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3129 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3123 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3058 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3046 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3045 | `eslint . && nyc mocha --recursive` | 
| [mde/ejs](https://github.com/mde/ejs) | 3040 | `mocha --require should --reporter spec` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3026 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2628 | `mocha-phantomjs ./test/index.html` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2616 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2613 | `mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2587 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2556 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2526 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2517 | `mocha test/src/**/*.unit.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2502 | `mocha --reporter=spec test/*-test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2490 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2444 | `mocha --no-colors --reporter spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2430 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2422 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2541 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2526 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2517 | `mocha test/src/**/*.unit.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2487 | `mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2465 | `mocha && eslint .` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2444 | `mocha --no-colors --reporter spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2435 | `mocha test/index.js --reporter dot` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2430 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2422 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2419 | `mocha -R spec` | 
| [Qix-/color](https://github.com/Qix-/color) | 2390 | `mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2374 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2372 | `node node_modules/mocha/bin/_mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2502 | `mocha --reporter=spec test/*-test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2490 | `nyc --reporter=html --reporter=text mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2487 | `mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2466 | `mocha test --exit && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2465 | `mocha && eslint .` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2444 | `mocha --no-colors --reporter spec` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2435 | `mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2430 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2422 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2419 | `mocha -R spec` | 
| [Qix-/color](https://github.com/Qix-/color) | 2390 | `mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2372 | `node node_modules/mocha/bin/_mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 2184 | `npm run lint && npm run mocha` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2154 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2154 | `mocha test/runner.js --reporter spec` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2142 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2139 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2136 | `mocha` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2124 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 2094 | `./node_modules/.bin/mocha && npm run jshint` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2087 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2044 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2372 | `node node_modules/mocha/bin/_mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2362 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2351 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2330 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2330 | `npm run build && mocha --require babel-register` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2316 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2316 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2315 | `nyc --require babel-register npm run _mocha` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2297 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [gajus/swing](https://github.com/gajus/swing) | 2284 | `mocha --compilers js:babel-register` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2271 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2241 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2234 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2217 | `mocha test test/unit/**/*_test.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2208 | `standard && mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2204 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2201 | `npm run lint && mocha tests/*/*/*.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2184 | `npm run lint && npm run mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2177 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2174 | `cross-env BABEL_ENV=test mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2149 | `mocha && eslint *.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2148 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2142 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2139 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2136 | `mocha` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2124 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2098 | `mocha --compilers js:babel-core/register __tests__` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 2094 | `./node_modules/.bin/mocha && npm run jshint` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2087 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2044 | `mocha --compilers js:babel-register` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2044 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2027 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2010 | `npm run lint && mocha -R dot && npm run cover` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2001 | `npm run mocha && npm run karma` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2001 | `mocha --reporter spec --timeout 5000` | 
| [slate/slate](https://github.com/slate/slate) | 1996 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1994 | `mocha --require=test/test_helper.js` | 
| [then/promise](https://github.com/then/promise) | 1980 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1963 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1955 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1953 | `mocha --require ./test/common --growl test/expect.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1952 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1948 | `mocha && npm run lint` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1851 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1830 | `mocha compiled_tests/` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1827 | `npm run lint && npm run mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1820 | `mocha test` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1794 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1772 | `npm run lint && npm run mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1765 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1765 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1756 | `mocha test/setup.js test/spec/*.js` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1830 | `mocha compiled_tests/` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1828 | `mocha ./test/basic.js -t 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1827 | `npm run lint && npm run mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1820 | `mocha test` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1798 | `mocha --timeout 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1794 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1772 | `npm run lint && npm run mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1765 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1765 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1756 | `mocha test/setup.js test/spec/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1747 | `eslint --cache . && tsc && mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1747 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1798 | `mocha --timeout 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1794 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1772 | `npm run lint && npm run mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1765 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1765 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1756 | `mocha test/setup.js test/spec/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1747 | `eslint --cache . && tsc && mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1747 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1735 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1732 | `./node_modules/.bin/mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1731 | `npm run lint && mocha && npm run typescript` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1730 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1292 | `npm run mocha:istanbul` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1290 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1286 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1273 | `mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1269 | `mocha tests/` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1268 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1265 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1253 | `mocha` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1250 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1248 | `mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1245 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1243 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1239 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1236 | `mocha --timeout 30000 --recursive ./tests` | 
| [normalize/mz](https://github.com/normalize/mz) | 1233 | `mocha --reporter spec` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1221 | `mocha --timeout 20000` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1219 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1217 | `node ./node_modules/mocha/bin/mocha tests` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1209 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1564 | `NODE_ENV=test mocha tests/*.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1562 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1561 | `nyc mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1547 | `npm run test:lint && npm run test:mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1540 | `mocha ./test/test*.js --reporter spec` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1535 | `mocha test/unit` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1534 | `node_modules/.bin/mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1530 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1530 | `mocha -u tdd` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1526 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1601 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1597 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1595 | `./node_modules/mocha/bin/mocha -R spec` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1594 | `mocha test.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1587 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1569 | `mocha --recursive` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1564 | `NODE_ENV=test mocha tests/*.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1562 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1561 | `nyc mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1553 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [router5/router5](https://github.com/router5/router5) | 1254 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1236 | `mocha --timeout 30000 --recursive ./tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1229 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1221 | `mocha --timeout 20000` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1219 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1213 | `mocha test/test.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1209 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1204 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1184 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1183 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1179 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1173 | `mocha --recursive -r tests/setup tests` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1170 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1164 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1162 | `xo && mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1161 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1160 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1159 | `mocha $(find test -name '*.test.js') --exit` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1153 | `mocha --reporter spec --bail --check-leaks test/` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1148 | `istanbul cover _mocha test/*.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1148 | `npm-run-all test:jest test:server:mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1146 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1144 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1139 | `mocha --reporter spec --bail --check-leaks test/` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1136 | `mocha` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1134 | `webpack && mocha test/unit` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1124 | `mocha test/*` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1123 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1116 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1115 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [electron/spectron](https://github.com/electron/spectron) | 1112 | `mocha && standard` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1112 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1110 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 1064 | `npm run build && mocha test/bootstrap.js --recursive test` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1059 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1053 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1048 | `mocha --async-only` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1039 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1038 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1031 | `mocha --reporter spec --timeout 3000` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1078 | `eslint src test && mocha --compilers babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1078 | `mocha test/tests.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1077 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1076 | `mocha` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 1064 | `npm run build && mocha test/bootstrap.js --recursive test` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1059 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [tomas/needle](https://github.com/tomas/needle) | 1055 | `mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1053 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1048 | `mocha --async-only` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1039 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1038 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1031 | `mocha --reporter spec --timeout 3000` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1026 | `mocha --recursive test/unit/` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1024 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1014 | `mocha --colors ./test/*.spec.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1014 | `mocha --colors ./test/*.spec.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1002 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1001 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 999 | `mocha -R list` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 998 | `mocha --reporter spec --bail --check-leaks test/` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 996 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 989 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 987 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 963 | `mocha spec/*.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 957 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 952 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 951 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 948 | `mocha` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 947 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 944 | `mocha -t 600000` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 943 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 941 | `mocha --timeout 5000` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 940 | `./node_modules/.bin/mocha -R spec` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 957 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 953 | `./node_modules/.bin/mocha --reporter spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 952 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 952 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 951 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 948 | `mocha` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 947 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 944 | `mocha -t 600000` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 943 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 941 | `mocha --timeout 5000` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 940 | `./node_modules/.bin/mocha -R spec` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 939 | `mocha test` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 937 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 931 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 931 | `npm run lint && npm run mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 931 | `mocha` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 930 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 929 | `nyc mocha specs` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 929 | `mocha test --compilers js:babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 923 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 922 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 920 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 919 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 918 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 835 | `mocha --opts mocha.opts` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 834 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 829 | `mocha -r babel-register --check-leaks test/index.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 829 | `mocha && ember test` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 825 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 820 | `mocha test` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 819 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 818 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 818 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 817 | `mocha --harmony tests/**` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 812 | `npm run mocha-test test/integration` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 812 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [edsu/anon](https://github.com/edsu/anon) | 811 | `mocha --colors --reporter spec test.js` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 811 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 806 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 805 | `_mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 805 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 804 | `mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 798 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 797 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 795 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 794 | `xo && mocha -R spec` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 792 | `mocha -u tdd` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 788 | `npm run lint && mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 782 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 782 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 779 | `mocha test` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 778 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 777 | `npm run lint && npm run mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 776 | `mocha --recursive -s 15 test/` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 776 | `mocha tests --timeout 10000` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 775 | `nyc mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 772 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 772 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 772 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 771 | `mocha -R spec src/**/*_test.js` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 777 | `npm run lint && npm run mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 776 | `mocha --recursive -s 15 test/` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 776 | `mocha tests --timeout 10000` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 775 | `nyc mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 772 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 772 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 772 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 771 | `mocha -R spec src/**/*_test.js` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 769 | `mocha test/mocha.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 767 | `babel-node node_modules/.bin/_mocha -- test` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 761 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 760 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 760 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 758 | `npm run-script jshint && npm run-script mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 755 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [susam/texme](https://github.com/susam/texme) | 754 | `standard && mocha` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 753 | `mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 752 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 751 | `./bin/selenium-standalone install && mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 750 | `mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 750 | `mocha --reporter spec build/test/index.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 750 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 749 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 748 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 749 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 748 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 748 | `mocha tests/*.mocha.js` | 
| [koajs/static](https://github.com/koajs/static) | 746 | `mocha --harmony --reporter spec --exit` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 745 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 745 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 744 | `mocha` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 742 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 742 | `mocha test.js` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 741 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 740 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 736 | `npm run bundle && mocha` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 731 | `npm run test-mocha && npm run test-karma` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 730 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 729 | `mocha` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 728 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 727 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 726 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 722 | `mocha $(find test -name '*.test.js')` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 722 | `mocha --reporter spec --bail --check-leaks test/` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 720 | `mocha ./test/test.js --timeout 1000000` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 718 | `eslint . && mocha` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 717 | `mocha --reporter spec test/` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 722 | `mocha $(find test -name '*.test.js')` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 722 | `mocha --reporter spec --bail --check-leaks test/` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 720 | `mocha ./test/test.js --timeout 1000000` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 718 | `eslint . && mocha` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 717 | `mocha --reporter spec test/` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 714 | `mocha --compilers js:babel-core/register` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 708 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 707 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [node-cron/node-cron](https://github.com/node-cron/node-cron) | 703 | `nyc --reporter=html --reporter=text mocha --recursive` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 699 | `mocha --reporter spec` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 697 | `mocha` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 697 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 696 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 696 | `mocha --reporter spec` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [electron/apps](https://github.com/electron/apps) | 624 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [rkusa/koa-passport](https://github.com/rkusa/koa-passport) | 623 | `mocha` | 
| [edankwan/penis.js](https://github.com/edankwan/penis.js) | 621 | `mocha --ui bdd --reporter spec test/` | 
| [gauntface/simple-push-demo](https://github.com/gauntface/simple-push-demo) | 620 | `gulp && npm run lint && node ./test/helpers/download-browsers.js && mocha` | 
| [shelljs/shx](https://github.com/shelljs/shx) | 620 | `nyc --reporter=text --reporter=lcov mocha` | 
| [robwierzbowski/generator-jekyllrb](https://github.com/robwierzbowski/generator-jekyllrb) | 619 | `mocha` | 
| [blueberryapps/react-bluekit](https://github.com/blueberryapps/react-bluekit) | 618 | `mocha --compilers js:babel/register --recursive` | 
| [azmenak/react-stripe-checkout](https://github.com/azmenak/react-stripe-checkout) | 615 | `mocha --require babel-register --require .test-setup.js -R spec ./spec.js` | 
| [werk85/node-html-to-text](https://github.com/werk85/node-html-to-text) | 614 | `istanbul cover _mocha && eslint .` | 
| [Munter/subfont](https://github.com/Munter/subfont) | 613 | `npm run lint && mocha` | 
| [backstrokeapp/server](https://github.com/backstrokeapp/server) | 612 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [ideal-postcodes/postcodes.io](https://github.com/ideal-postcodes/postcodes.io) | 611 | `NODE_ENV=test npm run test:create && npm run nyc_mocha && NODE_ENV=test npm run test:clear && npm run lint` | 
| [jfromaniello/passport.socketio](https://github.com/jfromaniello/passport.socketio) | 608 | `mocha` | 
| [cgross/generator-cg-angular](https://github.com/cgross/generator-cg-angular) | 608 | `mocha` | 
| [jovotech/jovo-framework-nodejs](https://github.com/jovotech/jovo-framework-nodejs) | 607 | `mocha test --recursive` | 
| [anandanand84/technicalindicators](https://github.com/anandanand84/technicalindicators) | 607 | `mocha --compilers js:babel-register --require babel-polyfill` | 
| [victorb/autochecker](https://github.com/victorb/autochecker) | 606 | `mocha` | 
| [shinnn/gulp-gh-pages](https://github.com/shinnn/gulp-gh-pages) | 606 | `nyc mocha test.js --timeout 50000 --full-trace` | 
| [macbre/analyze-css](https://github.com/macbre/analyze-css) | 605 | `mocha -R spec` | 
| [kwhitley/apicache](https://github.com/kwhitley/apicache) | 634 | `nyc mocha $(find test -name '*.test.js') --recursive` | 
| [pocketjoso/specificity-graph](https://github.com/pocketjoso/specificity-graph) | 630 | `node_modules/.bin/mocha test` | 
| [stevenvachon/broken-link-checker](https://github.com/stevenvachon/broken-link-checker) | 630 | `mocha test/ --reporter spec --check-leaks --bail` | 
| [docpress/docpress](https://github.com/docpress/docpress) | 630 | `nyc mocha` | 
| [danielstjules/buddy.js](https://github.com/danielstjules/buddy.js) | 629 | `mocha -R spec spec/unit spec/integration` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 627 | `nyc mocha test.js` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 625 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [electron/apps](https://github.com/electron/apps) | 624 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [rkusa/koa-passport](https://github.com/rkusa/koa-passport) | 623 | `mocha` | 
| [mysamai/mysam](https://github.com/mysamai/mysam) | 623 | `npm run lint && npm run mocha` | 
| [edankwan/penis.js](https://github.com/edankwan/penis.js) | 621 | `mocha --ui bdd --reporter spec test/` | 
| [jaredhanson/passport-google-oauth](https://github.com/jaredhanson/passport-google-oauth) | 621 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [gauntface/simple-push-demo](https://github.com/gauntface/simple-push-demo) | 620 | `gulp && npm run lint && node ./test/helpers/download-browsers.js && mocha` | 