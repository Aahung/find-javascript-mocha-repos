# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:19 10/23/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43984 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41540 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40682 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30478 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 24792 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 24763 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23954 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20419 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19453 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17652 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17274 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17168 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15858 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14450 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14340 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14183 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13496 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13146 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12783 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12520 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12296 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12279 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11834 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11708 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11677 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10897 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10573 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10431 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10399 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10270 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [tj/co](https://github.com/tj/co) | 10207 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10174 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [websockets/ws](https://github.com/websockets/ws) | 9781 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9592 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9497 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 9414 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9370 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9293 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9117 | `grunt mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9078 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 8983 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8965 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8667 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8578 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8493 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8379 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8325 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8274 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8138 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8018 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7959 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7814 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7560 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7503 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7498 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7494 | `npm run build && istanbul cover _mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7486 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7445 | `mocha` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7437 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7409 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [almende/vis](https://github.com/almende/vis) | 7225 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7176 | `xo && mocha test/*.js --timeout 100000` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7061 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7009 | `mocha $HARMONY_OPTS` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6957 | `mocha; jshint *.js lib` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6874 | `mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6803 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6796 | `mocha --exit --require @babel/register` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6645 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6453 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6382 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6302 | `npm run test:mocha:src` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6215 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6092 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6055 | `mocha tests/node.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6054 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5926 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5892 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5879 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5872 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5858 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5788 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5588 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5555 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5525 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5415 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5341 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5296 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5218 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5196 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5195 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5152 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5061 | `gulp lint && mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4997 | `mocha test` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4883 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4858 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4831 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4805 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4780 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4776 | `mocha test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4715 | `./node_modules/.bin/mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4711 | `mocha --reporter spec -t 8000` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4699 | `mocha --recursive` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4649 | `mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4621 | `nyc mocha --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4611 | `npm run lint && npm run mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4569 | `mocha ./test/runner.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4503 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4478 | `nyc mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4464 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4460 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4348 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4321 | `mocha -R spec src` | 
| [teambit/bit](https://github.com/teambit/bit) | 4315 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4252 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4211 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4211 | `node_modules/.bin/mocha test/tests.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4205 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4199 | `nyc mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4198 | `mocha --timeout=15000 tests/*.test.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4131 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4116 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4107 | `npm run lint ; mocha && mocha test/individual` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4067 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4031 | `mocha --require should --reporter spec` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4030 | `mocha --check-leaks --reporter spec --bail` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3977 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3906 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3867 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3842 | `nyc mocha "test/**/*.test.js"` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3802 | `NODE_ENV=test mocha --exit` | 
| [expressjs/session](https://github.com/expressjs/session) | 3771 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3768 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [primus/primus](https://github.com/primus/primus) | 3714 | `npm run build && mocha test/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3678 | `standard && mocha --timeout 60000 test/test.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3664 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3641 | `NODE_ENV=test mocha test/**/*.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3611 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3586 | `mocha tests/javascript` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3586 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3582 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3580 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3561 | `mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3554 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3542 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3521 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3473 | `node_modules/.bin/mocha test/lib/` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3521 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3473 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3461 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3444 | `mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3425 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3395 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3352 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3338 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3208 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3196 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3189 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3186 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3184 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3170 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3166 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3164 | `mocha test/*.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3158 | `./node_modules/.bin/mocha test/test.*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3157 | `mocha test/index.js && npm run demo` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3132 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3108 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3100 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3095 | `eslint . && mocha -t 5000` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3093 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3085 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3081 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3076 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3034 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3093 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3085 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3081 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3076 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3034 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3019 | `mocha -R landing test/index` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3014 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 3007 | `mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2973 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2951 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2927 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2917 | `npm run mocha && npm run lint` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2914 | `mocha -R spec --recursive src/test` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2906 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2902 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2775 | `mocha --require should --reporter spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2765 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [css/csso](https://github.com/css/csso) | 2764 | `mocha --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2732 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2720 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2712 | `npm run build && cd test && mocha . --reporter dot` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2708 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2693 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2682 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2661 | `mocha --timeout 100000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2652 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2634 | `nyc mocha --timeout=10000` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2631 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2618 | `mocha-phantomjs ./test/index.html` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2608 | `nyc mocha` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2732 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2720 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2712 | `npm run build && cd test && mocha . --reporter dot` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2708 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2693 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2682 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2661 | `mocha --timeout 100000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2652 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2634 | `nyc mocha --timeout=10000` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2631 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2618 | `mocha-phantomjs ./test/index.html` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2608 | `nyc mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2588 | `mocha "test/**/*-test.js"` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2579 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2440 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2421 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2409 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2383 | `mocha test/index.js --reporter dot` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2381 | `mocha && eslint .` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2370 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2368 | `mocha -R spec` | 
| [Qix-/color](https://github.com/Qix-/color) | 2313 | `mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2311 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2409 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2391 | `mocha test && npm run lint` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2390 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2383 | `mocha test/index.js --reporter dot` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2381 | `mocha && eslint .` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2370 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2368 | `mocha -R spec` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2314 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 2313 | `mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2311 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2304 | `mocha -R spec test/*.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2289 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2288 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2257 | `mocha --compilers js:babel-register` | 
| [gajus/swing](https://github.com/gajus/swing) | 2254 | `mocha --compilers js:babel-register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2226 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2222 | `mocha test test/unit/**/*_test.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2196 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2181 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2172 | `nyc npm run _mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2159 | `cross-env BABEL_ENV=test mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2156 | `standard && mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2155 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2139 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2127 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2122 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2118 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2109 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2108 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2106 | `mocha test/runner.js --reporter spec` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2096 | `mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2092 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2087 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2074 | `mocha && eslint *.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 2009 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2005 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [slate/slate](https://github.com/slate/slate) | 1998 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1991 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1991 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1983 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1979 | `mocha --reporter spec --timeout 5000` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1978 | `mocha --require=test/test_helper.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1957 | `npm run lint && mocha -R dot && npm run cover` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1939 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1936 | `mocha --require ./test/common --growl test/expect.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1936 | `mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1927 | `npm run mocha && npm run karma` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1926 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [kach/nearley](https://github.com/kach/nearley) | 1968 | `mocha test/*.test.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1963 | `mocha -c test/index.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1957 | `npm run lint && mocha -R dot && npm run cover` | 
| [then/promise](https://github.com/then/promise) | 1951 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1939 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1936 | `mocha --require ./test/common --growl test/expect.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1936 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1928 | `mocha --compilers js:babel-register` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1927 | `npm run mocha && npm run karma` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1926 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1921 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1910 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1821 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1819 | `mocha test -u bdd -R spec` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1818 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1807 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1801 | `mocha --timeout 5000` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1774 | `mocha ./test/basic.js -t 5000` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1732 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1731 | `npm run lint && npm run mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1729 | `mocha test/**/*_test.js --bail` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1722 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1821 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1819 | `mocha test -u bdd -R spec` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1818 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1807 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1801 | `mocha --timeout 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1797 | `npm run lint && npm run mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1775 | `mocha test` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1774 | `mocha ./test/basic.js -t 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1766 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1742 | `mocha compiled_tests/` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1736 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1732 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1731 | `npm run lint && npm run mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1729 | `mocha test/**/*_test.js --bail` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1722 | `./node_modules/.bin/mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1722 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1718 | `npm run lint && mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1717 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1708 | `mocha test/* --reporter spec` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1706 | `mocha test --timeout 600000` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1704 | `mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1704 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1697 | `mocha test/setup.js test/spec/*.js` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1694 | `mocha test/*.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1692 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1683 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1676 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1676 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1668 | `xo && mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1660 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1656 | `eslint --cache . && tsc && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1650 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1648 | `mocha && size-limit` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1643 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [zeit/ms](https://github.com/zeit/ms) | 1640 | `mocha tests.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1636 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1635 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1635 | `mocha tests/test.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1634 | `mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1622 | `standard "./src/*.js" && mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1621 | `mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1547 | `npm run test:lint && npm run test:mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1542 | `mocha --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1541 | `nyc mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1541 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1530 | `node_modules/.bin/mocha --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1525 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1520 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1519 | `mocha -u tdd` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1415 | `mocha ./test/test*.js --reporter spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1411 | `mocha -R spec ./test/unit/**` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1408 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1408 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1398 | `mocha tests/test-*` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1397 | `istanbul cover _mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1388 | `npm run build && mocha -r should` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1383 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1381 | `mocha --opts test/opts/mocha.opts` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1376 | `npm run lint && npm run mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1361 | `cross-env NODE_ENV=test nyc mocha` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1359 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1356 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1376 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1376 | `npm run lint && npm run mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1374 | `mocha --reporter dot` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1361 | `cross-env NODE_ENV=test nyc mocha` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1359 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1359 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1356 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1353 | `mocha --recursive` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1343 | `./node_modules/.bin/mocha test` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1343 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1340 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1337 | `mocha` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1331 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1327 | `NODE_PATH=. mocha **/*.spec.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1324 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1317 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1315 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1313 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1309 | `npm run prepublishOnly && mocha test/test.js` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1309 | `mocha --recursive test/bin` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1307 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1305 | `mocha-phantomjs tests/index.html` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1304 | `mocha` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1300 | `mocha spec/exec.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1299 | `mocha --recursive test` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1297 | `mocha --check-leaks --reporter spec --bail test/` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1296 | `mocha --timeout 60000 test/` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1295 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1286 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1281 | `mocha test/*.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1277 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1274 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1268 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1265 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1265 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1264 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1262 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1261 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1255 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1255 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1254 | `npm run lint && npm run mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1253 | `mocha tests` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1251 | `mocha src/test.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1250 | `mocha --compilers js:babel-core/register` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1245 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1243 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1238 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1237 | `istanbul test _mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1236 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1233 | `webpack && npm run lint && npm run mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1232 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1225 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [variety/variety](https://github.com/variety/variety) | 1222 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1218 | `npm run lint && mocha --require @babel/register` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1217 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [normalize/mz](https://github.com/normalize/mz) | 1217 | `mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1214 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1214 | `mocha test/test.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1213 | `npm run mocha:istanbul` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1213 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1201 | `mocha test --compilers js:babel-core/register` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1200 | `mocha test` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1200 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1199 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1194 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1188 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1184 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1179 | `mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1176 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1159 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1139 | `mocha --timeout 30000 --recursive ./tests` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1138 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1138 | `istanbul cover _mocha test/*.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1138 | `xo && mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1137 | `mocha $(find test -name '*.test.js') --exit` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1134 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1121 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1120 | `mocha test/*` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1117 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1115 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1115 | `mocha --reporter spec --bail --check-leaks test/` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1110 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1110 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1109 | `webpack && mocha test/unit` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1102 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1100 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1121 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1120 | `mocha test/*` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1117 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1115 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1115 | `mocha --reporter spec --bail --check-leaks test/` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1110 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1110 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1109 | `webpack && mocha test/unit` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1103 | `npm-run-all test:jest test:server:mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1102 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1100 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1097 | `mocha --reporter spec --bail --check-leaks test/` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1094 | `mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1094 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1090 | `mocha --check-leaks -t 20000` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1090 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1074 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1074 | `standard && mocha -b` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1073 | `mocha --recursive --bail --reporter spec test` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1072 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1068 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1067 | `mocha test/tests.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1064 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1061 | `mocha && standard` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1059 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1057 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1049 | `eslint src test && mocha --compilers babel-register` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1048 | `mocha --recursive -r tests/setup tests` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1049 | `eslint src test && mocha --compilers babel-register` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1048 | `mocha --recursive -r tests/setup tests` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1042 | `npm run convertto:es5 && npm run mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1040 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1036 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1034 | `mocha --reporter spec test --recursive` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1034 | `mocha --reporter spec --timeout 3000` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1035 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1028 | `mocha $(find test -name '*.test.js')` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1026 | `mocha --async-only` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1021 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 994 | `mocha -R list` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 994 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 991 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 988 | `mocha test` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 987 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 984 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 973 | `npm run rollup-cjs && mocha test/test.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 973 | `mocha --reporter spec` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 970 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 968 | `mocha` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 955 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 953 | `npm run lint && mocha -R spec` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 949 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 947 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 943 | `mocha --timeout 5000` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 934 | `mocha` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 934 | `mocha --recursive` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 932 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 932 | `mocha tests` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 932 | `mocha tests` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 927 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 925 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 925 | `mocha -t 600000` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 920 | `mocha test` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 919 | `./node_modules/.bin/mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 915 | `./node_modules/.bin/mocha -R spec` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 911 | `nyc mocha specs` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 910 | `mocha --recursive ./test/*_spec.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 910 | `mocha --recursive ./test/*_spec.js` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 908 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 908 | `mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 907 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 907 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 907 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 905 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 905 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 906 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 903 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 900 | `mocha test --compilers js:babel-register` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 897 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 896 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 894 | `mocha` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 891 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 889 | `node_modules/.bin/mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 880 | `npm run lint && npm run mocha:no-functional` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 877 | `mocha --timeout 200000` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 877 | `mocha -t 5000` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 871 | `node_modules/.bin/mocha test/spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 867 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 866 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 866 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 866 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 860 | `mocha test/index.js` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 859 | `eslint test && mocha --compilers js:babel/register` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 858 | `mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 866 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 866 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 860 | `mocha test/index.js` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 859 | `eslint test && mocha --compilers js:babel/register` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 858 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 855 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 854 | `mocha --reporter list` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 852 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 852 | `istanbul cover _mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 851 | `mocha test` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 849 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 847 | `mocha --check-leaks -t 20000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 840 | `mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 839 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 836 | `mocha --reporter spec --bail --check-leaks test/` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 836 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 835 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 835 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 835 | `mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 828 | `mocha && ember test` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 827 | `npm run build && istanbul test _mocha test/test.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 826 | `./node_modules/.bin/mocha test/**/*` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 825 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 824 | `mocha --opts mocha.opts` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 822 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 770 | `mocha --recursive -s 15 test/` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 764 | `mocha --ui tdd --require ./test/__setup` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 755 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 752 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 750 | `nyc mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 750 | `babel-node node_modules/.bin/_mocha -- test` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 750 | `mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 748 | `npm run lint && npm run mocha` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 790 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 789 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 788 | `xo && mocha -R spec` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 781 | `mocha --no-timeouts` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 776 | `nyc mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 774 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 771 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 781 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 780 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 778 | `mocha` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 776 | `nyc mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 774 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 771 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 770 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 770 | `mocha --recursive -s 15 test/` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 768 | `mocha test` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 764 | `mocha --ui tdd --require ./test/__setup` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 748 | `npm run lint && npm run mocha` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 747 | `mocha test/mocha.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 747 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 743 | `mocha --harmony tests/**` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 742 | `mocha tests/*.mocha.js` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 740 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 739 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 739 | `npm run lint && mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 736 | `mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 735 | `mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 734 | `npm run bundle && mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 755 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 752 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 750 | `nyc mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 750 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 750 | `babel-node node_modules/.bin/_mocha -- test` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 750 | `mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 750 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 748 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 748 | `npm run lint && npm run mocha` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 747 | `mocha test/mocha.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 747 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 743 | `mocha --harmony tests/**` | 