# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:57 06/18/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 42184 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40761 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38813 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29689 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24150 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23520 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 23274 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22496 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19129 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18519 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16380 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16015 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14526 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14173 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13567 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12809 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 12673 | `mocha --reporter spec` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12531 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12404 | `./node_modules/.bin/mocha test/` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12170 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12128 | `mocha --reporter spec test/*-test.js` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 12036 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11208 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11125 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10676 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10562 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10061 | `mocha test/index.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9761 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9760 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tj/co](https://github.com/tj/co) | 9758 | `mocha --harmony` | 
| [svg/svgo](https://github.com/svg/svgo) | 9729 | `set NODE_ENV=test && mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9612 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 8863 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8835 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8582 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8403 | `mocha test/test.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8390 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8311 | `mocha --check-leaks -R dot` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8253 | `mocha test/src` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8236 | `grunt clean:test && mocha --exit` | 
| [amark/gun](https://github.com/amark/gun) | 8233 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8111 | `mocha tests/*.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8037 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7962 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7846 | `nyc --reporter=html --reporter=text mocha && nsp check && cost-of-modules` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7761 | `npm run eslint && npm run mocha` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7663 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7652 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7846 | `nyc --reporter=html --reporter=text mocha && nsp check && cost-of-modules` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7761 | `npm run eslint && npm run mocha` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7663 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7652 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7531 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7527 | `./node_modules/.bin/mocha test` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7442 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7352 | `npm run build && istanbul cover _mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7138 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7122 | `mocha --opts mocha.opts` | 
| [aui/art-template](https://github.com/aui/art-template) | 6937 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6929 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6919 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6862 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6800 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6760 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6691 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6331 | `npm run lint -s && npm run mocha -s` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 6245 | `npm run build-cli && mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6216 | `npm run jshint && mocha test/` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6149 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6124 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6030 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5959 | `mocha --exit --require babel-core/register` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5934 | `mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5887 | `mocha test/test.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4957 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4823 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4717 | `mocha test` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4713 | `mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4706 | `mocha -R spec 'tests/app'` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4680 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4673 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4672 | `gulp build; mocha;` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4632 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4620 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4557 | `mocha ./test/runner.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4546 | `mocha test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4509 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4419 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5193 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5161 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5153 | `mocha --color` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5021 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5012 | `standard && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4957 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4901 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4823 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4717 | `mocha test` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4713 | `mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4706 | `mocha -R spec 'tests/app'` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4680 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4673 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4672 | `gulp build; mocha;` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4632 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4620 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4557 | `mocha ./test/runner.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4546 | `mocha test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4509 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4419 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4376 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4357 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4322 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4275 | `NODE_ENV=test mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4245 | `mocha --recursive && make test` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4223 | `nyc mocha --exit` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3704 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3650 | `mocha --check-leaks --reporter spec --bail` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3638 | `standard && mocha --timeout 60000 test/test.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3629 | `node_modules/.bin/mocha test/tests.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3628 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [primus/primus](https://github.com/primus/primus) | 3594 | `npm run build && mocha test/*.test.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3564 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3557 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3544 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3504 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3490 | `node_modules/.bin/mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3485 | `nyc mocha "test/**/*.test.js"` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3470 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3463 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3457 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3451 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3434 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3426 | `mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3308 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3244 | `NODE_ENV=test mocha test/**/*.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3143 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3123 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3117 | `mocha` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3090 | `mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3055 | `NODE_ENV=test mocha --exit` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3018 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3009 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2991 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2905 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2889 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2852 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2848 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2844 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2842 | `mocha -R spec --recursive src/test` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2801 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2786 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2775 | `mocha --require should --reporter spec` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2766 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2670 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2963 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2959 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2918 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2915 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2905 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2896 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2889 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2852 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2848 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2844 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2842 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2815 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2801 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2797 | `istanbul cover _mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2786 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2627 | `mocha --timeout 100000` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2612 | `node_modules/.bin/mocha --reporter spec` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2602 | `mocha-phantomjs ./test/index.html` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2590 | `mocha -R landing test/index` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2569 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2549 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2529 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2506 | `npm run build && cd test && mocha . --reporter dot` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2463 | `mocha --reporter=spec test/*-test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2462 | `nyc mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2439 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2640 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2627 | `mocha --timeout 100000` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2612 | `node_modules/.bin/mocha --reporter spec` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2602 | `mocha-phantomjs ./test/index.html` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2591 | `mocha --recursive --watch` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2590 | `mocha -R landing test/index` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2571 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2569 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2549 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2549 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2529 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2506 | `npm run build && cd test && mocha . --reporter dot` | 
| [json5/json5](https://github.com/json5/json5) | 2483 | `nyc --reporter=html --reporter=text mocha` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2363 | `mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2361 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2359 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2351 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2341 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2338 | `grunt jshint && mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2320 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2299 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2289 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2261 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2258 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2254 | `eslint . && mocha -t 5000` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2254 | `nyc --reporter=html --reporter=text mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2232 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [gajus/swing](https://github.com/gajus/swing) | 2198 | `mocha --compilers js:babel-register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2183 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2174 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2132 | `mocha -R spec test/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2114 | `cross-env BABEL_ENV=test mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2105 | `mocha test/index.js --reporter dot` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2090 | `mocha --compilers js:babel-register` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2090 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2089 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 2141 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [noble/noble](https://github.com/noble/noble) | 2132 | `mocha -R spec test/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2114 | `cross-env BABEL_ENV=test mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2105 | `mocha test/index.js --reporter dot` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2090 | `mocha --compilers js:babel-register` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2089 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2052 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [teambit/bit](https://github.com/teambit/bit) | 2050 | `mocha --require babel-core/register './specs/**/*.spec.js'` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2035 | `mocha test/ --no-timeouts` | 
| [Qix-/color](https://github.com/Qix-/color) | 2031 | `mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2028 | `standard && mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2052 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [teambit/bit](https://github.com/teambit/bit) | 2050 | `mocha --require babel-core/register './specs/**/*.spec.js'` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2035 | `mocha test/ --no-timeouts` | 
| [Qix-/color](https://github.com/Qix-/color) | 2031 | `mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2028 | `standard && mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2009 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1995 | `mocha test/runner.js --reporter spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1993 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1977 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1878 | `mocha && eslint *.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1871 | `./node_modules/.bin/mocha && npm run jshint` | 
| [then/promise](https://github.com/then/promise) | 1870 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1868 | `mocha tests.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1862 | `npm run lint && mocha -R dot && npm run cover` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1848 | `mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 1844 | `mocha test/*.test.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1843 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1830 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1822 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1816 | `mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1812 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1803 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1801 | `mocha --timeout 5000` | 
| [pahen/madge](https://github.com/pahen/madge) | 1801 | `npm run lint && npm run mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1796 | `mocha --reporter spec && npm run test-typescript` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1788 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1782 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1774 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1757 | `mocha test` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1734 | `mocha && npm run lint` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1722 | `mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1720 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1718 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1718 | `npm run lint && npm run mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1717 | `mocha --reporter spec --grep .` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1713 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1711 | `mocha tests --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1705 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1693 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1690 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1659 | `mocha test --timeout 600000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1705 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1693 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1690 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1680 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1680 | `mocha test/**/*.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1675 | `mocha test -u bdd -R spec` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1659 | `mocha test --timeout 600000` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1646 | `mocha ./test/basic.js -t 5000` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1643 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1642 | `mocha test/*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1641 | `mocha --compilers js:babel-register` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1641 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1638 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1638 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1632 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1629 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1627 | `mocha --expose-gc --slow 300` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1624 | `mocha` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1621 | `mocha tests/test.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1618 | `npm run lint && npm run mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1617 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1617 | `mocha && size-limit` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1612 | `mocha test/* --reporter spec` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1590 | `mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1560 | `mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1556 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1545 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1528 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1524 | `mocha compiled_tests/` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1524 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1521 | `mocha --reporter spec` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1483 | `node_modules/.bin/mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1482 | `mocha -u tdd` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1480 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1480 | `mocha test.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1477 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1477 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1471 | `mocha` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1468 | `nyc mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1458 | `mocha --check-leaks --reporter spec --bail` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1449 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1449 | `nyc npm run mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1449 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1440 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1437 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1449 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1440 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1437 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1434 | `mocha --recursive` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1401 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1395 | `mocha test` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1371 | `./node_modules/mocha/bin/mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1363 | `mocha -R spec test/*.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1354 | `cross-env NODE_ENV=test nyc mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1335 | `nyc mocha --timeout=20000 test.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1334 | `npm run build && mocha -r should` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1330 | `mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1328 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1328 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1322 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1313 | `mocha --check-leaks --require @babel/register` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1243 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1243 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1242 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1241 | `mocha --reporter dot` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1241 | `standard && istanbul cover _mocha` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1240 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1237 | `mocha test/*.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1234 | `mocha tests/test-*` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1223 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1216 | `mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1215 | `mocha test/test.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1212 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1208 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1197 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1194 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1193 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1305 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1301 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1299 | `istanbul cover _mocha test -- --timeout 20000` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1296 | `mocha-phantomjs tests/index.html` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1294 | `./node_modules/.bin/mocha test` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1292 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1289 | `mocha test/unit` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1288 | `mocha --recursive` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1288 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1284 | `mocha` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1284 | `mocha spec/exec.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1282 | `mocha --opts test/opts/mocha.opts` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1267 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1265 | `eslint src && mocha && karma start --single-run` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1197 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1193 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1192 | `TEST=all mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1191 | `mocha` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1189 | `node ./node_modules/mocha/bin/mocha tests` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1189 | `mocha test` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1187 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1186 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1174 | `mocha --check-leaks --reporter spec --bail test/` | 
| [normalize/mz](https://github.com/normalize/mz) | 1174 | `mocha --reporter spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1173 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1166 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1166 | `npm run lint && npm run mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1165 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1162 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1156 | `mocha -R spec ./test/unit/**` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1146 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1146 | `NODE_ENV=test mocha tests/*.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1145 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1142 | `mocha ./test/test*.js --reporter spec` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1142 | `mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1136 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1132 | `mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1132 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1130 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1128 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1127 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1126 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1123 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1119 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1118 | `mocha --recursive test/bin` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1106 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1115 | `npm run lint && npm run mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1106 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1103 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1102 | `mocha $(find test -name '*.test.js')` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1100 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1099 | `xo && mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1099 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1098 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1096 | `mocha --compilers js:babel-core/register` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1094 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1090 | `istanbul cover _mocha test/*.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1086 | `mocha --check-leaks -t 20000` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1085 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1085 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1084 | `mocha test/*` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1081 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1081 | `NODE_PATH=. mocha **/*.spec.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1077 | `nodeunit test; mocha test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1076 | `mocha --compilers js:babel-register` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1072 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1072 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1070 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1069 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1066 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1058 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [poooi/poi](https://github.com/poooi/poi) | 1057 | `mocha --recursive --harmony --require ./test/babelhook` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1056 | `istanbul test _mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1052 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1052 | `mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1051 | `webpack && npm run lint && npm run mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1040 | `mocha --reporter spec --timeout 3000` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1039 | `mocha test/tests.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1034 | `mocha --recursive --bail --reporter spec test` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1029 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1027 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1026 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1025 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1020 | `webpack && mocha test/unit` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1016 | `npm run lint && mocha --require @babel/register` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1014 | `mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1014 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1013 | `mocha --check-leaks -R dot` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1008 | `nyc mocha` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 922 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 918 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 917 | `mocha --compilers js:babel-register test/*.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 912 | `mocha spec/*.spec.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 912 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 909 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 908 | `npm run lint && mocha -R spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 906 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 905 | `mocha -R spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 894 | `mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 894 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 890 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 884 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 879 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 875 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 872 | `node_modules/.bin/mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 868 | `mocha -t 600000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 868 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 866 | `mocha spec/*.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 922 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 918 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 917 | `mocha --compilers js:babel-register test/*.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 914 | `mocha ./test/index.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 912 | `mocha --reporter spec --bail --check-leaks test/` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 912 | `mocha spec/*.spec.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 912 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 909 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 908 | `npm run lint && mocha -R spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 906 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 905 | `mocha -R spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 894 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 890 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 884 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 884 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 879 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 877 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 894 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 890 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 884 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 884 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 879 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 877 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 875 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 872 | `node_modules/.bin/mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 868 | `mocha -t 600000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 868 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 866 | `mocha spec/*.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 865 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 865 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 864 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 864 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 863 | `mocha --timeout 200000` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 863 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 862 | `npm run lint && npm run mocha:no-functional` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 861 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 854 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 853 | `eslint test && mocha --compilers js:babel/register` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 850 | `mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 849 | `mocha test --compilers js:babel-core/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 849 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 841 | `mocha -t 5000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 840 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 840 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 840 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 838 | `nyc mocha specs` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 837 | `mocha test --compilers js:babel-register` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 835 | `mocha --check-leaks -t 20000` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 834 | `mocha --reporter spec` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 834 | `standard && standard ./bin/* && mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 832 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 831 | `istanbul cover _mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 831 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 829 | `./node_modules/.bin/mocha -R spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 829 | `./node_modules/.bin/mocha -R spec` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 829 | `istanbul cover -- _mocha --reporter spec` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 828 | `mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 827 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 822 | `mocha && ember test` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 821 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 819 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 818 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 817 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 816 | `npm run lint && mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 816 | `mocha --timeout 30000 --recursive ./tests` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 810 | `nyc mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 809 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 806 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 805 | `mocha --reporter list` | 
| [webpack-contrib/webpack-serve](https://github.com/webpack-contrib/webpack-serve) | 805 | `nyc npm run mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 805 | `mocha test` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 803 | `mocha --require babel-register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 802 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 801 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 800 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 798 | `cake build && mocha ./test/mocha/*.coffee` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 797 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 796 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 794 | `mocha -u tdd` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 775 | `mocha --recursive ./test/*_spec.js` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 773 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 772 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 771 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 770 | `xo && mocha -R spec` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 769 | `npm run mocha-test test/integration` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 769 | `mocha --harmony --full-trace --check-leaks` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 769 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 768 | `mocha test` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 765 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 761 | `mocha --ui tdd --require ./test/__setup` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 759 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 758 | `npm run build && istanbul test _mocha test/test.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 757 | `mocha` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 757 | `mocha` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 756 | `mocha -R spec src/**/*_test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 756 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 773 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 773 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 772 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 772 | `mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 771 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 770 | `xo && mocha -R spec` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 769 | `npm run mocha-test test/integration` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 769 | `mocha --harmony --full-trace --check-leaks` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 769 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 768 | `mocha test` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 765 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 764 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 761 | `mocha --ui tdd --require ./test/__setup` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 759 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 758 | `npm run build && istanbul test _mocha test/test.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 757 | `mocha` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 757 | `mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 737 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 737 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 737 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 736 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 736 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 735 | `mocha test` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 734 | `mocha --no-timeouts` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 734 | `mocha test` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 734 | `mocha --reporter spec` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 733 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 730 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 729 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 729 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 727 | `mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 727 | `mocha` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 726 | `mocha test.js` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 724 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 724 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 723 | `mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 722 | `npm run lint && npm run mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 719 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 717 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 716 | `npm run bundle && mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 715 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 712 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 711 | `mocha -r should --reporter spec test/*.js` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 711 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 711 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 712 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 711 | `mocha -r should --reporter spec test/*.js` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 711 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 711 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 709 | `mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 708 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 708 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 707 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 704 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [scality/S3](https://github.com/scality/S3) | 704 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 701 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 700 | `mocha ./test/index.js` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 709 | `mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 708 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 708 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 707 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 704 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [scality/S3](https://github.com/scality/S3) | 704 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 701 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 700 | `mocha ./test/index.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 697 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 697 | `babel-node node_modules/.bin/_mocha -- test` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 695 | `mocha --reporter spec build/test/index.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 694 | `./bin/selenium-standalone install && mocha` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 693 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 692 | `nyc mocha` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 692 | `npm run-script jshint && npm run-script mocha` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 688 | `mocha --reporter spec` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 682 | `mocha ./test/test.js --timeout 1000000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 680 | `mocha` | 