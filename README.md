# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:23 12/29/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44746 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41893 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41676 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30750 | `mocha --async-only` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24712 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21156 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19934 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18225 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17801 | `mocha` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18225 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17801 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17644 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16804 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14942 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14750 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14635 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13806 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13485 | `mocha --globals document test` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12349 | `mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12228 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12168 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11339 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10990 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10762 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10514 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10374 | `mocha --harmony` | 
| [websockets/ws](https://github.com/websockets/ws) | 10262 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10514 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10374 | `mocha --harmony` | 
| [websockets/ws](https://github.com/websockets/ws) | 10262 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9651 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9632 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9549 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 9399 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9394 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9272 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9240 | `grunt mocha` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8818 | `mocha test/src` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8691 | `mocha --opts mocha.opts` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8646 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8541 | `mocha --check-leaks -R dot` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8512 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8476 | `mocha --compilers js:babel-register test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8429 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8364 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8220 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8011 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7949 | `./node_modules/.bin/mocha test` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7903 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7887 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7785 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7767 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7763 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6923 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6739 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6672 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6505 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6469 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6364 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6233 | `mocha tests/node.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6160 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6123 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6088 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6072 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6061 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6054 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6505 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6469 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6364 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6233 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6189 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6160 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6123 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6088 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6072 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6061 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6054 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5939 | `mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5872 | `standard && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5854 | `mocha && eslint lib/**` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5674 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5642 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5584 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5580 | `npm run lint && mocha tests/**/*.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5506 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5451 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5439 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5409 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5304 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5292 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5252 | `mocha test` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4905 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4859 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4846 | `./node_modules/.bin/mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4838 | `nyc mocha --exit` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4835 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4833 | `mocha test` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4817 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4806 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4784 | `npm run lint && npm run mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4778 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4733 | `mocha --reporter spec -t 8000` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4728 | `nyc mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4574 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4536 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4477 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4733 | `mocha --reporter spec -t 8000` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4728 | `nyc mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4574 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4536 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4506 | `mocha -R spec src` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4506 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4477 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 4405 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4363 | `mocha --timeout=15000 tests/*.test.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4363 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4309 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4261 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4247 | `mocha --check-leaks --reporter spec --bail` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4230 | `nyc mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4218 | `npm run lint ; mocha && mocha test/individual` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4206 | `NODE_ENV=test mocha --exit` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4200 | `mocha -R spec ./test --recursive` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4096 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4075 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4059 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4002 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3945 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3928 | `export TESTING=true; mocha --reporter list` | 
| [expressjs/session](https://github.com/expressjs/session) | 3919 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3862 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3860 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3821 | `NODE_ENV=test mocha test/**/*.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3811 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3793 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [primus/primus](https://github.com/primus/primus) | 3790 | `npm run build && mocha test/*.test.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3726 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3705 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3684 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3539 | `eslint . && mocha -t 5000` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3494 | `nyc mocha && tsc` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3485 | `node_modules/.bin/mocha test/lib/` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3459 | `mocha && tsc -p ./test/types` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3458 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3452 | `mocha` | 
| [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace) | 3421 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3417 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3415 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3374 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3352 | `npm run mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3343 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3339 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3321 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3303 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3375 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3352 | `npm run mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3343 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3339 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3321 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3303 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3282 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3281 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3276 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3275 | `mocha -R landing test/index --exit` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3257 | `mocha test/index.js && npm run demo` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3232 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3225 | `mocha test/*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3205 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3176 | `./node_modules/.bin/mocha test/test.*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3182 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3176 | `./node_modules/.bin/mocha test/test.*.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3176 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3174 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3161 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3133 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 3085 | `mocha --require should --reporter spec` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3061 | `eslint . && nyc mocha --recursive` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3054 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3049 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3007 | `npm run mocha && npm run lint` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3007 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2993 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2970 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2969 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2966 | `node_modules/.bin/mocha --reporter spec` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2947 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2947 | `mocha` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2940 | `mocha test-node` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2937 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2937 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2929 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2928 | `mocha --require @babel/register --recursive spec` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2927 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2907 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2886 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2875 | `mocha -R spec spec spec/reporters` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2867 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [retejs/rete](https://github.com/retejs/rete) | 2723 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2721 | `mocha "./test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2711 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2696 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2693 | `nyc mocha --timeout=10000` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2680 | `mocha --timeout 100000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2675 | `nyc mocha` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2643 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2630 | `mocha-phantomjs ./test/index.html` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2602 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2587 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2571 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2549 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2374 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2372 | `node node_modules/mocha/bin/_mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2356 | `npm run build && mocha --require babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2302 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2297 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [gajus/swing](https://github.com/gajus/swing) | 2290 | `mocha --compilers js:babel-register` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2256 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2240 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2452 | `mocha test/index.js --reporter dot` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2445 | `mocha --no-colors --reporter spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2438 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2434 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2424 | `mocha -R spec` | 
| [Qix-/color](https://github.com/Qix-/color) | 2409 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2392 | `TEST=all mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2374 | `mocha -R spec test/*.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2374 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2374 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2372 | `node node_modules/mocha/bin/_mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2366 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2364 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2364 | `nyc --require babel-register npm run _mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2356 | `npm run build && mocha --require babel-register` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2392 | `TEST=all mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2374 | `mocha -R spec test/*.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2374 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2374 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2372 | `node node_modules/mocha/bin/_mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2366 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2364 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2364 | `nyc --require babel-register npm run _mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2356 | `npm run build && mocha --require babel-register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2317 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2302 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2297 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [gajus/swing](https://github.com/gajus/swing) | 2290 | `mocha --compilers js:babel-register` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2256 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2240 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2218 | `standard && mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 2212 | `npm run lint && npm run mocha` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2210 | `npm run lint && mocha tests/**/*.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2192 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2179 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2179 | `cross-env BABEL_ENV=test mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2170 | `mocha test/runner.js --reporter spec` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2170 | `mocha test/runner.js --reporter spec` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2167 | `mocha && eslint *.js` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2163 | `mocha test/**/*.coffee` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2156 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2144 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2139 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2139 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2131 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2116 | `mocha --compilers js:babel-core/register __tests__` | 
| [share/sharedb](https://github.com/share/sharedb) | 2112 | `./node_modules/.bin/mocha && npm run jshint` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2099 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2081 | `mocha --compilers js:babel-register` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2042 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 2023 | `mocha test/*.test.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2018 | `npm run lint && mocha -R dot && npm run cover` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2010 | `npm run mocha && npm run karma` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2009 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2007 | `mocha --reporter spec --timeout 5000` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2004 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2000 | `mocha tests --require @babel/register` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1999 | `mocha --require=test/test_helper.js` | 
| [then/promise](https://github.com/then/promise) | 1995 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1977 | `mocha && npm run lint` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1967 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1944 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1938 | `mocha test` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1936 | `mocha --reporter spec && npm run test-typescript` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1930 | `mocha test/**/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1929 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1920 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1902 | `npm run lint && mocha --reporter spec test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1889 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1882 | `mocha test` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1880 | `mocha tests.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1870 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1868 | `mocha test -u bdd -R spec` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1853 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1853 | `mocha compiled_tests/` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1835 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1821 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1814 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1798 | `mocha --timeout 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1795 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1781 | `npm run lint && npm run mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1772 | `mocha test/setup.js test/spec/*.js` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1768 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1761 | `eslint --cache . && tsc && mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1759 | `nyc mocha --timeout=20000 test.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1747 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1798 | `mocha --timeout 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1795 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1785 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1781 | `npm run lint && npm run mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1772 | `mocha test/setup.js test/spec/*.js` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1768 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1761 | `eslint --cache . && tsc && mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1759 | `nyc mocha --timeout=20000 test.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1747 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1667 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1664 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1661 | `mocha spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1658 | `mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1644 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1639 | `mocha tests/test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1629 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1617 | `mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1616 | `mocha --reporter spec` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1613 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1605 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1602 | `mocha ./test/test*.js --reporter spec` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1602 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1602 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1601 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1678 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1676 | `standard "./src/*.js" && mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1676 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1674 | `mocha && size-limit` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1673 | `mocha test/test-*.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1668 | `mocha --check-leaks --reporter spec --bail` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1667 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1664 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1661 | `mocha spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1658 | `mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1644 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1639 | `mocha tests/test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1629 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1583 | `NODE_ENV=test mocha tests/*.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1582 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1581 | `mocha --recursive` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1571 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1563 | `nyc mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1557 | `mocha test/unit` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1557 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1556 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1538 | `node_modules/.bin/mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1535 | `mocha -u tdd` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1563 | `nyc mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1557 | `mocha test/unit` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1557 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1556 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1538 | `node_modules/.bin/mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1535 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1529 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1519 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive --exit` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1519 | `mocha --check-leaks --require @babel/register` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1517 | `mocha -R spec ./test/unit/**` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1513 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1507 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1507 | `mocha tests/test-*` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1505 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1501 | `mocha test/**/*.spec.js` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1499 | `mocha --recursive` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1490 | `mocha --timeout 10000 ./tests/lib.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1489 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1489 | `mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1482 | `mocha -R spec test/*.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1481 | `mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1480 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1479 | `npm run lint && mocha && karma start --single-run` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1475 | `mocha -R spec` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1473 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1469 | `npm run lint && npm run mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1459 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1453 | `mocha test.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1448 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1446 | `standard && istanbul cover _mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1445 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1441 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1440 | `mocha --reporter dot` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1440 | `mocha --opts test/opts/mocha.opts` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1437 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1422 | `npm run prepublishOnly && mocha test/test.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1422 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1414 | `npm run build && mocha -r should` | 
| [electron/devtron](https://github.com/electron/devtron) | 1398 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1397 | `mocha --recursive test` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1393 | `mocha --recursive test/bin` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1380 | `mocha test --compilers js:babel-core/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1378 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1375 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1370 | `cross-env NODE_ENV=test nyc mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1369 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1367 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1366 | `./node_modules/.bin/mocha test` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1361 | `NODE_PATH=. mocha **/*.spec.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1370 | `cross-env NODE_ENV=test nyc mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1369 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1367 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1366 | `./node_modules/.bin/mocha test` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1361 | `NODE_PATH=. mocha **/*.spec.js` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1360 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1349 | `mocha --check-leaks --reporter spec --bail test/` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1344 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1343 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1340 | `mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1336 | `mocha --compilers js:babel-core/register` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1332 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1290 | `npm run lint && npm run mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1287 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1287 | `mocha tests/` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1283 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1279 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1279 | `istanbul test _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1277 | `mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1267 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1267 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1264 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1260 | `mocha tests` | 
| [variety/variety](https://github.com/variety/variety) | 1260 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1252 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1222 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1219 | `node ./node_modules/mocha/bin/mocha tests` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1209 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1209 | `mocha test/test.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1204 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1192 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1179 | `mocha --recursive -r tests/setup tests` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1169 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1169 | `xo && mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1168 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1167 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1114 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1112 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1112 | `mocha --reporter spec test --recursive` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1101 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1099 | `mocha test` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1096 | `mocha --check-leaks -t 20000` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1095 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1091 | `mocha --recursive --bail --reporter spec test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1089 | `eslint src test && mocha --compilers babel-register` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1085 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1084 | `mocha test/tests.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1083 | `mocha` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1160 | `mocha --reporter spec --bail --check-leaks test/` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1158 | `npm-run-all test:jest test:server:mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1156 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1156 | `mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1149 | `istanbul cover _mocha test/*.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1149 | `mocha --reporter spec --bail --check-leaks test/` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1148 | `mocha` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1137 | `webpack && mocha test/unit` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1128 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1127 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1126 | `mocha test/*` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1095 | `node_modules/.bin/mocha && npm run lint` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1093 | `npm run convertto:es5 && npm run mocha` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1091 | `mocha --recursive --bail --reporter spec test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1089 | `eslint src test && mocha --compilers babel-register` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1085 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1084 | `mocha test/tests.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1083 | `mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1082 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1030 | `mocha --reporter spec --timeout 3000` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1028 | `mocha --recursive test/unit/` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1018 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1015 | `mocha --colors ./test/*.spec.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1012 | `mocha --reporter spec --bail --check-leaks test/` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1007 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1007 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1002 | `mocha -R list` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1000 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 991 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 989 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 988 | `npm run lint && mocha -R spec` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 987 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 982 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 980 | `mocha --compilers js:babel-register test/*.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 979 | `mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 977 | `mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 977 | `mocha --recursive ./test/*_spec.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 976 | `./node_modules/.bin/mocha -R spec` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 975 | `npm run rollup-cjs && mocha test/test.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 975 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 975 | `mocha "client.test" --compilers js:babel-register` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 973 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 972 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 967 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 958 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 956 | `./node_modules/.bin/mocha --reporter spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 955 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 958 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 956 | `./node_modules/.bin/mocha --reporter spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 955 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 952 | `mocha tests` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 945 | `mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 945 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 941 | `mocha --timeout 5000` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 938 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 936 | `nyc mocha specs` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 936 | `mocha test --compilers js:babel-register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 941 | `mocha --timeout 5000` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 938 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 938 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 936 | `nyc mocha specs` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 936 | `mocha test --compilers js:babel-register` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 935 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 934 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 934 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 930 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 928 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 927 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 922 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 919 | `istanbul cover -- _mocha --reporter spec` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 874 | `mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 868 | `npm run build && istanbul test _mocha test/test.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 867 | `mocha --reporter list` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 865 | `mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 860 | `istanbul cover _mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 860 | `mocha --harmony --full-trace --check-leaks` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 860 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 858 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 857 | `mocha --reporter spec` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 855 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 855 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 851 | `mocha -r should --exit test/*.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 850 | `mocha --reporter spec --bail --check-leaks test/` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 860 | `istanbul cover _mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 860 | `mocha --harmony --full-trace --check-leaks` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 860 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 858 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 857 | `mocha --reporter spec` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 855 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 855 | `mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 855 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 853 | `mocha --check-leaks -t 20000` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 847 | `npm run lint && mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 844 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 843 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 842 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 837 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 837 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 837 | `mocha --async-only` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 866 | `eslint test && mocha --compilers js:babel/register` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 865 | `mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 862 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 860 | `istanbul cover _mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 860 | `mocha --harmony --full-trace --check-leaks` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 860 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 858 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 857 | `mocha --reporter spec` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 855 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 855 | `mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 855 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 853 | `mocha --check-leaks -t 20000` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 851 | `mocha -r should --exit test/*.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 850 | `mocha --reporter spec --bail --check-leaks test/` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 847 | `npm run lint && mocha` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 828 | `mocha --harmony tests/**` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 827 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 825 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 822 | `nyc mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 822 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 818 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 817 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [fossasia/labyrinth](https://github.com/fossasia/labyrinth) | 815 | `./node_modules/.bin/mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 815 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 812 | `cake build && mocha ./test/mocha/*.coffee` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 812 | `npm run lint && mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 807 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 808 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 807 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 805 | `mocha --require babel-register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 794 | `xo && mocha -R spec` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 791 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 808 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 807 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 807 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 805 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 805 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 799 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 796 | `_mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 794 | `mocha --no-timeouts` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 794 | `xo && mocha -R spec` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 791 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 762 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 762 | `jenkins-mocha ./tests/*.js` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 762 | `npm run-script jshint && npm run-script mocha` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 761 | `mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 761 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 756 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 756 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 753 | `./bin/selenium-standalone install && mocha` | 
| [koajs/static](https://github.com/koajs/static) | 753 | `mocha --harmony --reporter spec --exit` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 753 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 752 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 752 | `mocha --reporter spec build/test/index.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 750 | `mocha` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 748 | `mocha test` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 747 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 