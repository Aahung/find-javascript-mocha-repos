# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:58 10/05/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43763 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41421 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40432 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30399 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 27022 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24693 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 24657 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23756 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20262 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19295 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17497 | `npm run test:lint && npm run test:mocha` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17087 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17046 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15646 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14405 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14244 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14011 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13408 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13019 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12743 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12468 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12262 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12205 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11720 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11564 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11536 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10765 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10444 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10357 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10341 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10156 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10118 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10083 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 9675 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9469 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9437 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9293 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9248 | `mocha -b -r esm` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 9138 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9078 | `grunt mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8953 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 8923 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8893 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8616 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8557 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8473 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8358 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8282 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8245 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8119 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7945 | `npm run eslint && npm run mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7887 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7772 | `./node_modules/.bin/mocha test` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7475 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7442 | `mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7434 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7419 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7411 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7338 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7284 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [almende/vis](https://github.com/almende/vis) | 7170 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7133 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6968 | `mocha $HARMONY_OPTS` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 6940 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6833 | `mocha; jshint *.js lib` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6822 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6696 | `mocha --exit --require @babel/register` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6650 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6590 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6371 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6346 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5496 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5490 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5481 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5415 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5271 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5225 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5189 | `mocha src/**/*Tests.js --harmony` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5171 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5147 | `mocha --color` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5146 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5028 | `gulp lint && mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4922 | `mocha test` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4869 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5496 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5490 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5481 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5415 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5271 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5225 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5189 | `mocha src/**/*Tests.js --harmony` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5171 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5147 | `mocha --color` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5146 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5028 | `gulp lint && mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4922 | `mocha test` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4869 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4814 | `gulp build; mocha;` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4796 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4792 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4767 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4757 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4699 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4683 | `./node_modules/.bin/mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4642 | `mocha --recursive` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4570 | `mocha ./test/runner.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4567 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4543 | `nyc mocha --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4543 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4452 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4445 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4413 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4388 | `nyc mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4337 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4266 | `mocha -R spec src` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4206 | `mocha -R spec ./test --recursive` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4188 | `node_modules/.bin/mocha test/tests.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4185 | `nyc mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4181 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4142 | `mocha --timeout=15000 tests/*.test.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 4091 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4088 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4088 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4083 | `npm run lint ; mocha && mocha test/individual` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4055 | `mocha --require test/babel-hook test/*.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4030 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [tj/ejs](https://github.com/tj/ejs) | 4018 | `mocha --require should --reporter spec` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3981 | `mocha --check-leaks --reporter spec --bail` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3951 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3904 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3870 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3808 | `nyc mocha "test/**/*.test.js"` | 
| [erming/shout](https://github.com/erming/shout) | 3798 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3772 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3723 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3722 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3705 | `NODE_ENV=test mocha --exit` | 
| [primus/primus](https://github.com/primus/primus) | 3686 | `npm run build && mocha test/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3675 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3664 | `npm run jshint && npm run mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3636 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3598 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3590 | `NODE_ENV=test mocha test/**/*.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3577 | `mocha tests/javascript` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3575 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3567 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3553 | `mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3553 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3549 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3521 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3470 | `node_modules/.bin/mocha test/lib/` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3470 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3462 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3444 | `mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3371 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3359 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3323 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3301 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3272 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3252 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3191 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3170 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3166 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3148 | `./node_modules/.bin/mocha test/test.*.js` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3143 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3140 | `mocha test/*.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3138 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3138 | `mocha` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3131 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3129 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3120 | `mocha test/index.js && npm run demo` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3092 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3086 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3083 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3064 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3057 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3050 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3034 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3030 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2984 | `eslint . && mocha -t 5000` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2984 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2983 | `mocha -R landing test/index` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2979 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2963 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2915 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2907 | `mocha -R spec --recursive src/test` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2901 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2893 | `mocha` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2889 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2887 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2877 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2773 | `mocha --require should --reporter spec` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2764 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2761 | `mocha test.js` | 
| [css/csso](https://github.com/css/csso) | 2740 | `mocha --reporter dot` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2729 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2723 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2705 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2688 | `npm run build && cd test && mocha . --reporter dot` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2667 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2653 | `mocha --timeout 100000` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2653 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2640 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2622 | `nyc mocha --timeout=10000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2612 | `mocha-phantomjs ./test/index.html` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2611 | `mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2593 | `nyc mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2729 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2723 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2705 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2688 | `npm run build && cd test && mocha . --reporter dot` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2667 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2660 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2653 | `mocha --timeout 100000` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2653 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2640 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2622 | `nyc mocha --timeout=10000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2612 | `mocha-phantomjs ./test/index.html` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2611 | `mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2593 | `nyc mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2573 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2567 | `mocha "test/**/*-test.js"` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2525 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2511 | `mocha test/unit --require mochahook` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2511 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2508 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2502 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2483 | `mocha test` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2482 | `mocha --reporter=spec test/*-test.js` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2481 | `mocha test/src/**/*.unit.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2468 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2447 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2418 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2417 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2399 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [noble/noble](https://github.com/noble/noble) | 2279 | `mocha -R spec test/*.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2240 | `mocha --compilers js:babel-register` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2231 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2228 | `mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2227 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2222 | `mocha test test/unit/**/*_test.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2168 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2151 | `cross-env BABEL_ENV=test mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2240 | `mocha --compilers js:babel-register` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2231 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2228 | `mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2227 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2222 | `mocha test test/unit/**/*_test.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2168 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2161 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2151 | `cross-env BABEL_ENV=test mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2139 | `standard && mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2139 | `nyc npm run _mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2129 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2126 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2116 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2113 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2095 | `mocha test/runner.js --reporter spec` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2089 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2062 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2062 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2059 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2054 | `mocha && eslint *.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2041 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [pahen/madge](https://github.com/pahen/madge) | 2038 | `npm run lint && npm run mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2021 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2008 | `mocha --compilers js:babel-core/register __tests__` | 
| [slate/slate](https://github.com/slate/slate) | 1999 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1994 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1993 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1979 | `./node_modules/.bin/mocha && npm run jshint` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1972 | `mocha --require=test/test_helper.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1969 | `mocha --reporter spec --timeout 5000` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1969 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1945 | `npm run lint && mocha -R dot && npm run cover` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1942 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [kach/nearley](https://github.com/kach/nearley) | 1941 | `mocha test/*.test.js` | 
| [then/promise](https://github.com/then/promise) | 1940 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1937 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1933 | `mocha` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1930 | `mocha --require ./test/common --growl test/expect.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1924 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1915 | `npm run mocha && npm run karma` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1911 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1890 | `mocha --compilers js:babel-register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1887 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1884 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1876 | `mocha tests.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1869 | `mocha --reporter spec && npm run test-typescript` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1843 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1838 | `mocha tests --require @babel/register` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1829 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1823 | `mocha test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1820 | `mocha --reporter spec --grep .` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1819 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1815 | `mocha test/**/*.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1808 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1800 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1800 | `mocha test -u bdd -R spec` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1752 | `mocha ./test/basic.js -t 5000` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1808 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1800 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1800 | `mocha test -u bdd -R spec` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1786 | `npm run lint && npm run mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1759 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1752 | `mocha ./test/basic.js -t 5000` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1734 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1729 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1728 | `mocha test/**/*_test.js --bail` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1703 | `mocha test --timeout 600000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1697 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1693 | `mocha test/* --reporter spec` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1690 | `mocha test/*.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1680 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1673 | `mocha` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1672 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1669 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1669 | `mocha test/setup.js test/spec/*.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1662 | `xo && mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1653 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1644 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1640 | `mocha && size-limit` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1638 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1638 | `eslint --cache . && tsc && mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1662 | `xo && mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1653 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1644 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1640 | `mocha && size-limit` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1638 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1638 | `eslint --cache . && tsc && mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1633 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1632 | `mocha tests/test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1623 | `mocha tests.js` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1621 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1616 | `mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1608 | `standard "./src/*.js" && mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1608 | `mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1607 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1589 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1585 | `./node_modules/mocha/bin/mocha -R spec` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1580 | `mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1577 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1576 | `mocha --check-leaks --reporter spec --bail` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1569 | `mocha --reporter spec` | 
| [retejs/rete](https://github.com/retejs/rete) | 1569 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1564 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1556 | `mocha test.js` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1555 | `./node_modules/.bin/mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1550 | `nyc mocha --timeout=20000 test.js` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1543 | `npm run test:lint && npm run test:mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1542 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1539 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1476 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1459 | `mocha --timeout 10000 ./tests/lib.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1454 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1447 | `mocha test.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1445 | `mocha --check-leaks --require @babel/register` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1441 | `mocha test/unit` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1439 | `NODE_ENV=test mocha tests/*.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1438 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1433 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1427 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1424 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1417 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1485 | `mocha test/**/*.spec.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1482 | `mocha -R spec` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1476 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1459 | `mocha --timeout 10000 ./tests/lib.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1454 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1447 | `mocha test.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1445 | `mocha --check-leaks --require @babel/register` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1441 | `mocha test/unit` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1439 | `NODE_ENV=test mocha tests/*.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1439 | `NODE_ENV=test mocha tests/*.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1438 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1433 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1428 | `mocha -R spec test/*.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1427 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1424 | `mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1422 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1417 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1412 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1410 | `npm run lint && mocha && karma start --single-run` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1407 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1401 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1399 | `mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1396 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1392 | `istanbul cover _mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1383 | `npm run build && mocha -r should` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1383 | `mocha tests/test-*` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1382 | `./node_modules/mocha/bin/mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1377 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1377 | `mocha ./test/test*.js --reporter spec` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1372 | `mocha --opts test/opts/mocha.opts` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1365 | `standard && istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1364 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1359 | `mocha --reporter dot` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1359 | `cross-env NODE_ENV=test nyc mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1349 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1347 | `mocha --recursive` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1343 | `npm run lint && npm run mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1338 | `./node_modules/.bin/mocha test` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1338 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1335 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1338 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1335 | `mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1332 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1330 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1327 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1320 | `NODE_PATH=. mocha **/*.spec.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1314 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1311 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1304 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1303 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1302 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1301 | `mocha-phantomjs tests/index.html` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1297 | `mocha` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1296 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1296 | `mocha spec/exec.js` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1295 | `mocha --recursive test/bin` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1289 | `mocha --timeout 60000 test/` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1288 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1287 | `mocha --check-leaks --reporter spec --bail test/` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1279 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1278 | `mocha --recursive test` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1276 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1275 | `mocha test/*.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1273 | `npm run prepublishOnly && mocha test/test.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1270 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1265 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1263 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1262 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1259 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1252 | `mocha tests` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1251 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1198 | `mocha test` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1196 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1196 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1186 | `npm run lint && mocha --require @babel/register` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1180 | `npm run mocha:istanbul` | 
| [router5/router5](https://github.com/router5/router5) | 1173 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1169 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1167 | `mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1165 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1151 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1198 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1198 | `mocha test` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1196 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1196 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1186 | `npm run lint && mocha --require @babel/register` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1186 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1183 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1180 | `npm run mocha:istanbul` | 
| [router5/router5](https://github.com/router5/router5) | 1173 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1169 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1167 | `mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1165 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1151 | `mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1136 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1136 | `istanbul cover _mocha test/*.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1133 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1132 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1130 | `mocha $(find test -name '*.test.js') --exit` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1125 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1124 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1118 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1112 | `mocha --timeout 30000 --recursive ./tests` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1112 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1110 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1110 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1133 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1132 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1132 | `xo && mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1130 | `mocha $(find test -name '*.test.js') --exit` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1125 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1124 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1118 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1117 | `mocha test/*` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1112 | `mocha --timeout 30000 --recursive ./tests` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1112 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1110 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1110 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1106 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1098 | `mocha --reporter spec --bail --check-leaks test/` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1096 | `webpack && mocha test/unit` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1088 | `mocha --check-leaks -t 20000` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1088 | `mocha test --compilers js:babel-core/register` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1086 | `mocha --reporter spec --bail --check-leaks test/` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1085 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1080 | `mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1080 | `mocha --compilers js:babel-register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1079 | `mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1078 | `mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1076 | `npm-run-all test:jest test:server:mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1072 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1071 | `mocha --recursive --bail --reporter spec test` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1070 | `standard && mocha -b` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1068 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1048 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1040 | `eslint src test && mocha --compilers babel-register` | 
| [tomas/needle](https://github.com/tomas/needle) | 1039 | `mocha test` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1034 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1034 | `mocha --reporter spec --timeout 3000` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1032 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1029 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1026 | `npm run convertto:es5 && npm run mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1023 | `mocha --async-only` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1022 | `mocha $(find test -name '*.test.js')` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1022 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1021 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1013 | `mocha --recursive -r tests/setup tests` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1009 | `mocha --check-leaks -R dot` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1008 | `mocha --recursive test/unit/` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 999 | `mocha --colors ./test/*.spec.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 992 | `mocha -R list` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 992 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 991 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 985 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 985 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 984 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 981 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 978 | `mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 975 | `npm run rollup-cjs && mocha test/test.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 973 | `mocha --reporter spec` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 970 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 964 | `mocha --reporter spec --bail --check-leaks test/` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 963 | `mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 963 | `mocha test` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 958 | `mocha "client.test" --compilers js:babel-register` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 953 | `mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 951 | `mocha --compilers js:babel-register test/*.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 949 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 948 | `npm run lint && mocha -R spec` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 929 | `mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 928 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 928 | `mocha tests` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 917 | `mocha test` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 915 | `mocha -t 600000` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 928 | `mocha spec/*.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 920 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 917 | `mocha test` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 915 | `mocha -t 600000` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 910 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 908 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 906 | `./node_modules/.bin/mocha --reporter spec` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 903 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 902 | `./node_modules/.bin/mocha -R spec` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 902 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 901 | `mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 900 | `nyc --check-coverage mocha test/*.test.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 900 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 897 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 895 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 892 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 891 | `mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 890 | `mocha --recursive ./test/*_spec.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 889 | `node_modules/.bin/mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 889 | `nyc mocha specs` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 888 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 887 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 887 | `./node_modules/.bin/mocha --globals angular,require` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 886 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 885 | `mocha test --compilers js:babel-register` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 884 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 880 | `npm run lint && npm run mocha:no-functional` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 878 | `istanbul cover -- _mocha --reporter spec` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 877 | `standard && standard ./bin/* && mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 876 | `mocha -t 5000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 875 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 871 | `mocha --timeout 200000` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 870 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 869 | `node_modules/.bin/mocha test/spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 866 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 866 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 861 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 858 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 857 | `eslint test && mocha --compilers js:babel/register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 854 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 851 | `mocha test/index.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 850 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 850 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 848 | `mocha --reporter spec` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 844 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 844 | `mocha --check-leaks -t 20000` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 843 | `mocha --compilers js:@babel/register --reporter spec test/**/*.test.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 842 | `npm run lint && mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 842 | `mocha test` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 842 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 819 | `npm run build && istanbul test _mocha test/test.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 818 | `./node_modules/.bin/mocha test/**/*` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 816 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 814 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 814 | `mocha --async-only` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 812 | `mocha --harmony --full-trace --check-leaks` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 811 | `mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 809 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 809 | `mocha --opts mocha.opts` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 806 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [edsu/anon](https://github.com/edsu/anon) | 805 | `mocha --colors --reporter spec test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 805 | `cake build && mocha ./test/mocha/*.coffee` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 821 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 821 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 819 | `npm run build && istanbul test _mocha test/test.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 818 | `./node_modules/.bin/mocha test/**/*` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 816 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 814 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 814 | `mocha --async-only` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 812 | `mocha --harmony --full-trace --check-leaks` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 811 | `mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 809 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 809 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 809 | `mocha --opts mocha.opts` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 806 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 796 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 796 | `npm run mocha-test test/integration` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 795 | `mocha -R spec tests/` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 794 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 792 | `mocha -u tdd` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 791 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 791 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 790 | `mocha -r should --reporter spec test/*.js` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 787 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [developit/decko](https://github.com/developit/decko) | 784 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 784 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 782 | `xo && mocha -R spec` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 781 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 