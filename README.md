# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:02 09/28/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43690 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41384 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40350 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30355 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 26827 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24668 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 24600 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23701 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20195 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19257 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17442 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17052 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16997 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15561 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14396 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14207 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13909 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13371 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12986 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12736 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12448 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12261 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12176 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11703 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11512 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11486 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10713 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10403 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10328 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10257 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10142 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10095 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10010 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 9636 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9459 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9371 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9271 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9077 | `grunt mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8910 | `mocha tests/*.js` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8910 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [amark/gun](https://github.com/amark/gun) | 8904 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8864 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8602 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8548 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8467 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8353 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8258 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8231 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8112 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7942 | `npm run eslint && npm run mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7848 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7769 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7551 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7476 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7440 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7409 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7394 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7393 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7261 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7223 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [almende/vis](https://github.com/almende/vis) | 7148 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7123 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6962 | `mocha $HARMONY_OPTS` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 6904 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6801 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6798 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6658 | `mocha --exit --require @babel/register` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6606 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6574 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6351 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6330 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6276 | `npm run test:mocha:src` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6051 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6050 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6019 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6013 | `mocha tests/node.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5939 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5889 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5812 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5779 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5769 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5767 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5700 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5471 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5465 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5457 | `standard && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5416 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5246 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5196 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5184 | `mocha src/**/*Tests.js --harmony` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5167 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5147 | `mocha --color` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5122 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5018 | `gulp lint && mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4899 | `mocha test` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4868 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4807 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4776 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4771 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [santinic/how2](https://github.com/santinic/how2) | 4765 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4756 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4696 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4676 | `./node_modules/.bin/mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4587 | `mocha --recursive` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4570 | `mocha ./test/runner.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4551 | `npm run lint && npm run mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4533 | `mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4527 | `nyc mocha --exit` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4449 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4443 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4382 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4340 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4328 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4244 | `mocha -R spec src` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4206 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4172 | `nyc mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4146 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4144 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4127 | `mocha --timeout=15000 tests/*.test.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4078 | `npm run lint ; mocha && mocha test/individual` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4071 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4053 | `mocha --require test/babel-hook test/*.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 4045 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4044 | `nyc --require ./test/helpers/register _mocha -- test/tests/index.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4016 | `mocha --require should --reporter spec` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4004 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3956 | `mocha --check-leaks --reporter spec --bail` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3942 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3901 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3871 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [erming/shout](https://github.com/erming/shout) | 3798 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3789 | `nyc mocha "test/**/*.test.js"` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3622 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3587 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3570 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3560 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3553 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3552 | `mocha --reporter spec --timeout 3000` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3541 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3512 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3353 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3353 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3337 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3310 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3289 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3264 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3237 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3186 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3168 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3166 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3264 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3237 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3186 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3168 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3166 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3163 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3147 | `./node_modules/.bin/mocha test/test.*.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3137 | `mocha test/*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3133 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3128 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3122 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3119 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3118 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3113 | `mocha test/index.js && npm run demo` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3086 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3083 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3061 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3057 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3046 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2875 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2873 | `npm run mocha && npm run lint` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2849 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2830 | `istanbul cover _mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2830 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 2820 | `mocha --require should --reporter spec` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2818 | `mocha -R spec spec spec/reporters` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2818 | `mocha test-node` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2814 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2808 | `mocha --require babel-register --recursive spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2800 | `node_modules/.bin/mocha --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2771 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2762 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2745 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2745 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [css/csso](https://github.com/css/csso) | 2736 | `mocha --reporter dot` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2724 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2723 | `xo && mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2503 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2503 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2494 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2482 | `mocha --reporter=spec test/*-test.js` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2476 | `mocha test/src/**/*.unit.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2447 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2417 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2415 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2398 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2368 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2354 | `grunt jshint && mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2352 | `mocha -R spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2349 | `mocha test/index.js --reporter dot` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2334 | `mocha && eslint .` | 
| [tj/should.js](https://github.com/tj/should.js) | 2715 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2705 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2682 | `npm run build && cd test && mocha . --reporter dot` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2663 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2657 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2653 | `mocha --timeout 100000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2641 | `mocha --recursive --watch` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2631 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2615 | `nyc mocha --timeout=10000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2611 | `mocha-phantomjs ./test/index.html` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2603 | `mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2586 | `nyc mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2572 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2563 | `mocha "test/**/*-test.js"` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2523 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2503 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2503 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2494 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2488 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2482 | `mocha --reporter=spec test/*-test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2480 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2476 | `mocha test/src/**/*.unit.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2464 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2447 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2417 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2415 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2398 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1829 | `mocha tests --require @babel/register` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1818 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1816 | `mocha test` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1813 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1809 | `mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1808 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1787 | `mocha test -u bdd -R spec` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1780 | `npm run lint && npm run mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1778 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1759 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1744 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1732 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2267 | `mocha -R spec test/*.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2237 | `mocha --compilers js:babel-register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2226 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2225 | `mocha --compilers js:babel-register` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2222 | `mocha test test/unit/**/*_test.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 2216 | `mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2158 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2150 | `cross-env BABEL_ENV=test mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2149 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2137 | `standard && mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2129 | `nyc npm run _mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2128 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2126 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2115 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2108 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2096 | `mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2091 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2078 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2058 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2056 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2050 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2044 | `mocha && eslint *.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2028 | `npm run lint && npm run mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2013 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2010 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2004 | `mocha --compilers js:babel-core/register __tests__` | 
| [slate/slate](https://github.com/slate/slate) | 1999 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1993 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1993 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1971 | `mocha --require=test/test_helper.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1970 | `./node_modules/.bin/mocha && npm run jshint` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1967 | `mocha --reporter spec --timeout 5000` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1963 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1959 | `mocha -c test/index.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1944 | `npm run lint && mocha -R dot && npm run cover` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1938 | `mocha --bail --reporter spec --check-leaks test/` | 
| [then/promise](https://github.com/then/promise) | 1938 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1936 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1935 | `mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 1934 | `mocha test/*.test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1930 | `mocha --require ./test/common --growl test/expect.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1924 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1911 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1909 | `npm run mocha && npm run karma` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1881 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1881 | `mocha --compilers js:babel-register` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1813 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1812 | `mocha test/**/*.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1809 | `mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1808 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1787 | `mocha test -u bdd -R spec` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1780 | `npm run lint && npm run mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1778 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1759 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1744 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1732 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1730 | `mocha test/**/*_test.js --bail` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1718 | `./node_modules/.bin/mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1787 | `mocha test -u bdd -R spec` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1780 | `npm run lint && npm run mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1778 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1759 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1746 | `mocha ./test/basic.js -t 5000` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1744 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1732 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1730 | `mocha test/**/*_test.js --bail` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1722 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1606 | `mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1604 | `standard "./src/*.js" && mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1595 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1581 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1579 | `mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1566 | `mocha --reporter spec` | 
| [retejs/rete](https://github.com/retejs/rete) | 1563 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1560 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1555 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1542 | `npm run test:lint && npm run test:mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1538 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1538 | `nyc mocha --timeout=20000 test.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1653 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1645 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1639 | `mocha && size-limit` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1638 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1635 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1631 | `mocha tests/test.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1630 | `eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1618 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [zeit/ms](https://github.com/zeit/ms) | 1615 | `mocha tests.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1608 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1607 | `mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1606 | `mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1604 | `standard "./src/*.js" && mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1520 | `mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1517 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1510 | `mocha -u tdd` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1497 | `TEST=all mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1485 | `mocha test/**/*.spec.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1482 | `mocha -R spec` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1472 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1472 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [samccone/drool](https://github.com/samccone/drool) | 1453 | `mocha test/tests.js --timeout=10000` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1453 | `mocha --timeout 10000 ./tests/lib.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1447 | `mocha test.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1441 | `mocha --check-leaks --require @babel/register` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1436 | `mocha test/unit` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1430 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1429 | `NODE_ENV=test mocha tests/*.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1424 | `mocha -R spec test/*.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1421 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1418 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1368 | `mocha -R spec ./test/unit/**` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1360 | `cross-env NODE_ENV=test nyc mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1354 | `standard && istanbul cover _mocha` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1347 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1347 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1338 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1337 | `mocha --recursive` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1335 | `mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1331 | `./node_modules/.bin/mocha test` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1326 | `npm run lint && npm run mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1321 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1320 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1318 | `NODE_PATH=. mocha **/*.spec.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1314 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1301 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1301 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1300 | `mocha-phantomjs tests/index.html` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1296 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1296 | `mocha spec/exec.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1294 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1291 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1290 | `mocha --recursive test/bin` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1284 | `mocha --timeout 60000 test/` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1273 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1271 | `mocha --recursive test` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1270 | `mocha test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1269 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1263 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1260 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1259 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1252 | `mocha tests` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1244 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1243 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1237 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1236 | `npm run lint && npm run mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1229 | `mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1220 | `mocha --compilers js:babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1212 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1211 | `mocha --reporter spec` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1210 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1229 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1228 | `istanbul test _mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1221 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1220 | `mocha --compilers js:babel-core/register` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1220 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1218 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1212 | `mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1211 | `mocha test/test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1211 | `mocha --reporter spec` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1210 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1210 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1209 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1207 | `node ./node_modules/mocha/bin/mocha tests` | 
| [variety/variety](https://github.com/variety/variety) | 1205 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1203 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1199 | `mocha test` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1199 | `webpack && npm run lint && npm run mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1196 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1194 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1189 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1186 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1181 | `npm run lint && mocha --require @babel/register` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1179 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1169 | `npm run mocha:istanbul` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1169 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1162 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1160 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1157 | `mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1153 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1152 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1149 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1134 | `istanbul cover _mocha test/*.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1133 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1133 | `mocha --timeout 20000` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1132 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1130 | `xo && mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1128 | `mocha $(find test -name '*.test.js') --exit` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1124 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1123 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1110 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1110 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1105 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1104 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1102 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1093 | `mocha --timeout 30000 --recursive ./tests` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1093 | `webpack && mocha test/unit` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1092 | `mocha --reporter spec --bail --check-leaks test/` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1088 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1086 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1082 | `mocha test --compilers js:babel-core/register` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1080 | `mocha --compilers js:babel-register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1079 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1079 | `mocha --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1077 | `mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1082 | `mocha test --compilers js:babel-core/register` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1080 | `mocha --compilers js:babel-register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1079 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1079 | `mocha --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1077 | `mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1072 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1070 | `mocha --recursive --bail --reporter spec test` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1069 | `standard && mocha -b` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1066 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1066 | `mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1062 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1062 | `mocha test/tests.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1059 | `npm-run-all test:jest test:server:mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1055 | `mocha` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1010 | `mocha --recursive -r tests/setup tests` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1009 | `mocha --check-leaks -R dot` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1006 | `mocha --recursive test/unit/` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 999 | `mocha --colors ./test/*.spec.js` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 993 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 992 | `mocha -R list` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 991 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 989 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 986 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 981 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 981 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1017 | `mocha --async-only` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1010 | `mocha --recursive -r tests/setup tests` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1009 | `mocha --check-leaks -R dot` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1006 | `mocha --recursive test/unit/` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 999 | `mocha --colors ./test/*.spec.js` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 993 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 992 | `mocha -R list` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 991 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 989 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 986 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 981 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 955 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 951 | `mocha --compilers js:babel-register test/*.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 951 | `mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 948 | `npm run lint && mocha -R spec` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 948 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 948 | `mocha test` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 943 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 942 | `mocha --timeout 5000` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 927 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 926 | `mocha spec/*.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 925 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 924 | `mocha tests` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 922 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 919 | `mocha test` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 919 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 913 | `mocha -t 600000` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 910 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 904 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 903 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 901 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 901 | `./node_modules/.bin/mocha --reporter spec` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 900 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 898 | `./node_modules/.bin/mocha -R spec` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 898 | `mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 896 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 895 | `nyc --check-coverage mocha test/*.test.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 892 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 891 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 890 | `node_modules/.bin/mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 887 | `mocha --recursive ./test/*_spec.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 885 | `nyc mocha specs` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 885 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 884 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 881 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 877 | `npm run lint && npm run mocha:no-functional` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 875 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 875 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 875 | `mocha test --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 874 | `standard && standard ./bin/* && mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 874 | `istanbul cover -- _mocha --reporter spec` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 873 | `mocha -t 5000` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 869 | `node_modules/.bin/mocha test/spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 865 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 866 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 865 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 861 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 860 | `mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 857 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 857 | `eslint test && mocha --compilers js:babel/register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 854 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 853 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 850 | `mocha test/index.js` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 850 | `mocha --exit --use_strict src/*.test.js` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 849 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 848 | `mocha --reporter spec` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 834 | `mocha --reporter spec --bail --check-leaks test/` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 831 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 831 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 830 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 828 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 826 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 824 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 824 | `mocha && ember test` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 822 | `mocha` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 821 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 821 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 826 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 824 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 824 | `mocha && ember test` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 822 | `mocha` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 821 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 821 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 818 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 818 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 816 | `./node_modules/.bin/mocha test/**/*` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 816 | `mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 815 | `npm run build && istanbul test _mocha test/test.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 814 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 812 | `mocha --async-only` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 810 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 810 | `mocha` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 804 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 802 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 799 | `mocha --colors --reporter spec test.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 799 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 798 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 797 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 796 | `npm run mocha-test test/integration` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 796 | `mocha --opts mocha.opts` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 795 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 793 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 791 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 790 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 787 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 787 | `mocha -r should --reporter spec test/*.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 764 | `mocha --ui tdd --require ./test/__setup` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 764 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 764 | `mocha --recursive -s 15 test/` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 761 | `mocha test` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 758 | `nyc mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 756 | `mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 752 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 752 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 750 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 749 | `mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 747 | `npm run lint && npm run mocha` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 747 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 752 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 752 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 750 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 746 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 744 | `babel-node node_modules/.bin/_mocha -- test` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 740 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 739 | `nyc mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 739 | `mocha tests/*.mocha.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 738 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 736 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 735 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 733 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 733 | `mocha` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 733 | `npm run-script jshint && npm run-script mocha` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 732 | `npm run bundle && mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 730 | `mocha --harmony tests/**` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 730 | `mocha --reporter spec build/test/index.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 729 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 724 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 723 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 