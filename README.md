# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:21 01/04/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44772 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41922 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41737 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30767 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 25618 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25091 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24782 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21193 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19962 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18284 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17832 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17666 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16882 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15005 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14792 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14642 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13827 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13510 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12960 | `mocha 'test/**/*.spec.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12772 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12715 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12686 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12352 | `mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12269 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12212 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12175 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11372 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11021 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10902 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10788 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10657 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10296 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9663 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9653 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9583 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 9431 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9401 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9288 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9249 | `grunt mocha` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8836 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8657 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8545 | `mocha --check-leaks -R dot` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8544 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8657 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8545 | `mocha --check-leaks -R dot` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8544 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8516 | `mocha --compilers js:babel-register test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8433 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8359 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8228 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8019 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7964 | `./node_modules/.bin/mocha test` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7937 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7937 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7802 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7791 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7776 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [dthree/cash](https://github.com/dthree/cash) | 7586 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7574 | `npm run build && istanbul cover _mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7538 | `mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7458 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7448 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7392 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7373 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7333 | `mocha --exit --require @babel/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7086 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7081 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6941 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6754 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6703 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5855 | `mocha && eslint lib/**` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5686 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5647 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5602 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5587 | `npm run lint && mocha tests/**/*.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5530 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5472 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5409 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5316 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5301 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5271 | `mocha test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5179 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [teambit/bit](https://github.com/teambit/bit) | 5177 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5136 | `mocha --color` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5855 | `mocha && eslint lib/**` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5686 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5647 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5602 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5587 | `npm run lint && mocha tests/**/*.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5530 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5472 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5451 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5409 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5316 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5301 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5271 | `mocha test` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5203 | `mocha src/**/*Tests.js --harmony` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5179 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [teambit/bit](https://github.com/teambit/bit) | 5177 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5136 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5106 | `gulp lint && mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4979 | `mocha --recursive` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4924 | `gulp build; mocha;` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4906 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4868 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4866 | `nyc mocha --exit` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4862 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4858 | `./node_modules/.bin/mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4837 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4833 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4814 | `mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4803 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4798 | `npm run lint && npm run mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4742 | `nyc mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4738 | `mocha --reporter spec -t 8000` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 4604 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4576 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4539 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4522 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4518 | `mocha -R spec src` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4475 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4379 | `mocha --timeout=15000 tests/*.test.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4367 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4321 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4266 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4265 | `mocha --check-leaks --reporter spec --bail` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4229 | `NODE_ENV=test mocha --exit` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4227 | `nyc mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4227 | `npm run lint ; mocha && mocha test/individual` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4199 | `mocha -R spec ./test --recursive` | 
| [muicss/mui](https://github.com/muicss/mui) | 4123 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4097 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4075 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4064 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4014 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3964 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3929 | `export TESTING=true; mocha --reporter list` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3871 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3862 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3812 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3797 | `npm run build && mocha test/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3792 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3729 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3690 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3684 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3682 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3669 | `npm run jshint && npm run mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3641 | `node_modules/.bin/mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3690 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3684 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3682 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3669 | `npm run jshint && npm run mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3641 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3629 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3613 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3600 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3585 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3581 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3574 | `eslint . && mocha -t 5000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3558 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3552 | `mocha && tsc -p ./test/types` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3546 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3502 | `nyc mocha && tsc` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3487 | `node_modules/.bin/mocha test/lib/` | 
| [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace) | 3473 | `mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3464 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3091 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3072 | `nyc mocha --recursive` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3055 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2997 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2977 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2953 | `mocha` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2948 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2946 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2942 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2932 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2908 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2891 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2884 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2836 | `npm run build && cd test && mocha . --reporter dot` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2820 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3238 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3232 | `mocha test/*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3209 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3192 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3181 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3178 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3177 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3163 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3141 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3136 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 3111 | `mocha --require should --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3091 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3072 | `nyc mocha --recursive` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3061 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3055 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2975 | `node_modules/.bin/mocha --reporter spec` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2970 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2953 | `mocha` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2952 | `mocha test-node` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2949 | `mocha -R spec --recursive src/test` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2948 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2946 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2942 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2937 | `mocha --require @babel/register --recursive spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2932 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2908 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2891 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2884 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2881 | `mocha -R spec spec spec/reporters` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2855 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2840 | `istanbul cover _mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2836 | `npm run build && cd test && mocha . --reporter dot` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2820 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [css/csso](https://github.com/css/csso) | 2805 | `mocha --reporter dot` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2783 | `mocha --require should --reporter spec` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2783 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2756 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2754 | `xo && mocha` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2747 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2738 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [retejs/rete](https://github.com/retejs/rete) | 2734 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2726 | `mocha "./test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2716 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2699 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2697 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2682 | `nyc mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2645 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2644 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2631 | `mocha-phantomjs ./test/index.html` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2585 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2574 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2550 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2537 | `mocha test` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2534 | `export TESTING=true; mocha --reporter list` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2526 | `mocha test/src/**/*.unit.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2516 | `mocha test --exit && npm run lint` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2510 | `mocha --reporter=spec test/*-test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2507 | `nyc --reporter=html --reporter=text mocha` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2503 | `mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2494 | `mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2476 | `mocha && eslint .` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2468 | `mocha test/index.js --reporter dot` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2387 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [noble/noble](https://github.com/noble/noble) | 2380 | `mocha -R spec test/*.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2377 | `nyc --require babel-register npm run _mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2375 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2372 | `node node_modules/mocha/bin/_mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2370 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2367 | `npm run build && mocha --require babel-register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2318 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2313 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2303 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [gajus/swing](https://github.com/gajus/swing) | 2298 | `mocha --compilers js:babel-register` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2287 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2107 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2095 | `mocha --compilers js:babel-register` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2064 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2046 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2037 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [kach/nearley](https://github.com/kach/nearley) | 2027 | `mocha test/*.test.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2022 | `npm run lint && mocha -R dot && npm run cover` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2017 | `npm run mocha && npm run karma` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2012 | `mocha tests --require @babel/register` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2010 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2009 | `mocha --reporter spec --timeout 5000` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2009 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1998 | `mocha --require=test/test_helper.js` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1986 | `mocha && npm run lint` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1969 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1961 | `mocha -c test/index.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1960 | `mocha --require ./test/common --growl test/expect.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1957 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1945 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1943 | `mocha test` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1938 | `mocha --reporter spec && npm run test-typescript` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1936 | `mocha test/**/*.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1933 | `bmocha --reporter spec test/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1929 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1921 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1905 | `npm run lint && mocha --reporter spec test/*.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1880 | `mocha tests.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1876 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1872 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1860 | `mocha compiled_tests/` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1853 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1850 | `mocha ./test/basic.js -t 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1839 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1815 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1713 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1710 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1701 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1679 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1675 | `mocha && size-limit` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1672 | `mocha --check-leaks --reporter spec --bail` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1669 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1663 | `mocha spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1661 | `mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1643 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1632 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1624 | `mocha ./test/test*.js --reporter spec` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1701 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1686 | `mocha test/test-*.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1682 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1679 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1675 | `mocha && size-limit` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1672 | `mocha --check-leaks --reporter spec --bail` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1669 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1663 | `mocha spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1661 | `mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1643 | `mocha --expose-gc --slow 300` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1686 | `mocha test/test-*.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1682 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1679 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1675 | `mocha && size-limit` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1672 | `mocha --check-leaks --reporter spec --bail` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1669 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1663 | `mocha spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1661 | `mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1643 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1542 | `mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1537 | `mocha -u tdd` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1524 | `mocha --check-leaks --require @babel/register` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1519 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1517 | `mocha tests/test-*` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1507 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1502 | `mocha test/**/*.spec.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1493 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1492 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1492 | `mocha --timeout 10000 ./tests/lib.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1492 | `npm run lint && mocha && karma start --single-run` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1488 | `mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1507 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1507 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1502 | `mocha test/**/*.spec.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1493 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1492 | `mocha --timeout 10000 ./tests/lib.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1492 | `npm run lint && mocha && karma start --single-run` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1488 | `mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1484 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [noble/bleno](https://github.com/noble/bleno) | 1484 | `mocha -R spec test/*.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1481 | `npm run lint && npm run mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1477 | `mocha -R spec` | 
| [samccone/drool](https://github.com/samccone/drool) | 1459 | `mocha test/tests.js --timeout=10000` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1455 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1452 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1427 | `npm run prepublishOnly && mocha test/test.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1420 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1418 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1415 | `npm run build && mocha -r should` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1408 | `mocha --recursive test` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1404 | `istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1399 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1397 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1354 | `mocha --check-leaks --reporter spec --bail test/` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1344 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1342 | `mocha --compilers js:babel-core/register` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1340 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1340 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1340 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1331 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1328 | `lerna run test && mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1326 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1326 | `npm run mocha:istanbul` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1322 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1322 | `webpack && npm run lint && npm run mocha` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1314 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1314 | `mocha test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1312 | `mocha --timeout 60000 test/` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1310 | `npm run lint && mocha --require @babel/register` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1305 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1303 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1301 | `mocha src/test.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1340 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1340 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1335 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1331 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1328 | `lerna run test && mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1326 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1326 | `npm run mocha:istanbul` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1322 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1322 | `webpack && npm run lint && npm run mocha` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1316 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1315 | `mocha-phantomjs tests/index.html` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1314 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1314 | `mocha test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1312 | `mocha --timeout 60000 test/` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1310 | `npm run lint && mocha --require @babel/register` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1305 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1303 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1300 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1289 | `npm run lint && npm run mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1286 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1285 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1284 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1281 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1280 | `istanbul test _mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1270 | `mocha --timeout 30000 --recursive ./tests` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1266 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1266 | `mocha --timeout 20000` | 
| [variety/variety](https://github.com/variety/variety) | 1262 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1254 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1244 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1239 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1236 | `mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1232 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1239 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1236 | `mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1232 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1227 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1222 | `mocha` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1220 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1220 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1210 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1209 | `mocha test/test.js` | 
| [electron/asar](https://github.com/electron/asar) | 1206 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1183 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1180 | `mocha --recursive -r tests/setup tests` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1174 | `mocha` | 
| [x-tag/core](https://github.com/x-tag/core) | 1173 | `NODE_ENV=test mocha --exit` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1170 | `xo && mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1169 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1167 | `mocha $(find test -name '*.test.js') --exit` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1167 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1161 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1159 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1159 | `npm-run-all test:jest test:server:mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1158 | `mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1152 | `istanbul cover _mocha test/*.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1151 | `mocha --reporter spec --bail --check-leaks test/` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1148 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1169 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1167 | `mocha $(find test -name '*.test.js') --exit` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1167 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1164 | `mocha --reporter spec --bail --check-leaks test/` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1161 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1159 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1159 | `npm-run-all test:jest test:server:mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1158 | `mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1152 | `istanbul cover _mocha test/*.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1151 | `mocha --reporter spec --bail --check-leaks test/` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1148 | `mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1140 | `mocha` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1139 | `webpack && mocha test/unit` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1135 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1102 | `npm run convertto:es5 && npm run mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1101 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1101 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1099 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1096 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1095 | `mocha --check-leaks -t 20000` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1093 | `mocha --recursive --bail --reporter spec test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1093 | `eslint src test && mocha --compilers babel-register` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1088 | `mocha --compilers js:babel-register` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1085 | `mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1084 | `mocha test/tests.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1083 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1063 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [tomas/needle](https://github.com/tomas/needle) | 1063 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1057 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1056 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1047 | `mocha $(find test -name '*.test.js')` | 
| [odota/core](https://github.com/odota/core) | 1046 | `NODE_ENV=test mocha --exit` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1043 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1042 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1030 | `mocha --reporter spec --timeout 3000` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1029 | `mocha --recursive test/unit/` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1025 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1047 | `mocha $(find test -name '*.test.js')` | 
| [odota/core](https://github.com/odota/core) | 1046 | `NODE_ENV=test mocha --exit` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1043 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1042 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1030 | `mocha --reporter spec --timeout 3000` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1029 | `mocha --recursive test/unit/` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1025 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1017 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 942 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 941 | `mocha --timeout 5000` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 940 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 939 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 936 | `mocha test --compilers js:babel-register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 936 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 935 | `nyc mocha specs` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 935 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 928 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 927 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 923 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 960 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 957 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 957 | `./node_modules/.bin/mocha --reporter spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 956 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 955 | `mocha -t 600000` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 952 | `mocha tests` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 950 | `mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 949 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 942 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 941 | `mocha --timeout 5000` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 960 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 957 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 957 | `./node_modules/.bin/mocha --reporter spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 956 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 955 | `mocha -t 600000` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 952 | `mocha tests` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 950 | `mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 942 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 941 | `mocha --timeout 5000` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 940 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 939 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 939 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 936 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 936 | `mocha test --compilers js:babel-register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 936 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 935 | `nyc mocha specs` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 935 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 928 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 927 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 923 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 922 | `istanbul cover -- _mocha --reporter spec` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 919 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 916 | `standard && standard ./bin/* && mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 915 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 914 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 914 | `mocha -t 5000` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 912 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 906 | `npm run lint && npm run mocha:no-functional` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 905 | `./node_modules/.bin/mocha test/**/*` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 904 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 902 | `mocha test` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 899 | `mocha test/index.js` | 
| [nimiq-network/core](https://github.com/nimiq-network/core) | 896 | `NODE_ENV=test mocha --exit` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 895 | `node_modules/.bin/mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 892 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 891 | `mocha --timeout 200000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 882 | `node_modules/.bin/mocha test/spec` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 882 | `./node_modules/.bin/mocha --globals angular,require` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 879 | `mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 872 | `npm run build && istanbul test _mocha test/test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 870 | `mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 870 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 867 | `mocha --reporter list` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 866 | `eslint test && mocha --compilers js:babel/register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 864 | `mocha --harmony --full-trace --check-leaks` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 863 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 863 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [developit/decko](https://github.com/developit/decko) | 832 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 829 | `mocha test` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 825 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 825 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 824 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 816 | `npm run mocha-test test/integration` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 816 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 815 | `npm run lint && mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 813 | `mocha --colors --reporter spec test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 812 | `cake build && mocha ./test/mocha/*.coffee` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 809 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 809 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 808 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 807 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 848 | `npm run lint && mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 847 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 844 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 844 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 842 | `mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 842 | `mocha --opts mocha.opts` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 838 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 838 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 838 | `mocha --async-only` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 837 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 835 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 834 | `mocha` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 833 | `mocha -r babel-register --check-leaks test/index.js` | 
| [developit/decko](https://github.com/developit/decko) | 832 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 827 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 827 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 825 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 825 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 824 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 822 | `nyc mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 818 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 818 | `mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 816 | `npm run mocha-test test/integration` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 816 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 815 | `npm run lint && mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 813 | `mocha --colors --reporter spec test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 809 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 808 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 807 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 801 | `_mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 799 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 794 | `mocha --no-timeouts` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 794 | `mocha test` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 794 | `xo && mocha -R spec` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 781 | `mocha test/mocha.js` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 780 | `nyc mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 779 | `mocha --recursive -s 15 test/` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 775 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 773 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 773 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 772 | `mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 769 | `babel-node node_modules/.bin/_mocha -- test` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 784 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 782 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 781 | `mocha test/mocha.js` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 780 | `nyc mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 779 | `mocha --recursive -s 15 test/` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 775 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 773 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 773 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 772 | `mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 771 | `mocha tests --timeout 10000` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 769 | `babel-node node_modules/.bin/_mocha -- test` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 764 | `mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 763 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 763 | `npm run-script jshint && npm run-script mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 762 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 762 | `jenkins-mocha ./tests/*.js` | 
| [susam/texme](https://github.com/susam/texme) | 762 | `standard && mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 757 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [koajs/static](https://github.com/koajs/static) | 757 | `mocha --harmony --reporter spec --exit` | 