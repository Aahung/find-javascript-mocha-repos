# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:08 08/30/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43360 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41217 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39921 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30196 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 26160 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24544 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23363 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19915 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19066 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17147 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16868 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16715 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15288 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14355 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14027 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13628 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13228 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12784 | `./node_modules/.bin/mocha test/` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12666 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12359 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12232 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11912 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11547 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11291 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11255 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10540 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10224 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10177 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10154 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10061 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9993 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9765 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9730 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 9434 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9404 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9155 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9148 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9026 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8767 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8755 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8746 | `mocha tests/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8512 | `mocha test/test.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8497 | `mocha test/src` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8449 | `mocha --check-leaks -R dot` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8422 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8338 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8194 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8101 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8080 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7914 | `npm run eslint && npm run mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7904 | `mocha --opts mocha.opts` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7731 | `./node_modules/.bin/mocha test` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7673 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [dthree/cash](https://github.com/dthree/cash) | 7558 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7442 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7439 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7288 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7273 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7271 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7112 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7075 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 7040 | `mocha --compilers js:babel-core/register` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6978 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6916 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6726 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6559 | `mocha; jshint *.js lib` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6500 | `npm run jshint && mocha test/` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6438 | `mocha --exit --require babel-core/register` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6332 | `mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6280 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6263 | `mocha test/test.js` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6241 | `npm run test:mocha:src` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5416 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5372 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5367 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5354 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5352 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5181 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5147 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5106 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5052 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5019 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4981 | `gulp lint && mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 4953 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4845 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5416 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5372 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5367 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5354 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5352 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5181 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5147 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5106 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5052 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5019 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4981 | `gulp lint && mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 4953 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4845 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4793 | `mocha test` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4775 | `gulp build; mocha;` | 
| [santinic/how2](https://github.com/santinic/how2) | 4761 | `mocha test` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4755 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4737 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4696 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4644 | `./node_modules/.bin/mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4621 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4574 | `mocha ./test/runner.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4482 | `mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4470 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4453 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4451 | `nyc mocha --exit` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4437 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4427 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4333 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4243 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4214 | `mocha -R spec ./test --recursive` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4193 | `mocha -R spec src` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4158 | `nyc mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4151 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4093 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4041 | `mocha --timeout=15000 tests/*.test.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4039 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4035 | `mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4021 | `npm run lint ; mocha && mocha test/individual` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4019 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 3987 | `mocha --require should --reporter spec` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3986 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3898 | `export TESTING=true; mocha --reporter list` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3878 | `mocha --check-leaks --reporter spec --bail` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3878 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3876 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3873 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3869 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [teambit/bit](https://github.com/teambit/bit) | 3864 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [erming/shout](https://github.com/erming/shout) | 3806 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3758 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3709 | `nyc mocha "test/**/*.test.js"` | 
| [primus/primus](https://github.com/primus/primus) | 3674 | `npm run build && mocha test/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3670 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3666 | `npm run jshint && npm run mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3648 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3645 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3579 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3560 | `node_modules/.bin/mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3554 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3551 | `mocha --reporter spec --timeout 3000` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3540 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3532 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3500 | `NODE_ENV=test mocha --exit` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3492 | `NODE_ENV=test mocha test/**/*.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3484 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3469 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3466 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3445 | `mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3427 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3389 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3280 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3265 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3262 | `nyc mocha && tsc` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3235 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3223 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3183 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3178 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3151 | `./node_modules/.bin/mocha test/test.*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3148 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3137 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3129 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3107 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3105 | `mocha test/*.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3073 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3070 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3069 | `mocha test/index.js && npm run demo` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3064 | `mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3063 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3054 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3030 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3030 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3028 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3009 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2902 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2898 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2889 | `mocha -R spec --recursive src/test` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2882 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2871 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2869 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2865 | `mocha -R landing test/index` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2851 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2840 | `npm run mocha && npm run lint` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2835 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2833 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2816 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2795 | `mocha -R spec spec spec/reporters` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2791 | `mocha` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2775 | `mocha test-node` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2753 | `eslint . && mocha -t 5000` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2713 | `xo && mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2707 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2705 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2675 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2670 | `mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2658 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2656 | `mocha --timeout 100000` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2643 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2635 | `npm run build && cd test && mocha . --reporter dot` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2629 | `mocha --recursive --watch` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2621 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2611 | `mocha-phantomjs ./test/index.html` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2598 | `nyc mocha --timeout=10000` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2573 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2566 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2557 | `nyc mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2557 | `mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2313 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2292 | `mocha && eslint .` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2289 | `mocha test/ --no-timeouts` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2285 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2262 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2229 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [gajus/swing](https://github.com/gajus/swing) | 2227 | `mocha --compilers js:babel-register` | 
| [noble/noble](https://github.com/noble/noble) | 2219 | `mocha -R spec test/*.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2401 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2391 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2353 | `grunt jshint && mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2352 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2339 | `mocha test && npm run lint` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2333 | `mocha -R spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2321 | `mocha test/index.js --reporter dot` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2313 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2292 | `mocha && eslint .` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2289 | `mocha test/ --no-timeouts` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2285 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2124 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2116 | `standard && mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2113 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2112 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2112 | `mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2074 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2070 | `nyc npm run _mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2068 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2063 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 2170 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2147 | `cross-env BABEL_ENV=test mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2124 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2116 | `standard && mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2113 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2112 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2112 | `mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2108 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2074 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2070 | `nyc npm run _mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2068 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2063 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2034 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2031 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [slate/slate](https://github.com/slate/slate) | 2005 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2000 | `mocha && eslint *.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1990 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1989 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1982 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 1978 | `npm run lint && npm run mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1977 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1970 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1968 | `mocha --require=test/test_helper.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1949 | `./node_modules/.bin/mocha && npm run jshint` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1952 | `mocha --reporter spec --timeout 5000` | 
| [share/sharedb](https://github.com/share/sharedb) | 1949 | `./node_modules/.bin/mocha && npm run jshint` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1939 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1936 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1931 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [then/promise](https://github.com/then/promise) | 1930 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1929 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1928 | `npm run lint && mocha -R dot && npm run cover` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1918 | `mocha --require ./test/common --growl test/expect.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1905 | `mocha test/*.test.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1897 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1890 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1824 | `mocha --reporter spec test/*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1820 | `mocha --compilers js:babel-register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1814 | `mocha && npm run lint` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1812 | `mocha test` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1807 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1804 | `npm run lint && mocha --reporter spec test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1792 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1791 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1773 | `npm run lint && npm run mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1753 | `mocha test -u bdd -R spec` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1750 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1808 | `mocha tests --require babel-core/register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1807 | `mocha test` | 
| [zeeshanu/dumper.js](https://github.com/zeeshanu/dumper.js) | 1806 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1804 | `npm run lint && mocha --reporter spec test/*.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1803 | `mocha --timeout 5000` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1792 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1791 | `mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1781 | `mocha test/**/*.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1773 | `npm run lint && npm run mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1754 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1753 | `mocha test -u bdd -R spec` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1750 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1731 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1730 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1728 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1720 | `mocha ./test/basic.js -t 5000` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1716 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1715 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1709 | `./node_modules/.bin/mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1701 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1700 | `npm run lint && mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1698 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1689 | `mocha test --timeout 600000` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1686 | `mocha test/*.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1686 | `npm run lint && npm run mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1680 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1675 | `mocha test/* --reporter spec` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1671 | `xo && mocha` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1630 | `mocha tests/test.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1620 | `mocha test/setup.js test/spec/*.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1609 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1607 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1595 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1593 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1592 | `eslint --cache . && tsc && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1589 | `mocha tests.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1582 | `standard "./src/*.js" && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1578 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1595 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1593 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1592 | `eslint --cache . && tsc && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1589 | `mocha tests.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1582 | `standard "./src/*.js" && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1578 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1573 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1565 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1553 | `mocha --reporter spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1552 | `./node_modules/.bin/mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1551 | `mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1550 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1546 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1521 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [retejs/rete](https://github.com/retejs/rete) | 1512 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1508 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1507 | `nyc mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1507 | `mocha -u tdd` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1498 | `mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1485 | `mocha -R spec` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1482 | `nyc mocha --timeout=20000 test.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1459 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [samccone/drool](https://github.com/samccone/drool) | 1457 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1443 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1434 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1431 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1419 | `mocha -R spec test/*.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1417 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1415 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1434 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1431 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1419 | `mocha -R spec test/*.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1417 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1415 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1407 | `mocha --check-leaks --require @babel/register` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1404 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1398 | `mocha test/unit` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1397 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1394 | `TEST=all mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1390 | `istanbul cover _mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1390 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1387 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1382 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1373 | `npm run build && mocha -r should` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1367 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1365 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1365 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1365 | `npm run lint && mocha && karma start --single-run` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1363 | `cross-env NODE_ENV=test nyc mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1353 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1352 | `mocha --opts test/opts/mocha.opts` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1343 | `mocha tests/test-*` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1341 | `istanbul cover _mocha test -- --timeout 20000` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1335 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1328 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1328 | `mocha --recursive` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1335 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1328 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1328 | `mocha --recursive` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1327 | `NODE_ENV=test mocha tests/*.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1327 | `standard && istanbul cover _mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1322 | `./node_modules/.bin/mocha test` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1318 | `mocha --reporter dot` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1314 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1309 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1307 | `mocha -R spec ./test/unit/**` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1304 | `mocha-phantomjs tests/index.html` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1303 | `NODE_PATH=. mocha **/*.spec.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1301 | `mocha spec/exec.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1298 | `mocha ./test/test*.js --reporter spec` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1287 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1285 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1284 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1279 | `npm run lint && npm run mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1278 | `mocha --timeout 60000 test/` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1276 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1275 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1273 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1263 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1263 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1262 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1261 | `mocha --check-leaks --reporter spec --bail test/` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1259 | `mocha` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1258 | `mocha test/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1252 | `mocha tests` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1252 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1251 | `mocha --recursive test/bin` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1249 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1242 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1237 | `npm run prepublishOnly && mocha test/test.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1234 | `mocha src/test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1230 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1230 | `mocha` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1229 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1225 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1221 | `istanbul test _mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1217 | `mocha test/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1216 | `npm run lint && npm run mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1213 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1208 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1207 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [normalize/mz](https://github.com/normalize/mz) | 1207 | `mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1206 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1204 | `node ./node_modules/mocha/bin/mocha tests` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1202 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1200 | `mocha --recursive test` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1199 | `mocha --compilers js:babel-core/register` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1199 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1199 | `mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1195 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1193 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1193 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [variety/variety](https://github.com/variety/variety) | 1192 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1171 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1146 | `npm run lint && mocha --require @babel/register` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1143 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1141 | `mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1140 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1127 | `npm run mocha:istanbul` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1125 | `mocha $(find test -name '*.test.js')` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1124 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [router5/router5](https://github.com/router5/router5) | 1123 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1120 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1119 | `istanbul cover _mocha test/*.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1119 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1107 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1107 | `mocha --timeout 20000` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1107 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1127 | `npm run mocha:istanbul` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1125 | `mocha $(find test -name '*.test.js')` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1124 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1124 | `xo && mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1123 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1120 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1119 | `istanbul cover _mocha test/*.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1119 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1107 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1107 | `mocha --timeout 20000` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1107 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1106 | `mocha test/*` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1105 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1102 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1100 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1097 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [electron/asar](https://github.com/electron/asar) | 1096 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1092 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1090 | `mocha --check-leaks -t 20000` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1082 | `nodeunit test; mocha test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1082 | `mocha --compilers js:babel-register` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1081 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1077 | `webpack && mocha test/unit` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1072 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1070 | `mocha --recursive --bail --reporter spec test` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1068 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1062 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1046 | `mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1045 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1044 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1038 | `mocha --reporter spec --timeout 3000` | 
| [electron/spectron](https://github.com/electron/spectron) | 1033 | `mocha && standard` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1030 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 1027 | `mocha test` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1024 | `npm-run-all test:jest test:server:mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1024 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1023 | `mocha test --compilers js:babel-core/register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1021 | `mocha $(find test -name '*.test.js')` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1014 | `mocha --check-leaks -R dot` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1012 | `mocha --recursive test/unit/` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1012 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1010 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1007 | `mocha --async-only` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 984 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 983 | `mocha --recursive -r tests/setup tests` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 978 | `npm run rollup-cjs && mocha test/test.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 976 | `mocha --reporter spec` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 975 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 973 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 962 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 951 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 949 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 948 | `mocha --compilers js:babel-register test/*.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 946 | `mocha "client.test" --compilers js:babel-register` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 946 | `mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 945 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 945 | `mocha --timeout 5000` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 943 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 941 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 937 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 935 | `npm run lint && mocha -R spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 926 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 919 | `mocha tests` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 918 | `mocha spec/*.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 917 | `mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 914 | `mocha ./test/index.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 913 | `mocha test` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 912 | `mocha test` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 905 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 904 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 902 | `mocha -t 600000` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 897 | `mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 892 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 890 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 890 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 888 | `nyc mocha specs` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 886 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 885 | `node_modules/.bin/mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 883 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 882 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 881 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 880 | `./node_modules/.bin/mocha --reporter spec` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 877 | `mocha --reporter list` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 874 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 870 | `istanbul cover -- _mocha --reporter spec` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 869 | `mocha --timeout 200000` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 868 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 867 | `nyc --check-coverage mocha test/*.test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 867 | `mocha -t 5000` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 866 | `npm run lint && npm run mocha:no-functional` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 877 | `mocha --reporter list` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 874 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 870 | `istanbul cover -- _mocha --reporter spec` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 869 | `mocha --timeout 200000` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 868 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 867 | `nyc --check-coverage mocha test/*.test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 867 | `mocha -t 5000` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 866 | `npm run lint && npm run mocha:no-functional` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 865 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 863 | `node_modules/.bin/mocha test/spec` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 863 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 862 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 862 | `mocha test --compilers js:babel-register` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 861 | `standard && standard ./bin/* && mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 861 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 859 | `mocha --recursive ./test/*_spec.js` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 857 | `eslint test && mocha --compilers js:babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 855 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 849 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 848 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 847 | `istanbul cover _mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 846 | `mocha --reporter list` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 844 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 844 | `mocha --check-leaks -t 20000` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 843 | `mocha --reporter spec` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 843 | `mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 842 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 840 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 836 | `npm run lint && mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 825 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 823 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 823 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 823 | `mocha test` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 823 | `mocha && ember test` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 821 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 821 | `mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 818 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 818 | `mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 816 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 816 | `mocha --async-only` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 812 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 812 | `mocha tests/*.test.js --reporter spec` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 816 | `mocha --async-only` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 815 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 812 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 812 | `mocha tests/*.test.js --reporter spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 808 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 807 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 807 | `cake build && mocha ./test/mocha/*.coffee` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 804 | `mocha --harmony --full-trace --check-leaks` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 804 | `mocha` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 801 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 800 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 800 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 791 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 791 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 791 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 790 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 789 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [edsu/anon](https://github.com/edsu/anon) | 789 | `mocha --colors --reporter spec test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 783 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 782 | `mocha --exit --use_strict src/*.test.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 780 | `xo && mocha -R spec` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 778 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 778 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 777 | `mocha` | 
| [developit/decko](https://github.com/developit/decko) | 774 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 778 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 778 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 777 | `mocha` | 
| [developit/decko](https://github.com/developit/decko) | 774 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 771 | `mocha test` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 771 | `./node_modules/.bin/mocha test/**/*` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 770 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 770 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 770 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 769 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 765 | `mocha --ui tdd --require ./test/__setup` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 765 | `mocha -r should --reporter spec test/*.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 764 | `mocha --recursive -s 15 test/` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 764 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 764 | `mocha --recursive -s 15 test/` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 764 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 758 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 758 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 755 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 753 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 752 | `mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 751 | `mocha` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 747 | `nyc mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 746 | `mocha test` | 