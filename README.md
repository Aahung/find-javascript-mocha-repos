# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:04 09/05/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43434 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41252 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40014 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30225 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 26293 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24570 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23416 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19970 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19097 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17215 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16908 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16806 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15335 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14368 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14066 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13690 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13255 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12815 | `./node_modules/.bin/mocha test/` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12691 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12375 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12238 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11990 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11584 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11342 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11302 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10580 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10251 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10200 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10165 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10089 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10016 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9809 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9789 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 9483 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9422 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9187 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9174 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9041 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8790 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8780 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8777 | `mocha tests/*.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8522 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8520 | `mocha test/test.js` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8477 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8450 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8344 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8203 | `mocha --compilers js:babel-register test/test.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7743 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7559 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7452 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7441 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7312 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7301 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7286 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7135 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7086 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 7066 | `mocha --compilers js:babel-core/register` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7022 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6927 | `mocha $HARMONY_OPTS` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 6790 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js'` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6751 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7066 | `mocha --compilers js:babel-core/register` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7022 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6927 | `mocha $HARMONY_OPTS` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 6790 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js'` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6751 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6617 | `mocha; jshint *.js lib` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6507 | `npm run jshint && mocha test/` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6484 | `mocha --exit --require babel-core/register` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6384 | `mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6293 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6282 | `mocha test/test.js` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6247 | `npm run test:mocha:src` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6054 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5999 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5961 | `mocha tests/node.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5934 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5849 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5788 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5744 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5743 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5727 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5707 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5465 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5420 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5400 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5381 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5372 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5184 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5147 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5122 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5075 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5048 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5017 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4985 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4848 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4818 | `mocha test` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4785 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4765 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4764 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4741 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4696 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4658 | `./node_modules/.bin/mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4649 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4572 | `mocha ./test/runner.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4499 | `mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4496 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4480 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4468 | `nyc mocha --exit` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4440 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4431 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4338 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4279 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4207 | `mocha -R spec src` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4190 | `nyc mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4153 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4102 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4064 | `mocha --timeout=15000 tests/*.test.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4050 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4041 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4038 | `mocha --require test/babel-hook test/*.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4026 | `npm run lint ; mocha && mocha test/individual` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4023 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 3995 | `mocha --require should --reporter spec` | 
| [teambit/bit](https://github.com/teambit/bit) | 3911 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3908 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3908 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3900 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3879 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [erming/shout](https://github.com/erming/shout) | 3805 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [primus/primus](https://github.com/primus/primus) | 3674 | `npm run build && mocha test/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3672 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3665 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3660 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3579 | `mocha tests/javascript` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3563 | `node_modules/.bin/mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3552 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3665 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3660 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3579 | `mocha tests/javascript` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3563 | `node_modules/.bin/mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3552 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3550 | `mocha --reporter spec --timeout 3000` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3508 | `NODE_ENV=test mocha test/**/*.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3499 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3488 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3406 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3469 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3445 | `mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3406 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3298 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3280 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3271 | `nyc mocha && tsc` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3241 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3237 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3196 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3181 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3163 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3153 | `./node_modules/.bin/mocha test/test.*.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3141 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3130 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3122 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3111 | `mocha test/*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3080 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3080 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3078 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3072 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3072 | `mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3068 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3045 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3034 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3030 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2936 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2927 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2908 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2900 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2895 | `mocha -R spec --recursive src/test` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2892 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2886 | `mocha -R landing test/index` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2875 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2873 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2857 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2848 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2846 | `npm run mocha && npm run lint` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2837 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2832 | `istanbul cover _mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2821 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2806 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2799 | `mocha -R spec spec spec/reporters` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2799 | `eslint . && mocha -t 5000` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2785 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2781 | `mocha --require babel-register --recursive spec` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2846 | `npm run mocha && npm run lint` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2837 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2832 | `istanbul cover _mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2821 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2806 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2799 | `mocha -R spec spec spec/reporters` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2799 | `eslint . && mocha -t 5000` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2785 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2781 | `mocha --require babel-register --recursive spec` | 
| [mde/ejs](https://github.com/mde/ejs) | 2773 | `mocha --require should --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2773 | `mocha --require should --reporter spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2769 | `node_modules/.bin/mocha --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2736 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [css/csso](https://github.com/css/csso) | 2733 | `mocha --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2719 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2706 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2702 | `mocha test.js` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2689 | `mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2687 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2678 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2657 | `mocha --timeout 100000` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2647 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2639 | `npm run build && cd test && mocha . --reporter dot` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2632 | `mocha --recursive --watch` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2630 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2610 | `mocha-phantomjs ./test/index.html` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2600 | `nyc mocha --timeout=10000` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2584 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2574 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2564 | `nyc mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2563 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2539 | `mocha "test/**/*-test.js"` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2420 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2418 | `mocha --no-colors --reporter spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2405 | `nyc --reporter=html --reporter=text mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2396 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2354 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2352 | `grunt jshint && mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2346 | `mocha test && npm run lint` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2335 | `mocha -R spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2330 | `mocha test/index.js --reporter dot` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2315 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2311 | `mocha test/ --no-timeouts` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2296 | `mocha && eslint .` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2354 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2352 | `grunt jshint && mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2346 | `mocha test && npm run lint` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2335 | `mocha -R spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2330 | `mocha test/index.js --reporter dot` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2315 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2311 | `mocha test/ --no-timeouts` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2296 | `mocha && eslint .` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2287 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2283 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2269 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2237 | `mocha test test/unit/**/*_test.js` | 
| [noble/noble](https://github.com/noble/noble) | 2230 | `mocha -R spec test/*.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2230 | `mocha --compilers js:babel-register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2229 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2210 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2181 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2149 | `cross-env BABEL_ENV=test mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2129 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2127 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2121 | `standard && mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2117 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2116 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2115 | `mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2098 | `mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2089 | `nyc npm run _mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2084 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2072 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2068 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2038 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2033 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2012 | `mocha && eslint *.js` | 
| [slate/slate](https://github.com/slate/slate) | 2005 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1995 | `mocha --compilers js:babel-core/register __tests__` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1993 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1986 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [pahen/madge](https://github.com/pahen/madge) | 1984 | `npm run lint && npm run mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1971 | `mocha -c test/index.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1960 | `mocha --reporter spec --timeout 5000` | 
| [share/sharedb](https://github.com/share/sharedb) | 1956 | `./node_modules/.bin/mocha && npm run jshint` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1937 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1936 | `mocha` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1936 | `npm run lint && mocha -R dot && npm run cover` | 
| [then/promise](https://github.com/then/promise) | 1935 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1934 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1929 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [zeeshanu/dumper.js](https://github.com/zeeshanu/dumper.js) | 1928 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1936 | `npm run lint && mocha -R dot && npm run cover` | 
| [then/promise](https://github.com/then/promise) | 1935 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1934 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1929 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [zeeshanu/dumper.js](https://github.com/zeeshanu/dumper.js) | 1928 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1919 | `mocha --require ./test/common --growl test/expect.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1910 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [kach/nearley](https://github.com/kach/nearley) | 1908 | `mocha test/*.test.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1899 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1881 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1880 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1879 | `mocha tests.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1868 | `npm run mocha && npm run karma` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1816 | `mocha tests --require babel-core/register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1811 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1810 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1807 | `npm run lint && mocha --reporter spec test/*.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1805 | `mocha --timeout 5000` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1797 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1797 | `mocha --reporter spec --grep .` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1791 | `mocha test/**/*.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1773 | `npm run lint && npm run mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1761 | `mocha test -u bdd -R spec` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1754 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1752 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1743 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1736 | `mocha test/**/*_test.js --bail` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1743 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1736 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1732 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1730 | `mocha ./test/basic.js -t 5000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1728 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1715 | `./node_modules/.bin/mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1715 | `mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1705 | `npm run lint && mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1704 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1701 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1694 | `mocha test --timeout 600000` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1691 | `npm run lint && npm run mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1686 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1683 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1705 | `npm run lint && mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1704 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1701 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1694 | `mocha test --timeout 600000` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1691 | `npm run lint && npm run mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1686 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1683 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1676 | `mocha test/* --reporter spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1674 | `mocha compiled_tests/` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1668 | `mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1662 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1661 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1661 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1660 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1649 | `mocha test` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1610 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1609 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [zeit/ms](https://github.com/zeit/ms) | 1600 | `mocha tests.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1600 | `eslint --cache . && tsc && mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1594 | `mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1589 | `standard "./src/*.js" && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1586 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1575 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1567 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1564 | `mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1499 | `mocha --recursive` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1491 | `nyc mocha --timeout=20000 test.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1485 | `mocha -R spec` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1461 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [samccone/drool](https://github.com/samccone/drool) | 1458 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1443 | `mocha test.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1499 | `mocha --recursive` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1491 | `nyc mocha --timeout=20000 test.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1485 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1478 | `mocha test/**/*.spec.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1461 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [samccone/drool](https://github.com/samccone/drool) | 1458 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1443 | `mocha test.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1443 | `mocha test.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1435 | `mocha --timeout 10000 ./tests/lib.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1434 | `mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1422 | `mocha -R spec test/*.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1419 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1415 | `TEST=all mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1413 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1407 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1406 | `mocha test/unit` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1404 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1393 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1392 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1389 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1385 | `./node_modules/mocha/bin/mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1377 | `npm run lint && mocha && karma start --single-run` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1375 | `npm run build && mocha -r should` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1371 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1371 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1371 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1370 | `mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1363 | `cross-env NODE_ENV=test nyc mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1361 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1357 | `mocha --opts test/opts/mocha.opts` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1348 | `mocha tests/test-*` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1342 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1342 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1340 | `NODE_ENV=test mocha tests/*.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1337 | `standard && istanbul cover _mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1335 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1325 | `./node_modules/.bin/mocha test` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1324 | `mocha --reporter dot` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1315 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1313 | `mocha -R spec ./test/unit/**` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1313 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1306 | `mocha ./test/test*.js --reporter spec` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1305 | `NODE_PATH=. mocha **/*.spec.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1290 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1286 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1285 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1284 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1283 | `npm run lint && npm run mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1280 | `mocha --timeout 60000 test/` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1280 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1266 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1286 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1285 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1284 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1283 | `npm run lint && npm run mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1280 | `mocha --timeout 60000 test/` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1280 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1274 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1266 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1265 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1264 | `mocha --check-leaks --reporter spec --bail test/` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1263 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1262 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1260 | `mocha test/*.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1260 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1259 | `mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1258 | `mocha --recursive test/bin` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1256 | `mocha tests` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1249 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1244 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1244 | `npm run prepublishOnly && mocha test/test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1244 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1244 | `npm run prepublishOnly && mocha test/test.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1236 | `mocha src/test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1233 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1233 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1228 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1223 | `istanbul test _mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1218 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1218 | `npm run lint && npm run mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1217 | `mocha test/test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1215 | `mocha --recursive test` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1212 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1211 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1210 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1181 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1176 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1172 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1169 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1158 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1155 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1152 | `mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1145 | `mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1135 | `npm run mocha:istanbul` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1172 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1172 | `webpack && npm run lint && npm run mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1169 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1158 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1156 | `npm run lint && mocha --require @babel/register` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1155 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1152 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1147 | `mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1145 | `mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1135 | `npm run mocha:istanbul` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1120 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1109 | `mocha test/*` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1108 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1106 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1105 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1102 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [electron/asar](https://github.com/electron/asar) | 1097 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1094 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1092 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1084 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1082 | `nodeunit test; mocha test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1082 | `mocha --compilers js:babel-register` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1094 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1092 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1084 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1082 | `nodeunit test; mocha test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1082 | `mocha --compilers js:babel-register` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1081 | `webpack && mocha test/unit` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1075 | `mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1074 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1070 | `mocha --recursive --bail --reporter spec test` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1068 | `mocha --reporter spec --bail --check-leaks test/` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1065 | `mocha --timeout 30000 --recursive ./tests` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1046 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [electron/spectron](https://github.com/electron/spectron) | 1037 | `mocha && standard` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1037 | `mocha --reporter spec --timeout 3000` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1035 | `npm-run-all test:jest test:server:mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1034 | `mocha test --compilers js:babel-core/register` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1034 | `eslint src test && mocha --compilers babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1030 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 1030 | `mocha test` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1025 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1023 | `mocha $(find test -name '*.test.js')` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1014 | `mocha --recursive test/unit/` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1014 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1013 | `mocha --check-leaks -R dot` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1008 | `mocha --async-only` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1008 | `mocha` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1003 | `mocha --colors ./test/*.spec.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 999 | `npm run convertto:es5 && npm run mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 995 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 990 | `mocha -R list` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 987 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 987 | `mocha --recursive -r tests/setup tests` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 987 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 978 | `npm run rollup-cjs && mocha test/test.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 976 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 976 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 976 | `mocha --reporter spec` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 973 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 966 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 961 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 956 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 950 | `mocha --reporter spec --bail --check-leaks test/` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 950 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 950 | `mocha --compilers js:babel-register test/*.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 949 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 948 | `mocha "client.test" --compilers js:babel-register` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 946 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 945 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 944 | `mocha --timeout 5000` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 943 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 936 | `npm run lint && mocha -R spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 926 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 923 | `mocha spec/*.js` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 922 | `mocha test` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 920 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 920 | `mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 916 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 914 | `mocha test` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 912 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 907 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 906 | `mocha -t 600000` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 905 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 904 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 896 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 895 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 894 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 891 | `./node_modules/.bin/mocha --globals angular,require` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 890 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 889 | `nyc mocha specs` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 888 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 887 | `node_modules/.bin/mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 885 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 885 | `./node_modules/.bin/mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 884 | `./node_modules/.bin/mocha -R spec` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 884 | `mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 879 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 877 | `mocha --reporter list` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 873 | `nyc --check-coverage mocha test/*.test.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 867 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 867 | `npm run lint && npm run mocha:no-functional` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 866 | `standard && standard ./bin/* && mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 865 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 863 | `node_modules/.bin/mocha test/spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 860 | `mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 859 | `eslint test && mocha --compilers js:babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 856 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 855 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 854 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 850 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 848 | `mocha --reporter list` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 845 | `mocha --check-leaks -t 20000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 843 | `mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 842 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 837 | `npm run lint && mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 836 | `mocha test/index.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 836 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 835 | `nyc mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 833 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 828 | `mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 828 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 825 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 825 | `mocha && ember test` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 823 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 828 | `mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 828 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 825 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 825 | `mocha && ember test` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 823 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 823 | `mocha` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 822 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 821 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 821 | `mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 819 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 818 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 818 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 817 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 816 | `mocha --async-only` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 814 | `mocha tests/*.test.js --reporter spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 810 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 809 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 808 | `cake build && mocha ./test/mocha/*.coffee` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 807 | `mocha` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 807 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 805 | `mocha --harmony --full-trace --check-leaks` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 803 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 801 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 800 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 799 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 799 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 798 | `mocha --exit --use_strict src/*.test.js` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 797 | `npm run build && istanbul test _mocha test/test.js` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 797 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 797 | `mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 795 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 795 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 792 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 791 | `npm run mocha-test test/integration` | 
| [edsu/anon](https://github.com/edsu/anon) | 791 | `mocha --colors --reporter spec test.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 790 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 790 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 789 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 784 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 783 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 781 | `xo && mocha -R spec` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 781 | `./node_modules/.bin/mocha test/**/*` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 738 | `mocha tests/*.mocha.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 737 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 733 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 731 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 731 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 731 | `mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 730 | `npm run-script jshint && npm run-script mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 727 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 726 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 726 | `mocha --reporter spec build/test/index.js` | 