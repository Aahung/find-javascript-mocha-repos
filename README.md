# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:34 03/18/19 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45561 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42898 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42468 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30995 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 26399 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 26058 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25661 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25331 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21943 | `npm-run-all lint build --parallel test:mocha test:karma test:ts` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20351 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18367 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18199 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 18012 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15671 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14807 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14166 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13964 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13558 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13102 | `mocha 'test/**/*.spec.js'` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13102 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12901 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12820 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12765 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12488 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12382 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11811 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11626 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11394 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 11086 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [websockets/ws](https://github.com/websockets/ws) | 10843 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10796 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10519 | `mocha --harmony` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 11086 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [websockets/ws](https://github.com/websockets/ws) | 10843 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10796 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10519 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 10083 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9920 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9773 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9683 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9620 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9511 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9410 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9363 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 9099 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6653 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6378 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6355 | `mocha tests/node.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6309 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6278 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6272 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 6135 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 6016 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5961 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5923 | `mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5854 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5779 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5747 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7699 | `mocha --compilers js:babel-core/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7691 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7680 | `mocha; jshint *.js lib` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7641 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7592 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7453 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7249 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7173 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7151 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7095 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6653 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5937 | `mocha && eslint lib/**` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5923 | `mocha` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5892 | `npm run lint && mocha tests/**/*.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5854 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5779 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5747 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5638 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5564 | `mocha test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5531 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5468 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5438 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5397 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5212 | `mocha src/**/*Tests.js --harmony` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5190 | `mocha --recursive` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5779 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5747 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5638 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5564 | `mocha test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5531 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5513 | `mocha -r esm` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5468 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5212 | `mocha src/**/*Tests.js --harmony` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5190 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5168 | `npm run lint && npm run mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5152 | `gulp lint && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5125 | `mocha --color` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5117 | `nyc mocha --exit` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 5102 | `NODE_ENV=test mocha --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5087 | `nyc mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 5010 | `gulp build; mocha;` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4992 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4934 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4921 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4898 | `mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4891 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4874 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4837 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4765 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4716 | `mocha -R spec src` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4898 | `mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4891 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4874 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4837 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4765 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4716 | `mocha -R spec src` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 4610 | `./node_modules/mocha/bin/mocha --require @babel/register test/*` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4593 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4592 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4560 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4540 | `mocha --timeout=15000 tests/*.test.js` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4525 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4493 | `mocha --check-leaks --reporter spec --bail` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4492 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4444 | `mocha test/tests.js` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 4417 | `npm run mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4398 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4387 | `npm run lint && mocha && mocha test/individual && if [ "$TRAVIS_PULL_REQUEST" = "false" ]; then snyk test; fi` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4281 | `npm run build && cd test && mocha . --reporter dot` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4250 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4187 | `mocha -R spec ./test --recursive` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4164 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 4132 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4092 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3764 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3756 | `mocha test/* --reporter spec` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3682 | `standard && mocha --timeout 60000 test/test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3618 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3609 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3606 | `mocha tests/javascript` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3596 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3564 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3501 | `node_modules/.bin/mocha test/lib/` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3493 | `node ./test/import-test.js && mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3469 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3468 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3459 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3446 | `mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3422 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3407 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3673 | `npm run jshint && npm run mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3618 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3609 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3606 | `mocha tests/javascript` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3596 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3564 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3557 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3538 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3501 | `node_modules/.bin/mocha test/lib/` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3493 | `node ./test/import-test.js && mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3469 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3468 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3464 | `mocha -R landing test/index --exit` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3459 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3456 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3455 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3446 | `mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3446 | `mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3422 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3407 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3377 | `mocha test/index.js && npm run demo` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3302 | `mocha test/*.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3298 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3294 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3241 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3203 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3032 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3029 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2988 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2988 | `mocha` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2980 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2929 | `mocha -R spec spec spec/reporters` | 
| [github-tools/github](https://github.com/github-tools/github) | 2925 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2922 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2895 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2851 | `istanbul cover _mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2805 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2788 | `mocha --require should --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2788 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2788 | `mocha --require should --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2788 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2775 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2775 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [nosqlclient/nosqlclient](https://github.com/nosqlclient/nosqlclient) | 2762 | `cross-env TEST_BROWSER_DRIVER=chrome BABEL_ENV=coverage COVERAGE=1 COVERAGE_OUT_LCOVONLY=1 COVERAGE_APP_FOLDER=$PWD/ meteor test --once --driver-package meteortesting:mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2760 | `nyc mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2733 | `mocha --recursive --watch` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2723 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2712 | `mocha --timeout 100000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2655 | `mocha-phantomjs ./test/index.html` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2646 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2635 | `TEST=all mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2624 | `mocha test --exit && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2613 | `mocha && eslint .` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2611 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2608 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2598 | `mocha test/src/**/*.unit.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2597 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [nosqlclient/nosqlclient](https://github.com/nosqlclient/nosqlclient) | 2762 | `cross-env TEST_BROWSER_DRIVER=chrome BABEL_ENV=coverage COVERAGE=1 COVERAGE_OUT_LCOVONLY=1 COVERAGE_APP_FOLDER=$PWD/ meteor test --once --driver-package meteortesting:mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2746 | `nyc mocha --timeout=10000` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2736 | `mocha test/unit --require mochahook` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2733 | `mocha --recursive --watch` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2723 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2705 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2655 | `mocha-phantomjs ./test/index.html` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2646 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2635 | `TEST=all mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2624 | `mocha test --exit && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2613 | `mocha && eslint .` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2608 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2598 | `mocha test/src/**/*.unit.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2597 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2256 | `mocha test/test-*.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2245 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2228 | `mocha --timeout 15000 --bail --exit test/*-test.js test/security/*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2218 | `mocha --compilers js:babel-register` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2194 | `mocha test` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2192 | `cross-env BABEL_ENV=test mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2178 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2170 | `mocha --compilers js:babel-core/register __tests__` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2163 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2132 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2101 | `mocha` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1885 | `mocha tests.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1868 | `npm run lint && npm run mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1863 | `mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1857 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1828 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1824 | `mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1821 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1817 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1800 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1794 | `mocha --timeout 5000` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1766 | `mocha --check-leaks --reporter spec --bail` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1766 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1764 | `mocha test/*.js` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2323 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2321 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2295 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2287 | `standard && mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2265 | `mocha` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2256 | `mocha test/test-*.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2228 | `mocha --timeout 15000 --bail --exit test/*-test.js test/security/*.js` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2218 | `mocha test test/unit/**/*_test.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2218 | `mocha --compilers js:babel-register` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2218 | `mocha test/runner.js --reporter spec` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2215 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2175 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2137 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2121 | `npm run mocha && npm run karma` | 
| [kach/nearley](https://github.com/kach/nearley) | 2118 | `mocha test/*.test.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2110 | `mocha tests --require @babel/register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2101 | `mocha` | 
| [htmlhint/HTMLHint](https://github.com/htmlhint/HTMLHint) | 2075 | `mocha` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2069 | `npm run lint && mocha -R dot && npm run cover` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 2069 | `mocha --recursive` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2060 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2055 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2031 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2020 | `mocha --require=test/test_helper.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 2012 | `mocha test/**/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1996 | `mocha --reporter spec && npm run test-typescript` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2069 | `npm run lint && mocha -R dot && npm run cover` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 2069 | `mocha --recursive` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2066 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2060 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2031 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 2029 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2020 | `mocha --require=test/test_helper.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 2001 | `nyc mocha --timeout=20000 test.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1996 | `mocha --reporter spec && npm run test-typescript` | 
| [slate/slate](https://github.com/slate/slate) | 1993 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1984 | `mocha --require ./test/common --growl test/expect.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1974 | `npm run lint && mocha --reporter spec test/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1974 | `mocha --bail --reporter spec --check-leaks test/` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 2001 | `nyc mocha --timeout=20000 test.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1996 | `mocha --reporter spec && npm run test-typescript` | 
| [slate/slate](https://github.com/slate/slate) | 1993 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1984 | `mocha --require ./test/common --growl test/expect.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1979 | `bmocha --reporter spec test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1974 | `npm run lint && mocha --reporter spec test/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1974 | `mocha --bail --reporter spec --check-leaks test/` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1965 | `mocha -c test/index.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1964 | `mocha tests.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1959 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1958 | `mocha --reporter spec --grep .` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1948 | `mocha test -u bdd -R spec` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1948 | `mocha test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1942 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1935 | `mocha ./test/basic.js -t 5000` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1788 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1780 | `npm run lint && mocha && npm run typescript` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1774 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1766 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1764 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1750 | `./node_modules/.bin/mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1747 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1742 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1738 | `mocha test --timeout 600000` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1731 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1730 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1728 | `mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1726 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1723 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1715 | `mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1817 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1800 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1794 | `mocha --timeout 5000` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1788 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1780 | `npm run lint && mocha && npm run typescript` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1774 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1766 | `mocha --check-leaks --reporter spec --bail` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1766 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1764 | `mocha test/*.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1764 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1750 | `./node_modules/.bin/mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1748 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1747 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1742 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1739 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1738 | `mocha test --timeout 600000` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1748 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1747 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1742 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1739 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1738 | `mocha test --timeout 600000` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1731 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1730 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1728 | `mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1726 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1725 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1723 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1715 | `mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1710 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1701 | `NODE_ENV=test mocha tests/*.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1221 | `mocha --reporter spec test --recursive` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1218 | `mocha --reporter spec --bail --check-leaks test/` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1214 | `mocha test` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1185 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1184 | `npm run lint && npm run mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1172 | `npm run convertto:es5 && npm run mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1170 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1160 | `mocha && standard` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1341 | `npm run lint && npm run mocha` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1341 | `mocha test/*.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1339 | `mocha src/test.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1337 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1315 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1312 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1305 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [variety/variety](https://github.com/variety/variety) | 1293 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1283 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1273 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1269 | `mocha --reporter spec` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1305 | `istanbul test _mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1305 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1302 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1283 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1273 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1267 | `mocha tests` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1258 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1404 | `mocha --recursive` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1400 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1393 | `NODE_PATH=. mocha **/*.spec.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1391 | `./node_modules/mocha/bin/mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1390 | `./node_modules/.bin/mocha test` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1381 | `npm run lint && mocha --require @babel/register` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1379 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1377 | `cross-env NODE_ENV=test nyc mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1376 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1357 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1356 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1356 | `mocha --timeout 20000` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1355 | `mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1353 | `mocha --timeout 60000 test/` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1351 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1351 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1348 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1348 | `mocha --timeout 30000 --recursive ./tests` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1346 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1345 | `lerna run test && mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1341 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1341 | `npm run lint && npm run mocha` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1341 | `mocha test/*.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1339 | `mocha src/test.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1339 | `mocha spec/exec.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1337 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1330 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1325 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1323 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1321 | `mocha-phantomjs tests/index.html` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1315 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1312 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1305 | `istanbul test _mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1305 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1305 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1302 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1293 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1283 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1273 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1269 | `mocha --reporter spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1267 | `mocha tests` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1258 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1257 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1255 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1253 | `mocha test` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1241 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1232 | `node ./node_modules/mocha/bin/mocha tests` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1227 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1224 | `mocha --recursive -r tests/setup tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1224 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1222 | `mocha --reporter spec --bail --check-leaks test/` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1221 | `mocha --reporter spec test --recursive` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1217 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1217 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1214 | `mocha test` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1213 | `npm-run-all test:jest test:server:mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1209 | `mocha test/test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1202 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1197 | `xo && mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1185 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1185 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1184 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [electron/spectron](https://github.com/electron/spectron) | 1160 | `mocha && standard` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1158 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1141 | `standard && mocha -b` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1137 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1121 | `mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1115 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1112 | `mocha --recursive --bail --reporter spec test` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1109 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1099 | `mocha --check-leaks -t 20000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1099 | `node_modules/.bin/mocha && npm run lint` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1094 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1089 | `mocha test/tests.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1086 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [tomas/needle](https://github.com/tomas/needle) | 1086 | `mocha test` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 1060 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1059 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1053 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1044 | `mocha --recursive test/unit/` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1041 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1037 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1032 | `mocha --reporter spec --bail --check-leaks test/` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1031 | `npm run lint && mocha -R spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1031 | `./node_modules/.bin/mocha -R spec` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1031 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1031 | `mocha spec/*.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1029 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 1028 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1025 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1044 | `mocha --recursive test/unit/` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1041 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1037 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1032 | `mocha --reporter spec --bail --check-leaks test/` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1031 | `npm run lint && mocha -R spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1031 | `./node_modules/.bin/mocha -R spec` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1031 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1031 | `mocha spec/*.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1029 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 1028 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1027 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1025 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1024 | `mocha --reporter spec --timeout 3000` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 1023 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1022 | `mocha --async-only` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1020 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1013 | `mocha --compilers js:babel-register test/*.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1010 | `mocha -R list` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 998 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 996 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 987 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 987 | `mocha -t 600000 --exit` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 987 | `mocha tests` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 986 | `mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 984 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1013 | `mocha --compilers js:babel-register test/*.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1010 | `mocha -R list` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 998 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 996 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 993 | `mocha "client.test" --compilers js:babel-register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 987 | `mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 984 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 975 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 975 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 974 | `nyc mocha specs` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 973 | `mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 968 | `standard && standard ./bin/* && mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 965 | `mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 962 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 955 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 951 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 955 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 954 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 953 | `istanbul cover -- _mocha --reporter spec` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 951 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 951 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 941 | `mocha test/index.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 937 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 937 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 941 | `mocha test/index.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 937 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 937 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 936 | `mocha --timeout 5000` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 932 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 927 | `mocha -t 5000` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 926 | `mocha -r should --exit test/*.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 925 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 924 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 914 | `mocha --harmony tests/**` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 913 | `mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 906 | `npm run build && istanbul test _mocha test/test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 905 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 903 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 902 | `npm run lint && mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 901 | `node_modules/.bin/mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 899 | `mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 898 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 898 | `mocha --timeout 200000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 893 | `node_modules/.bin/mocha test/spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 892 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 874 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 873 | `istanbul cover _mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 873 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 868 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 868 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 867 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 867 | `mocha --reporter spec` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 867 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 866 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 864 | `nyc mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 864 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 864 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 862 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 860 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [ebradyjobory/finance.js](https://github.com/ebradyjobory/finance.js) | 860 | `mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 858 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 857 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 856 | `mocha test` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 856 | `mocha` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 854 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 854 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 853 | `mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 851 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 845 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 845 | `mocha test` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 844 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 842 | `ts-mocha test/` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 842 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 841 | `mocha --async-only` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 837 | `mocha test/mocha.js test/crc/index.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 836 | `npm run mocha-test test/integration` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 836 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 836 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 832 | `_mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 832 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 832 | `mocha && ember test` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 796 | `npm run lint && npm run mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 796 | `mocha tests --timeout 10000` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 795 | `mocha --recursive -s 15 test/` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 790 | `mocha -u tdd` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 815 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 815 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 813 | `mocha test` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 807 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 805 | `jenkins-mocha ./tests/*.js` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 802 | `nyc mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 800 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 778 | `mocha ./test/serializer/ --compilers js:@babel/register` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 778 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 777 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 775 | `mocha -R spec src/**/*_test.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 771 | `./bin/selenium-standalone install && mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 770 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 770 | `mocha --ui tdd --require ./test/__setup` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 766 | `mocha --reporter spec build/test/index.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 763 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 757 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 775 | `mocha -R spec src/**/*_test.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 772 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 771 | `./bin/selenium-standalone install && mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 770 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 770 | `mocha --ui tdd --require ./test/__setup` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 766 | `mocha --reporter spec build/test/index.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 763 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [electron/apps](https://github.com/electron/apps) | 763 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 