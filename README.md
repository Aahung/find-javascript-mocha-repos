# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:00 09/03/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43404 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41241 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39977 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30210 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 26246 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24555 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23391 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19940 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19089 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17194 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16888 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16751 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15317 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14363 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14048 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13658 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13242 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12804 | `./node_modules/.bin/mocha test/` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12680 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12373 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12237 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11958 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11567 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11323 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11282 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10560 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10242 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10191 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10158 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10077 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10010 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9796 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9764 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 9462 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9417 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9169 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9168 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9034 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8784 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8769 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8762 | `mocha tests/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8517 | `mocha test/test.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8512 | `mocha test/src` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8462 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8449 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8340 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8198 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8117 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8082 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7924 | `mocha --opts mocha.opts` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7916 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7738 | `./node_modules/.bin/mocha test` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7707 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [dthree/cash](https://github.com/dthree/cash) | 7558 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7447 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7439 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7304 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7287 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7282 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7124 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7080 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 7056 | `mocha --compilers js:babel-core/register` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7005 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6925 | `mocha $HARMONY_OPTS` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 6785 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js'` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6741 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6584 | `mocha; jshint *.js lib` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6503 | `npm run jshint && mocha test/` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6461 | `mocha --exit --require babel-core/register` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6360 | `mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6289 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6275 | `mocha test/test.js` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6246 | `npm run test:mocha:src` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6051 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5992 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5953 | `mocha tests/node.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5935 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5843 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5765 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5743 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5736 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5717 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5699 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5430 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5417 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5389 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5374 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5365 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5182 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5147 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5115 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5067 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5038 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4983 | `gulp lint && mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 4954 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4847 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4810 | `mocha test` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4780 | `gulp build; mocha;` | 
| [santinic/how2](https://github.com/santinic/how2) | 4762 | `mocha test` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4759 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4738 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4696 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4648 | `./node_modules/.bin/mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4640 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4573 | `mocha ./test/runner.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4492 | `mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4483 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4471 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4460 | `nyc mocha --exit` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4438 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4431 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4335 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4270 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4202 | `mocha -R spec src` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4187 | `nyc mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4152 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4100 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4057 | `mocha --timeout=15000 tests/*.test.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4045 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4040 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4032 | `mocha --require test/babel-hook test/*.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4022 | `npm run lint ; mocha && mocha test/individual` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4008 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 3993 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3904 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3898 | `export TESTING=true; mocha --reporter list` | 
| [teambit/bit](https://github.com/teambit/bit) | 3895 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3892 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3884 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3879 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [erming/shout](https://github.com/erming/shout) | 3805 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3761 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3719 | `nyc mocha "test/**/*.test.js"` | 
| [primus/primus](https://github.com/primus/primus) | 3674 | `npm run build && mocha test/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3671 | `standard && mocha --timeout 60000 test/test.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3719 | `nyc mocha "test/**/*.test.js"` | 
| [primus/primus](https://github.com/primus/primus) | 3674 | `npm run build && mocha test/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3671 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3664 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3650 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3580 | `mocha tests/javascript` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3565 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3561 | `node_modules/.bin/mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3551 | `mocha --reporter spec --timeout 3000` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3542 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3535 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3523 | `NODE_ENV=test mocha --exit` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3502 | `NODE_ENV=test mocha test/**/*.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3490 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3484 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3445 | `mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3398 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3288 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3274 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3266 | `nyc mocha && tsc` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3240 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3038 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3032 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3030 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3012 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2986 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2918 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2905 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2899 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2895 | `mocha -R spec --recursive src/test` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2890 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2881 | `mocha -R landing test/index` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2874 | `mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2855 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2844 | `npm run mocha && npm run lint` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2841 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2986 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2933 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2924 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2918 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2905 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2899 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2895 | `mocha -R spec --recursive src/test` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2890 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2881 | `mocha -R landing test/index` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2874 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2871 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2855 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2844 | `npm run mocha && npm run lint` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2841 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2835 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2831 | `istanbul cover _mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2819 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2841 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2835 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2831 | `istanbul cover _mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2819 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2804 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2798 | `mocha -R spec spec spec/reporters` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2781 | `eslint . && mocha -t 5000` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2779 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2779 | `mocha --require babel-register --recursive spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2772 | `mocha --require should --reporter spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2762 | `node_modules/.bin/mocha --reporter spec` | 
| [mde/ejs](https://github.com/mde/ejs) | 2762 | `mocha --require should --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2732 | `mocha --reporter dot` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2725 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2711 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2706 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2699 | `mocha test.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2471 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2466 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2461 | `mocha test/src/**/*.unit.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2448 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2445 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2417 | `mocha --no-colors --reporter spec` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2413 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2404 | `nyc --reporter=html --reporter=text mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2393 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2352 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2352 | `grunt jshint && mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2341 | `mocha test && npm run lint` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2326 | `mocha test/index.js --reporter dot` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2314 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2304 | `mocha test/ --no-timeouts` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2524 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2485 | `mocha --reporter=spec test/*-test.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2471 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2471 | `mocha` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2468 | `mocha test` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2466 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2461 | `mocha test/src/**/*.unit.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2448 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2445 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2417 | `mocha --no-colors --reporter spec` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2413 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2404 | `nyc --reporter=html --reporter=text mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2393 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2372 | `node node_modules/mocha/bin/_mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2237 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2229 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [gajus/swing](https://github.com/gajus/swing) | 2229 | `mocha --compilers js:babel-register` | 
| [noble/noble](https://github.com/noble/noble) | 2223 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2208 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2175 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2149 | `cross-env BABEL_ENV=test mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2126 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2123 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2120 | `standard && mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2115 | `mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 1905 | `mocha test/*.test.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1901 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1897 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [zeeshanu/dumper.js](https://github.com/zeeshanu/dumper.js) | 1892 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1878 | `mocha tests.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1864 | `npm run mocha && npm run karma` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1847 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1844 | `mocha --reporter spec && npm run test-typescript` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1829 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1827 | `mocha --compilers js:babel-register` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1823 | `mocha --reporter spec test/*.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1818 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1816 | `mocha && npm run lint` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1813 | `mocha tests --require babel-core/register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1811 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1806 | `npm run lint && mocha --reporter spec test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1806 | `npm run lint && mocha --reporter spec test/*.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1805 | `mocha --timeout 5000` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1796 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1793 | `mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1786 | `mocha test/**/*.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1773 | `npm run lint && npm run mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1757 | `mocha test -u bdd -R spec` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1754 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1752 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1736 | `mocha test/**/*_test.js --bail` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1736 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1715 | `./node_modules/.bin/mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1715 | `mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1702 | `npm run lint && mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1701 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1699 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1690 | `mocha test --timeout 600000` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1689 | `npm run lint && npm run mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1686 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1682 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1676 | `mocha test/* --reporter spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1670 | `mocha compiled_tests/` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1661 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1661 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1660 | `mocha` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1659 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1661 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1661 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1660 | `mocha` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1659 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1641 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1641 | `mocha test` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1639 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1635 | `mocha && size-limit` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1631 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1630 | `mocha tests/test.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1624 | `mocha test/setup.js test/spec/*.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1609 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1608 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1597 | `eslint --cache . && tsc && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1595 | `mocha tests.js` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1595 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1594 | `mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1586 | `standard "./src/*.js" && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1581 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1575 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1566 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1557 | `mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1556 | `mocha --reporter spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1553 | `./node_modules/.bin/mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1552 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1548 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1476 | `mocha test/**/*.spec.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1457 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1443 | `mocha test.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1435 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1419 | `mocha -R spec test/*.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1418 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1417 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1411 | `mocha --check-leaks --require @babel/register` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1406 | `TEST=all mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1374 | `npm run lint && mocha && karma start --single-run` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1373 | `npm run build && mocha -r should` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1368 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1366 | `mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1359 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1345 | `mocha tests/test-*` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1342 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1342 | `istanbul cover _mocha test -- --timeout 20000` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1341 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1336 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1333 | `standard && istanbul cover _mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1332 | `NODE_ENV=test mocha tests/*.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1331 | `mocha --recursive` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1323 | `./node_modules/.bin/mocha test` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1322 | `mocha --reporter dot` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1314 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1313 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1435 | `mocha --timeout 10000 ./tests/lib.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1434 | `mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1419 | `mocha -R spec test/*.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1418 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1417 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1411 | `mocha --check-leaks --require @babel/register` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1406 | `TEST=all mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1404 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1401 | `mocha test/unit` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1400 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1392 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1390 | `istanbul cover _mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1390 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1304 | `NODE_PATH=. mocha **/*.spec.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1303 | `mocha ./test/test*.js --reporter spec` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1287 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1286 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1285 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1284 | `npm run lint && npm run mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1281 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1277 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1264 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1263 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1263 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1263 | `mocha --check-leaks --reporter spec --bail test/` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1262 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1260 | `mocha test/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1254 | `mocha tests` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1260 | `mocha test/*.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1256 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1254 | `mocha tests` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1249 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1242 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1234 | `mocha src/test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1232 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1231 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1230 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1227 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1222 | `istanbul test _mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1218 | `npm run lint && npm run mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1217 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1217 | `mocha test/test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1264 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1263 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1263 | `mocha --check-leaks --reporter spec --bail test/` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1262 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1260 | `mocha test/*.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1259 | `mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1256 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1255 | `mocha --recursive test/bin` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1254 | `mocha tests` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1249 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1242 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1234 | `mocha src/test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1232 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1231 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1230 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1227 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1222 | `istanbul test _mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1218 | `npm run lint && npm run mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1217 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1217 | `mocha test/test.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1210 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1209 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1208 | `mocha --recursive test` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1208 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1207 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [normalize/mz](https://github.com/normalize/mz) | 1207 | `mocha --reporter spec` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1205 | `mocha --compilers js:babel-core/register` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1205 | `node ./node_modules/mocha/bin/mocha tests` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1203 | `mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1198 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1195 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1195 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [variety/variety](https://github.com/variety/variety) | 1194 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1173 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1172 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1168 | `webpack && npm run lint && npm run mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1166 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1162 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1148 | `npm run lint && mocha --require @babel/register` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1145 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1143 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1128 | `mocha $(find test -name '*.test.js') --exit` | 
| [router5/router5](https://github.com/router5/router5) | 1127 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1143 | `mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1132 | `npm run mocha:istanbul` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1128 | `mocha $(find test -name '*.test.js') --exit` | 
| [router5/router5](https://github.com/router5/router5) | 1127 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1124 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1123 | `xo && mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1121 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1120 | `istanbul cover _mocha test/*.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1120 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1110 | `mocha --timeout 20000` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1109 | `mocha test/*` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1108 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1107 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1105 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1105 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1100 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1110 | `mocha --timeout 20000` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1109 | `mocha test/*` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1108 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1107 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1105 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1105 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1100 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [electron/asar](https://github.com/electron/asar) | 1097 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1095 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1092 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1084 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1082 | `nodeunit test; mocha test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1082 | `mocha --compilers js:babel-register` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1079 | `webpack && mocha test/unit` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1074 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1070 | `mocha --recursive --bail --reporter spec test` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1070 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1067 | `mocha --reporter spec --bail --check-leaks test/` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1064 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1062 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1061 | `mocha --timeout 30000 --recursive ./tests` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1061 | `mocha --reporter spec --bail --check-leaks test/` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1060 | `mocha test/tests.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1057 | `standard && mocha -b` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1047 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1047 | `mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1038 | `mocha --reporter spec --timeout 3000` | 
| [electron/spectron](https://github.com/electron/spectron) | 1035 | `mocha && standard` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1032 | `eslint src test && mocha --compilers babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1030 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 1029 | `mocha test` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1029 | `mocha test --compilers js:babel-core/register` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1027 | `npm-run-all test:jest test:server:mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1025 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1013 | `mocha --recursive test/unit/` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1013 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1013 | `mocha --check-leaks -R dot` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1011 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1008 | `mocha --async-only` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1003 | `mocha --colors ./test/*.spec.js` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1008 | `mocha --async-only` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1003 | `mocha --colors ./test/*.spec.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1002 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 997 | `npm run convertto:es5 && npm run mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 995 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 989 | `mocha -R list` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 987 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 987 | `mocha --recursive -r tests/setup tests` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 986 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 978 | `npm run rollup-cjs && mocha test/test.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 977 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 950 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 950 | `mocha --compilers js:babel-register test/*.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 948 | `mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 946 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 946 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 946 | `mocha "client.test" --compilers js:babel-register` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 945 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 943 | `mocha --timeout 5000` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 941 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 935 | `npm run lint && mocha -R spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 927 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 921 | `mocha spec/*.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 871 | `istanbul cover -- _mocha --reporter spec` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 870 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 867 | `nyc --check-coverage mocha test/*.test.js` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 867 | `npm run lint && npm run mocha:no-functional` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 865 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 865 | `standard && standard ./bin/* && mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 865 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 864 | `node_modules/.bin/mocha test/spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 859 | `eslint test && mocha --compilers js:babel/register` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 854 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 849 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 849 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 888 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 885 | `node_modules/.bin/mocha` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 883 | `mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 881 | `./node_modules/.bin/mocha -R spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 881 | `./node_modules/.bin/mocha --reporter spec` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 878 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 877 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 871 | `istanbul cover -- _mocha --reporter spec` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 870 | `mocha --timeout 200000` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 870 | `mocha test --compilers js:babel-register` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 870 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 868 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 868 | `mocha -t 5000` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 867 | `nyc --check-coverage mocha test/*.test.js` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 867 | `npm run lint && npm run mocha:no-functional` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 867 | `mocha --recursive ./test/*_spec.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 865 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 865 | `standard && standard ./bin/* && mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 865 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 864 | `node_modules/.bin/mocha test/spec` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 861 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 859 | `eslint test && mocha --compilers js:babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 856 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 854 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 849 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 849 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 848 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 847 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 845 | `mocha --reporter spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 845 | `mocha --check-leaks -t 20000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 843 | `mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 843 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 840 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 837 | `npm run lint && mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 834 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 833 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 832 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 831 | `mocha test/index.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 827 | `mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 827 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 825 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 825 | `mocha && ember test` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 823 | `mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 821 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 820 | `mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 818 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 818 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 817 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 816 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 816 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 816 | `mocha --async-only` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 814 | `mocha tests/*.test.js --reporter spec` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 812 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 810 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 808 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 807 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 798 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 795 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 795 | `mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 794 | `npm run build && istanbul test _mocha test/test.js` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 793 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 792 | `mocha --exit --use_strict src/*.test.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 791 | `npm run mocha-test test/integration` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 790 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 789 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [edsu/anon](https://github.com/edsu/anon) | 789 | `mocha --colors --reporter spec test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 784 | `mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 782 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 781 | `xo && mocha -R spec` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 790 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 789 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [edsu/anon](https://github.com/edsu/anon) | 789 | `mocha --colors --reporter spec test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 784 | `mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 782 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 781 | `xo && mocha -R spec` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 779 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 779 | `./node_modules/.bin/mocha test/**/*` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 778 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 778 | `mocha` | 
| [developit/decko](https://github.com/developit/decko) | 774 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 773 | `mocha test` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 771 | `mocha --no-timeouts` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 770 | `mocha -r should --reporter spec test/*.js` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 769 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 765 | `mocha --ui tdd --require ./test/__setup` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 765 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 763 | `mocha --recursive -s 15 test/` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 759 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 759 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 757 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 727 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 725 | `mocha --reporter spec build/test/index.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 724 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 724 | `npm run bundle && mocha` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 724 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 717 | `./bin/selenium-standalone install && mocha` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 712 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 710 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 710 | `mocha` | 
| [koajs/static](https://github.com/koajs/static) | 709 | `mocha --harmony --reporter spec --exit` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 731 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 731 | `mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 730 | `npm run-script jshint && npm run-script mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 729 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 727 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 727 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 725 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 725 | `mocha --reporter spec build/test/index.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 724 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 724 | `npm run bundle && mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 725 | `mocha --reporter spec build/test/index.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 724 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 724 | `npm run bundle && mocha` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 724 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 718 | `nyc mocha` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 717 | `./bin/selenium-standalone install && mocha` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 712 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 711 | `mocha ./test/index.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 710 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 710 | `mocha` | 
| [koajs/static](https://github.com/koajs/static) | 709 | `mocha --harmony --reporter spec --exit` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 708 | `mocha --harmony tests/**` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 706 | `mocha ./test/test.js --timeout 1000000` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 706 | `npm run lint && mocha` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 703 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 700 | `mocha` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 697 | `mocha $(find test -name '*.test.js')` | 