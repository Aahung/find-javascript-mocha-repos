# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:34 02/04/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [expressjs/express](https://github.com/expressjs/express) | 42215 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42072 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30869 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25660 | `nyc mocha --timeout=10000 --exit` | 
| [caolan/async](https://github.com/caolan/async) | 25198 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25138 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21430 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20130 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18508 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18508 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18046 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17894 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17419 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15290 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14980 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14712 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13978 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13020 | `mocha 'test/**/*.spec.js'` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12789 | `istanbul cover _mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12493 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12474 | `mocha --require @babel/register --reporter dot` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12356 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12307 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11551 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11202 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11180 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10911 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10655 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10655 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10526 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10429 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9796 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9779 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9710 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9541 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9444 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9418 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9328 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8984 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8917 | `mocha test/src` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8772 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8698 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8601 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8575 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8459 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8327 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8292 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8269 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8128 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8055 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8022 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7992 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7933 | `mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7920 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7877 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5707 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5632 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5577 | `mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 5564 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5414 | `mocha test` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5405 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5347 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5319 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5136 | `mocha --color` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5094 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5064 | `mocha --recursive` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4963 | `gulp build; mocha;` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4960 | `nyc mocha --exit` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6580 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6402 | `npm run test:mocha:src` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6298 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6279 | `mocha tests/node.js` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6259 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6225 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6214 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6143 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6105 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6020 | `standard && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5931 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5891 | `mocha && eslint lib/**` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 5780 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5771 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5771 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5740 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5707 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5632 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5577 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5575 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 5564 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5414 | `mocha test` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5405 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5396 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5347 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4660 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4596 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4581 | `mocha ./test/runner.js` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4484 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4443 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4392 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4381 | `NODE_ENV=test mocha --exit` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4371 | `mocha --check-leaks --reporter spec --bail` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4371 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4325 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4284 | `npm run lint ; mocha && mocha test/individual` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4749 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4660 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4596 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4581 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4556 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4484 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4443 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4392 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4383 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4381 | `NODE_ENV=test mocha --exit` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4371 | `mocha --check-leaks --reporter spec --bail` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4371 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4325 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4284 | `npm run lint ; mocha && mocha test/individual` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4193 | `mocha -R spec ./test --recursive` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4158 | `npm run build && cd test && mocha . --reporter dot` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4129 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4095 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4094 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4074 | `nyc mocha "test/**/*.test.js"` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3947 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3932 | `export TESTING=true; mocha --reporter list` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3947 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3932 | `export TESTING=true; mocha --reporter list` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3831 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3820 | `npm run build && mocha test/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3794 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3786 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3783 | `npm run mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3728 | `eslint . && mocha -t 5000` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3728 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3686 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3670 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3669 | `node_modules/.bin/mocha` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3761 | `mocha && tsc -p ./test/types` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3747 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3737 | `mocha test/* --reporter spec` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3728 | `eslint . && mocha -t 5000` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3728 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3686 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3684 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3670 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3669 | `node_modules/.bin/mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3667 | `npm run jshint && npm run mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3612 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3602 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3594 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3584 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3551 | `nyc mocha && tsc` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3462 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3448 | `mocha` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3441 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3431 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3423 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3397 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3391 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3377 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3374 | `mocha -R landing test/index --exit` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3330 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3315 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3308 | `mocha test/index.js && npm run demo` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3258 | `mocha test/*.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3054 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3040 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3022 | `node_modules/.bin/mocha --reporter spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2998 | `mocha test-node` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2989 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2981 | `mocha --require @babel/register --recursive spec` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2966 | `mocha -R spec --recursive src/test` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2952 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2946 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2917 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2910 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2905 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2899 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2898 | `mocha -R spec spec spec/reporters` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2847 | `istanbul cover _mocha` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2844 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [css/csso](https://github.com/css/csso) | 2822 | `mocha --reporter dot` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2768 | `mocha "./test/**/*-test.js"` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2765 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2763 | `mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2757 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [tj/should.js](https://github.com/tj/should.js) | 2730 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2715 | `nyc mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2715 | `mocha --recursive --watch` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2688 | `mocha --timeout 100000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2633 | `mocha-phantomjs ./test/index.html` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2604 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2592 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2899 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2898 | `mocha -R spec spec spec/reporters` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2847 | `istanbul cover _mocha` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2844 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2838 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [retejs/rete](https://github.com/retejs/rete) | 2826 | `BABEL_ENV=test mocha --compilers js:@babel/register` | 
| [css/csso](https://github.com/css/csso) | 2822 | `mocha --reporter dot` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2787 | `mocha --require should --reporter spec` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2768 | `mocha "./test/**/*-test.js"` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2765 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2763 | `xo && mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2763 | `mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2757 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [tj/should.js](https://github.com/tj/should.js) | 2730 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2720 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2715 | `nyc mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2715 | `mocha --recursive --watch` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2688 | `mocha --timeout 100000` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2680 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2674 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2654 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2633 | `mocha-phantomjs ./test/index.html` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2604 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2592 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2367 | `node node_modules/mocha/bin/_mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2313 | `mocha --compilers js:babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2308 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [pahen/madge](https://github.com/pahen/madge) | 2297 | `npm run lint && npm run mocha` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2262 | `mocha test/**/*.coffee` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2252 | `standard && mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2249 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2249 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2059 | `npm run mocha && npm run karma` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2049 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2046 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2033 | `mocha && npm run lint` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2023 | `mocha test` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2022 | `mocha --reporter spec --timeout 5000` | 
| [then/promise](https://github.com/then/promise) | 2013 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2003 | `mocha --require=test/test_helper.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1989 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1974 | `mocha --require ./test/common --growl test/expect.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1966 | `mocha -c test/index.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1964 | `mocha test/**/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1963 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1959 | `mocha --reporter spec && npm run test-typescript` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1952 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1951 | `mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1951 | `bmocha --reporter spec test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1933 | `npm run lint && mocha --reporter spec test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1933 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1918 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1918 | `mocha test` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1911 | `mocha test/test-*.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1904 | `mocha test -u bdd -R spec` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1904 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1900 | `mocha compiled_tests/` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1892 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1881 | `mocha ./test/basic.js -t 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1879 | `mocha tests.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1864 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1863 | `nyc mocha --timeout=20000 test.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1845 | `npm run lint && npm run mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1829 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1788 | `mocha --recursive` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1780 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1769 | `mocha tests.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1762 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1762 | `npm run lint && mocha && npm run typescript` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1747 | `mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1743 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1742 | `mocha test/*.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1734 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1725 | `mocha ./test/test*.js --reporter spec` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1719 | `mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1718 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1714 | `mocha --check-leaks --reporter spec --bail` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1708 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1708 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1686 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1685 | `mocha && size-limit` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1682 | `mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1672 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1667 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1665 | `mocha spec` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1658 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1654 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1658 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1654 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1637 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1628 | `mocha --reporter spec` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1626 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1625 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1621 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1620 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1616 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1615 | `./node_modules/mocha/bin/mocha -R spec` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1613 | `mocha --recursive` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1611 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1525 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1524 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1521 | `npm run lint && mocha && karma start --single-run` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1520 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1508 | `mocha --timeout 10000 ./tests/lib.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1508 | `mocha test/**/*.spec.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1502 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [noble/bleno](https://github.com/noble/bleno) | 1502 | `mocha -R spec test/*.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1487 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1482 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1474 | `standard && istanbul cover _mocha` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1471 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1469 | `mocha --opts test/opts/mocha.opts` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1364 | `mocha --compilers js:babel-core/register` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1355 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1335 | `lerna run test && mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1330 | `mocha --timeout 60000 test/` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1327 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1327 | `mocha spec/exec.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1323 | `mocha tests/` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1322 | `mocha-phantomjs tests/index.html` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1318 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1310 | `npm run lint && npm run mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1309 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1480 | `mocha --recursive test` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1475 | `npm run prepublishOnly && mocha test/test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1474 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1473 | `mocha --reporter dot` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1471 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1470 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1469 | `mocha --opts test/opts/mocha.opts` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1454 | `mocha test --compilers js:babel-core/register` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1454 | `mocha test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1445 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 1069 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1067 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1067 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1062 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1057 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1034 | `mocha --recursive test/unit/` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1015 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1011 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1007 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1006 | `mocha --check-leaks -R dot` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1002 | `mocha --compilers js:babel-register test/*.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1288 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1274 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1268 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1265 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1263 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1262 | `mocha tests` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1258 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1254 | `mocha --reporter spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1242 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1242 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1238 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1236 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [electron/asar](https://github.com/electron/asar) | 1230 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1226 | `node ./node_modules/mocha/bin/mocha tests` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1212 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1199 | `mocha --recursive -r tests/setup tests` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1182 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1182 | `xo && mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1182 | `mocha --reporter spec --bail --check-leaks test/` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1180 | `mocha test` | 
| [x-tag/core](https://github.com/x-tag/core) | 1174 | `NODE_ENV=test mocha --exit` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1171 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1170 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1170 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1169 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1169 | `mocha $(find test -name '*.test.js') --exit` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1167 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1166 | `mocha --reporter spec test --recursive` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1158 | `mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1156 | `istanbul cover _mocha test/*.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1137 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1137 | `npm run convertto:es5 && npm run mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1130 | `mocha test/*` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1128 | `standard && mocha -b` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1127 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1115 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1113 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1111 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1105 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1104 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1103 | `mocha --recursive --bail --reporter spec test` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1115 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1113 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1111 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1105 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1104 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1103 | `mocha --recursive --bail --reporter spec test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1103 | `eslint src test && mocha --compilers babel-register` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1099 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1098 | `node_modules/.bin/mocha && npm run lint` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1096 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1096 | `mocha --check-leaks -t 20000` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1090 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1090 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1086 | `mocha test/tests.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1086 | `mocha test/tests.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [tomas/needle](https://github.com/tomas/needle) | 1069 | `mocha test` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1069 | `npm run lint && npm run mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1067 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1067 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1062 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1057 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1057 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [odota/core](https://github.com/odota/core) | 1052 | `NODE_ENV=test mocha --exit` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1049 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1046 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1034 | `mocha --recursive test/unit/` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1034 | `mocha test/*.test.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1027 | `mocha --reporter spec --bail --check-leaks test/` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1027 | `mocha --reporter spec --timeout 3000` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 1026 | `mocha --recursive ./test/*_spec.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1025 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1022 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 990 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 987 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 986 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 986 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 983 | `mocha --reporter spec` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 981 | `mocha "client.test" --compilers js:babel-register` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 977 | `npm run rollup-cjs && mocha test/test.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 972 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 966 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 966 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 964 | `mocha tests` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 964 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 964 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 963 | `./node_modules/.bin/mocha --reporter spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 966 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 966 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 964 | `mocha tests` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 964 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 963 | `./node_modules/.bin/mocha --reporter spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 961 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 959 | `nyc mocha specs` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 952 | `mocha test --compilers js:babel-register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 950 | `mocha` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 948 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 947 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 964 | `mocha tests` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 964 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 964 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 963 | `./node_modules/.bin/mocha --reporter spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 962 | `mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 961 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 959 | `nyc mocha specs` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 952 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 950 | `mocha` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 948 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 947 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 913 | `mocha test/index.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 912 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 910 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 909 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 907 | `npm run lint && npm run mocha:no-functional` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [nimiq-network/core](https://github.com/nimiq-network/core) | 899 | `NODE_ENV=test mocha --exit` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 899 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 897 | `node_modules/.bin/mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 894 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 889 | `mocha -r should --exit test/*.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 888 | `node_modules/.bin/mocha test/spec` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 887 | `npm run build && istanbul test _mocha test/test.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 887 | `npm run build && istanbul test _mocha test/test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 886 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 885 | `mocha --harmony --full-trace --check-leaks` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 877 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 877 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 868 | `istanbul cover _mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 865 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 865 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 863 | `mocha --reporter spec` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 860 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 862 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 861 | `mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 860 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 859 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 858 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 858 | `mocha --harmony tests/**` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 857 | `mocha --reporter spec --bail --check-leaks test/` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 856 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 855 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 855 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 853 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 851 | `npm run lint && mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 851 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 849 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 849 | `mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 849 | `npm run lint && mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 847 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 845 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 845 | `mocha --opts mocha.opts` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 843 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 839 | `mocha --async-only` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 835 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 835 | `mocha test` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 833 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 829 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 829 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 828 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 826 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 825 | `mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 823 | `npm run mocha-test test/integration` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 813 | `cake build && mocha ./test/mocha/*.coffee` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 812 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 811 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 809 | `mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 807 | `mocha index.test.js` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 804 | `mocha test` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 804 | `mocha test/mocha.js` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 802 | `_mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 800 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 811 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 809 | `mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 808 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 807 | `mocha index.test.js` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 804 | `mocha test` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 804 | `mocha test/mocha.js` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 802 | `_mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 800 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 800 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 799 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 797 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 796 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 796 | `xo && mocha -R spec` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 795 | `mocha` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 795 | `mocha` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 795 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 790 | `nyc mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 790 | `npm run lint && npm run mocha` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 787 | `mocha test` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 783 | `mocha --recursive -s 15 test/` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 751 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 750 | `mocha 'test/**/*.tests.js'` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 748 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 744 | `npm run test-mocha && npm run test-karma` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 744 | `mocha test.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 742 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 740 | `npm run bundle && mocha` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 763 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 762 | `mocha --reporter spec build/test/index.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 761 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 761 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 760 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 760 | `./bin/selenium-standalone install && mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 751 | `mocha tests/*.mocha.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 751 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 750 | `mocha 'test/**/*.tests.js'` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 748 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 737 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 736 | `mocha --compilers js:babel-core/register` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 734 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 733 | `./node_modules/.bin/mocha tests/*.js` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 732 | `mocha` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 731 | `mocha --reporter spec --bail --check-leaks test/` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 730 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 730 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 728 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 728 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 727 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 724 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 723 | `mocha ./test/index.js` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 683 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 682 | `mocha --bail test/` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 679 | `mocha -R spec` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 679 | `mocha --compilers js:babel-register` | 
| [afc163/fanyi](https://github.com/afc163/fanyi) | 677 | `npm run lint && mocha tests/index.js --timeout 0` | 
| [fin-hypergrid/core](https://github.com/fin-hypergrid/core) | 675 | `NODE_ENV=test mocha --exit` | 
| [Savjee/SavjeeCoin](https://github.com/Savjee/SavjeeCoin) | 675 | `mocha tests/*.test.js` | 
| [Kagami/ffmpeg.js](https://github.com/Kagami/ffmpeg.js) | 673 | `mocha test/test.js` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 672 | `mocha --require babel-register` | 
| [shime/livedown](https://github.com/shime/livedown) | 671 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 671 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [apollographql/eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) | 665 | `tav --ci && mocha test/index.js` | 