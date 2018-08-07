# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:09 08/07/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43086 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41080 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39566 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30033 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 25540 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24417 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23078 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19612 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18896 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16744 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16485 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15058 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14311 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13893 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13367 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13082 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12655 | `./node_modules/.bin/mocha test/` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12609 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12284 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12234 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11709 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11442 | `nyc grunt mocha-and-karma` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11069 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11065 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10390 | `mocha test/index.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10072 | `mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10063 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 10060 | `set NODE_ENV=test && mocha` | 
| [tj/co](https://github.com/tj/co) | 9998 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9917 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9596 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9528 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9336 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 9286 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9042 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8978 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8967 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8661 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8650 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8568 | `mocha tests/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8475 | `mocha test/test.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8420 | `mocha test/src` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8420 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8295 | `grunt clean:test && mocha --exit` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8164 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8159 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8046 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7935 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7882 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7674 | `./node_modules/.bin/mocha test` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7666 | `mocha --opts mocha.opts` | 
| [dthree/cash](https://github.com/dthree/cash) | 7550 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7525 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7438 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7410 | `npm run build && istanbul cover _mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7199 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7181 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7157 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7015 | `xo && mocha test/*.js --timeout 100000` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6986 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [almende/vis](https://github.com/almende/vis) | 6949 | `mocha --compilers js:babel-core/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6874 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6768 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6428 | `npm run jshint && mocha test/` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6344 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6285 | `mocha --exit --require babel-core/register` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6230 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6208 | `npm run test:mocha:src` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6147 | `mocha test/test.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6045 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6031 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5953 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5943 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5874 | `mocha tests/node.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5787 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5715 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5681 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5581 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5580 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5526 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5408 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5293 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5241 | `standard && mocha` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5173 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5152 | `mocha --color` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5078 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5070 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4946 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4944 | `gulp lint && mocha` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4913 | `mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4839 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4731 | `mocha test` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4729 | `gulp build; mocha;` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4727 | `mocha -R spec 'tests/app'` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4726 | `mocha test` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4723 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4693 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4591 | `./node_modules/.bin/mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4569 | `mocha ./test/runner.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4509 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4459 | `mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4429 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4398 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4394 | `nyc mocha --exit` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4388 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4370 | `npm run lint && npm run mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4325 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4148 | `npm run lint && npm run mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4131 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4123 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4073 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4038 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4009 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4008 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4004 | `mocha --require test/babel-hook test/*.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3974 | `mocha --timeout=15000 tests/*.test.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3974 | `npm run lint ; mocha && mocha test/individual` | 
| [tj/ejs](https://github.com/tj/ejs) | 3967 | `mocha --require should --reporter spec` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3890 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3881 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3829 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3824 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3810 | `mocha --check-leaks --reporter spec --bail` | 
| [erming/shout](https://github.com/erming/shout) | 3803 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3741 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3737 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3732 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [teambit/bit](https://github.com/teambit/bit) | 3721 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3698 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3672 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3660 | `standard && mocha --timeout 60000 test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3645 | `npm run build && mocha test/*.test.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3635 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 3599 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3577 | `mocha tests/javascript` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3566 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3563 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3542 | `node_modules/.bin/mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3535 | `mocha --reporter spec --timeout 3000` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3521 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3517 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3490 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3457 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3456 | `node_modules/.bin/mocha test/lib/` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3439 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3435 | `mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3420 | `NODE_ENV=test mocha test/**/*.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3388 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3363 | `NODE_ENV=test mocha --exit` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3311 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3228 | `nyc mocha && tsc` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3221 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3216 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3215 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3163 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3160 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3145 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3142 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3139 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3127 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3105 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3063 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3051 | `mocha test/*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3034 | `mocha test/index.js && npm run demo` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3032 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3031 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3023 | `mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3023 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3014 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3002 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3000 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2977 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2955 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2939 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2911 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2883 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2878 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2876 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2874 | `mocha -R spec --recursive src/test` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2861 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2861 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2852 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2840 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2821 | `istanbul cover _mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2817 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2814 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2803 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2796 | `npm run mocha && npm run lint` | 
| [github-tools/github](https://github.com/github-tools/github) | 2794 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2771 | `mocha --require should --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2771 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2768 | `mocha -R landing test/index` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2757 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2748 | `mocha --require babel-register --recursive spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2741 | `mocha test-node` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2716 | `node_modules/.bin/mocha --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2715 | `mocha --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2704 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2700 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tj/should.js](https://github.com/tj/should.js) | 2698 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 2678 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2666 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2650 | `mocha -R spec spec spec/reporters` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2645 | `mocha --timeout 100000` | 
| [json5/json5](https://github.com/json5/json5) | 2642 | `nyc --reporter=html --reporter=text mocha` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2633 | `mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2627 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2623 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2618 | `mocha --recursive --watch` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2610 | `mocha-phantomjs ./test/index.html` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2606 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2602 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2587 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2586 | `npm run build && cd test && mocha . --reporter dot` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2580 | `nyc mocha --timeout=10000` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2568 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2566 | `eslint . && mocha -t 5000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2524 | `nyc mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2508 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2499 | `mocha "test/**/*-test.js"` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2483 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2244 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2231 | `mocha test test/unit/**/*_test.js` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2190 | `mocha test/ --no-timeouts` | 
| [noble/noble](https://github.com/noble/noble) | 2188 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2165 | `mocha --compilers js:babel-register` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2141 | `cross-env BABEL_ENV=test mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2126 | `mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2106 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2098 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [Qix-/color](https://github.com/Qix-/color) | 2126 | `mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2106 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2098 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2091 | `standard && mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2061 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2043 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2035 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2033 | `nyc npm run _mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2091 | `standard && mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2078 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2061 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2043 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2035 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2033 | `nyc npm run _mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2007 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [slate/slate](https://github.com/slate/slate) | 2004 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1981 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1973 | `mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1966 | `mocha -c test/index.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1964 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1963 | `mocha --compilers js:babel-core/register __tests__` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1959 | `mocha --require=test/test_helper.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1952 | `mocha && eslint *.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1950 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1943 | `mocha --reporter spec --timeout 5000` | 
| [share/sharedb](https://github.com/share/sharedb) | 1930 | `./node_modules/.bin/mocha && npm run jshint` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1929 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1925 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1920 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [then/promise](https://github.com/then/promise) | 1916 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1909 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1908 | `mocha --require ./test/common --growl test/expect.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1908 | `npm run lint && mocha -R dot && npm run cover` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1904 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [pahen/madge](https://github.com/pahen/madge) | 1900 | `npm run lint && npm run mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 1883 | `mocha test/*.test.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1874 | `mocha tests.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1866 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1863 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1837 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1830 | `mocha --reporter spec && npm run test-typescript` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1829 | `npm run mocha && npm run karma` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1810 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1809 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1804 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1797 | `mocha test` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1795 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1794 | `mocha --reporter spec test/*.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1793 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1792 | `mocha && npm run lint` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1788 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1785 | `mocha test` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1784 | `mocha tests --compilers js:babel-core/register` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1776 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1774 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1767 | `mocha --compilers js:babel-register` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1756 | `npm run lint && npm run mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1754 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1750 | `mocha test/**/*.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1737 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1732 | `mocha test/**/*_test.js --bail` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1728 | `mocha test -u bdd -R spec` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1727 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1727 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1724 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1719 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1709 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1703 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1698 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1694 | `mocha ./test/basic.js -t 5000` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1689 | `npm run lint && mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1683 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1681 | `mocha test --timeout 600000` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1674 | `mocha test/*.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1650 | `mocha test/* --reporter spec` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1649 | `mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1645 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1632 | `mocha spec` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1632 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1630 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1626 | `mocha tests/test.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1624 | `mocha && size-limit` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1621 | `mocha compiled_tests/` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1606 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1599 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1594 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1606 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1599 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1594 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1584 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1580 | `mocha test/setup.js test/spec/*.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1568 | `./node_modules/mocha/bin/mocha -R spec` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1562 | `eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1559 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1558 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [zeit/ms](https://github.com/zeit/ms) | 1557 | `mocha tests.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1553 | `mocha test` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1520 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1518 | `mocha test.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1514 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1513 | `mocha --check-leaks --reporter spec --bail` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1512 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1503 | `nyc npm run mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1501 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1496 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1495 | `nyc mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1481 | `mocha -R spec` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1480 | `mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1496 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1495 | `nyc mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1481 | `mocha -R spec` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1480 | `mocha --recursive` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1473 | `mocha test/**/*.spec.js` | 
| [retejs/rete](https://github.com/retejs/rete) | 1464 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [samccone/drool](https://github.com/samccone/drool) | 1454 | `mocha test/tests.js --timeout=10000` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1411 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [noble/bleno](https://github.com/noble/bleno) | 1403 | `mocha -R spec test/*.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1401 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1401 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1387 | `istanbul cover _mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1379 | `./node_modules/mocha/bin/mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1376 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1373 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1372 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1366 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1360 | `cross-env NODE_ENV=test nyc mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1360 | `npm run build && mocha -r should` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1387 | `istanbul cover _mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1379 | `./node_modules/mocha/bin/mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1376 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1373 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1372 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1366 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1363 | `mocha test/unit` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1360 | `cross-env NODE_ENV=test nyc mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1360 | `npm run build && mocha -r should` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1350 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [electron/devtron](https://github.com/electron/devtron) | 1346 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1345 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1339 | `mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1337 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1337 | `npm run lint && mocha && karma start --single-run` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1336 | `TEST=all mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1331 | `mocha --opts test/opts/mocha.opts` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1327 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1327 | `istanbul cover _mocha test -- --timeout 20000` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1323 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1322 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1320 | `./node_modules/.bin/mocha test` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1317 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1315 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1315 | `mocha --recursive` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1309 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1307 | `mocha tests/test-*` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1306 | `mocha-phantomjs tests/index.html` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1300 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1300 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1299 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1295 | `mocha --reporter dot` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1295 | `mocha spec/exec.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1281 | `NODE_PATH=. mocha **/*.spec.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1279 | `mocha` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1268 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1268 | `mocha --timeout 60000 test/` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1263 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1260 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1259 | `NODE_ENV=test mocha tests/*.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1251 | `mocha ./test/test*.js --reporter spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1251 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1250 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1248 | `mocha tests` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1248 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1247 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1246 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1246 | `mocha test/*.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1245 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1243 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1242 | `mocha -R spec ./test/unit/**` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1226 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1223 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1219 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1218 | `mocha src/test.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1213 | `mocha` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1211 | `mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1209 | `npm run prepublishOnly && mocha test/test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1208 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1208 | `mocha --recursive test/bin` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1202 | `mocha test` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1201 | `npm run lint && npm run mocha` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1200 | `node ./node_modules/mocha/bin/mocha tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1200 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [normalize/mz](https://github.com/normalize/mz) | 1198 | `mocha --reporter spec` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1194 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1201 | `npm run lint && npm run mocha` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1200 | `node ./node_modules/mocha/bin/mocha tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1200 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [normalize/mz](https://github.com/normalize/mz) | 1198 | `mocha --reporter spec` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1194 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1186 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1186 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1185 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1183 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [variety/variety](https://github.com/variety/variety) | 1183 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1178 | `mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1178 | `mocha --recursive test` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1174 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1171 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1167 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1167 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1159 | `mocha --compilers js:babel-core/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1155 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1149 | `mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1147 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1145 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1144 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1133 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1131 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1123 | `mocha $(find test -name '*.test.js')` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1122 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1121 | `webpack && npm run lint && npm run mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1121 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1120 | `mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1117 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1114 | `xo && mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1114 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1111 | `istanbul cover _mocha test/*.js` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1110 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1107 | `npm run lint && mocha --require @babel/register` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1107 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1106 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1105 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1102 | `mocha test/*` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1100 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1098 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1097 | `npm run mocha:istanbul` | 
| [router5/router5](https://github.com/router5/router5) | 1097 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1090 | `mocha --check-leaks -t 20000` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1090 | `mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1082 | `mocha --compilers js:babel-register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1075 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1074 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [electron/asar](https://github.com/electron/asar) | 1074 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1070 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1065 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1062 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1062 | `webpack && mocha test/unit` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1058 | `mocha --recursive --bail --reporter spec test` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1057 | `mocha --timeout 20000` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1054 | `mocha test/tests.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1053 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1050 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1041 | `mocha --reporter spec --bail --check-leaks test/` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1039 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1039 | `mocha --reporter spec --bail --check-leaks test/` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1037 | `mocha --reporter spec --timeout 3000` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1034 | `mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1033 | `standard && mocha -b` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1029 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 1024 | `mocha && standard` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1022 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [tomas/needle](https://github.com/tomas/needle) | 1019 | `mocha test` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1019 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1017 | `eslint src test && mocha --compilers babel-register` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1013 | `mocha --timeout 30000 --recursive ./tests` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1013 | `mocha $(find test -name '*.test.js')` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1012 | `mocha --check-leaks -R dot` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1007 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1003 | `mocha --recursive test/unit/` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1002 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1000 | `mocha --async-only` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 997 | `mocha --colors ./test/*.spec.js` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 997 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 992 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 938 | `mocha --compilers js:babel-register test/*.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 936 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 934 | `mocha --recursive -r tests/setup tests` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 934 | `mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 931 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 929 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 927 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 923 | `npm run lint && mocha -R spec` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 916 | `mocha ./test/index.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 915 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 913 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 907 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 906 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 906 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 903 | `mocha spec/*.js` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 897 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 896 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 884 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 884 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 882 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 881 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 881 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 875 | `nyc mocha specs` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 875 | `mocha test` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 875 | `mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 871 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 868 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 865 | `npm run lint && npm run mocha:no-functional` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 865 | `mocha --timeout 200000` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 864 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 864 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 864 | `./node_modules/.bin/mocha --reporter spec` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 863 | `mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 855 | `istanbul cover -- _mocha --reporter spec` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 854 | `standard && standard ./bin/* && mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 849 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 848 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 848 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 842 | `nyc --check-coverage mocha test/*.test.js` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 840 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 840 | `mocha --check-leaks -t 20000` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 839 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 838 | `istanbul cover _mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 837 | `mocha --reporter list` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 836 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 835 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 834 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 832 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 830 | `npm run lint && mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 829 | `mocha --reporter spec --bail --check-leaks test/` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 829 | `mocha --recursive ./test/*_spec.js` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 828 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 823 | `mocha && ember test` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 819 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 817 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 814 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 806 | `cake build && mocha ./test/mocha/*.coffee` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 806 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 805 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 805 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 805 | `mocha --async-only` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 799 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 795 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 792 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 771 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 771 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 769 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 765 | `mocha test` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 755 | `mocha --recursive -s 15 test/` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 785 | `npm run mocha-test test/integration` | 
| [edsu/anon](https://github.com/edsu/anon) | 785 | `mocha --colors --reporter spec test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 784 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 782 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 782 | `npm run build && istanbul test _mocha test/test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 781 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 781 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 780 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 780 | `mocha` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 779 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 778 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 777 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 776 | `xo && mocha -R spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 771 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 771 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 769 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 767 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 766 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 765 | `mocha --ui tdd --require ./test/__setup` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 765 | `mocha test` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 763 | `mocha --no-timeouts` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 756 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 755 | `mocha --recursive -s 15 test/` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 751 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 751 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 751 | `mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 750 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 749 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 749 | `mocha -r should --reporter spec test/*.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 739 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 739 | `mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 738 | `npm run lint && npm run mocha` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 738 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 738 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 737 | `mocha test` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 737 | `mocha --reporter spec` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 736 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 735 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 735 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 735 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 716 | `mocha --exit --use_strict src/*.test.js` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 715 | `mocha --reporter spec build/test/index.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 713 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [typicode/katon](https://github.com/typicode/katon) | 710 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 709 | `./bin/selenium-standalone install && mocha` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 708 | `npm run-script jshint && npm run-script mocha` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 704 | `mocha ./test/index.js` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 703 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 702 | `mocha ./test/test.js --timeout 1000000` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 700 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 