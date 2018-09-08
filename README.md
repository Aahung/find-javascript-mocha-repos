# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:48 09/08/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43471 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41268 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40060 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30241 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 26356 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24581 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23461 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20010 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19113 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17246 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16928 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16830 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15357 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14372 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14087 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13705 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13268 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12828 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12698 | `mocha 'test/**/*.spec.js'` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11598 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11364 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11332 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10594 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10282 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10217 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10178 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10097 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10030 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9831 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 9502 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9425 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9207 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9184 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9049 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8805 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8794 | `mocha tests/*.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8786 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8546 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8525 | `mocha test/test.js` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8519 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8450 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8346 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8209 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8172 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8088 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7965 | `mocha --opts mocha.opts` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7923 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7747 | `./node_modules/.bin/mocha test` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7739 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7456 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7439 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7328 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7316 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7300 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7160 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7093 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 7076 | `mocha --compilers js:babel-core/register` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7043 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6935 | `mocha $HARMONY_OPTS` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 6808 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js'` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6758 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6652 | `mocha; jshint *.js lib` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6516 | `npm run jshint && mocha test/` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6516 | `mocha --exit --require babel-core/register` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6408 | `mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6299 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6296 | `mocha test/test.js` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6255 | `npm run test:mocha:src` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6053 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6001 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5969 | `mocha tests/node.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5934 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5854 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5805 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5750 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5747 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5739 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5726 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5497 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5420 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5416 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5390 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5386 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5183 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5147 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5127 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5092 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5074 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5056 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4990 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4848 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4834 | `mocha test` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4786 | `gulp build; mocha;` | 
| [santinic/how2](https://github.com/santinic/how2) | 4766 | `mocha test` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4766 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4743 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4695 | `mocha --reporter spec -t 8000` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4676 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4660 | `./node_modules/.bin/mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4573 | `mocha ./test/runner.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4507 | `mocha --recursive` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4499 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4486 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4473 | `nyc mocha --exit` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4443 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4436 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3763 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3733 | `nyc mocha "test/**/*.test.js"` | 
| [primus/primus](https://github.com/primus/primus) | 3679 | `npm run build && mocha test/*.test.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3673 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3672 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3669 | `npm run jshint && npm run mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 3665 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3580 | `mocha tests/javascript` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3579 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3565 | `node_modules/.bin/mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3560 | `NODE_ENV=test mocha --exit` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3555 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3550 | `mocha --reporter spec --timeout 3000` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3537 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3516 | `NODE_ENV=test mocha test/**/*.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3470 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3466 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3447 | `mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3417 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3300 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3277 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3244 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3214 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3214 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3184 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3163 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3153 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3131 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3128 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3114 | `mocha test/*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3089 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3087 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3083 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3083 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3078 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3069 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3056 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3036 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3033 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3021 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3015 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2998 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2944 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2943 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2935 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2909 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2901 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2900 | `mocha -R landing test/index` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2897 | `mocha -R spec --recursive src/test` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2895 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2878 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2874 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2862 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2853 | `npm run mocha && npm run lint` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2853 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2610 | `mocha-phantomjs ./test/index.html` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2568 | `nyc mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2567 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2544 | `mocha "test/**/*-test.js"` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2525 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2485 | `mocha --reporter=spec test/*-test.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2478 | `mocha test/unit --require mochahook` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2470 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2465 | `mocha test/src/**/*.unit.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2456 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2449 | `mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2431 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2418 | `mocha --no-colors --reporter spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2406 | `nyc --reporter=html --reporter=text mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2688 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2657 | `mocha --timeout 100000` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2654 | `npm run build && cd test && mocha . --reporter dot` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2651 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2633 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2633 | `mocha --recursive --watch` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2610 | `mocha-phantomjs ./test/index.html` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2603 | `nyc mocha --timeout=10000` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2594 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2577 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2568 | `nyc mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2567 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2544 | `mocha "test/**/*-test.js"` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2525 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2485 | `mocha --reporter=spec test/*-test.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2482 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2478 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2474 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2470 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2465 | `mocha test/src/**/*.unit.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2456 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2449 | `mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2431 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2418 | `mocha --no-colors --reporter spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2406 | `nyc --reporter=html --reporter=text mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2396 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2358 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2352 | `grunt jshint && mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2349 | `mocha test && npm run lint` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2340 | `mocha -R spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2334 | `mocha test/index.js --reporter dot` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2319 | `mocha test/ --no-timeouts` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2315 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2301 | `mocha && eslint .` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2288 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2283 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2273 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2237 | `mocha test test/unit/**/*_test.js` | 
| [noble/noble](https://github.com/noble/noble) | 2233 | `mocha -R spec test/*.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2230 | `mocha --compilers js:babel-register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2229 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2214 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2183 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2149 | `cross-env BABEL_ENV=test mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2135 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2127 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2122 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2121 | `standard && mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2118 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2115 | `mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2099 | `mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2096 | `nyc npm run _mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2089 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2079 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2067 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2042 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2040 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2020 | `mocha && eslint *.js` | 
| [slate/slate](https://github.com/slate/slate) | 2006 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2000 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1998 | `mocha --compilers js:babel-core/register __tests__` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1993 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1991 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 1988 | `npm run lint && npm run mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1971 | `mocha -c test/index.js` | 
| [zeeshanu/dumper.js](https://github.com/zeeshanu/dumper.js) | 1970 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1969 | `mocha --require=test/test_helper.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1961 | `mocha --reporter spec --timeout 5000` | 
| [share/sharedb](https://github.com/share/sharedb) | 1957 | `./node_modules/.bin/mocha && npm run jshint` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1945 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1943 | `npm run lint && mocha -R dot && npm run cover` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1939 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1938 | `mocha` | 
| [then/promise](https://github.com/then/promise) | 1937 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1930 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1924 | `mocha --require ./test/common --growl test/expect.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1923 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [kach/nearley](https://github.com/kach/nearley) | 1910 | `mocha test/*.test.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1903 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1888 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1882 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1878 | `mocha tests.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1872 | `npm run mocha && npm run karma` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1851 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1850 | `mocha --reporter spec && npm run test-typescript` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1837 | `mocha --compilers js:babel-register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1837 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1829 | `mocha --reporter spec test/*.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1829 | `mocha && npm run lint` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1819 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1811 | `npm run lint && mocha --reporter spec test/*.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1811 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1810 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1806 | `mocha --timeout 5000` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1799 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1798 | `mocha --reporter spec --grep .` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1797 | `mocha test/**/*.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1778 | `npm run lint && npm run mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1760 | `mocha test -u bdd -R spec` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1753 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1752 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1750 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1738 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1737 | `mocha test/**/*_test.js --bail` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1735 | `mocha ./test/basic.js -t 5000` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1735 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1733 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1728 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1716 | `./node_modules/.bin/mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1715 | `mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1709 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1706 | `npm run lint && mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1702 | `mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1696 | `npm run lint && npm run mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1695 | `mocha test --timeout 600000` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1688 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1685 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1678 | `mocha test/* --reporter spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1677 | `mocha compiled_tests/` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1669 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1668 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1662 | `mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1661 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1660 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1656 | `mocha test` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1642 | `mocha spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1640 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1636 | `mocha && size-limit` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1634 | `mocha test/setup.js test/spec/*.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1633 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1632 | `mocha tests/test.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1610 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1609 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [zeit/ms](https://github.com/zeit/ms) | 1603 | `mocha tests.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1601 | `eslint --cache . && tsc && mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1596 | `mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1590 | `standard "./src/*.js" && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1588 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1512 | `mocha -u tdd` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1510 | `nyc mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1510 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1500 | `nyc mocha --timeout=20000 test.js` | 
| [retejs/rete](https://github.com/retejs/rete) | 1526 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1522 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1512 | `mocha -u tdd` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1510 | `nyc mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1510 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1500 | `nyc mocha --timeout=20000 test.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1499 | `mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1486 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1478 | `mocha test/**/*.spec.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1383 | `npm run lint && mocha && karma start --single-run` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1379 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1378 | `npm run build && mocha -r should` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1378 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1378 | `mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1376 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [electron/devtron](https://github.com/electron/devtron) | 1364 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1363 | `cross-env NODE_ENV=test nyc mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1359 | `mocha --opts test/opts/mocha.opts` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1352 | `mocha tests/test-*` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1347 | `istanbul cover _mocha test -- --timeout 20000` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1346 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1341 | `standard && istanbul cover _mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1337 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1335 | `mocha --recursive` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1195 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1192 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1187 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1179 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1175 | `webpack && npm run lint && npm run mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1173 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1164 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1163 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1159 | `npm run lint && mocha --require @babel/register` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1151 | `mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1149 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1148 | `mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1144 | `npm run mocha:istanbul` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1309 | `mocha ./test/test*.js --reporter spec` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1308 | `NODE_PATH=. mocha **/*.spec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1304 | `mocha-phantomjs tests/index.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1302 | `mocha spec/exec.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1290 | `npm run lint && npm run mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1287 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1286 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1285 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1283 | `mocha --timeout 60000 test/` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1282 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1277 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1268 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1266 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1265 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1264 | `mocha --recursive test/bin` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1262 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1261 | `mocha test/*.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1258 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1256 | `mocha tests` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1249 | `npm run prepublishOnly && mocha test/test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1249 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1245 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1238 | `mocha src/test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1237 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1235 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1228 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1225 | `npm run lint && npm run mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1224 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1224 | `istanbul test _mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1217 | `mocha --recursive test` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1217 | `mocha test/test.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1215 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1212 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1211 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [normalize/mz](https://github.com/normalize/mz) | 1211 | `mocha --reporter spec` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1210 | `mocha --compilers js:babel-core/register` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1210 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1210 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1210 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1208 | `node ./node_modules/mocha/bin/mocha tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1207 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1206 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1206 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1197 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1197 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1195 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1192 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1187 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1179 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1175 | `webpack && npm run lint && npm run mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1173 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1169 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1164 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1163 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1159 | `npm run lint && mocha --require @babel/register` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1154 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1151 | `mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1149 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1148 | `mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1144 | `npm run mocha:istanbul` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1128 | `mocha $(find test -name '*.test.js') --exit` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1128 | `xo && mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1128 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1127 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [poooi/poi](https://github.com/poooi/poi) | 1127 | `mocha --recursive --harmony --require ./test/babelhook` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1126 | `istanbul cover _mocha test/*.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1122 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1119 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1116 | `mocha --timeout 20000` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1109 | `mocha test/*` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1108 | `mocha` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1108 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1107 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1107 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1104 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [electron/asar](https://github.com/electron/asar) | 1101 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1094 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1092 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1084 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1082 | `mocha --compilers js:babel-register` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1082 | `webpack && mocha test/unit` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1079 | `mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1073 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1071 | `mocha --recursive --bail --reporter spec test` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1070 | `mocha --reporter spec --bail --check-leaks test/` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1069 | `mocha --timeout 30000 --recursive ./tests` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1067 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1067 | `mocha --reporter spec --bail --check-leaks test/` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1066 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1061 | `mocha test/tests.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1059 | `standard && mocha -b` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1055 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1050 | `mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1046 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1044 | `mocha test --compilers js:babel-core/register` | 
| [electron/spectron](https://github.com/electron/spectron) | 1039 | `mocha && standard` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1037 | `mocha --reporter spec --timeout 3000` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1037 | `npm-run-all test:jest test:server:mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1035 | `eslint src test && mocha --compilers babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1031 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 1030 | `mocha test` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1025 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1024 | `mocha $(find test -name '*.test.js')` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1017 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1017 | `mocha` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1017 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1014 | `mocha --recursive test/unit/` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1013 | `mocha --check-leaks -R dot` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1011 | `mocha --async-only` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1004 | `npm run convertto:es5 && npm run mocha` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1003 | `mocha --colors ./test/*.spec.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 996 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 991 | `mocha -R list` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 990 | `mocha --recursive -r tests/setup tests` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 988 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 988 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 980 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 980 | `npm run rollup-cjs && mocha test/test.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 976 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 976 | `mocha --reporter spec` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 927 | `mocha spec/*.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 923 | `mocha tests` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 923 | `mocha test` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 920 | `mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 916 | `mocha ./test/index.js` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 915 | `mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 909 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 907 | `mocha -t 600000` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 904 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 917 | `mocha test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 916 | `mocha ./test/index.js` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 915 | `mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 912 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 909 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 907 | `mocha -t 600000` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 904 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 898 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 898 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 896 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 895 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 890 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 890 | `./node_modules/.bin/mocha -R spec` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 889 | `nyc mocha specs` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 889 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 889 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 888 | `./node_modules/.bin/mocha --reporter spec` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 887 | `node_modules/.bin/mocha` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 886 | `mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 881 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 879 | `nyc --check-coverage mocha test/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 876 | `mocha --reporter list` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 875 | `istanbul cover -- _mocha --reporter spec` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 872 | `mocha --recursive ./test/*_spec.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 872 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 871 | `mocha test --compilers js:babel-register` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 870 | `mocha --timeout 200000` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 870 | `mocha -t 5000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 870 | `standard && standard ./bin/* && mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 869 | `npm run lint && npm run mocha:no-functional` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 868 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 867 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 866 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 865 | `node_modules/.bin/mocha test/spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 860 | `mocha` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 859 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 859 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 858 | `eslint test && mocha --compilers js:babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 856 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 851 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 850 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 847 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 845 | `mocha --reporter spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 845 | `mocha --check-leaks -t 20000` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 844 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 843 | `mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 841 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 838 | `npm run lint && mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 837 | `mocha test/index.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 835 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 835 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 834 | `mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 832 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 827 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 825 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 825 | `mocha && ember test` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 824 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 823 | `mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 821 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 821 | `mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 818 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 818 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 817 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 816 | `mocha --async-only` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 815 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 814 | `mocha tests/*.test.js --reporter spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 812 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 809 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 808 | `cake build && mocha ./test/mocha/*.coffee` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 807 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 804 | `mocha --harmony --full-trace --check-leaks` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 804 | `mocha --exit --use_strict src/*.test.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 802 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 799 | `npm run build && istanbul test _mocha test/test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 799 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 799 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 799 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 798 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 797 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 796 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 796 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 794 | `mocha --colors --reporter spec test.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 794 | `npm run mocha-test test/integration` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 794 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 792 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 791 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 798 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 797 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 796 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 796 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 794 | `mocha --colors --reporter spec test.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 794 | `npm run mocha-test test/integration` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 794 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 792 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 791 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 791 | `./node_modules/.bin/mocha test/**/*` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 790 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 785 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 781 | `xo && mocha -R spec` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 781 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 779 | `mocha` | 
| [developit/decko](https://github.com/developit/decko) | 778 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 775 | `mocha -r should --reporter spec test/*.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 774 | `mocha test` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 773 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 772 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 771 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 770 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 768 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 765 | `mocha --ui tdd --require ./test/__setup` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 764 | `mocha --recursive -s 15 test/` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 761 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 759 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 754 | `mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 753 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 752 | `mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 752 | `mocha` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 750 | `nyc mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 750 | `mocha test` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 748 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 746 | `npm run lint && npm run mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 742 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 742 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 741 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 739 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 739 | `babel-node node_modules/.bin/_mocha -- test` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 738 | `mocha tests/*.mocha.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 737 | `mocha --reporter spec` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 734 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 732 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 732 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 731 | `npm run-script jshint && npm run-script mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 729 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 729 | `mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 728 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 727 | `mocha --reporter spec build/test/index.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 726 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 725 | `npm run bundle && mocha` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 724 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 724 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 723 | `nyc mocha` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 719 | `./bin/selenium-standalone install && mocha` | 