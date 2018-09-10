# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:02 09/10/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43485 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41275 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40082 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30261 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 26394 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24589 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23472 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20029 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19126 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17265 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16933 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16850 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15366 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14376 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14098 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13723 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13274 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12843 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12701 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12393 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12242 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12045 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11609 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11371 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11339 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10605 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10291 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10226 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10181 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10103 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10035 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9848 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 9515 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9428 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9217 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9187 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9049 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8813 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8802 | `mocha tests/*.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8796 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8550 | `mocha test/src` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8538 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8527 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8452 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8347 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8211 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8181 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8092 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7976 | `mocha --opts mocha.opts` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7927 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7753 | `./node_modules/.bin/mocha test` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7745 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [dthree/cash](https://github.com/dthree/cash) | 7560 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7457 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7440 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7332 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7321 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7301 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7162 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7097 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 7082 | `mocha --compilers js:babel-core/register` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7058 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6939 | `mocha $HARMONY_OPTS` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 6814 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js'` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6759 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6673 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6527 | `mocha --exit --require babel-core/register` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6522 | `npm run jshint && mocha test/` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6420 | `mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6304 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6299 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6255 | `npm run test:mocha:src` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6054 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6004 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5971 | `mocha tests/node.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5934 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5858 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5812 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5751 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5750 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5749 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5734 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5518 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5421 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5420 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5407 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5394 | `standard && mocha` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5183 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5148 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5128 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5109 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5089 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5065 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4991 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4857 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4840 | `mocha test` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4791 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4767 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4766 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4744 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4700 | `mocha --reporter spec -t 8000` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4680 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4661 | `./node_modules/.bin/mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4574 | `mocha ./test/runner.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4515 | `mocha --recursive` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4502 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4491 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4476 | `nyc mocha --exit` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4444 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4439 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [primus/primus](https://github.com/primus/primus) | 3680 | `npm run build && mocha test/*.test.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3676 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3669 | `npm run jshint && npm run mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3587 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3568 | `NODE_ENV=test mocha --exit` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3565 | `node_modules/.bin/mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3563 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3550 | `mocha --reporter spec --timeout 3000` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3538 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3506 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3493 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3470 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3447 | `mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3301 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3292 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3281 | `nyc mocha && tsc` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3248 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3246 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3218 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3069 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3058 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3038 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3024 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3017 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3003 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2949 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2946 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2939 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2911 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2902 | `mocha -R spec --recursive src/test` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2902 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2901 | `mocha -R landing test/index` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2899 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2881 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2874 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2862 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2857 | `eslint . && mocha -t 5000` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2856 | `npm run mocha && npm run lint` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2855 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2949 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2946 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2939 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2911 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2902 | `mocha -R spec --recursive src/test` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2902 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2901 | `mocha -R landing test/index` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2899 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2881 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2874 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2862 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2857 | `eslint . && mocha -t 5000` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2856 | `npm run mocha && npm run lint` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2855 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2839 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2833 | `istanbul cover _mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2824 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2807 | `mocha -R spec spec spec/reporters` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2806 | `mocha` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2795 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2783 | `mocha --require babel-register --recursive spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2778 | `node_modules/.bin/mocha --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2774 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2744 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [css/csso](https://github.com/css/csso) | 2734 | `mocha --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2723 | `xo && mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2714 | `mocha test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2706 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2702 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2699 | `mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2693 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2603 | `nyc mocha --timeout=10000` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2596 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2577 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2570 | `nyc mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2570 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2546 | `mocha "test/**/*-test.js"` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2525 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2485 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2476 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2469 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2466 | `mocha test/src/**/*.unit.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2457 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2451 | `mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2358 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2353 | `grunt jshint && mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2350 | `mocha test && npm run lint` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2341 | `mocha -R spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2334 | `mocha test/index.js --reporter dot` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2323 | `mocha test/ --no-timeouts` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2315 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2305 | `mocha && eslint .` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2288 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2283 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2274 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2236 | `mocha -R spec test/*.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2232 | `mocha --compilers js:babel-register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2229 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2216 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2184 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2150 | `cross-env BABEL_ENV=test mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2128 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2123 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2121 | `standard && mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2120 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2115 | `mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2099 | `mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2099 | `nyc npm run _mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2092 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2092 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2083 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2069 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2044 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2040 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2022 | `mocha && eslint *.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2000 | `mocha --compilers js:babel-core/register __tests__` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1995 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 1993 | `npm run lint && npm run mocha` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1991 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2099 | `mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2099 | `nyc npm run _mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2092 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2083 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2069 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2044 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2040 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2022 | `mocha && eslint *.js` | 
| [slate/slate](https://github.com/slate/slate) | 2006 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2000 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1999 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1995 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1944 | `npm run lint && mocha -R dot && npm run cover` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1939 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1938 | `mocha` | 
| [then/promise](https://github.com/then/promise) | 1938 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1931 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1928 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1924 | `mocha --require ./test/common --growl test/expect.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1912 | `mocha test/*.test.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1906 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1891 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1883 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1878 | `mocha tests.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1875 | `npm run mocha && npm run karma` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1851 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1850 | `mocha --reporter spec && npm run test-typescript` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1839 | `mocha --compilers js:babel-register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1839 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1832 | `mocha --reporter spec test/*.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1831 | `mocha && npm run lint` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1820 | `mocha tests --require @babel/register` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1819 | `mocha test` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1813 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1812 | `npm run lint && mocha --reporter spec test/*.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1810 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1806 | `mocha --timeout 5000` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1801 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1800 | `mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1797 | `mocha test/**/*.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1761 | `mocha test -u bdd -R spec` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1754 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1753 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1753 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1737 | `mocha test/**/*_test.js --bail` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1735 | `mocha ./test/basic.js -t 5000` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1735 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1733 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1728 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1717 | `./node_modules/.bin/mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1715 | `mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1708 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1705 | `mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1708 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1706 | `npm run lint && mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1705 | `mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1699 | `npm run lint && npm run mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1696 | `mocha test --timeout 600000` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1688 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1685 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1680 | `mocha test/* --reporter spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1678 | `mocha compiled_tests/` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1671 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1668 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1662 | `mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1661 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1660 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1659 | `mocha test` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1641 | `mocha spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1640 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1638 | `mocha && size-limit` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1637 | `mocha test/setup.js test/spec/*.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1634 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1633 | `mocha tests/test.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1610 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1609 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [zeit/ms](https://github.com/zeit/ms) | 1604 | `mocha tests.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1602 | `eslint --cache . && tsc && mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1597 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1592 | `standard "./src/*.js" && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1592 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1578 | `./node_modules/mocha/bin/mocha -R spec` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1576 | `mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1568 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1564 | `mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1562 | `mocha --reporter spec` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1561 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1556 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1546 | `mocha --check-leaks --reporter spec --bail` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1546 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1543 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1537 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1535 | `node_modules/.bin/mocha --recursive` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1531 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [retejs/rete](https://github.com/retejs/rete) | 1527 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1522 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1511 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1511 | `mocha -u tdd` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1510 | `nyc mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1502 | `mocha --recursive` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1500 | `nyc mocha --timeout=20000 test.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1486 | `mocha -R spec` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1442 | `mocha test.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1439 | `mocha --timeout 10000 ./tests/lib.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1431 | `TEST=all mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1425 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1424 | `mocha -R spec test/*.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1420 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1419 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1410 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1408 | `mocha test/unit` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1407 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1420 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1419 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1410 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1408 | `mocha test/unit` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1407 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1398 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1396 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1395 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1391 | `istanbul cover _mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1386 | `./node_modules/mocha/bin/mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1385 | `npm run lint && mocha && karma start --single-run` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1383 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1380 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1379 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1378 | `npm run build && mocha -r should` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1376 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1365 | `NODE_ENV=test mocha tests/*.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1364 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1363 | `cross-env NODE_ENV=test nyc mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1360 | `mocha --opts test/opts/mocha.opts` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1353 | `mocha tests/test-*` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1349 | `istanbul cover _mocha test -- --timeout 20000` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1347 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1343 | `standard && istanbul cover _mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1338 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1335 | `mocha --recursive` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1331 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1330 | `mocha --reporter dot` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1186 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1173 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1169 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1164 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1155 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1151 | `mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1150 | `mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1146 | `npm run mocha:istanbul` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1131 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1129 | `mocha $(find test -name '*.test.js') --exit` | 
| [poooi/poi](https://github.com/poooi/poi) | 1129 | `mocha --recursive --harmony --require ./test/babelhook` | 
| [router5/router5](https://github.com/router5/router5) | 1129 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1128 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1127 | `istanbul cover _mocha test/*.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1123 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1119 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1118 | `mocha --timeout 20000` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1109 | `mocha test/*` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1108 | `mocha` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1108 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1107 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1107 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1105 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [electron/asar](https://github.com/electron/asar) | 1101 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1095 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1092 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1084 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1083 | `webpack && mocha test/unit` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1081 | `mocha --compilers js:babel-register` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1079 | `mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1074 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1071 | `mocha --recursive --bail --reporter spec test` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1071 | `mocha --reporter spec --bail --check-leaks test/` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1069 | `mocha --timeout 30000 --recursive ./tests` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1068 | `mocha --reporter spec --bail --check-leaks test/` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1067 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1066 | `mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1061 | `mocha test/tests.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1059 | `standard && mocha -b` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1056 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1050 | `mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1046 | `mocha test --compilers js:babel-core/register` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1046 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [electron/spectron](https://github.com/electron/spectron) | 1040 | `mocha && standard` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1037 | `mocha --reporter spec --timeout 3000` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1037 | `npm-run-all test:jest test:server:mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1035 | `eslint src test && mocha --compilers babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1034 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 1030 | `mocha test` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1025 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1025 | `mocha $(find test -name '*.test.js')` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1020 | `mocha` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1018 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1017 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1014 | `mocha --recursive test/unit/` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1014 | `mocha --check-leaks -R dot` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1012 | `mocha --async-only` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1006 | `npm run convertto:es5 && npm run mocha` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1003 | `mocha --colors ./test/*.spec.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 995 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 993 | `mocha -R list` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 992 | `mocha --recursive -r tests/setup tests` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 989 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 988 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 988 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 980 | `npm run rollup-cjs && mocha test/test.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 976 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 975 | `mocha --reporter spec` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 971 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 961 | `mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 959 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 958 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 955 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 951 | `mocha --compilers js:babel-register test/*.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 951 | `mocha "client.test" --compilers js:babel-register` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 948 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 946 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 945 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 943 | `mocha --timeout 5000` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 940 | `npm run lint && mocha -R spec` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 926 | `mocha test` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 924 | `mocha tests` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 923 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 920 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 918 | `mocha test` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 912 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 909 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 908 | `mocha -t 600000` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 904 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 912 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 909 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 908 | `mocha -t 600000` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 904 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 899 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 897 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 896 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 876 | `mocha --recursive ./test/*_spec.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 876 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 872 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 872 | `npm run lint && npm run mocha:no-functional` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 871 | `mocha test --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 871 | `standard && standard ./bin/* && mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 870 | `mocha --timeout 200000` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 870 | `mocha -t 5000` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 869 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 867 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 865 | `node_modules/.bin/mocha test/spec` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 863 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 861 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 860 | `mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 858 | `eslint test && mocha --compilers js:babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 856 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 809 | `mocha` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 809 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 808 | `cake build && mocha ./test/mocha/*.coffee` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 802 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 799 | `npm run build && istanbul test _mocha test/test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 799 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 798 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 797 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 796 | `npm run mocha-test test/integration` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 796 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 795 | `./node_modules/.bin/mocha test/**/*` | 
| [edsu/anon](https://github.com/edsu/anon) | 794 | `mocha --colors --reporter spec test.js` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 794 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 794 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 792 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 792 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 792 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 786 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 781 | `xo && mocha -R spec` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 781 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 779 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 778 | `mocha` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 777 | `mocha -r should --reporter spec test/*.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 776 | `mocha test` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 764 | `mocha --recursive -s 15 test/` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 763 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 756 | `mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 753 | `mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 750 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 743 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 742 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 742 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 740 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 739 | `babel-node node_modules/.bin/_mocha -- test` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 738 | `mocha tests/*.mocha.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 737 | `mocha --reporter spec` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 735 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 733 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 731 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 733 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 731 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 729 | `mocha` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 729 | `mocha test.js` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 728 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 726 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 725 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 725 | `npm run bundle && mocha` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 724 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 723 | `nyc mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 723 | `nyc mocha` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 720 | `./bin/selenium-standalone install && mocha` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 719 | `mocha --harmony tests/**` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 718 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 714 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 714 | `mocha` | 
| [koajs/static](https://github.com/koajs/static) | 713 | `mocha --harmony --reporter spec --exit` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 712 | `mocha ./test/index.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 710 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 709 | `npm run lint && mocha` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 708 | `mocha ./test/test.js --timeout 1000000` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 708 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 712 | `mocha ./test/index.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 710 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 709 | `npm run lint && mocha` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 708 | `mocha ./test/test.js --timeout 1000000` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 708 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 706 | `mocha` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 703 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 702 | `mocha $(find test -name '*.test.js')` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 698 | `npm run test-mocha && npm run test-karma` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 698 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 696 | `./node_modules/.bin/mocha -t 60000` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 695 | `mocha --reporter spec` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 692 | `mocha --compilers js:babel-core/register` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 691 | `jenkins-mocha ./tests/*.js` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 688 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 687 | `mocha --opts mocha.opts` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 685 | `mocha` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 663 | `mocha --compilers js:babel-register` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 662 | `mocha` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 661 | `mocha` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 659 | `./node_modules/.bin/mocha` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 658 | `mocha --reporter spec` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 657 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 657 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 656 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 655 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 654 | `mocha --recursive --compilers js:babel-core/register` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 654 | `mocha` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 653 | `./node_modules/.bin/mocha test/integration` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 653 | `mocha --require babel-register src/**/*.spec.js src/*.spec.js` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 652 | `mocha --require babel-register` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 662 | `mocha` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 661 | `mocha` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 659 | `./node_modules/.bin/mocha` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 657 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 657 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 656 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 655 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 654 | `mocha --recursive --compilers js:babel-core/register` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 654 | `mocha` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 653 | `./node_modules/.bin/mocha test/integration` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 653 | `mocha --require babel-register src/**/*.spec.js src/*.spec.js` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 652 | `mocha --require babel-register` | 
| [aaronshaf/react-toggle](https://github.com/aaronshaf/react-toggle) | 622 | `nyc mocha --require babel-register --require spec/setup.js spec/**/*.spec.js` | 
| [danielstjules/buddy.js](https://github.com/danielstjules/buddy.js) | 621 | `mocha -R spec spec/unit spec/integration` | 
| [maxkueng/victor](https://github.com/maxkueng/victor) | 621 | `mocha --ui bdd --reporter spec` | 
| [robwierzbowski/generator-jekyllrb](https://github.com/robwierzbowski/generator-jekyllrb) | 620 | `mocha` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 619 | `eslint . && mocha` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 616 | `mocha test` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 616 | `mocha 'test/**/*.tests.js'` | 
| [phodal/sherlock](https://github.com/phodal/sherlock) | 615 | `mocha --reporter spec` | 
| [jaredhanson/passport-google-oauth](https://github.com/jaredhanson/passport-google-oauth) | 614 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [mysamai/mysam](https://github.com/mysamai/mysam) | 613 | `npm run lint && npm run mocha` | 
| [w0rm/gulp-svgstore](https://github.com/w0rm/gulp-svgstore) | 612 | `gulp build && mocha test.js` | 