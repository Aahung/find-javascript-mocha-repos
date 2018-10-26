# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:15 10/26/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44026 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41566 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40717 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30502 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24776 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23989 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20454 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19471 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17682 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17299 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17195 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15899 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14462 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14365 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14213 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13518 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13155 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12799 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12532 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12326 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12283 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11853 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11741 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11709 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10932 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10597 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10462 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10410 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10303 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [tj/co](https://github.com/tj/co) | 10216 | `mocha --harmony` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9379 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9298 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9125 | `grunt mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9108 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 8998 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8971 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8674 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8580 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8494 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8381 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8329 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8279 | `mocha --compilers js:babel-register test/test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8030 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7960 | `npm run eslint && npm run mocha` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8381 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8329 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8279 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8142 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8030 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7960 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7825 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7560 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7509 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7507 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [aui/art-template](https://github.com/aui/art-template) | 7499 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7497 | `npm run build && istanbul cover _mocha` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7464 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7446 | `mocha` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7429 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [almende/vis](https://github.com/almende/vis) | 7233 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7198 | `xo && mocha test/*.js --timeout 100000` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7068 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7015 | `mocha $HARMONY_OPTS` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6978 | `mocha; jshint *.js lib` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6882 | `mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6826 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6818 | `mocha --exit --require @babel/register` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6674 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6471 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6389 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6307 | `npm run test:mocha:src` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6230 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6107 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6064 | `mocha tests/node.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6054 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5938 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5935 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5919 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5893 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5886 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5865 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5791 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5599 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5560 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5534 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5415 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5348 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5305 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5229 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5200 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5195 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5151 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5063 | `gulp lint && mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5014 | `mocha test` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4887 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4876 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4836 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4806 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4780 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4777 | `mocha test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4726 | `./node_modules/.bin/mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4711 | `mocha --recursive` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4711 | `mocha --reporter spec -t 8000` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4653 | `mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4631 | `nyc mocha --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4618 | `npm run lint && npm run mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4570 | `mocha ./test/runner.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4516 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4495 | `nyc mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4467 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4462 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [teambit/bit](https://github.com/teambit/bit) | 4377 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4348 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4332 | `mocha -R spec src` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4275 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4229 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4218 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4206 | `mocha --timeout=15000 tests/*.test.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4205 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4201 | `nyc mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4137 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4134 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4109 | `npm run lint ; mocha && mocha test/individual` | 
| [muicss/mui](https://github.com/muicss/mui) | 4078 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4073 | `mocha --require test/babel-hook test/*.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4037 | `mocha --check-leaks --reporter spec --bail` | 
| [tj/ejs](https://github.com/tj/ejs) | 4033 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3984 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3906 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3867 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3857 | `nyc mocha "test/**/*.test.js"` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3844 | `NODE_ENV=test mocha --exit` | 
| [erming/shout](https://github.com/erming/shout) | 3797 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3784 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 3783 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3775 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [primus/primus](https://github.com/primus/primus) | 3713 | `npm run build && mocha test/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3681 | `standard && mocha --timeout 60000 test/test.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3672 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3653 | `NODE_ENV=test mocha test/**/*.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3618 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3589 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3589 | `node_modules/.bin/mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3588 | `mocha tests/javascript` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3584 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3560 | `mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3554 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3545 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3531 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3475 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3461 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3444 | `mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3432 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3404 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3358 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3347 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3324 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3297 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3034 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3033 | `mocha -R landing test/index` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2979 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2955 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2928 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2924 | `npm run mocha && npm run lint` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2917 | `mocha -R spec --recursive src/test` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2913 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2905 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2885 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2870 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2848 | `mocha test-node` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2846 | `node_modules/.bin/mocha --reporter spec` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2845 | `mocha --require babel-register --recursive spec` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3089 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3089 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3087 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3034 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3033 | `mocha -R landing test/index` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3025 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 3017 | `mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2979 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2955 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2928 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2924 | `npm run mocha && npm run lint` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2917 | `mocha -R spec --recursive src/test` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2913 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2905 | `mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2893 | `mocha --require should --reporter spec` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2885 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2870 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2848 | `mocha test-node` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2846 | `node_modules/.bin/mocha --reporter spec` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2845 | `mocha --require babel-register --recursive spec` | 
| [github-tools/github](https://github.com/github-tools/github) | 2840 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2839 | `mocha` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2836 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2835 | `mocha test.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2833 | `mocha -R spec spec spec/reporters` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2829 | `istanbul cover _mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2827 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2818 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2776 | `mocha --require should --reporter spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2774 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [css/csso](https://github.com/css/csso) | 2766 | `mocha --reporter dot` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2704 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2684 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2661 | `mocha --timeout 100000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2657 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2635 | `nyc mocha --timeout=10000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2619 | `mocha-phantomjs ./test/index.html` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2616 | `nyc mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2591 | `mocha "test/**/*-test.js"` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2578 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2549 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2547 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2492 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2487 | `mocha test/src/**/*.unit.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2484 | `mocha --reporter=spec test/*-test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2460 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2445 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2422 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2409 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2395 | `mocha test && npm run lint` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2390 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2387 | `mocha && eslint .` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2386 | `mocha test/index.js --reporter dot` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2373 | `mocha -R spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2370 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2422 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2409 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2395 | `mocha test && npm run lint` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2390 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2387 | `mocha && eslint .` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2386 | `mocha test/index.js --reporter dot` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2373 | `mocha -R spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2370 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2315 | `mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2314 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2313 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2308 | `mocha -R spec test/*.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2289 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2288 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2260 | `mocha --compilers js:babel-register` | 
| [gajus/swing](https://github.com/gajus/swing) | 2256 | `mocha --compilers js:babel-register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2225 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2222 | `mocha test test/unit/**/*_test.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2205 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2185 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2181 | `nyc npm run _mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2181 | `nyc npm run _mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2161 | `standard && mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2161 | `cross-env BABEL_ENV=test mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2160 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2139 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2127 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2123 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2123 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2120 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2109 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2109 | `mocha test/runner.js --reporter spec` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2096 | `mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2094 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2090 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2080 | `mocha && eslint *.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2075 | `npm run lint && npm run mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2043 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2043 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [share/sharedb](https://github.com/share/sharedb) | 2015 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2008 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2002 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2000 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1998 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1987 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1960 | `npm run lint && mocha -R dot && npm run cover` | 
| [then/promise](https://github.com/then/promise) | 1950 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1939 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1936 | `mocha --require ./test/common --growl test/expect.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1929 | `mocha --compilers js:babel-register` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1928 | `npm run mocha && npm run karma` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1926 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1923 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1918 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1884 | `mocha && npm run lint` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1871 | `mocha tests --require @babel/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1884 | `mocha && npm run lint` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1876 | `mocha tests.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1871 | `mocha tests --require @babel/register` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1859 | `mocha --reporter spec test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1848 | `npm run lint && mocha --reporter spec test/*.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1846 | `mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1846 | `mocha test/**/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1839 | `mocha test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1836 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1832 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1822 | `mocha test -u bdd -R spec` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1821 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1822 | `mocha test -u bdd -R spec` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1821 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1807 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1800 | `mocha --timeout 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1800 | `npm run lint && npm run mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1785 | `mocha test` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1776 | `mocha ./test/basic.js -t 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1770 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1752 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1748 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1746 | `mocha compiled_tests/` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1736 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1734 | `npm run lint && npm run mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1733 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1728 | `mocha test/**/*_test.js --bail` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1723 | `./node_modules/.bin/mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1723 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1718 | `npm run lint && mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1711 | `mocha test/* --reporter spec` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1708 | `mocha test --timeout 600000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1707 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1704 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1699 | `mocha test/setup.js test/spec/*.js` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1697 | `mocha test/*.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1694 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1682 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1680 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1677 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1668 | `xo && mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1661 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1659 | `eslint --cache . && tsc && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1650 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1650 | `mocha && size-limit` | 
| [zeit/ms](https://github.com/zeit/ms) | 1647 | `mocha tests.js` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1645 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1640 | `mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1636 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1636 | `mocha tests/test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1635 | `mocha --expose-gc --slow 300` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1624 | `standard "./src/*.js" && mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1588 | `./node_modules/mocha/bin/mocha -R spec` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1585 | `mocha --reporter spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1583 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1578 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1572 | `TEST=all mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1566 | `mocha test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1558 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1555 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1547 | `npm run test:lint && npm run test:mocha` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1546 | `nyc mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1544 | `mocha --recursive` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1542 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1566 | `mocha test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1558 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1555 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1547 | `npm run test:lint && npm run test:mocha` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1546 | `nyc mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1544 | `mocha --recursive` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1542 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1530 | `node_modules/.bin/mocha --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1525 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1522 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1519 | `mocha -u tdd` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1401 | `mocha tests/test-*` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1397 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1395 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1394 | `standard && istanbul cover _mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1390 | `npm run build && mocha -r should` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1384 | `npm run lint && npm run mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1378 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1377 | `mocha --reporter dot` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1373 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1362 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1356 | `mocha --recursive` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1351 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1343 | `./node_modules/.bin/mocha test` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1341 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1333 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1331 | `NODE_PATH=. mocha **/*.spec.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1328 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1315 | `npm run prepublishOnly && mocha test/test.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1314 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1313 | `mocha --recursive test/bin` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1310 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1305 | `mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1305 | `mocha-phantomjs tests/index.html` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1301 | `mocha --recursive test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1300 | `mocha spec/exec.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1299 | `mocha --check-leaks --reporter spec --bail test/` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1298 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1296 | `mocha --timeout 60000 test/` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1305 | `mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1305 | `mocha-phantomjs tests/index.html` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1301 | `mocha --recursive test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1300 | `mocha spec/exec.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1299 | `mocha --check-leaks --reporter spec --bail test/` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1298 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1296 | `mocha --timeout 60000 test/` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1290 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1283 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1282 | `mocha test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1275 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1269 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1265 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1265 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1265 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1265 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1263 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1245 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1241 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1241 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1239 | `istanbul test _mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1235 | `webpack && npm run lint && npm run mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1232 | `mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1224 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1221 | `npm run mocha:istanbul` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1221 | `npm run lint && mocha --require @babel/register` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1220 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [normalize/mz](https://github.com/normalize/mz) | 1217 | `mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1215 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1215 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1211 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1210 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1211 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1210 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1203 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1199 | `mocha test` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1198 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1189 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1184 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1180 | `mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1176 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1154 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1141 | `mocha --timeout 30000 --recursive ./tests` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1140 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1140 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1139 | `istanbul cover _mocha test/*.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1139 | `mocha $(find test -name '*.test.js') --exit` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1135 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1123 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1118 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1117 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1117 | `mocha --reporter spec --bail --check-leaks test/` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1139 | `istanbul cover _mocha test/*.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1139 | `mocha $(find test -name '*.test.js') --exit` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1139 | `xo && mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1135 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1123 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1121 | `mocha test/*` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1118 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1117 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1117 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1113 | `mocha` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1113 | `webpack && mocha test/unit` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1111 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1110 | `npm-run-all test:jest test:server:mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1076 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1075 | `mocha --recursive --bail --reporter spec test` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 1074 | `mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1072 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1068 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1065 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1062 | `mocha && standard` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1060 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1059 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1051 | `eslint src test && mocha --compilers babel-register` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1048 | `mocha --recursive -r tests/setup tests` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1046 | `npm run convertto:es5 && npm run mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1036 | `mocha --reporter spec test --recursive` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1036 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1036 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1034 | `mocha --reporter spec --timeout 3000` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1030 | `mocha $(find test -name '*.test.js')` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1027 | `mocha --async-only` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1023 | `mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1021 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1013 | `mocha --recursive test/unit/` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1012 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1036 | `mocha --reporter spec test --recursive` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1036 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1036 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1034 | `mocha --reporter spec --timeout 3000` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1030 | `mocha $(find test -name '*.test.js')` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1027 | `mocha --async-only` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1023 | `mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1021 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1013 | `mocha --recursive test/unit/` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1012 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1010 | `mocha --colors ./test/*.spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1008 | `mocha --check-leaks -R dot` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 995 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 994 | `mocha -R list` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 993 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 989 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 984 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 978 | `mocha --reporter spec --bail --check-leaks test/` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 974 | `mocha --reporter spec` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 973 | `npm run rollup-cjs && mocha test/test.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 969 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 966 | `mocha "client.test" --compilers js:babel-register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 965 | `mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 961 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 958 | `mocha --compilers js:babel-register test/*.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 958 | `mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 955 | `npm run lint && mocha -R spec` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 955 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 951 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 947 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 943 | `mocha --timeout 5000` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 935 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 935 | `mocha spec/*.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 933 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 933 | `mocha tests` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 929 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 926 | `mocha -t 600000` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 926 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 923 | `./node_modules/.bin/mocha --reporter spec` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 921 | `nyc --check-coverage mocha test/*.test.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 920 | `mocha test` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 916 | `./node_modules/.bin/mocha -R spec` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 915 | `mocha --recursive ./test/*_spec.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 915 | `mocha --recursive ./test/*_spec.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 913 | `nyc mocha specs` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 911 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 911 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 909 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 909 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 908 | `mocha` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 907 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 906 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 905 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 903 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 902 | `mocha test --compilers js:babel-register` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 898 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 897 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 897 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 894 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 888 | `node_modules/.bin/mocha` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 886 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 886 | `standard && standard ./bin/* && mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 886 | `istanbul cover -- _mocha --reporter spec` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 885 | `./node_modules/.bin/mocha --globals angular,require` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 883 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 881 | `npm run lint && npm run mocha:no-functional` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 878 | `mocha -t 5000` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 877 | `mocha --timeout 200000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 871 | `node_modules/.bin/mocha test/spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 855 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 854 | `mocha --reporter list` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 854 | `mocha --reporter spec` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 854 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 853 | `istanbul cover _mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 853 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 847 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 844 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 843 | `npm run lint && mocha` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 842 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 839 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 838 | `nyc mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 844 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 843 | `npm run lint && mocha` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 842 | `mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 841 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 839 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 838 | `nyc mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 836 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 835 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 835 | `mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 830 | `npm run build && istanbul test _mocha test/test.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 829 | `./node_modules/.bin/mocha test/**/*` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 828 | `mocha && ember test` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 826 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 830 | `npm run build && istanbul test _mocha test/test.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 829 | `./node_modules/.bin/mocha test/**/*` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 828 | `mocha && ember test` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 826 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 824 | `mocha --opts mocha.opts` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 823 | `mocha --harmony --full-trace --check-leaks` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 822 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 821 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 821 | `mocha --async-only` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 819 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 818 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 818 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 817 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 815 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 812 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 810 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [edsu/anon](https://github.com/edsu/anon) | 809 | `mocha --colors --reporter spec test.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 807 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 806 | `cake build && mocha ./test/mocha/*.coffee` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 802 | `mocha -r should --reporter spec test/*.js` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 801 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 801 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 801 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 800 | `npm run mocha-test test/integration` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 800 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 799 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [developit/decko](https://github.com/developit/decko) | 796 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 796 | `mocha -R spec tests/` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 778 | `nyc mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 778 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 775 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 774 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 770 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 770 | `mocha --recursive -s 15 test/` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 767 | `mocha test` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 765 | `mocha --ui tdd --require ./test/__setup` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 740 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 739 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 736 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 735 | `npm run bundle && mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 735 | `mocha` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 735 | `mocha test.js` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 735 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 734 | `mocha --reporter spec build/test/index.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 731 | `./bin/selenium-standalone install && mocha` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 731 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 730 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 728 | `mocha` | 
| [koajs/static](https://github.com/koajs/static) | 726 | `mocha --harmony --reporter spec --exit` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 726 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 