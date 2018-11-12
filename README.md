# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:33 11/12/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44211 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30554 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 24993 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 24869 | `npm run lint && npm run mocha-node-test` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19584 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17830 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17430 | `mocha` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14504 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14445 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17830 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17430 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17323 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16099 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14504 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14445 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14439 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13596 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13221 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12859 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12571 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12414 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12296 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11943 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11848 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11816 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11060 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10703 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10531 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10455 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10436 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10257 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10236 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [websockets/ws](https://github.com/websockets/ws) | 9918 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9751 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 9648 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9550 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9438 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9324 | `mocha -b -r esm` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9217 | `mocha tests/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9164 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 9068 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9030 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8707 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8599 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8506 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8386 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8340 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8301 | `mocha --compilers js:babel-register test/test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8165 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8153 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7972 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7856 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7581 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7579 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7568 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7562 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [aui/art-template](https://github.com/aui/art-template) | 7561 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7547 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7508 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7445 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7276 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7257 | `npm run xo && npm run mocha` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7139 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7105 | `mocha; jshint *.js lib` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7022 | `mocha $HARMONY_OPTS` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6964 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6942 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6935 | `mocha --exit --require @babel/register` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6732 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6543 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6418 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6329 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6315 | `npm run test:mocha:src` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6125 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6104 | `mocha tests/node.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6097 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6064 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6018 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5968 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5938 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5917 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5916 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5804 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5679 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5578 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5560 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5412 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5387 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5368 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5292 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5220 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5186 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5143 | `mocha --color` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5079 | `mocha test` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5070 | `gulp lint && mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4816 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4796 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4790 | `mocha -R spec 'tests/app'` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4780 | `mocha --recursive` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4748 | `./node_modules/.bin/mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4718 | `mocha --reporter spec -t 8000` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4699 | `nyc mocha --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4666 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4656 | `npm run lint && npm run mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4584 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4571 | `mocha ./test/runner.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4552 | `nyc mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 4549 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4488 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4463 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4552 | `nyc mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 4549 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4488 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4463 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4371 | `mocha -R spec src` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4368 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4350 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4327 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4248 | `mocha --timeout=15000 tests/*.test.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4229 | `node_modules/.bin/mocha test/tests.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4228 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4208 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4203 | `mocha -R spec ./test --recursive` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4159 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4128 | `npm run lint ; mocha && mocha test/individual` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4079 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4002 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3964 | `NODE_ENV=test mocha --exit` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3910 | `export TESTING=true; mocha --reporter list` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3900 | `nyc mocha "test/**/*.test.js"` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3868 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3830 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3813 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [erming/shout](https://github.com/erming/shout) | 3793 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3787 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3726 | `npm run build && mocha test/*.test.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3709 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3700 | `NODE_ENV=test mocha test/**/*.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3685 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3666 | `npm run jshint && npm run mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3645 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3604 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3604 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3598 | `node_modules/.bin/mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3566 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3564 | `mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3554 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3554 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3551 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3481 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3477 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3462 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3447 | `mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3433 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3394 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3377 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3360 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3320 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3195 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3188 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3178 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3177 | `mocha test/*.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3161 | `./node_modules/.bin/mocha test/test.*.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3152 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3148 | `mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3136 | `mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3132 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3109 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3108 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3099 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3089 | `mocha -R landing test/index` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3040 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2996 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2992 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 3045 | `mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3040 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3005 | `eslint . && nyc mocha --recursive` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2996 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2992 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2948 | `npm run mocha && npm run lint` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2939 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2937 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2925 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2917 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2890 | `mocha test.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2890 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2890 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2925 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2917 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2890 | `mocha test.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2890 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2890 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2887 | `node_modules/.bin/mocha --reporter spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2866 | `mocha test-node` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2866 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2863 | `mocha --require babel-register --recursive spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2858 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2855 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2851 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2849 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2846 | `mocha -R spec spec spec/reporters` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2829 | `istanbul cover _mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2793 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 2340 | `mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2327 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2323 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2314 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2290 | `npm run build && mocha --require babel-register` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2288 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [gajus/swing](https://github.com/gajus/swing) | 2267 | `mocha --compilers js:babel-register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2214 | `nyc npm run _mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2201 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2223 | `mocha test test/unit/**/*_test.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2214 | `nyc npm run _mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2201 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2189 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2178 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2165 | `cross-env BABEL_ENV=test mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2147 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2132 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2214 | `nyc npm run _mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2201 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2189 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2179 | `standard && mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2178 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2165 | `cross-env BABEL_ENV=test mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2147 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2132 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2130 | `mocha test/runner.js --reporter spec` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2128 | `mocha` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2127 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2127 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2126 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2109 | `mocha && eslint *.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2323 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2314 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2290 | `npm run build && mocha --require babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2289 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2288 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [gajus/swing](https://github.com/gajus/swing) | 2267 | `mocha --compilers js:babel-register` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2260 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2223 | `mocha test test/unit/**/*_test.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2214 | `nyc npm run _mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2201 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2189 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2179 | `standard && mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2165 | `cross-env BABEL_ENV=test mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2147 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2132 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2130 | `mocha test/runner.js --reporter spec` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2128 | `mocha` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2127 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2127 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2126 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2109 | `mocha && eslint *.js` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2106 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [pahen/madge](https://github.com/pahen/madge) | 2098 | `npm run lint && npm run mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2063 | `mocha --compilers js:babel-core/register __tests__` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2047 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2009 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2004 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2002 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [slate/slate](https://github.com/slate/slate) | 1996 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1987 | `mocha --reporter spec --timeout 5000` | 
| [kach/nearley](https://github.com/kach/nearley) | 1985 | `mocha test/*.test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1944 | `mocha --require ./test/common --growl test/expect.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1938 | `mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1937 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1935 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1926 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1913 | `mocha && npm run lint` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1896 | `mocha --reporter spec && npm run test-typescript` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1892 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1892 | `mocha tests --require @babel/register` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1879 | `mocha --reporter spec test/*.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1877 | `mocha tests.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 1865 | `mocha && tsc -p ./test/types` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1864 | `mocha test/**/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1860 | `npm run lint && mocha --reporter spec test/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1926 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1913 | `mocha && npm run lint` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1896 | `mocha --reporter spec && npm run test-typescript` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1892 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1892 | `mocha tests --require @babel/register` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1879 | `mocha --reporter spec test/*.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1877 | `mocha tests.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 1865 | `mocha && tsc -p ./test/types` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1864 | `mocha test/**/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1860 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1851 | `mocha test` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1735 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1725 | `./node_modules/.bin/mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1725 | `npm run lint && mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1711 | `mocha test/setup.js test/spec/*.js` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1710 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1709 | `mocha test/*.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1693 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1682 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1678 | `eslint --cache . && tsc && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1671 | `mocha tests.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1664 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1661 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1661 | `mocha && size-limit` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1656 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1492 | `mocha test/unit` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1488 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1478 | `mocha -R spec` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1478 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1454 | `mocha -R spec test/*.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1454 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1450 | `mocha -R spec ./test/unit/**` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1447 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1431 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1427 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1425 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1425 | `mocha tests/test-*` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1409 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1408 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1406 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1587 | `./node_modules/mocha/bin/mocha -R spec` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1577 | `mocha test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1575 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1549 | `nyc mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1549 | `mocha --recursive` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1548 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1547 | `npm run test:lint && npm run test:mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1533 | `node_modules/.bin/mocha --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1525 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1522 | `mocha -u tdd` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1589 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1587 | `./node_modules/mocha/bin/mocha -R spec` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1577 | `mocha test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1575 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1559 | `./node_modules/.bin/mocha` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1549 | `nyc mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1549 | `mocha --recursive` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1547 | `npm run test:lint && npm run test:mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1533 | `node_modules/.bin/mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1478 | `mocha -R spec` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1478 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1473 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1466 | `mocha ./test/test*.js --reporter spec` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1454 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1450 | `mocha -R spec ./test/unit/**` | 
| [samccone/drool](https://github.com/samccone/drool) | 1450 | `mocha test/tests.js --timeout=10000` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1441 | `mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1435 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1431 | `npm run lint && mocha && karma start --single-run` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1427 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1425 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1425 | `mocha tests/test-*` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1527 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1525 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1522 | `mocha -u tdd` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1505 | `NODE_ENV=test mocha tests/*.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1494 | `mocha test/**/*.spec.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1492 | `mocha test/unit` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1492 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1488 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1478 | `mocha -R spec` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1478 | `mocha --timeout 10000 ./tests/lib.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1477 | `mocha --check-leaks --require @babel/register` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1473 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1473 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1466 | `mocha ./test/test*.js --reporter spec` | 
| [noble/bleno](https://github.com/noble/bleno) | 1454 | `mocha -R spec test/*.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1454 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1450 | `mocha -R spec ./test/unit/**` | 
| [samccone/drool](https://github.com/samccone/drool) | 1450 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1449 | `mocha test.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1449 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1447 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1441 | `mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1436 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1435 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1431 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1431 | `npm run lint && mocha && karma start --single-run` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1427 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1425 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1425 | `mocha tests/test-*` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1409 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1408 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1407 | `standard && istanbul cover _mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1406 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1403 | `npm run lint && npm run mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1401 | `istanbul cover _mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1400 | `npm run build && mocha -r should` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1400 | `mocha --opts test/opts/mocha.opts` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1392 | `mocha --reporter dot` | 
| [electron/devtron](https://github.com/electron/devtron) | 1385 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1384 | `./node_modules/mocha/bin/mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1372 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1369 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1356 | `mocha --recursive test/bin` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1355 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1352 | `./node_modules/.bin/mocha test` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1345 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1341 | `NODE_PATH=. mocha **/*.spec.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1337 | `npm run prepublishOnly && mocha test/test.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1337 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1337 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1330 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1330 | `mocha --recursive test` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1324 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1314 | `mocha --check-leaks --reporter spec --bail test/` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1313 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1330 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1330 | `mocha --recursive test` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1324 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1314 | `mocha --check-leaks --reporter spec --bail test/` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1313 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1309 | `mocha spec/exec.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1308 | `mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1307 | `mocha-phantomjs tests/index.html` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1306 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1305 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1303 | `mocha test --compilers js:babel-core/register` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1300 | `mocha --timeout 60000 test/` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1299 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1288 | `mocha test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1283 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1278 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1274 | `mocha` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1273 | `mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1272 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1270 | `mocha --compilers js:babel-core/register` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1268 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1267 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1267 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1266 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1266 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1264 | `mocha src/test.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1262 | `webpack && npm run lint && npm run mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1259 | `npm run lint && npm run mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1258 | `mocha tests` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1257 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1253 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1247 | `istanbul test _mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1246 | `npm run mocha:istanbul` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1232 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [variety/variety](https://github.com/variety/variety) | 1231 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1226 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1223 | `mocha tests/` | 
| [normalize/mz](https://github.com/normalize/mz) | 1222 | `mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1220 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1219 | `mocha` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1215 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1215 | `mocha test/test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1214 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1205 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [router5/router5](https://github.com/router5/router5) | 1203 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1196 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1163 | `mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1161 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1160 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 1155 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1150 | `mocha $(find test -name '*.test.js') --exit` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1149 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1144 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1143 | `istanbul cover _mocha test/*.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1142 | `mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1141 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1138 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1135 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1150 | `mocha $(find test -name '*.test.js') --exit` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1149 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1144 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1143 | `istanbul cover _mocha test/*.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1142 | `mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1141 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1138 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1135 | `mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1127 | `npm-run-all test:jest test:server:mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1123 | `mocha test/*` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1122 | `mocha --recursive -r tests/setup tests` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1120 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1119 | `mocha --reporter spec --bail --check-leaks test/` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1118 | `webpack && mocha test/unit` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1059 | `mocha --reporter spec test --recursive` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1056 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1055 | `npm run convertto:es5 && npm run mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 1049 | `mocha test` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1048 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1043 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1037 | `mocha --async-only` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1037 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1034 | `mocha --reporter spec --timeout 3000` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1033 | `mocha $(find test -name '*.test.js')` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1025 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [ulid/javascript](https://github.com/ulid/javascript) | 1025 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha -- -R spec` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1024 | `mocha test` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1022 | `mocha --recursive test/unit/` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 931 | `./node_modules/.bin/mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 926 | `./node_modules/.bin/mocha -R spec` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 926 | `mocha --recursive ./test/*_spec.js` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 920 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 919 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 917 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 915 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 913 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 912 | `mocha test --compilers js:babel-register` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 910 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 908 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 905 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 900 | `standard && standard ./bin/* && mocha` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 896 | `mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 893 | `istanbul cover -- _mocha --reporter spec` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 890 | `node_modules/.bin/mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 887 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 884 | `./node_modules/.bin/mocha --globals angular,require` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 881 | `mocha -t 5000` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 878 | `mocha --timeout 200000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 875 | `mocha test/index.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 873 | `node_modules/.bin/mocha test/spec` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 873 | `node_modules/.bin/mocha test/spec` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 870 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 867 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 866 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 865 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 863 | `mocha test` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 862 | `eslint test && mocha --compilers js:babel/register` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 857 | `mocha --reporter list` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 857 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 856 | `mocha --reporter spec` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 856 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 856 | `mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 854 | `istanbul cover _mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 842 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 839 | `npm run build && istanbul test _mocha test/test.js` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 839 | `mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 838 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 835 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 832 | `npm run lint && npm run mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 830 | `mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 829 | `mocha --opts mocha.opts` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 828 | `mocha --harmony --full-trace --check-leaks` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 828 | `mocha && ember test` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 828 | `mocha --async-only` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 827 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 823 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 828 | `mocha --harmony --full-trace --check-leaks` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 828 | `mocha && ember test` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 828 | `mocha --async-only` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 827 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 823 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 823 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 818 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 817 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 816 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 815 | `mocha -r should --reporter spec test/*.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 814 | `mocha` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 812 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 811 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [edsu/anon](https://github.com/edsu/anon) | 810 | `mocha --colors --reporter spec test.js` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 815 | `mocha -r should --reporter spec test/*.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 814 | `mocha` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 812 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 811 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [edsu/anon](https://github.com/edsu/anon) | 810 | `mocha --colors --reporter spec test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 810 | `cake build && mocha ./test/mocha/*.coffee` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 810 | `mocha test` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 808 | `npm run mocha-test test/integration` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 807 | `mocha` | 
| [developit/decko](https://github.com/developit/decko) | 806 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 805 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 803 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 803 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 802 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 802 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 799 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 796 | `mocha -R spec tests/` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 794 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 793 | `nyc mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 791 | `xo && mocha -R spec` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 790 | `mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 786 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 784 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 783 | `mocha --no-timeouts` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 775 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 773 | `mocha test` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 772 | `mocha --recursive -s 15 test/` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 769 | `mocha -R spec src/**/*_test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 764 | `mocha --ui tdd --require ./test/__setup` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 762 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 762 | `npm run lint && npm run mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 762 | `npm run lint && mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 760 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 759 | `mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 758 | `nyc mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 758 | `babel-node node_modules/.bin/_mocha -- test` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 753 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 753 | `mocha --harmony tests/**` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 753 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 752 | `mocha test/mocha.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 751 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 751 | `npm run-script jshint && npm run-script mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 750 | `mocha` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 738 | `mocha test.js` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 738 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 737 | `jenkins-mocha ./tests/*.js` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 736 | `npm run bundle && mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 735 | `mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 734 | `mocha --reporter spec` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 733 | `./bin/selenium-standalone install && mocha` | 
| [koajs/static](https://github.com/koajs/static) | 733 | `mocha --harmony --reporter spec --exit` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 733 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 731 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 730 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 730 | `mocha` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 730 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 729 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 727 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 736 | `npm run bundle && mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 735 | `mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 734 | `mocha --reporter spec` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 733 | `./bin/selenium-standalone install && mocha` | 
| [koajs/static](https://github.com/koajs/static) | 733 | `mocha --harmony --reporter spec --exit` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 733 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 731 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 730 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 730 | `mocha` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 730 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 729 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 727 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 726 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 726 | `mocha` | 