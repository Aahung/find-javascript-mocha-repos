# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:35 12/18/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44634 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41826 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41529 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30701 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 25481 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25028 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24570 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21050 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19847 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17719 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17567 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16689 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14827 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14609 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13772 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13439 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12932 | `mocha 'test/**/*.spec.js'` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12932 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12678 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12601 | `istanbul cover _mocha` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12591 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12328 | `mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12151 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12111 | `nyc grunt mocha-and-karma` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12092 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11260 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10940 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10779 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10718 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9633 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9591 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9385 | `mocha -b -r esm` | 
| [amark/gun](https://github.com/amark/gun) | 9227 | `mocha` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8787 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8636 | `mocha test/test.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8636 | `mocha --opts mocha.opts` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8535 | `mocha --check-leaks -R dot` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8450 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8416 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8397 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8359 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8197 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8010 | `npm run eslint && npm run mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8636 | `mocha test/test.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8636 | `mocha --opts mocha.opts` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8535 | `mocha --check-leaks -R dot` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8450 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8416 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8397 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8359 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8197 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8010 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7924 | `./node_modules/.bin/mocha test` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7821 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7819 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7738 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7727 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7720 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [dthree/cash](https://github.com/dthree/cash) | 7583 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7555 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7459 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7397 | `mocha --compilers js:babel-core/register` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7357 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7333 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7295 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7217 | `mocha --exit --require @babel/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7071 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7038 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6876 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6690 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6619 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5135 | `mocha --color` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5116 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5091 | `gulp lint && mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 4983 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4907 | `gulp build; mocha;` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4904 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4852 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4825 | `./node_modules/.bin/mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4792 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4765 | `npm run lint && npm run mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4709 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5835 | `standard && mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5646 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5632 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5560 | `npm run lint && mocha tests/*/*/*.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5545 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5426 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5413 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5412 | `mocha` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5283 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5272 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5264 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5225 | `mocha test` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5201 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5135 | `mocha --color` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5116 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5091 | `gulp lint && mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 4983 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4929 | `mocha --recursive` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4907 | `gulp build; mocha;` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4904 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4852 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4828 | `mocha -R spec 'tests/app'` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4825 | `./node_modules/.bin/mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4820 | `mocha test` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4809 | `nyc mocha --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4792 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4765 | `npm run lint && npm run mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4729 | `mocha --reporter spec -t 8000` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4720 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4709 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4685 | `nyc mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4570 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4526 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4476 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4476 | `mocha -R spec src` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4456 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4360 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4338 | `mocha --timeout=15000 tests/*.test.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4287 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4241 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4227 | `nyc mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4218 | `mocha --check-leaks --reporter spec --bail` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4201 | `mocha -R spec ./test --recursive` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4197 | `npm run lint ; mocha && mocha test/individual` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4169 | `NODE_ENV=test mocha --exit` | 
| [muicss/mui](https://github.com/muicss/mui) | 4111 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4094 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4070 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4049 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3982 | `nyc mocha "test/**/*.test.js"` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3925 | `export TESTING=true; mocha --reporter list` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3919 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3897 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3863 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3839 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3809 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3793 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3787 | `NODE_ENV=test mocha test/**/*.js` | 
| [primus/primus](https://github.com/primus/primus) | 3774 | `npm run build && mocha test/*.test.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3712 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3687 | `mocha test/* --reporter spec` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3682 | `standard && mocha --timeout 60000 test/test.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3676 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3652 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3627 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3627 | `node_modules/.bin/mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3597 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3575 | `mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3574 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3567 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3556 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3523 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3481 | `nyc mocha && tsc` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3479 | `node_modules/.bin/mocha test/lib/` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3462 | `eslint . && mocha -t 5000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3458 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3451 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3411 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3403 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3360 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace) | 3346 | `mocha` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3346 | `mocha && tsc -p ./test/types` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3343 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 3334 | `npm run build && mocha test/bootstrap.js --recursive test` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3319 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3316 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3288 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3284 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3279 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3273 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3269 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3247 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3230 | `mocha test/index.js && npm run demo` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3064 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [mde/ejs](https://github.com/mde/ejs) | 3055 | `mocha --require should --reporter spec` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3049 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3037 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2990 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2978 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2955 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2948 | `node_modules/.bin/mocha --reporter spec` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2948 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2939 | `mocha` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2926 | `mocha test-node` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2924 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2919 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2917 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2914 | `mocha --require @babel/register --recursive spec` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2910 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2904 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2373 | `node node_modules/mocha/bin/_mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2365 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2355 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2342 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2330 | `nyc --require babel-register npm run _mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2314 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [gajus/swing](https://github.com/gajus/swing) | 2285 | `mocha --compilers js:babel-register` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2242 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2234 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2593 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2588 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2561 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2527 | `mocha test` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2505 | `mocha --reporter=spec test/*-test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2491 | `nyc --reporter=html --reporter=text mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2490 | `mocha test --exit && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2469 | `mocha && eslint .` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2452 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2445 | `mocha --no-colors --reporter spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2440 | `mocha test/index.js --reporter dot` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2452 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2440 | `mocha test/index.js --reporter dot` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2424 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2420 | `mocha -R spec` | 
| [Qix-/color](https://github.com/Qix-/color) | 2392 | `mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2375 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2373 | `node node_modules/mocha/bin/_mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2365 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2355 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2342 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2332 | `npm run build && mocha --require babel-register` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2331 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2330 | `nyc --require babel-register npm run _mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2373 | `node node_modules/mocha/bin/_mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2365 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2355 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2342 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2332 | `npm run build && mocha --require babel-register` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2331 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2298 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [gajus/swing](https://github.com/gajus/swing) | 2285 | `mocha --compilers js:babel-register` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2281 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2298 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [gajus/swing](https://github.com/gajus/swing) | 2285 | `mocha --compilers js:babel-register` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2281 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2242 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2234 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2218 | `mocha test test/unit/**/*_test.js` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2215 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2210 | `standard && mocha` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2203 | `npm run lint && mocha tests/*/*/*.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2192 | `npm run lint && npm run mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2186 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2175 | `cross-env BABEL_ENV=test mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2158 | `mocha test/runner.js --reporter spec` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2156 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2154 | `mocha && eslint *.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2154 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2152 | `mocha test/**/*.coffee` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2141 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2139 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2137 | `mocha` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2124 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2105 | `mocha --compilers js:babel-core/register __tests__` | 
| [share/sharedb](https://github.com/share/sharedb) | 2097 | `./node_modules/.bin/mocha && npm run jshint` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2013 | `npm run lint && mocha -R dot && npm run cover` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2004 | `npm run mocha && npm run karma` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2004 | `mocha --reporter spec --timeout 5000` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1981 | `mocha tests --require @babel/register` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1963 | `mocha -c test/index.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1956 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1955 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1953 | `mocha --require ./test/common --growl test/expect.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1942 | `mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1920 | `mocha test/**/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1920 | `mocha --reporter spec && npm run test-typescript` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1918 | `bmocha --reporter spec test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1892 | `npm run lint && mocha --reporter spec test/*.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1881 | `mocha tests.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1879 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1878 | `mocha test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1857 | `mocha test -u bdd -R spec` | 
| [then/promise](https://github.com/then/promise) | 1982 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1981 | `mocha tests --require @babel/register` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1963 | `mocha -c test/index.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1956 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1955 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1953 | `mocha --require ./test/common --growl test/expect.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1951 | `mocha && npm run lint` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1942 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1927 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1920 | `mocha test/**/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1920 | `mocha --reporter spec && npm run test-typescript` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1918 | `bmocha --reporter spec test/*.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1917 | `mocha test` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1920 | `mocha test/**/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1920 | `mocha --reporter spec && npm run test-typescript` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1918 | `bmocha --reporter spec test/*.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1917 | `mocha test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1910 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1892 | `npm run lint && mocha --reporter spec test/*.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1881 | `mocha tests.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1879 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1878 | `mocha test` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1866 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1857 | `mocha test -u bdd -R spec` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1848 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1837 | `mocha compiled_tests/` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1832 | `mocha ./test/basic.js -t 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1828 | `npm run lint && npm run mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1819 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1813 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1798 | `mocha --timeout 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1794 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1775 | `npm run lint && npm run mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1767 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1764 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1759 | `mocha test/setup.js test/spec/*.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1734 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1732 | `./node_modules/.bin/mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1731 | `npm run lint && mocha && npm run typescript` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1730 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1728 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1723 | `mocha test/*.js` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1721 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1720 | `mocha test --timeout 600000` | 
| [zeit/ms](https://github.com/zeit/ms) | 1718 | `mocha tests.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1718 | `TEST=all mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1717 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1711 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1697 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1696 | `mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1692 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1692 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1697 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1696 | `mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1692 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1692 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1672 | `mocha && size-limit` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1668 | `standard "./src/*.js" && mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1665 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1665 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1665 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1657 | `mocha spec` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1657 | `mocha` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1654 | `mocha test/test-*.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1654 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1653 | `mocha --check-leaks --reporter spec --bail` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1643 | `mocha --expose-gc --slow 300` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1591 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1573 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1572 | `NODE_ENV=test mocha tests/*.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1571 | `mocha --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1562 | `nyc mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1559 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1555 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1549 | `mocha ./test/test*.js --reporter spec` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1539 | `mocha test/unit` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1536 | `node_modules/.bin/mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1531 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1530 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1388 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1385 | `mocha --recursive test/bin` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1383 | `mocha --recursive` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1372 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1370 | `mocha test --compilers js:babel-core/register` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1368 | `cross-env NODE_ENV=test nyc mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1368 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1367 | `./node_modules/.bin/mocha test` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1356 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1353 | `NODE_PATH=. mocha **/*.spec.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1341 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1340 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1393 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1393 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1388 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1385 | `mocha --recursive test/bin` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1383 | `mocha --recursive` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1379 | `mocha --recursive test` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1370 | `mocha test --compilers js:babel-core/register` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1367 | `./node_modules/.bin/mocha test` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1356 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1355 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1343 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1341 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1340 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1339 | `mocha --check-leaks --reporter spec --bail test/` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1327 | `mocha --compilers js:babel-core/register` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1327 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1325 | `lerna run test && mocha` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1320 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1316 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1316 | `mocha-phantomjs tests/index.html` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1310 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1310 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1309 | `webpack && npm run lint && npm run mocha` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1309 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1308 | `mocha --timeout 60000 test/` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1306 | `mocha test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1303 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1300 | `npm run mocha:istanbul` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1296 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1294 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1296 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1294 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1293 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1288 | `mocha src/test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1285 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1284 | `npm run lint && npm run mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1283 | `mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1279 | `npm run lint && mocha --require @babel/register` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1275 | `mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1274 | `mocha tests/` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1272 | `istanbul test _mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1271 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1270 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1263 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1261 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [normalize/mz](https://github.com/normalize/mz) | 1233 | `mocha --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1231 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1229 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1226 | `mocha --timeout 20000` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1220 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1219 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1218 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1213 | `mocha test/test.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1212 | `mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1208 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [electron/asar](https://github.com/electron/asar) | 1185 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1192 | `mocha` | 
| [poooi/poi](https://github.com/poooi/poi) | 1192 | `mocha --recursive --harmony --require ./test/babelhook` | 
| [electron/asar](https://github.com/electron/asar) | 1185 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1176 | `mocha --recursive -r tests/setup tests` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1172 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1164 | `xo && mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1162 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1160 | `mocha $(find test -name '*.test.js') --exit` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1164 | `xo && mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1162 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1160 | `mocha $(find test -name '*.test.js') --exit` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1152 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1152 | `mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1150 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1149 | `istanbul cover _mocha test/*.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1149 | `npm-run-all test:jest test:server:mocha` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1146 | `mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1144 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1144 | `mocha --reporter spec --bail --check-leaks test/` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1136 | `webpack && mocha test/unit` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1129 | `mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1124 | `mocha test/*` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1124 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1119 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [electron/spectron](https://github.com/electron/spectron) | 1112 | `mocha && standard` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1112 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1110 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1107 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1103 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1100 | `mocha --reporter spec test --recursive` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1100 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1095 | `mocha --check-leaks -t 20000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1095 | `node_modules/.bin/mocha && npm run lint` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1094 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1089 | `mocha --recursive --bail --reporter spec test` | 
| [tomas/needle](https://github.com/tomas/needle) | 1057 | `mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1054 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1053 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1053 | `mocha --async-only` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1039 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1038 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 974 | `npm run rollup-cjs && mocha test/test.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 973 | `mocha "client.test" --compilers js:babel-register` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 972 | `mocha spec/*.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 969 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 969 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 967 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 967 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 965 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 954 | `./node_modules/.bin/mocha --reporter spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 953 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 953 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 953 | `mocha` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 951 | `./node_modules/.bin/mocha -R spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 951 | `mocha` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 948 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 947 | `mocha -t 600000` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1038 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1030 | `mocha --reporter spec --timeout 3000` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1028 | `mocha --recursive test/unit/` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1028 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1014 | `mocha --colors ./test/*.spec.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1009 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1007 | `mocha --check-leaks -R dot` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1003 | `mocha --reporter spec --bail --check-leaks test/` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1002 | `mocha -R list` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1002 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 997 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 989 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 987 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 984 | `mocha test/*.test.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 983 | `npm run lint && mocha -R spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 982 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 981 | `mocha --reporter spec` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 979 | `mocha --compilers js:babel-register test/*.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 975 | `mocha` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 975 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 974 | `npm run rollup-cjs && mocha test/test.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 973 | `mocha "client.test" --compilers js:babel-register` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 972 | `mocha spec/*.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 969 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 969 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 967 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 967 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 966 | `mocha --recursive ./test/*_spec.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 965 | `mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 960 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 954 | `./node_modules/.bin/mocha --reporter spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 953 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 953 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 953 | `mocha` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 951 | `./node_modules/.bin/mocha -R spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 951 | `mocha` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 948 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 947 | `mocha -t 600000` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 942 | `mocha` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 942 | `npm run lint && npm run mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 939 | `mocha test` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 935 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 932 | `nyc mocha specs` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 932 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 931 | `mocha test --compilers js:babel-register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 931 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 929 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 913 | `istanbul cover -- _mocha --reporter spec` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 912 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 912 | `mocha -t 5000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 909 | `standard && standard ./bin/* && mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 908 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 900 | `npm run lint && npm run mocha:no-functional` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 900 | `mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 896 | `mocha test` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 894 | `mocha test/index.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 893 | `node_modules/.bin/mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 900 | `mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 896 | `mocha test` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 894 | `mocha test/index.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 893 | `node_modules/.bin/mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 893 | `./node_modules/.bin/mocha test/**/*` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 886 | `mocha --timeout 200000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 882 | `./node_modules/.bin/mocha --globals angular,require` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 880 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 879 | `node_modules/.bin/mocha test/spec` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 869 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 868 | `mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 866 | `mocha --reporter list` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 862 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 862 | `eslint test && mocha --compilers js:babel/register` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 859 | `mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 858 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 858 | `istanbul cover _mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 858 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 858 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 853 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 853 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 852 | `mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 852 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 852 | `mocha --check-leaks -t 20000` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 851 | `mocha --harmony --full-trace --check-leaks` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 828 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [developit/decko](https://github.com/developit/decko) | 825 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 825 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 823 | `nyc mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 821 | `mocha test` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 820 | `mocha --harmony tests/**` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 819 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 818 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 818 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 817 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 813 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 812 | `npm run mocha-test test/integration` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 812 | `cake build && mocha ./test/mocha/*.coffee` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 812 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [edsu/anon](https://github.com/edsu/anon) | 811 | `mocha --colors --reporter spec test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 807 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 795 | `xo && mocha -R spec` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 782 | `mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 781 | `npm run lint && npm run mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 780 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 780 | `mocha test` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 778 | `nyc mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 778 | `mocha --recursive -s 15 test/` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 772 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 813 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 812 | `npm run mocha-test test/integration` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 812 | `cake build && mocha ./test/mocha/*.coffee` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 812 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [edsu/anon](https://github.com/edsu/anon) | 811 | `mocha --colors --reporter spec test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 807 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 806 | `mocha` | 
| [fossasia/labyrinth](https://github.com/fossasia/labyrinth) | 805 | `./node_modules/.bin/mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 805 | `mocha --require babel-register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 804 | `mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 802 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 801 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 784 | `_mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 782 | `mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 781 | `mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 781 | `npm run lint && npm run mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 780 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 780 | `mocha test` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 778 | `nyc mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 778 | `mocha --recursive -s 15 test/` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 773 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 772 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 772 | `mocha -R spec src/**/*_test.js` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 772 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 791 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 790 | `mocha --no-timeouts` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 784 | `_mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 782 | `mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 781 | `mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 781 | `npm run lint && npm run mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 780 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 780 | `mocha test` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 778 | `nyc mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 778 | `mocha --recursive -s 15 test/` | 