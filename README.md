# Find Repos in JavaScript Tested using Mocha

The list was updated at 01:02:41 03/21/19 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45614 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42944 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42483 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 31007 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 26084 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25719 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25347 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21976 | `npm-run-all lint build --parallel test:mocha test:karma test:ts` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20373 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18971 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18403 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18213 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 18063 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15714 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15277 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14814 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14183 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11833 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11656 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11415 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 11100 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [websockets/ws](https://github.com/websockets/ws) | 10876 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10816 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10531 | `mocha --harmony` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9924 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9780 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9701 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9515 | `mocha -b -r esm` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 11100 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [websockets/ws](https://github.com/websockets/ws) | 10876 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10816 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10531 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 10113 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9924 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9780 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9701 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9645 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9515 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9414 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9393 | `mocha --opts mocha.opts` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 9143 | `mocha test/*/**` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 9125 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9054 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8756 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8682 | `mocha --compilers js:babel-register test/test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8661 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8601 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8527 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8452 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8321 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8296 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8295 | `mocha` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8213 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8133 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8124 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8121 | `./node_modules/.bin/mocha test` | 
| [aui/art-template](https://github.com/aui/art-template) | 7995 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7452 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7418 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7276 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7176 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7158 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7108 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6664 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6466 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6451 | `npm run test:mocha:src` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6383 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6357 | `mocha tests/node.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6326 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6290 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6278 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6235 | `standard && mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 6187 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6169 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6068 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 6044 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5983 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5944 | `mocha && eslint lib/**` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5921 | `mocha` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5902 | `npm run lint && mocha tests/**/*.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5855 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6068 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 6044 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5983 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5944 | `mocha && eslint lib/**` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5921 | `mocha` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5902 | `npm run lint && mocha tests/**/*.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5855 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5781 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5778 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5645 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5584 | `mocha test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5540 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5521 | `mocha -r esm` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5499 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5442 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5398 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5217 | `mocha --recursive` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5212 | `mocha src/**/*Tests.js --harmony` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5177 | `npm run lint && npm run mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5154 | `gulp lint && mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5140 | `nyc mocha --exit` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 5134 | `NODE_ENV=test mocha --exit` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5124 | `mocha --color` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5099 | `nyc mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 5015 | `gulp build; mocha;` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 5001 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4934 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4925 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4898 | `mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4892 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4876 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4858 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4765 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4726 | `mocha -R spec src` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 4666 | `./node_modules/mocha/bin/mocha --require @babel/register test/*` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4601 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4594 | `mocha ./test/runner.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4576 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4549 | `mocha --timeout=15000 tests/*.test.js` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4531 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4497 | `mocha --check-leaks --reporter spec --bail` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4495 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 4481 | `npm run mocha` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4425 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4402 | `npm run lint && mocha && mocha test/individual && if [ "$TRAVIS_PULL_REQUEST" = "false" ]; then snyk test; fi` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4400 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4293 | `npm run build && cd test && mocha . --reporter dot` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4187 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4172 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4132 | `mocha --require should --reporter spec` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4101 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 4062 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4101 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 4062 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 4018 | `NODE_ENV=test mocha test/**/*.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3987 | `mocha && tsc -p ./test/types` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3963 | `eslint . && mocha -t 5000` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3941 | `export TESTING=true; mocha --reporter list` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3856 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3852 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [primus/primus](https://github.com/primus/primus) | 3847 | `npm run build && mocha test/*.test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3839 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3835 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3797 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [erming/shout](https://github.com/erming/shout) | 3797 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3780 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3771 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3761 | `mocha test/* --reporter spec` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3706 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3701 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3696 | `node_modules/.bin/mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3680 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3672 | `npm run jshint && npm run mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3632 | `nyc mocha && tsc` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3626 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3619 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3611 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3610 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3608 | `mocha tests/javascript` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3574 | `mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3384 | `mocha test/index.js && npm run demo` | 
| [mde/ejs](https://github.com/mde/ejs) | 3342 | `mocha --require should --reporter spec` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3320 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3307 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3302 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3299 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3244 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3205 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3201 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3194 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3184 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3164 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3141 | `nyc mocha --recursive` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2993 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2989 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2988 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2960 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2929 | `mocha -R spec spec spec/reporters` | 
| [github-tools/github](https://github.com/github-tools/github) | 2926 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2924 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2852 | `mocha "./test/**/*-test.js"` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2851 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2843 | `mocha --reporter dot` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2811 | `mocha` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3141 | `nyc mocha --recursive` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3124 | `npm run mocha && npm run lint` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3096 | `node_modules/.bin/mocha --reporter spec` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 3076 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 3075 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3074 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3069 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3067 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 3048 | `mocha --require @babel/register --recursive spec` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3035 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3034 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2998 | `mocha -R spec --recursive src/test` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2993 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2989 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2988 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [zeit/ms](https://github.com/zeit/ms) | 1986 | `mocha tests.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1975 | `mocha --bail --reporter spec --check-leaks test/` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1974 | `npm run lint && mocha --reporter spec test/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1960 | `mocha --reporter spec --grep .` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1960 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1950 | `mocha test` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1939 | `mocha ./test/basic.js -t 5000` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1920 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1900 | `mocha ./test/test*.js --reporter spec` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1887 | `mocha tests.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1864 | `npm run lint && npm run mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1862 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2743 | `mocha test/unit --require mochahook` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2734 | `mocha --recursive --watch` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2726 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2712 | `mocha --timeout 100000` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2709 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2656 | `mocha-phantomjs ./test/index.html` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2652 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2647 | `TEST=all mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2620 | `mocha && eslint .` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2619 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2598 | `mocha test/src/**/*.unit.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2597 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1950 | `mocha test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1941 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1900 | `mocha ./test/test*.js --reporter spec` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1887 | `mocha tests.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1882 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1866 | `mocha test/setup.js test/spec/*.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1864 | `npm run lint && npm run mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1826 | `mocha test` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2031 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2021 | `mocha --require=test/test_helper.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 2018 | `mocha test/**/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 2001 | `mocha --reporter spec && npm run test-typescript` | 
| [zeit/ms](https://github.com/zeit/ms) | 1986 | `mocha tests.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1980 | `bmocha --reporter spec test/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1975 | `mocha --bail --reporter spec --check-leaks test/` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1974 | `npm run lint && mocha --reporter spec test/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1960 | `mocha --reporter spec --grep .` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1960 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1950 | `mocha test` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1939 | `mocha ./test/basic.js -t 5000` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1926 | `eslint --cache . && tslint --project . && node build && mocha && tsc` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1920 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1866 | `mocha test/setup.js test/spec/*.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1864 | `npm run lint && npm run mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1862 | `mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1828 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1827 | `mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1826 | `mocha test` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1822 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1808 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1794 | `mocha --timeout 5000` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1769 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1766 | `mocha test/*.js` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1748 | `./node_modules/.bin/mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1747 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1742 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1739 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1725 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1723 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1707 | `NODE_ENV=test mocha tests/*.js` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1731 | `mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1730 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1730 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1725 | `mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1723 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1723 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1707 | `NODE_ENV=test mocha tests/*.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1696 | `mocha && size-limit` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1695 | `npm run jshint && mocha --recursive` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1676 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1665 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1660 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1651 | `mocha --recursive` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1647 | `mocha --reporter spec` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1647 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1646 | `mocha --expose-gc --slow 300` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1645 | `mocha test/unit` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1647 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1646 | `mocha --expose-gc --slow 300` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1645 | `mocha test/unit` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1638 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1632 | `mocha test.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1631 | `mocha tests/test-*` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1624 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1617 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1588 | `npm run lint && npm run mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1590 | `nyc mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1588 | `npm run lint && npm run mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1575 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1570 | `mocha` | 
| [fbeline/design-patterns-JS](https://github.com/fbeline/design-patterns-JS) | 1568 | `mocha test --compilers js:babel-core/register` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1564 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1564 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1560 | `node_modules/.bin/mocha --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1559 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1555 | `mocha --recursive test` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1553 | `mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1550 | `npm run test:lint && npm run test:mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1549 | `mocha -u tdd` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1545 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1553 | `mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1549 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1549 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1549 | `mocha -u tdd` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1545 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1538 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [noble/bleno](https://github.com/noble/bleno) | 1533 | `mocha -R spec test/*.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1532 | `mocha --timeout 10000 ./tests/lib.js` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1530 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1529 | `mocha test/**/*.spec.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1528 | `standard && istanbul cover _mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1518 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1515 | `mocha --reporter dot` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1509 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1502 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1464 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1456 | `mocha test.js` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1449 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1447 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1435 | `mocha --recursive test/bin` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1433 | `mocha --check-leaks --reporter spec --bail test/` | 
| [electron/devtron](https://github.com/electron/devtron) | 1428 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1426 | `istanbul cover _mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1394 | `NODE_PATH=. mocha **/*.spec.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1391 | `./node_modules/.bin/mocha test` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1390 | `./node_modules/mocha/bin/mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1386 | `mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1384 | `npm run lint && mocha --require @babel/register` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1382 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1379 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1377 | `cross-env NODE_ENV=test nyc mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1361 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1361 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1360 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1360 | `mocha --timeout 20000` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1354 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1354 | `mocha --timeout 30000 --recursive ./tests` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1354 | `mocha --timeout 60000 test/` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1351 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1348 | `mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1435 | `mocha --recursive test/bin` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1433 | `mocha --check-leaks --reporter spec --bail test/` | 
| [electron/devtron](https://github.com/electron/devtron) | 1428 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1427 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1426 | `istanbul cover _mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1420 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1412 | `mocha --compilers js:babel-core/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1410 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1408 | `mocha --recursive` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1406 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1400 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1399 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1394 | `NODE_PATH=. mocha **/*.spec.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1391 | `./node_modules/.bin/mocha test` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1390 | `./node_modules/mocha/bin/mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1386 | `mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1384 | `npm run lint && mocha --require @babel/register` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1382 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1379 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1377 | `cross-env NODE_ENV=test nyc mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1375 | `mocha tests/` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1361 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1361 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1360 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1360 | `mocha --timeout 20000` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1354 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1354 | `mocha --timeout 30000 --recursive ./tests` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1354 | `mocha --timeout 60000 test/` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1351 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1348 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1343 | `mocha test/*.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1339 | `mocha src/test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1339 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1330 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1328 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1315 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1315 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1306 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1304 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1293 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1306 | `mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1305 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1304 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1304 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [variety/variety](https://github.com/variety/variety) | 1293 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1274 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1270 | `mocha --reporter spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1267 | `mocha tests` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1265 | `mocha test` | 
| [electron/asar](https://github.com/electron/asar) | 1263 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1258 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1241 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1232 | `node ./node_modules/mocha/bin/mocha tests` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1227 | `mocha --reporter spec test --recursive` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1227 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1225 | `mocha --recursive -r tests/setup tests` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1222 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1218 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1217 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1215 | `npm-run-all test:jest test:server:mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1210 | `mocha test/test.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1197 | `xo && mocha` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1196 | `npm run lint && npm run mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1218 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1217 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1215 | `npm-run-all test:jest test:server:mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1214 | `mocha test` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1210 | `mocha test/test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1207 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1197 | `xo && mocha` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1196 | `npm run lint && npm run mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1190 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1187 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1183 | `mocha $(find test -name '*.test.js') --exit` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1178 | `npm run convertto:es5 && npm run mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1178 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1183 | `mocha $(find test -name '*.test.js') --exit` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1178 | `npm run convertto:es5 && npm run mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1178 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1172 | `mocha` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1170 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1170 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1164 | `istanbul cover _mocha test/*.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1163 | `webpack && mocha test/unit` | 
| [electron/spectron](https://github.com/electron/spectron) | 1162 | `mocha && standard` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1158 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1030 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1028 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 1026 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1024 | `mocha --reporter spec --timeout 3000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1013 | `mocha --compilers js:babel-register test/*.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 995 | `mocha "client.test" --compilers js:babel-register` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 990 | `mocha tests` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 1032 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1030 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1030 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1028 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1022 | `mocha --async-only` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1020 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1013 | `mocha --compilers js:babel-register test/*.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1010 | `mocha -R list` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1008 | `mocha --check-leaks -R dot` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 996 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 995 | `mocha "client.test" --compilers js:babel-register` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 990 | `mocha tests` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 990 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 988 | `mocha` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 987 | `mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 985 | `mocha --reporter spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 978 | `./node_modules/.bin/mocha --reporter spec` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 977 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 977 | `./node_modules/.bin/mocha test/**/*` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 976 | `nyc mocha specs` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 973 | `mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 970 | `standard && standard ./bin/* && mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 977 | `./node_modules/.bin/mocha test/**/*` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 976 | `nyc mocha specs` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 973 | `mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 970 | `standard && standard ./bin/* && mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 967 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 965 | `mocha` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 957 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 957 | `istanbul cover -- _mocha --reporter spec` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 962 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 957 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 957 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 957 | `istanbul cover -- _mocha --reporter spec` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 952 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 952 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 944 | `mocha test/index.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 941 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 938 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 937 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 936 | `mocha --timeout 5000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 930 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 928 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 921 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 919 | `mocha --harmony tests/**` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 909 | `mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 909 | `npm run build && istanbul test _mocha test/test.js` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 909 | `npm run lint && mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 905 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 901 | `node_modules/.bin/mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 909 | `mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 909 | `npm run build && istanbul test _mocha test/test.js` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 909 | `npm run lint && mocha` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 906 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 905 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 902 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 902 | `mocha --harmony --full-trace --check-leaks` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 901 | `node_modules/.bin/mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 898 | `mocha --timeout 200000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 893 | `node_modules/.bin/mocha test/spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 892 | `mocha --reporter list` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 878 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 875 | `istanbul cover _mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 875 | `mocha --reporter list` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 874 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 874 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 873 | `mocha` | 
| [developit/decko](https://github.com/developit/decko) | 870 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 870 | `mocha --reporter spec` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 870 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 869 | `mocha -r babel-register --check-leaks test/index.js` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 869 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 866 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 865 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 864 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 864 | `eslint test && mocha --compilers js:babel/register` | 
| [ebradyjobory/finance.js](https://github.com/ebradyjobory/finance.js) | 861 | `mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 860 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 842 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 842 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 841 | `mocha --async-only` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 838 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 836 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 836 | `npm run mocha-test test/integration` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 833 | `mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 833 | `mocha && ember test` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 832 | `_mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 832 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 829 | `cake build && mocha ./test/mocha/*.coffee` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 827 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 826 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 824 | `eslint . && mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 822 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 820 | `mocha --colors --reporter spec test.js` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 819 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 853 | `mocha` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 853 | `mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 852 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 851 | `mocha --check-leaks -t 20000` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 847 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 846 | `mocha test` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 845 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 845 | `ts-mocha test/` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 842 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 842 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 841 | `mocha --async-only` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 840 | `mocha test/mocha.js test/crc/index.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 838 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 837 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 836 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 836 | `npm run mocha-test test/integration` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 819 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 815 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 814 | `mocha` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 808 | `jenkins-mocha ./tests/*.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 807 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 803 | `nyc mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 819 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 814 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 811 | `mocha test` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 808 | `jenkins-mocha ./tests/*.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 807 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 803 | `nyc mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 800 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 796 | `mocha --recursive -s 15 test/` | 
| [fivdi/onoff](https://github.com/fivdi/onoff) | 796 | `nyc mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 796 | `npm run lint && npm run mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 795 | `mocha tests --timeout 10000` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [koajs/static](https://github.com/koajs/static) | 792 | `mocha --harmony --reporter spec --exit` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 790 | `mocha -u tdd` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 790 | `npm run lint&&mocha tests/*.js` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 759 | `mocha --reporter spec --bail --check-leaks test/` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 758 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 757 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 755 | `npm run test-mocha && npm run test-karma` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 755 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 752 | `mocha tests/*.mocha.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 752 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [formio/formio](https://github.com/formio/formio) | 749 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 746 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 746 | `mocha --compilers js:babel-core/register` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 744 | `mocha $(find test -name '*.test.js')` | 
| [justinfagnani/mixwith.js](https://github.com/justinfagnani/mixwith.js) | 600 | `mocha build/test` | 
| [csstree/csstree](https://github.com/csstree/csstree) | 600 | `mocha --reporter progress` | 
| [matthewmueller/graph.ql](https://github.com/matthewmueller/graph.ql) | 599 | `./node_modules/.bin/mocha` | 
| [mhart/kinesalite](https://github.com/mhart/kinesalite) | 597 | `mocha --require should --reporter spec -t $([ $REMOTE ] && echo 30s || echo 4s)` | 
| [putaoshu/jdf](https://github.com/putaoshu/jdf) | 597 | `mocha test/index.js` | 
| [SamyPesse/gitkit-js](https://github.com/SamyPesse/gitkit-js) | 596 | `./node_modules/.bin/mocha ./testing/setup.js ./lib/**/*/__tests__/*.js --bail --reporter=list` | 
| [ck86/main-bower-files](https://github.com/ck86/main-bower-files) | 596 | `mocha` | 
| [jkphl/gulp-svg-sprite](https://github.com/jkphl/gulp-svg-sprite) | 596 | `gulp && istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [jimpick/lambda-comments](https://github.com/jimpick/lambda-comments) | 595 | `mocha --compilers js:./babel-register` | 
| [bitovi/documentjs](https://github.com/bitovi/documentjs) | 593 | `mocha test/test.js --reporter spec` | 
| [mhart/dynalite](https://github.com/mhart/dynalite) | 592 | `mocha --require should --reporter spec -t $([ $REMOTE ] && echo 30s || echo 4s)` | 
| [gsuitedevs/apps-script-oauth2](https://github.com/gsuitedevs/apps-script-oauth2) | 588 | `mocha` | 
| [gridcontrol/gridcontrol](https://github.com/gridcontrol/gridcontrol) | 587 | `NODE_ENV='test' DEBUG='gc:*' ./node_modules/.bin/mocha test/*.mocha.js -b` | 
| [JoshKaufman/ursa](https://github.com/JoshKaufman/ursa) | 583 | `mocha --recursive --reporter spec` | 