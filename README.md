# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:09 12/15/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44605 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41818 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41488 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [caolan/async](https://github.com/caolan/async) | 25022 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24536 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21038 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18110 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17690 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17550 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16622 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14807 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14657 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14606 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13763 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13421 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12925 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12672 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12590 | `istanbul cover _mocha` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12548 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12327 | `mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12135 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12101 | `nyc grunt mocha-and-karma` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12072 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11246 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10921 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10759 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10712 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10509 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10493 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10332 | `mocha --harmony` | 
| [websockets/ws](https://github.com/websockets/ws) | 10197 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9625 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9583 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9449 | `mocha tests/*.js` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9387 | `mocha -b -r esm` | 
| [amark/gun](https://github.com/amark/gun) | 9220 | `mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9214 | `grunt mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9200 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8777 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8632 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8531 | `mocha --check-leaks -R dot` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8434 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8413 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8391 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8356 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8194 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8006 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7919 | `./node_modules/.bin/mocha test` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7808 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7806 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7729 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7720 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7714 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5834 | `mocha && eslint lib/**` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5643 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5632 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5562 | `npm run lint && mocha tests/*/*/*.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5526 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5414 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5407 | `mocha` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5273 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5269 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5210 | `mocha test` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5137 | `mocha --color` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5109 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5090 | `gulp lint && mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6480 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6359 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6341 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6197 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6175 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6113 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6086 | `mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6046 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6042 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6024 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5834 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5821 | `standard && mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5643 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5632 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5562 | `npm run lint && mocha tests/*/*/*.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5526 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5420 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5414 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5407 | `mocha` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5273 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5269 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5210 | `mocha test` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5201 | `mocha src/**/*Tests.js --harmony` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4850 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4825 | `mocha -R spec 'tests/app'` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4820 | `./node_modules/.bin/mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4815 | `mocha test` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4797 | `nyc mocha --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4791 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4758 | `npm run lint && npm run mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4730 | `mocha --reporter spec -t 8000` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4712 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4688 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4681 | `nyc mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4572 | `mocha ./test/runner.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4561 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4522 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4476 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4151 | `NODE_ENV=test mocha --exit` | 
| [muicss/mui](https://github.com/muicss/mui) | 4105 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4094 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4068 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4042 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3980 | `nyc mocha "test/**/*.test.js"` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3924 | `export TESTING=true; mocha --reporter list` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3911 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3887 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3864 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3827 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [erming/shout](https://github.com/erming/shout) | 3794 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3783 | `NODE_ENV=test mocha test/**/*.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3682 | `standard && mocha --timeout 60000 test/test.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3682 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3674 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3669 | `npm run jshint && npm run mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3648 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3628 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3626 | `node_modules/.bin/mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3575 | `mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3554 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3519 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3479 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3453 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3408 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3479 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3458 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3453 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3408 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3359 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3338 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3328 | `mocha && tsc -p ./test/types` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3265 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3267 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3265 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3231 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3216 | `mocha -R landing test/index --exit` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3214 | `mocha test/*.js` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3214 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3195 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3174 | `./node_modules/.bin/mocha test/test.*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3167 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3163 | `mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3159 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3159 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3130 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3123 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3062 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [mde/ejs](https://github.com/mde/ejs) | 3047 | `mocha --require should --reporter spec` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3047 | `eslint . && nyc mocha --recursive` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3047 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3062 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [mde/ejs](https://github.com/mde/ejs) | 3047 | `mocha --require should --reporter spec` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3047 | `eslint . && nyc mocha --recursive` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3047 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3030 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2988 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2972 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2953 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2944 | `node_modules/.bin/mocha --reporter spec` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2943 | `mocha -R spec --recursive src/test` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2941 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2937 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2712 | `mocha "./test/**/*-test.js"` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2703 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2695 | `mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 2694 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2686 | `mocha --recursive --watch` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2677 | `mocha --timeout 100000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2665 | `nyc mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2628 | `mocha-phantomjs ./test/index.html` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 2618 | `npm run build && mocha test/bootstrap.js --recursive test` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2616 | `mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2587 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2556 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2532 | `export TESTING=true; mocha --reporter list` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2526 | `mocha test` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2556 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2542 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2532 | `export TESTING=true; mocha --reporter list` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2526 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2517 | `mocha test/src/**/*.unit.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2502 | `mocha --reporter=spec test/*-test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2490 | `nyc --reporter=html --reporter=text mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2488 | `mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2484 | `mocha test --exit && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2468 | `mocha && eslint .` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2444 | `mocha --no-colors --reporter spec` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2440 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2437 | `mocha test/index.js --reporter dot` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2431 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2421 | `mocha -R spec` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2468 | `mocha && eslint .` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2440 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2437 | `mocha test/index.js --reporter dot` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2431 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2422 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2421 | `mocha -R spec` | 
| [Qix-/color](https://github.com/Qix-/color) | 2393 | `mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2375 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2372 | `node node_modules/mocha/bin/_mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2363 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2353 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2334 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2329 | `npm run build && mocha --require babel-register` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2322 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2375 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2372 | `node node_modules/mocha/bin/_mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2363 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2353 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2329 | `npm run build && mocha --require babel-register` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2322 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2318 | `nyc --require babel-register npm run _mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2316 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2298 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [gajus/swing](https://github.com/gajus/swing) | 2284 | `mocha --compilers js:babel-register` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2278 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2210 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2210 | `standard && mocha` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2201 | `npm run lint && mocha tests/*/*/*.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2189 | `npm run lint && npm run mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2174 | `cross-env BABEL_ENV=test mocha` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2154 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2151 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2150 | `mocha && eslint *.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2141 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2139 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2137 | `mocha` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2124 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2101 | `mocha --compilers js:babel-core/register __tests__` | 
| [share/sharedb](https://github.com/share/sharedb) | 2095 | `./node_modules/.bin/mocha && npm run jshint` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2088 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2210 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2210 | `standard && mocha` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2201 | `npm run lint && mocha tests/*/*/*.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2189 | `npm run lint && npm run mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2180 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2174 | `cross-env BABEL_ENV=test mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2157 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2154 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2151 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2150 | `mocha && eslint *.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2141 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2139 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2137 | `mocha` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2124 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2101 | `mocha --compilers js:babel-core/register __tests__` | 
| [share/sharedb](https://github.com/share/sharedb) | 2095 | `./node_modules/.bin/mocha && npm run jshint` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2088 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2047 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2045 | `mocha --compilers js:babel-register` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2033 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2027 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [kach/nearley](https://github.com/kach/nearley) | 2014 | `mocha test/*.test.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2011 | `npm run lint && mocha -R dot && npm run cover` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2008 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2004 | `npm run mocha && npm run karma` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2002 | `mocha --reporter spec --timeout 5000` | 
| [slate/slate](https://github.com/slate/slate) | 1996 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2002 | `mocha --reporter spec --timeout 5000` | 
| [slate/slate](https://github.com/slate/slate) | 1996 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1994 | `mocha --require=test/test_helper.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1988 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1963 | `mocha -c test/index.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1955 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1955 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1954 | `mocha --require ./test/common --growl test/expect.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1949 | `mocha && npm run lint` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1942 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1942 | `mocha tests --require @babel/register` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1927 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1921 | `mocha --reporter spec && npm run test-typescript` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1832 | `mocha compiled_tests/` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1829 | `mocha ./test/basic.js -t 5000` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1820 | `mocha test` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1819 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1813 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1798 | `mocha --timeout 5000` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1766 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1765 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1758 | `mocha test/setup.js test/spec/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1750 | `eslint --cache . && tsc && mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1798 | `mocha --timeout 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1794 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1773 | `npm run lint && npm run mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1766 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1765 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1758 | `mocha test/setup.js test/spec/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1750 | `eslint --cache . && tsc && mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1747 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1735 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1731 | `npm run lint && mocha && npm run typescript` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1730 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1728 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1721 | `mocha test/*.js` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1721 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1735 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1732 | `./node_modules/.bin/mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1731 | `npm run lint && mocha && npm run typescript` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1730 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1728 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1721 | `mocha test/*.js` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1721 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1718 | `mocha test --timeout 600000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1717 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1714 | `mocha tests.js` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1710 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1705 | `TEST=all mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1698 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1696 | `mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1691 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1690 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1670 | `mocha && size-limit` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1665 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1665 | `xo && mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1658 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1655 | `mocha spec` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1655 | `mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1653 | `mocha` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1652 | `mocha test/test-*.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1647 | `mocha --check-leaks --reporter spec --bail` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1643 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1637 | `mocha tests/test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1635 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1623 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1496 | `mocha -R spec ./test/unit/**` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1494 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1484 | `mocha --timeout 10000 ./tests/lib.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1481 | `mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1474 | `mocha -R spec test/*.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1467 | `mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1464 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1461 | `npm run lint && mocha && karma start --single-run` | 
| [samccone/drool](https://github.com/samccone/drool) | 1457 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1452 | `mocha test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1439 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1436 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1433 | `standard && istanbul cover _mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1429 | `mocha --opts test/opts/mocha.opts` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1422 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1420 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1425 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1422 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1406 | `mocha --recursive` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1401 | `istanbul cover _mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1393 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [electron/devtron](https://github.com/electron/devtron) | 1392 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1385 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1382 | `mocha --recursive` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1381 | `mocha --recursive test/bin` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1375 | `mocha --recursive test` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1367 | `./node_modules/.bin/mocha test` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1367 | `mocha test --compilers js:babel-core/register` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1531 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1530 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1526 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1509 | `mocha --check-leaks --require @babel/register` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1500 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1500 | `mocha test/**/*.spec.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1499 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1498 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1496 | `mocha -R spec ./test/unit/**` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1496 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive --exit` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1494 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1491 | `mocha tests/test-*` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1484 | `mocha --timeout 10000 ./tests/lib.js` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1406 | `mocha --recursive` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1401 | `istanbul cover _mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1394 | `npm run prepublishOnly && mocha test/test.js` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1393 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [electron/devtron](https://github.com/electron/devtron) | 1392 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1385 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1382 | `mocha --recursive` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1375 | `mocha --recursive test` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1368 | `cross-env NODE_ENV=test nyc mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1367 | `./node_modules/.bin/mocha test` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1367 | `mocha test --compilers js:babel-core/register` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1352 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1349 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1346 | `NODE_PATH=. mocha **/*.spec.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1342 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1340 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1340 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1337 | `mocha --check-leaks --reporter spec --bail test/` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1335 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1329 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1325 | `mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1324 | `mocha --compilers js:babel-core/register` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1311 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1310 | `webpack && npm run lint && npm run mocha` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1309 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1308 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1306 | `mocha --timeout 60000 test/` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1303 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1297 | `npm run mocha:istanbul` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1294 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1287 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1284 | `npm run lint && npm run mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1283 | `mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1276 | `npm run lint && mocha --require @babel/register` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1274 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1271 | `istanbul test _mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1271 | `mocha tests/` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1269 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1276 | `npm run lint && mocha --require @babel/register` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1274 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1271 | `istanbul test _mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1271 | `mocha tests/` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1269 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1265 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1265 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1264 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1261 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1258 | `mocha tests` | 
| [router5/router5](https://github.com/router5/router5) | 1255 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1254 | `mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1253 | `mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1247 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [variety/variety](https://github.com/variety/variety) | 1245 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1223 | `mocha --timeout 20000` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1219 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1217 | `node ./node_modules/mocha/bin/mocha tests` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1216 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1213 | `mocha test/test.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1211 | `mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1206 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [poooi/poi](https://github.com/poooi/poi) | 1193 | `mocha --recursive --harmony --require ./test/babelhook` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1189 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1187 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [poooi/poi](https://github.com/poooi/poi) | 1193 | `mocha --recursive --harmony --require ./test/babelhook` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1189 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1187 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1183 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1174 | `mocha --recursive -r tests/setup tests` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1170 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1165 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1163 | `xo && mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1161 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1159 | `mocha $(find test -name '*.test.js') --exit` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1014 | `mocha --colors ./test/*.spec.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1002 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1001 | `mocha -R list` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1000 | `mocha --reporter spec --bail --check-leaks test/` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 989 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 988 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 982 | `mocha test/*.test.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 981 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 981 | `npm run lint && mocha -R spec` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 981 | `mocha --reporter spec` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 974 | `npm run rollup-cjs && mocha test/test.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1080 | `npm run convertto:es5 && npm run mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1080 | `mocha test` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1080 | `eslint src test && mocha --compilers babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1079 | `mocha test/tests.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1078 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1078 | `mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1061 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [tomas/needle](https://github.com/tomas/needle) | 1055 | `mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1053 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1051 | `mocha --async-only` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1061 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [tomas/needle](https://github.com/tomas/needle) | 1055 | `mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1053 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1051 | `mocha --async-only` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1046 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 895 | `mocha test` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 893 | `node_modules/.bin/mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 892 | `mocha test/index.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 886 | `mocha --timeout 200000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 882 | `./node_modules/.bin/mocha --globals angular,require` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 881 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 873 | `mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 868 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 864 | `mocha --reporter list` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1014 | `mocha --colors ./test/*.spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1007 | `mocha --check-leaks -R dot` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1004 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1002 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1001 | `mocha -R list` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1000 | `mocha --reporter spec --bail --check-leaks test/` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 996 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 989 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 988 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 982 | `mocha test/*.test.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 981 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 981 | `npm run lint && mocha -R spec` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 981 | `mocha --reporter spec` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 979 | `mocha --compilers js:babel-register test/*.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 975 | `mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 974 | `npm run rollup-cjs && mocha test/test.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 971 | `mocha "client.test" --compilers js:babel-register` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 971 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 969 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 968 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 968 | `mocha spec/*.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 967 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 966 | `mocha` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 965 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 964 | `mocha --recursive ./test/*_spec.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 958 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 954 | `./node_modules/.bin/mocha --reporter spec` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 953 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 953 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 952 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 950 | `mocha` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 948 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 946 | `mocha -t 600000` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 945 | `./node_modules/.bin/mocha -R spec` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 941 | `mocha --timeout 5000` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 935 | `npm run lint && npm run mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 932 | `nyc mocha specs` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 931 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 931 | `mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 925 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 923 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 920 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 914 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 913 | `istanbul cover -- _mocha --reporter spec` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 908 | `standard && standard ./bin/* && mocha` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 905 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 901 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 896 | `npm run lint && npm run mocha:no-functional` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 895 | `mocha test` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 892 | `mocha test/index.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 886 | `mocha --timeout 200000` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 885 | `./node_modules/.bin/mocha test/**/*` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 882 | `./node_modules/.bin/mocha --globals angular,require` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 881 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 880 | `node_modules/.bin/mocha test/spec` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 896 | `npm run lint && npm run mocha:no-functional` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 895 | `mocha test` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 893 | `node_modules/.bin/mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 892 | `mocha test/index.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 886 | `mocha --timeout 200000` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 885 | `./node_modules/.bin/mocha test/**/*` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 882 | `./node_modules/.bin/mocha --globals angular,require` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 881 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 880 | `node_modules/.bin/mocha test/spec` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 862 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 862 | `eslint test && mocha --compilers js:babel/register` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 860 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 860 | `npm run build && istanbul test _mocha test/test.js` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 858 | `mocha --reporter spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 858 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 858 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 857 | `istanbul cover _mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 856 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 852 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 852 | `mocha --check-leaks -t 20000` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 851 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 851 | `mocha --harmony --full-trace --check-leaks` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 851 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 850 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 847 | `npm run lint && mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 851 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 851 | `mocha --harmony --full-trace --check-leaks` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 851 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 850 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 847 | `npm run lint && mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 845 | `nyc mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 842 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 840 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 840 | `mocha -r should --exit test/*.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 840 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 840 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 839 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 838 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 837 | `mocha --async-only` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 836 | `mocha --opts mocha.opts` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 819 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 818 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 818 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 817 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 817 | `mocha --harmony tests/**` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 813 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 812 | `npm run mocha-test test/integration` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 812 | `cake build && mocha ./test/mocha/*.coffee` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 812 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [edsu/anon](https://github.com/edsu/anon) | 811 | `mocha --colors --reporter spec test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 806 | `_mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 806 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 804 | `mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 813 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 812 | `npm run mocha-test test/integration` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 812 | `cake build && mocha ./test/mocha/*.coffee` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 812 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [edsu/anon](https://github.com/edsu/anon) | 811 | `mocha --colors --reporter spec test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 806 | `_mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 806 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 806 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 805 | `mocha --require babel-register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 804 | `mocha` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 739 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 736 | `npm run bundle && mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 735 | `mocha test` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 735 | `mocha` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 733 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 731 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 728 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 728 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 723 | `mocha --reporter spec --bail --check-leaks test/` | 