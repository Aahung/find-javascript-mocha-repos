# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:58 09/17/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43575 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41323 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40203 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30297 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 26538 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24628 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23558 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20089 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19177 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17330 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16972 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16914 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15433 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14386 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14143 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13787 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13313 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12920 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12718 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12415 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12248 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12102 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11639 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11432 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11388 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10651 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10337 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10277 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10202 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10118 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10069 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9914 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 9579 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9446 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9283 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9223 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9073 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8861 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8849 | `mocha tests/*.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8824 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8603 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8572 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8542 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8460 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8355 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8221 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8209 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8101 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8026 | `mocha --opts mocha.opts` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7934 | `npm run eslint && npm run mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7791 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7766 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7562 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7462 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7440 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7368 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7346 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7336 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7194 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7135 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [almende/vis](https://github.com/almende/vis) | 7109 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7108 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6955 | `mocha $HARMONY_OPTS` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 6842 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js'` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6778 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6728 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6590 | `mocha --exit --require @babel/register` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6548 | `npm run jshint && mocha test/` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6493 | `mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6317 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6314 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6264 | `npm run test:mocha:src` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6051 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6030 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5992 | `mocha tests/node.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5877 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5873 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5773 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5762 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5758 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5750 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5596 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5444 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5437 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5429 | `standard && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5420 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5181 | `mocha src/**/*Tests.js --harmony` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5172 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5153 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5148 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5141 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5094 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5005 | `gulp lint && mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4866 | `mocha test` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4863 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4802 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4775 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4767 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4753 | `mocha -R spec 'tests/app'` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4720 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4702 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4674 | `./node_modules/.bin/mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4577 | `mocha ./test/runner.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4539 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4527 | `npm run lint && npm run mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4516 | `mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4498 | `nyc mocha --exit` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4449 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4449 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4346 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4333 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4227 | `mocha -R spec src` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4216 | `mocha -R spec ./test --recursive` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4212 | `nyc mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4168 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4118 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4096 | `mocha --timeout=15000 tests/*.test.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4087 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4061 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4054 | `npm run lint ; mocha && mocha test/individual` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4048 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4008 | `mocha --require should --reporter spec` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3987 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 3980 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3962 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3940 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3926 | `mocha --check-leaks --reporter spec --bail` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3903 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3876 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [erming/shout](https://github.com/erming/shout) | 3803 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3696 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [primus/primus](https://github.com/primus/primus) | 3688 | `npm run build && mocha test/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3676 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3670 | `npm run jshint && npm run mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3609 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3597 | `NODE_ENV=test mocha --exit` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3585 | `mocha tests/javascript` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3578 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3549 | `mocha --reporter spec --timeout 3000` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3547 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3527 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3470 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3469 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3451 | `mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3433 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3314 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3298 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3252 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3250 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3226 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3188 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3167 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3155 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3252 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3250 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3226 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3188 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3167 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3155 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3154 | `./node_modules/.bin/mocha test/test.*.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3148 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3136 | `mocha test/*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3134 | `mocha` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3105 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3104 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3104 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3100 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3084 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3080 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3070 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3049 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2972 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2958 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2952 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2922 | `mocha -R landing test/index` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2913 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2909 | `mocha -R spec --recursive src/test` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2906 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2901 | `eslint . && mocha -t 5000` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2891 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2878 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2872 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2868 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2843 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2830 | `istanbul cover _mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2829 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2862 | `npm run mocha && npm run lint` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2843 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2830 | `istanbul cover _mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2829 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2816 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2815 | `mocha -R spec spec spec/reporters` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2813 | `mocha test-node` | 
| [mde/ejs](https://github.com/mde/ejs) | 2803 | `mocha --require should --reporter spec` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2795 | `mocha --require babel-register --recursive spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2788 | `node_modules/.bin/mocha --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2778 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2756 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [css/csso](https://github.com/css/csso) | 2735 | `mocha --reporter dot` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2730 | `mocha test.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2727 | `xo && mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2717 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2577 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2527 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2494 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2486 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2474 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2472 | `mocha test` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2467 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2461 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2452 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2417 | `mocha --no-colors --reporter spec` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2527 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2497 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2494 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2490 | `mocha --reporter=spec test/*-test.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2486 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2474 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2472 | `mocha test` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2467 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2461 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2452 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2417 | `mocha --no-colors --reporter spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2414 | `nyc --reporter=html --reporter=text mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2399 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2287 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2278 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2246 | `mocha -R spec test/*.js` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2237 | `mocha test test/unit/**/*_test.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2234 | `mocha --compilers js:babel-register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2229 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2220 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2196 | `mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2237 | `mocha test test/unit/**/*_test.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2234 | `mocha --compilers js:babel-register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2229 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2220 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2196 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2157 | `cross-env BABEL_ENV=test mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2151 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2135 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2126 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2125 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2118 | `mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2113 | `nyc npm run _mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2109 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2100 | `mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2089 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2072 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2050 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2049 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2037 | `mocha && eslint *.js` | 
| [zeeshanu/dumper.js](https://github.com/zeeshanu/dumper.js) | 2025 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2005 | `mocha --compilers js:babel-core/register __tests__` | 
| [slate/slate](https://github.com/slate/slate) | 2005 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2003 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [pahen/madge](https://github.com/pahen/madge) | 2001 | `npm run lint && npm run mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1997 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1993 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1972 | `mocha --require=test/test_helper.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1970 | `mocha -c test/index.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1969 | `./node_modules/.bin/mocha && npm run jshint` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1966 | `mocha --reporter spec --timeout 5000` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1961 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1957 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1948 | `npm run lint && mocha -R dot && npm run cover` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1943 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1943 | `mocha --bail --reporter spec --check-leaks test/` | 
| [then/promise](https://github.com/then/promise) | 1937 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1932 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1928 | `mocha --require ./test/common --growl test/expect.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1921 | `mocha test/*.test.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1914 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1910 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1886 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1882 | `npm run mocha && npm run karma` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1879 | `mocha tests.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1859 | `mocha --compilers js:babel-register` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1856 | `mocha --reporter spec && npm run test-typescript` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1854 | `mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1852 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1843 | `mocha && npm run lint` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1837 | `mocha --reporter spec test/*.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1828 | `mocha tests --require @babel/register` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1823 | `mocha test` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1821 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1818 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1817 | `npm run lint && mocha --reporter spec test/*.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1810 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1808 | `mocha --reporter spec --grep .` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1805 | `mocha --timeout 5000` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1805 | `mocha test/**/*.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1805 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1785 | `npm run lint && npm run mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1682 | `mocha test` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1673 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1669 | `xo && mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1665 | `mocha` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1664 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1653 | `mocha test/setup.js test/spec/*.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1641 | `mocha spec` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1635 | `mocha tests/test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1613 | `mocha tests.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1612 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1717 | `./node_modules/.bin/mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1716 | `mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1715 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1708 | `npm run lint && mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1707 | `mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1702 | `npm run lint && npm run mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1702 | `mocha test --timeout 600000` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1690 | `mocha compiled_tests/` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1688 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1686 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1683 | `mocha test/* --reporter spec` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1682 | `mocha test` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1673 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1669 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1669 | `xo && mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1665 | `mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1664 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1664 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1653 | `mocha test/setup.js test/spec/*.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1641 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1640 | `mocha && size-limit` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1638 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1635 | `mocha tests/test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1613 | `mocha tests.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1612 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1610 | `eslint --cache . && tsc && mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1609 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1601 | `standard "./src/*.js" && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1600 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1599 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1595 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1581 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1575 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1574 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1571 | `mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1566 | `mocha --reporter spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1552 | `mocha test.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1551 | `mocha --check-leaks --reporter spec --bail` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1550 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1547 | `npm run test:lint && npm run test:mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 1547 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1542 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1485 | `mocha test/**/*.spec.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1470 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1465 | `TEST=all mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1443 | `mocha --timeout 10000 ./tests/lib.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1440 | `mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1429 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1427 | `mocha -R spec test/*.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1487 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1485 | `mocha test/**/*.spec.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1470 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1465 | `TEST=all mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1451 | `mocha test.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1443 | `mocha --timeout 10000 ./tests/lib.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1440 | `mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1438 | `mocha --check-leaks --require @babel/register` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1429 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1427 | `mocha -R spec test/*.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1422 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1420 | `mocha test/unit` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1415 | `mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1410 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1406 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1401 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1398 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1396 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1395 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1392 | `istanbul cover _mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1391 | `npm run lint && mocha && karma start --single-run` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1387 | `./node_modules/mocha/bin/mocha` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1383 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1380 | `npm run build && mocha -r should` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1374 | `NODE_ENV=test mocha tests/*.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1368 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1367 | `mocha --opts test/opts/mocha.opts` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1366 | `mocha tests/test-*` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1363 | `cross-env NODE_ENV=test nyc mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1356 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1350 | `standard && istanbul cover _mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1343 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1340 | `mocha --reporter dot` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1337 | `mocha --recursive` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1336 | `mocha -R spec ./test/unit/**` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1332 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1329 | `mocha ./test/test*.js --reporter spec` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1329 | `./node_modules/.bin/mocha test` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1318 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1317 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1305 | `mocha-phantomjs tests/index.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1303 | `mocha spec/exec.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1297 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1296 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1294 | `mocha` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1289 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1286 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1285 | `mocha --timeout 60000 test/` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1283 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1281 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1278 | `mocha --recursive test/bin` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1272 | `mocha --check-leaks --reporter spec --bail test/` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1270 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1268 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1250 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1247 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1243 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1243 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1241 | `mocha src/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1236 | `npm run lint && npm run mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1233 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1230 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1229 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1226 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1225 | `istanbul test _mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1217 | `mocha test/test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1216 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1215 | `mocha --compilers js:babel-core/register` | 
| [normalize/mz](https://github.com/normalize/mz) | 1215 | `mocha --reporter spec` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1214 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1213 | `mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1212 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1230 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1229 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1226 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1225 | `istanbul test _mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1217 | `mocha test/test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1216 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1215 | `mocha --compilers js:babel-core/register` | 
| [normalize/mz](https://github.com/normalize/mz) | 1215 | `mocha --reporter spec` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1214 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1213 | `mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1212 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1210 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1208 | `node ./node_modules/mocha/bin/mocha tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1208 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1203 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1201 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1200 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1197 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1203 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1201 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1200 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1197 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [wilk/microjob](https://github.com/wilk/microjob) | 1196 | `node --experimental-worker node_modules/.bin/_mocha ./test` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1194 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1188 | `webpack && npm run lint && npm run mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1175 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1171 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1170 | `npm run lint && mocha --require @babel/register` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1130 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1129 | `istanbul cover _mocha test/*.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1129 | `mocha $(find test -name '*.test.js') --exit` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1124 | `mocha --timeout 20000` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1120 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1115 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1115 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1112 | `mocha test/*` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1111 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1108 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1108 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [electron/asar](https://github.com/electron/asar) | 1107 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1098 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1120 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1115 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1115 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1112 | `mocha test/*` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1111 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1108 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1108 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [electron/asar](https://github.com/electron/asar) | 1107 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1098 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1093 | `mocha --check-leaks -t 20000` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1088 | `webpack && mocha test/unit` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1086 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1084 | `mocha --compilers js:babel-register` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1093 | `mocha --check-leaks -t 20000` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1088 | `webpack && mocha test/unit` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1086 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1084 | `mocha --compilers js:babel-register` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1082 | `mocha` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1078 | `mocha --reporter spec --bail --check-leaks test/` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1075 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1075 | `mocha --timeout 30000 --recursive ./tests` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1073 | `mocha` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1072 | `mocha --recursive --bail --reporter spec test` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1072 | `mocha --reporter spec --bail --check-leaks test/` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1066 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1066 | `standard && mocha -b` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1063 | `mocha test/tests.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1060 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1058 | `mocha test --compilers js:babel-core/register` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1055 | `mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1047 | `npm-run-all test:jest test:server:mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1046 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [electron/spectron](https://github.com/electron/spectron) | 1045 | `mocha && standard` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1043 | `eslint src test && mocha --compilers babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1042 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1038 | `mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1037 | `mocha --reporter spec --timeout 3000` | 
| [tomas/needle](https://github.com/tomas/needle) | 1035 | `mocha test` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1029 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1027 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1024 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1017 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1016 | `npm run convertto:es5 && npm run mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1015 | `mocha --async-only` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1014 | `mocha --check-leaks -R dot` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1013 | `mocha --recursive test/unit/` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1004 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1004 | `mocha --colors ./test/*.spec.js` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1001 | `mocha --recursive -r tests/setup tests` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 995 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 994 | `mocha -R list` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 991 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 990 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 981 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 980 | `npm run rollup-cjs && mocha test/test.js` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 975 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 975 | `mocha --reporter spec` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 974 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 970 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 963 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 962 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 961 | `mocha --reporter spec --bail --check-leaks test/` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 945 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 944 | `npm run lint && mocha -R spec` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 943 | `mocha --timeout 5000` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 942 | `mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 940 | `mocha test` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 930 | `mocha spec/*.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 928 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 926 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 921 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 908 | `mocha -t 600000` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 904 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 897 | `./node_modules/.bin/mocha -R spec` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 897 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 896 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 893 | `nyc mocha specs` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 892 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 891 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 890 | `node_modules/.bin/mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 889 | `nyc --check-coverage mocha test/*.test.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 889 | `./node_modules/.bin/mocha --globals angular,require` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 888 | `mocha` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 885 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 881 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 908 | `mocha -t 600000` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 904 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 902 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 901 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 897 | `./node_modules/.bin/mocha -R spec` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 897 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 896 | `./node_modules/.bin/mocha --reporter spec` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 896 | `mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 894 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 893 | `nyc mocha specs` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 892 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 891 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 890 | `node_modules/.bin/mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 889 | `nyc --check-coverage mocha test/*.test.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 889 | `./node_modules/.bin/mocha --globals angular,require` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 888 | `mocha` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 885 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 881 | `mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 879 | `mocha --recursive ./test/*_spec.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 877 | `istanbul cover -- _mocha --reporter spec` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 876 | `mocha --reporter list` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 875 | `mocha test --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 875 | `standard && standard ./bin/* && mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 874 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 874 | `npm run lint && npm run mocha:no-functional` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 873 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 873 | `mocha -t 5000` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 872 | `mocha --timeout 200000` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 871 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 868 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 867 | `node_modules/.bin/mocha test/spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 867 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 866 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 860 | `mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 859 | `eslint test && mocha --compilers js:babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 856 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 852 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 850 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 848 | `istanbul cover _mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 847 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 846 | `mocha --reporter spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 846 | `mocha --check-leaks -t 20000` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 845 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 843 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 842 | `mocha test/index.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 841 | `npm run lint && mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 839 | `mocha --reporter spec --bail --check-leaks test/` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 838 | `mocha test` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 837 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 837 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 835 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 834 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 830 | `mocha --exit --use_strict src/*.test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 829 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 781 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 778 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 778 | `mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 778 | `mocha test` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 775 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 775 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 774 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 765 | `mocha --recursive -s 15 test/` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 764 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 764 | `mocha -R spec src/**/*_test.js` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 806 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 805 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 805 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 805 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 803 | `npm run build && istanbul test _mocha test/test.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 801 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 800 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 799 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 798 | `mocha -u tdd` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 798 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 796 | `npm run mocha-test test/integration` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 796 | `mocha -R spec tests/` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 796 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 796 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 795 | `mocha --colors --reporter spec test.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 793 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 