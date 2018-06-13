# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:17 06/13/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 42100 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29668 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24122 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23466 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 23116 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22439 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19079 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18485 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16348 | `mocha` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16348 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15970 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14472 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14162 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13527 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12774 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 12519 | `mocha --reporter spec` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12515 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12366 | `./node_modules/.bin/mocha test/` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12162 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12113 | `mocha --reporter spec test/*-test.js` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11956 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11177 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11089 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10631 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10514 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10036 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9750 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9747 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9735 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9710 | `set NODE_ENV=test && mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9530 | `mocha` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9249 | `mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9176 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9022 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8856 | `grunt mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 8827 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8809 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8545 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8396 | `mocha test/test.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8374 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8308 | `mocha --check-leaks -R dot` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8250 | `mocha test/src` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8226 | `grunt clean:test && mocha --exit` | 
| [amark/gun](https://github.com/amark/gun) | 8201 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8082 | `mocha tests/*.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8031 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7956 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7821 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7755 | `npm run eslint && npm run mocha` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7625 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7617 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7527 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7519 | `./node_modules/.bin/mocha test` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7440 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7344 | `npm run build && istanbul cover _mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7107 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7100 | `mocha --opts mocha.opts` | 
| [aui/art-template](https://github.com/aui/art-template) | 6919 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6915 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6908 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6839 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6793 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6739 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6653 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6321 | `npm run lint -s && npm run mocha -s` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 6238 | `mocha test node-test --recursive` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 6202 | `npm run build-cli && mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6186 | `npm run jshint && mocha test/` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6142 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6119 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6030 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5919 | `mocha --exit --require babel-core/register` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5862 | `mocha test/test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5855 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5764 | `mocha; jshint *.js lib` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5738 | `mocha tests/node.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5646 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5609 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5538 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5406 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5404 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5403 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5313 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5283 | `mocha --timeout 10000 && npm run lint` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5161 | `mocha src/**/*Tests.js --harmony` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5157 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5153 | `mocha --color` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4996 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4991 | `standard && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4947 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4900 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4824 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4718 | `mocha test` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4702 | `mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4700 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4673 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4665 | `gulp build; mocha;` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4664 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4610 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4600 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4556 | `mocha ./test/runner.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4529 | `mocha test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4504 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4419 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4372 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4347 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4322 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4251 | `NODE_ENV=test mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4228 | `mocha --recursive && make test` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4219 | `mocha -R spec ./test --recursive` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4206 | `nyc mocha --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4140 | `npm run lint && npm run mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4107 | `nyc mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 3975 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3969 | `mocha --require test/babel-hook test/*.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3964 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3964 | `mocha -R spec ./test` | 
| [tj/ejs](https://github.com/tj/ejs) | 3908 | `mocha --require should --reporter spec` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3894 | `npm run lint && npm run mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3883 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3879 | `export TESTING=true; mocha --reporter list` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3878 | `npm run lint ; mocha && mocha test/individual` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3819 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3813 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [erming/shout](https://github.com/erming/shout) | 3802 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3699 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3660 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3621 | `standard && mocha --timeout 60000 test/test.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3620 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [primus/primus](https://github.com/primus/primus) | 3595 | `npm run build && mocha test/*.test.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3562 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3558 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3502 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3486 | `node_modules/.bin/mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3473 | `nyc mocha "test/**/*.test.js"` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3466 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 3459 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3448 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3502 | `mocha --reporter spec --timeout 3000` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3473 | `nyc mocha "test/**/*.test.js"` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3466 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 3459 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3457 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3448 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3432 | `node_modules/.bin/mocha test/lib/` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3427 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3426 | `mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3416 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3398 | `node_modules/.bin/mocha test/tests.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3384 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3368 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3343 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3299 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3227 | `NODE_ENV=test mocha test/**/*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3128 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3128 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3126 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3119 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3115 | `mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3105 | `nyc mocha && tsc` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3080 | `mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3059 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3056 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3035 | `NODE_ENV=test mocha --exit` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3010 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3009 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3000 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2980 | `mocha test/*.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2973 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2960 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2952 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2912 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2911 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2895 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2889 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2880 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2850 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2846 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2840 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2351 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2297 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2289 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2260 | `mocha -R spec` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2249 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2243 | `eslint . && mocha -t 5000` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2227 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [gajus/swing](https://github.com/gajus/swing) | 2195 | `mocha --compilers js:babel-register` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2191 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2191 | `mocha test && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2174 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2165 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2128 | `mocha -R spec test/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2111 | `cross-env BABEL_ENV=test mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2289 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2261 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2260 | `mocha -R spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2251 | `nyc --reporter=html --reporter=text mocha` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2249 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2233 | `mocha test test/unit/**/*_test.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2191 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2191 | `mocha test && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2174 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2165 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1926 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1914 | `mocha --compilers js:babel-core/register __tests__` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1912 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1891 | `nyc npm run _mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1888 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1884 | `mocha --require ./test/common --growl test/expect.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1875 | `mocha && eslint *.js` | 
| [then/promise](https://github.com/then/promise) | 1861 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1831 | `mocha` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1830 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1820 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1817 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2111 | `cross-env BABEL_ENV=test mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2090 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2088 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2076 | `mocha --compilers js:babel-register` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2046 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [Qix-/color](https://github.com/Qix-/color) | 2028 | `mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2023 | `standard && mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2195 | `mocha --compilers js:babel-register` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2191 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2191 | `mocha test && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2174 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2165 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2128 | `mocha -R spec test/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2111 | `cross-env BABEL_ENV=test mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1916 | `mocha --bail --reporter spec --check-leaks test/` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1914 | `mocha --compilers js:babel-core/register __tests__` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1912 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1909 | `mocha --reporter spec --timeout 5000` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1908 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1884 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1875 | `mocha && eslint *.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1868 | `./node_modules/.bin/mocha && npm run jshint` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1865 | `mocha tests.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1857 | `npm run lint && mocha -R dot && npm run cover` | 
| [kach/nearley](https://github.com/kach/nearley) | 1841 | `mocha test/*.test.js` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1831 | `mocha` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1830 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1817 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1815 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1811 | `mocha` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1802 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1801 | `mocha --timeout 5000` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1800 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1790 | `mocha --reporter spec && npm run test-typescript` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1786 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1781 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1772 | `npm run mocha && npm run karma` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1771 | `mocha -R spec spec spec/reporters` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1770 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1755 | `mocha test` | 
| [pahen/madge](https://github.com/pahen/madge) | 1753 | `npm run lint && npm run mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1719 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1714 | `mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1713 | `mocha --reporter spec test/*.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1713 | `npm run lint && npm run mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1710 | `mocha --reporter spec --grep .` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1708 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1705 | `mocha tests --compilers js:babel-core/register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1705 | `npm run lint && mocha test/unit --recursive && mocha test/runner --recursive` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1697 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1692 | `./node_modules/.bin/mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1689 | `mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1678 | `mocha test/**/*.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1673 | `xo && mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1672 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1667 | `mocha test -u bdd -R spec` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1655 | `npm run lint && mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1589 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1545 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1529 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1520 | `mocha compiled_tests/` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1517 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1557 | `mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1551 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1529 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1477 | `mocha test/setup.js test/spec/*.js` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1474 | `mocha test.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1473 | `mocha -R spec` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1472 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1469 | `nyc mocha` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1466 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1465 | `mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1461 | `mocha test/**/*.spec.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1449 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1440 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1436 | `mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1435 | `mocha test.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1432 | `mocha --recursive` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1237 | `mocha test/*.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1223 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1217 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1215 | `mocha test/test.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1203 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1194 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1191 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1191 | `mocha` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1189 | `node ./node_modules/mocha/bin/mocha tests` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1187 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1186 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1185 | `mocha src/test.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1184 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1180 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1177 | `TEST=all mocha` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1173 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1172 | `mocha --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1167 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1207 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1194 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1188 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1188 | `mocha test` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1186 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1185 | `mocha src/test.js` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1161 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1146 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1145 | `mocha -R spec ./test/unit/**` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1138 | `mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1135 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1135 | `NODE_ENV=test mocha tests/*.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1173 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1172 | `mocha --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1167 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1164 | `mocha --check-leaks --reporter spec --bail test/` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1164 | `npm run lint && npm run mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1161 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1146 | `mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1143 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1138 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1131 | `mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1125 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1124 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1123 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1121 | `npm run prepublishOnly && mocha test/test.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1120 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1118 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1115 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1322 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1318 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1308 | `mocha --check-leaks --require @babel/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1306 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1300 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1297 | `istanbul cover _mocha test -- --timeout 20000` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1294 | `mocha-phantomjs tests/index.html` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1293 | `./node_modules/.bin/mocha test` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1289 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1287 | `mocha --recursive` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1285 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1283 | `mocha` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1283 | `mocha spec/exec.js` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1069 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1067 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1065 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1064 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1054 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1054 | `istanbul test _mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1054 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1049 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1040 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1040 | `mocha --reporter spec --timeout 3000` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1031 | `mocha --recursive --bail --reporter spec test` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1026 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [electron/asar](https://github.com/electron/asar) | 1023 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [jas/playground](https://github.com/jas/playground) | 1023 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [electron/asar](https://github.com/electron/asar) | 1023 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1016 | `webpack && mocha test/unit` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1013 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1013 | `mocha --check-leaks -R dot` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1012 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1005 | `mocha --reporter spec --bail --check-leaks test/` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1004 | `mocha $(find test -name '*.test.js')` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 998 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 996 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 996 | `mocha --reporter spec --bail --check-leaks test/` | 
| [tomas/needle](https://github.com/tomas/needle) | 993 | `mocha test` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 992 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 992 | `standard && mocha -b` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 979 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 978 | `npm run mocha:istanbul` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 976 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 980 | `mocha --async-only` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 979 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 978 | `npm run mocha:istanbul` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 976 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 976 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 976 | `eslint src test && mocha --compilers babel-register` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 975 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 971 | `mocha -R list` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 967 | `mocha --timeout 20000` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 963 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 961 | `mocha --reporter spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 903 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 902 | `mocha -R spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 892 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 884 | `mocha tests` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 871 | `node_modules/.bin/mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 871 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 867 | `mocha -t 600000` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 866 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 865 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 865 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 861 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 903 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 902 | `mocha -R spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 892 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 884 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 884 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 875 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 873 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 871 | `node_modules/.bin/mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 902 | `mocha -R spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 892 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 890 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 884 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 884 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 875 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 873 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 871 | `node_modules/.bin/mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 871 | `mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 867 | `mocha -t 600000` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 866 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 865 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 865 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 863 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 862 | `mocha --timeout 200000` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 862 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 861 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 861 | `npm run lint && npm run mocha:no-functional` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 859 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 856 | `mocha spec/*.js` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 803 | `mocha --require babel-register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 802 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 801 | `mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 801 | `mocha test` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 800 | `mocha --timeout 30000 --recursive ./tests` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 799 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 795 | `cake build && mocha ./test/mocha/*.coffee` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 795 | `mocha -u tdd` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 794 | `mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 791 | `mocha -R spec tests/` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 788 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 787 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 785 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [edsu/anon](https://github.com/edsu/anon) | 781 | `mocha --colors --reporter spec test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 780 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 814 | `npm run lint && mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 809 | `mocha --reporter spec --bail --check-leaks test/` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 808 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 806 | `./node_modules/.bin/mocha --reporter spec` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 805 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 804 | `mocha --reporter list` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 803 | `mocha --require babel-register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 802 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 801 | `mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 801 | `mocha test` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 800 | `mocha --timeout 30000 --recursive ./tests` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 799 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 806 | `./node_modules/.bin/mocha --reporter spec` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 805 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 804 | `mocha --reporter list` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 803 | `mocha --require babel-register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 802 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 801 | `mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 801 | `mocha test` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 800 | `mocha --timeout 30000 --recursive ./tests` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 799 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 795 | `cake build && mocha ./test/mocha/*.coffee` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 795 | `mocha -u tdd` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 794 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 794 | `mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 791 | `mocha -R spec tests/` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 788 | `mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 775 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 775 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 773 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 772 | `mocha test/index.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 771 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 769 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 769 | `xo && mocha -R spec` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 769 | `mocha --recursive ./test/*_spec.js` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 768 | `mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 767 | `npm run mocha-test test/integration` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 766 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 765 | `mocha test` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 763 | `mocha --harmony --full-trace --check-leaks` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 761 | `mocha --ui tdd --require ./test/__setup` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 761 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 759 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 757 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 756 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 754 | `npm run build && istanbul test _mocha test/test.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 753 | `mocha` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 751 | `mocha` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 750 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 748 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 747 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 746 | `mocha --recursive -s 15 test/` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 746 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 745 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [developit/decko](https://github.com/developit/decko) | 744 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 741 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 737 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 736 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 734 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 733 | `mocha test` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 733 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 733 | `mocha test` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 733 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 732 | `mocha --reporter spec` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 731 | `mocha --no-timeouts` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 729 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 728 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 727 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 725 | `mocha test.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 725 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 723 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 723 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 723 | `mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 721 | `mocha tests/*.mocha.js` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 721 | `npm run lint && npm run mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 719 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 715 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 715 | `npm run bundle && mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 715 | `mocha` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 712 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [typicode/katon](https://github.com/typicode/katon) | 711 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 710 | `mocha -r should --reporter spec test/*.js` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 710 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 664 | `mocha --compilers js:babel-core/register` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 662 | `npm run test-mocha && npm run test-karma` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 661 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 661 | `mocha` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 656 | `mocha` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 655 | `mocha -R spec` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 650 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 650 | `mocha --bail test/` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 649 | `mocha --recursive --compilers js:babel-core/register` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 644 | `./node_modules/.bin/mocha` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 643 | `mocha --compilers js:babel-register src/**/*.spec.js src/*.spec.js` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 643 | `./node_modules/.bin/mocha --bail` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 642 | `jenkins-mocha ./tests/*.js` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 692 | `./bin/selenium-standalone install && mocha` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 692 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 691 | `npm run-script jshint && npm run-script mocha` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 688 | `mocha --reporter spec` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 681 | `mocha ./test/test.js --timeout 1000000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 681 | `mocha` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 679 | `npm run lint && mocha test` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 664 | `mocha --compilers js:babel-core/register` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 662 | `npm run test-mocha && npm run test-karma` | 
| [koajs/static](https://github.com/koajs/static) | 661 | `mocha --harmony --reporter spec --exit` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 661 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 661 | `mocha` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 658 | `mocha --reporter spec` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 658 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 656 | `mocha` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 655 | `./node_modules/.bin/mocha test/integration` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 655 | `mocha -R spec` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 654 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 654 | `mocha` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 650 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 650 | `mocha` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 650 | `mocha --bail test/` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 649 | `mocha --recursive --compilers js:babel-core/register` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 664 | `mocha --compilers js:babel-core/register` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 662 | `npm run test-mocha && npm run test-karma` | 
| [koajs/static](https://github.com/koajs/static) | 661 | `mocha --harmony --reporter spec --exit` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 661 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 661 | `mocha` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 658 | `mocha --reporter spec` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 658 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 656 | `mocha` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 655 | `./node_modules/.bin/mocha test/integration` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 655 | `mocha -R spec` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 654 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 654 | `mocha` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 643 | `mocha --compilers js:babel-register src/**/*.spec.js src/*.spec.js` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 643 | `./node_modules/.bin/mocha --bail` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 642 | `jenkins-mocha ./tests/*.js` | 
| [shime/livedown](https://github.com/shime/livedown) | 640 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 637 | `mocha --reporter spec --bail --check-leaks test/` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 632 | `mocha --reporter spec` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 632 | `mocha --reporter spec` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 628 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 637 | `mocha --reporter spec --bail --check-leaks test/` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 632 | `mocha --reporter spec` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 632 | `mocha --reporter spec` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 628 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [tonyhb/redux-ui](https://github.com/tonyhb/redux-ui) | 628 | `$(npm bin)/mocha  --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 628 | `npm run lint && mocha` | 
| [coinbase/gdax-node](https://github.com/coinbase/gdax-node) | 612 | `mocha --full-trace --ui tdd --bail --reporter spec tests/*.js` | 
| [pocketjoso/specificity-graph](https://github.com/pocketjoso/specificity-graph) | 612 | `node_modules/.bin/mocha test` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 610 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [danielstjules/buddy.js](https://github.com/danielstjules/buddy.js) | 609 | `mocha -R spec spec/unit spec/integration` | 
| [cgross/generator-cg-angular](https://github.com/cgross/generator-cg-angular) | 608 | `mocha` | 
| [hparra/gulp-rename](https://github.com/hparra/gulp-rename) | 607 | `mocha` | 
| [VictorBjelkholm/autochecker](https://github.com/VictorBjelkholm/autochecker) | 607 | `mocha` | 
| [maxkueng/victor](https://github.com/maxkueng/victor) | 607 | `mocha --ui bdd --reporter spec` | 
| [danawoodman/react-fontawesome](https://github.com/danawoodman/react-fontawesome) | 604 | `mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 603 | `mocha` | 
| [phodal/sherlock](https://github.com/phodal/sherlock) | 603 | `mocha --reporter spec` | 
| [Ivshti/linvodb3](https://github.com/Ivshti/linvodb3) | 602 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [rofrischmann/react-look](https://github.com/rofrischmann/react-look) | 601 | `npm run lint && mocha --recursive --compilers js:babel/register` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 601 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require babel-register` | 