# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:10 08/10/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43126 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41098 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39611 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30065 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 25643 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24440 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23110 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19679 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18922 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16510 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15109 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13920 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13415 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13099 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12667 | `./node_modules/.bin/mocha test/` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12619 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12293 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12238 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11749 | `istanbul cover _mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11749 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11457 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11098 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11090 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10411 | `mocha test/index.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10088 | `mocha` | 
| [svg/svgo](https://github.com/svg/svgo) | 10082 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10077 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [tj/co](https://github.com/tj/co) | 10011 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9933 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9619 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9560 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9353 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 9308 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9061 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9004 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8974 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8685 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8662 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8612 | `mocha tests/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8480 | `mocha test/test.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8433 | `mocha test/src` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8421 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8299 | `grunt clean:test && mocha --exit` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8207 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8161 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8051 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7946 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7889 | `npm run eslint && npm run mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7703 | `mocha --opts mocha.opts` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7687 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7551 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7545 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7437 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7418 | `npm run build && istanbul cover _mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7212 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7186 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7174 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7025 | `xo && mocha test/*.js --timeout 100000` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6996 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [almende/vis](https://github.com/almende/vis) | 6960 | `mocha --compilers js:babel-core/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6879 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6799 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6435 | `npm run jshint && mocha test/` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6368 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6306 | `mocha --exit --require babel-core/register` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6238 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6210 | `npm run test:mocha:src` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6165 | `mocha test/test.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6059 | `mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6048 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5957 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5940 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5882 | `mocha tests/node.js` | 
| [shipshapecode/shepherd](https://github.com/shipshapecode/shepherd) | 5812 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5796 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5716 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5685 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5593 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5591 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5568 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5410 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5308 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5256 | `standard && mocha` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5175 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5151 | `mocha --color` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5108 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5077 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4959 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4950 | `gulp lint && mocha` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4932 | `mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4839 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4734 | `gulp build; mocha;` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4733 | `mocha test` | 
| [santinic/how2](https://github.com/santinic/how2) | 4731 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4728 | `mocha -R spec 'tests/app'` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4725 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4695 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4597 | `./node_modules/.bin/mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4569 | `mocha ./test/runner.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4523 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4461 | `mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4431 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4404 | `nyc mocha --exit` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4398 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4398 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4389 | `npm run lint && npm run mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4326 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4214 | `mocha -R spec ./test --recursive` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4160 | `npm run lint && npm run mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4135 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4126 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4079 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4057 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4016 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4011 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4005 | `mocha --require test/babel-hook test/*.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3986 | `mocha --timeout=15000 tests/*.test.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3982 | `npm run lint ; mocha && mocha test/individual` | 
| [tj/ejs](https://github.com/tj/ejs) | 3973 | `mocha --require should --reporter spec` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3891 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3881 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3845 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3840 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3823 | `mocha --check-leaks --reporter spec --bail` | 
| [erming/shout](https://github.com/erming/shout) | 3803 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3765 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 3756 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3700 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3664 | `standard && mocha --timeout 60000 test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3649 | `npm run build && mocha test/*.test.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 3606 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [expressjs/session](https://github.com/expressjs/session) | 3606 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3576 | `mocha tests/javascript` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3569 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3563 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3539 | `mocha --reporter spec --timeout 3000` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3521 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3517 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3498 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3460 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3457 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3437 | `mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3429 | `NODE_ENV=test mocha test/**/*.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3391 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3383 | `NODE_ENV=test mocha --exit` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3227 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3222 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3218 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3168 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3162 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3147 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3142 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3140 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3128 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3109 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3064 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3056 | `mocha test/*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3038 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3037 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3034 | `mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3023 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3014 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3002 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3168 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3162 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3147 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3142 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3140 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3128 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3109 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 3073 | `export TESTING=true; mocha --reporter list` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3064 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3056 | `mocha test/*.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3043 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3042 | `mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3038 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3037 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3034 | `mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3023 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3014 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3002 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2985 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2923 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2886 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2881 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2880 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2875 | `mocha -R spec --recursive src/test` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2868 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2861 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2856 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2842 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2824 | `istanbul cover _mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2823 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2815 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2811 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2801 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2799 | `npm run mocha && npm run lint` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2782 | `mocha -R landing test/index` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2778 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2770 | `mocha --require should --reporter spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2766 | `mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2411 | `mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2378 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2349 | `grunt jshint && mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2339 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2337 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2313 | `mocha -R spec` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2307 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2301 | `mocha test && npm run lint` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2295 | `mocha test/index.js --reporter dot` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2277 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2261 | `mocha && eslint .` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2228 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2637 | `mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2635 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2624 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2621 | `mocha --recursive --watch` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2614 | `mocha test.js` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2610 | `mocha-phantomjs ./test/index.html` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2607 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2601 | `npm run build && cd test && mocha . --reporter dot` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2599 | `eslint . && mocha -t 5000` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2597 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2584 | `nyc mocha --timeout=10000` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2569 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2532 | `export TESTING=true; mocha --reporter list` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2530 | `nyc mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2517 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2505 | `mocha "test/**/*-test.js"` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2492 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2313 | `mocha -R spec` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2307 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2301 | `mocha test && npm run lint` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2295 | `mocha test/index.js --reporter dot` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2281 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2277 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2261 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2244 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2231 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2228 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [gajus/swing](https://github.com/gajus/swing) | 2218 | `mocha --compilers js:babel-register` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2197 | `mocha test/ --no-timeouts` | 
| [noble/noble](https://github.com/noble/noble) | 2189 | `mocha -R spec test/*.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2337 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2313 | `mocha -R spec` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2307 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2301 | `mocha test && npm run lint` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2295 | `mocha test/index.js --reporter dot` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2281 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2277 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2261 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2244 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2231 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2228 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [gajus/swing](https://github.com/gajus/swing) | 2218 | `mocha --compilers js:babel-register` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1640 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1635 | `mocha compiled_tests/` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1634 | `mocha spec` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1606 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1599 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1590 | `mocha test/setup.js test/spec/*.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1585 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1569 | `./node_modules/mocha/bin/mocha -R spec` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1563 | `mocha test` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1563 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1556 | `standard "./src/*.js" && mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1542 | `mocha --reporter spec` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1531 | `mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1529 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1529 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1522 | `node_modules/.bin/mocha --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1520 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1512 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1496 | `nyc mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1496 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1482 | `mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1481 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1473 | `mocha test/**/*.spec.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1482 | `mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1481 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1473 | `mocha test/**/*.spec.js` | 
| [retejs/rete](https://github.com/retejs/rete) | 1472 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [samccone/drool](https://github.com/samccone/drool) | 1455 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1451 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1440 | `nyc mocha --timeout=20000 test.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1439 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1416 | `mocha --timeout 10000 ./tests/lib.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1412 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [noble/bleno](https://github.com/noble/bleno) | 1407 | `mocha -R spec test/*.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1406 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1401 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1387 | `istanbul cover _mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1379 | `./node_modules/mocha/bin/mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1379 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1375 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1374 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1333 | `mocha --opts test/opts/mocha.opts` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1329 | `istanbul cover _mocha test -- --timeout 20000` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1328 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1327 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1322 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1321 | `./node_modules/.bin/mocha test` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1319 | `mocha --recursive` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1318 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1313 | `mocha tests/test-*` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1310 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1309 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1306 | `mocha-phantomjs tests/index.html` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1306 | `standard && istanbul cover _mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1300 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1296 | `mocha spec/exec.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1283 | `mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1284 | `NODE_PATH=. mocha **/*.spec.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1283 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1273 | `NODE_ENV=test mocha tests/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1271 | `mocha --timeout 60000 test/` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1268 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1263 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1261 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1258 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1255 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1252 | `mocha -R spec ./test/unit/**` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1250 | `mocha` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1250 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1248 | `mocha tests` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1248 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1247 | `mocha test/*.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1246 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1250 | `mocha` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1250 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1248 | `mocha tests` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1248 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1247 | `mocha test/*.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1246 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1239 | `npm run lint && npm run mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1229 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1228 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1222 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1219 | `mocha src/test.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1217 | `istanbul test _mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1215 | `npm run prepublishOnly && mocha test/test.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1215 | `mocha` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1214 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1213 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1213 | `mocha test/test.js` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1211 | `mocha --recursive test/bin` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1208 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1229 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1228 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1222 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1219 | `mocha src/test.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1217 | `istanbul test _mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1215 | `npm run prepublishOnly && mocha test/test.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1215 | `mocha` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1214 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1213 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1213 | `mocha test/test.js` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1211 | `mocha --recursive test/bin` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1208 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1204 | `npm run lint && npm run mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1200 | `node ./node_modules/mocha/bin/mocha tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1200 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [normalize/mz](https://github.com/normalize/mz) | 1198 | `mocha --reporter spec` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1197 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1178 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1175 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1168 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1167 | `mocha --compilers js:babel-core/register` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1155 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1151 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1150 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1148 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1144 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1138 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1132 | `mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1126 | `webpack && npm run lint && npm run mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1124 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1123 | `mocha $(find test -name '*.test.js')` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1121 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1121 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1119 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1118 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1116 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1114 | `istanbul cover _mocha test/*.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1110 | `npm run lint && mocha --require @babel/register` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1107 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1106 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1105 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [electron/asar](https://github.com/electron/asar) | 1075 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1071 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1071 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1066 | `webpack && mocha test/unit` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1064 | `mocha --recursive --bail --reporter spec test` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1063 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1053 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1051 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1044 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1042 | `mocha --reporter spec --bail --check-leaks test/` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1041 | `mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1038 | `standard && mocha -b` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1037 | `mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1037 | `mocha --reporter spec --timeout 3000` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1034 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 1025 | `mocha && standard` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1022 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [tomas/needle](https://github.com/tomas/needle) | 1020 | `mocha test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1020 | `eslint src test && mocha --compilers babel-register` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1019 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1016 | `mocha --timeout 30000 --recursive ./tests` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1014 | `mocha $(find test -name '*.test.js')` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1012 | `mocha --check-leaks -R dot` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1011 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1008 | `mocha --recursive test/unit/` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1004 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1001 | `mocha --async-only` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1001 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 997 | `mocha --colors ./test/*.spec.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 993 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 983 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 983 | `mocha -R list` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 982 | `npm run convertto:es5 && npm run mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 975 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 975 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 974 | `npm run rollup-cjs && mocha test/test.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 974 | `npm-run-all test:jest test:server:mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 972 | `mocha --reporter spec` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 971 | `mocha test --compilers js:babel-core/register` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 969 | `npm run lint && npm run flow && NODE_ENV=test nyc mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 959 | `mocha` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 952 | `mocha` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 948 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 943 | `mocha --recursive -r tests/setup tests` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 943 | `mocha "client.test" --compilers js:babel-register` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 939 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 938 | `mocha --compilers js:babel-register test/*.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 938 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 937 | `mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 933 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 932 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 928 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 925 | `npm run lint && mocha -R spec` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 918 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 917 | `mocha ./test/index.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 915 | `mocha tests` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 914 | `mocha spec/*.spec.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 913 | `mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 910 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 908 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 907 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 907 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 903 | `mocha spec/*.js` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 900 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 900 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 894 | `mocha -t 600000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 881 | `mocha test` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 878 | `nyc mocha specs` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 875 | `mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 870 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 868 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 867 | `./node_modules/.bin/mocha --reporter spec` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 866 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 865 | `npm run lint && npm run mocha:no-functional` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 865 | `mocha --timeout 200000` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 865 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 863 | `./node_modules/.bin/mocha -R spec` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 863 | `mocha` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 863 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 862 | `mocha -t 5000` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 800 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 797 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 794 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 789 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 786 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 785 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 784 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 781 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 812 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 812 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 811 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 807 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 806 | `cake build && mocha ./test/mocha/*.coffee` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 806 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 805 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 805 | `mocha --async-only` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 800 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 797 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 800 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 797 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 795 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 794 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 792 | `mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 789 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 789 | `mocha --harmony --full-trace --check-leaks` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 786 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 786 | `npm run mocha-test test/integration` | 
| [edsu/anon](https://github.com/edsu/anon) | 785 | `mocha --colors --reporter spec test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 785 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 784 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 784 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 807 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 806 | `cake build && mocha ./test/mocha/*.coffee` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 806 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 805 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 805 | `mocha --async-only` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 800 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 797 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 795 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 794 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 792 | `mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 789 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 789 | `mocha --harmony --full-trace --check-leaks` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 786 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 786 | `npm run mocha-test test/integration` | 
| [edsu/anon](https://github.com/edsu/anon) | 785 | `mocha --colors --reporter spec test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 785 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 784 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 784 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 783 | `npm run build && istanbul test _mocha test/test.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 782 | `mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 782 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 781 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 780 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 779 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 777 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 776 | `xo && mocha -R spec` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 774 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 773 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 771 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [developit/decko](https://github.com/developit/decko) | 769 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 766 | `mocha test` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 765 | `mocha --ui tdd --require ./test/__setup` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 765 | `mocha --no-timeouts` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 763 | `mocha -R spec src/**/*_test.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 758 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 756 | `mocha --recursive -s 15 test/` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 756 | `mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 751 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 751 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 751 | `mocha -r should --reporter spec test/*.js` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 751 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 751 | `mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 742 | `mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 740 | `npm run lint && npm run mocha` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 739 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 739 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 739 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 738 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 738 | `./node_modules/.bin/mocha test/**/*` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 737 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 737 | `mocha test` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 737 | `mocha --reporter spec` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 737 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 736 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 736 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 735 | `mocha tests/*.mocha.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 731 | `nyc mocha` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 729 | `mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 727 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 727 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 727 | `mocha --exit --use_strict src/*.test.js` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 726 | `babel-node node_modules/.bin/_mocha -- test` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 725 | `npm run bundle && mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 720 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 718 | `mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 715 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 715 | `mocha --reporter spec build/test/index.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 711 | `./bin/selenium-standalone install && mocha` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 710 | `npm run-script jshint && npm run-script mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 709 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 706 | `mocha ./test/index.js` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 705 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 710 | `npm run-script jshint && npm run-script mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 709 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 706 | `mocha ./test/index.js` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 705 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 703 | `mocha ./test/test.js --timeout 1000000` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 699 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 699 | `mocha` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 696 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 696 | `./node_modules/.bin/mocha -t 60000` | 
| [koajs/static](https://github.com/koajs/static) | 694 | `mocha --harmony --reporter spec --exit` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 692 | `mocha $(find test -name '*.test.js')` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 692 | `mocha --reporter spec` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 688 | `npm run test-mocha && npm run test-karma` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 687 | `mocha --compilers js:babel-core/register` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 685 | `mocha --harmony tests/**` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 683 | `mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 683 | `npm run lint && mocha` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 682 | `jenkins-mocha ./tests/*.js` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 679 | `mocha` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 679 | `npm run lint && mocha test` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 679 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 675 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 675 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 672 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 667 | `mocha --bail test/` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 663 | `mocha --reporter spec --bail --check-leaks test/` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 663 | `mocha` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 662 | `mocha -R spec` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 661 | `mocha` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 660 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 659 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 659 | `mocha --reporter spec` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 658 | `mocha --reporter spec` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 658 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require babel-register` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 656 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 652 | `mocha --recursive --compilers js:babel-core/register` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 650 | `mocha --require babel-register src/**/*.spec.js src/*.spec.js` | 
| [shime/livedown](https://github.com/shime/livedown) | 649 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 648 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 646 | `mocha --reporter spec` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 646 | `./node_modules/.bin/mocha --bail` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 642 | `mocha --require babel-register` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 642 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 