# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:47 10/07/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43777 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41429 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40456 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30408 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 27078 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24697 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 24664 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23770 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20278 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19301 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14407 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14253 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14023 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13421 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13020 | `mocha --globals document test` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12472 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12212 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11727 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11569 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10774 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10454 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10361 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10348 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10156 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10125 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10107 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 9686 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9451 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9253 | `mocha -b -r esm` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 9154 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 9686 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9471 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9451 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9300 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9253 | `mocha -b -r esm` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 9154 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9081 | `grunt mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8962 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 8927 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8899 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8619 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8558 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8476 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8356 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8291 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8251 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8120 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7946 | `npm run eslint && npm run mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7899 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7775 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7554 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7476 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7442 | `mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7439 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7424 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [aui/art-template](https://github.com/aui/art-template) | 7422 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7359 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7301 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [almende/vis](https://github.com/almende/vis) | 7172 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7136 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6972 | `mocha $HARMONY_OPTS` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 6946 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6843 | `mocha; jshint *.js lib` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6826 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6701 | `mocha --exit --require @babel/register` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6656 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6592 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6375 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6349 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6282 | `npm run test:mocha:src` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6083 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6060 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6054 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6021 | `mocha tests/node.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5938 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5899 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5825 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5817 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5801 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5777 | `mocha && eslint lib/**` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5750 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5504 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5495 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5482 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5416 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5273 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5230 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5189 | `mocha src/**/*Tests.js --harmony` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5172 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5153 | `mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5146 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5030 | `gulp lint && mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4924 | `mocha test` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4873 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4813 | `gulp build; mocha;` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4797 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4793 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4767 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4760 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4699 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4683 | `./node_modules/.bin/mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4642 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4573 | `npm run lint && npm run mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4571 | `mocha ./test/runner.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4551 | `nyc mocha --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4544 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4454 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4446 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4417 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4404 | `nyc mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4337 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4281 | `mocha -R spec src` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4206 | `mocha -R spec ./test --recursive` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4189 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4188 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4188 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4146 | `mocha --timeout=15000 tests/*.test.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 4106 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [teambit/bit](https://github.com/teambit/bit) | 4106 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4096 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4091 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4083 | `npm run lint ; mocha && mocha test/individual` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4059 | `mocha --require test/babel-hook test/*.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4041 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [tj/ejs](https://github.com/tj/ejs) | 4019 | `mocha --require should --reporter spec` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3985 | `mocha --check-leaks --reporter spec --bail` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3954 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3903 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3870 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3808 | `nyc mocha "test/**/*.test.js"` | 
| [erming/shout](https://github.com/erming/shout) | 3799 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3773 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3773 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 3729 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3727 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3723 | `NODE_ENV=test mocha --exit` | 
| [primus/primus](https://github.com/primus/primus) | 3687 | `npm run build && mocha test/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3676 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3665 | `npm run jshint && npm run mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3598 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3595 | `NODE_ENV=test mocha test/**/*.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3577 | `mocha tests/javascript` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3575 | `node_modules/.bin/mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3553 | `mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3553 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3553 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3521 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3471 | `node_modules/.bin/mocha test/lib/` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3471 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3462 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3444 | `mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3376 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3362 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3322 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3308 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3273 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3255 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3197 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3180 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3171 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3168 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3149 | `./node_modules/.bin/mocha test/test.*.js` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3145 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3141 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3141 | `mocha test/*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3139 | `mocha` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3136 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3131 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3121 | `mocha test/index.js && npm run demo` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3093 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3087 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3086 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3064 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3059 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2894 | `npm run mocha && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2877 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2854 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [mde/ejs](https://github.com/mde/ejs) | 2845 | `mocha --require should --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2830 | `istanbul cover _mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2830 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2825 | `mocha test-node` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2824 | `mocha -R spec spec spec/reporters` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2820 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2818 | `mocha --require babel-register --recursive spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2811 | `node_modules/.bin/mocha --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2790 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2778 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2773 | `mocha --require should --reporter spec` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2765 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [css/csso](https://github.com/css/csso) | 2743 | `mocha --reporter dot` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2790 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2778 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2773 | `mocha --require should --reporter spec` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2767 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2765 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [css/csso](https://github.com/css/csso) | 2743 | `mocha --reporter dot` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2730 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [tj/should.js](https://github.com/tj/should.js) | 2716 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2707 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2689 | `npm run build && cd test && mocha . --reporter dot` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2668 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2663 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2660 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2653 | `mocha --timeout 100000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2642 | `mocha --recursive --watch` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2724 | `xo && mocha` | 
| [tj/should.js](https://github.com/tj/should.js) | 2716 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2707 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2689 | `npm run build && cd test && mocha . --reporter dot` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2668 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2663 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2660 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2653 | `mocha --timeout 100000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2642 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2624 | `nyc mocha --timeout=10000` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2613 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2611 | `mocha-phantomjs ./test/index.html` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2593 | `nyc mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2574 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2569 | `mocha "test/**/*-test.js"` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2525 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2514 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2512 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2511 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2505 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2482 | `mocha --reporter=spec test/*-test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2482 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2481 | `mocha test/src/**/*.unit.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2470 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2448 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2420 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2418 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2401 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2375 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2373 | `mocha test/index.js --reporter dot` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2373 | `mocha test && npm run lint` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2356 | `mocha -R spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2354 | `grunt jshint && mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2344 | `mocha && eslint .` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2311 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2290 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2284 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [noble/noble](https://github.com/noble/noble) | 2282 | `mocha -R spec test/*.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2281 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2130 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2126 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2117 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2113 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2097 | `mocha test/runner.js --reporter spec` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2092 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2065 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2063 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2054 | `mocha && eslint *.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2048 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [pahen/madge](https://github.com/pahen/madge) | 2040 | `npm run lint && npm run mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2010 | `mocha --compilers js:babel-core/register __tests__` | 
| [slate/slate](https://github.com/slate/slate) | 1999 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1995 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1994 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1981 | `./node_modules/.bin/mocha && npm run jshint` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1972 | `mocha --require=test/test_helper.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1972 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1970 | `mocha --reporter spec --timeout 5000` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1960 | `mocha -c test/index.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1946 | `mocha test/*.test.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1945 | `npm run lint && mocha -R dot && npm run cover` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1943 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [then/promise](https://github.com/then/promise) | 1941 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1937 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1935 | `mocha` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1931 | `mocha --require ./test/common --growl test/expect.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1924 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1915 | `npm run mocha && npm run karma` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1910 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1904 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1893 | `mocha --compilers js:babel-register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1887 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1884 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1877 | `mocha tests.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1869 | `mocha --reporter spec && npm run test-typescript` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1852 | `mocha --reporter spec test/*.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1852 | `mocha && npm run lint` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1758 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1754 | `mocha ./test/basic.js -t 5000` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1747 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1734 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1728 | `mocha test/**/*_test.js --bail` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1723 | `mocha test` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1715 | `mocha compiled_tests/` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1706 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1690 | `mocha test/*.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1758 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1754 | `mocha ./test/basic.js -t 5000` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1747 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1734 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1729 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1728 | `mocha test/**/*_test.js --bail` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1723 | `mocha test` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1720 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1720 | `npm run lint && npm run mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1719 | `./node_modules/.bin/mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1715 | `mocha compiled_tests/` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1714 | `mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1708 | `npm run lint && mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1706 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1703 | `mocha test --timeout 600000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1698 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1694 | `mocha test/* --reporter spec` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1690 | `mocha test/*.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1680 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1672 | `mocha` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1671 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1671 | `mocha test/setup.js test/spec/*.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1669 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1662 | `xo && mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1655 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1644 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1642 | `mocha && size-limit` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1641 | `eslint --cache . && tsc && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1624 | `mocha tests.js` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1622 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1617 | `mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1611 | `standard "./src/*.js" && mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1608 | `mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1607 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1591 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1585 | `./node_modules/mocha/bin/mocha -R spec` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1581 | `mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1577 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1577 | `mocha --check-leaks --reporter spec --bail` | 
| [retejs/rete](https://github.com/retejs/rete) | 1571 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1569 | `mocha --reporter spec` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1581 | `mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1577 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1577 | `mocha --check-leaks --reporter spec --bail` | 
| [retejs/rete](https://github.com/retejs/rete) | 1571 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1569 | `mocha --reporter spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1565 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1556 | `mocha test.js` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1555 | `./node_modules/.bin/mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1554 | `nyc mocha --timeout=20000 test.js` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1543 | `npm run test:lint && npm run test:mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1542 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1539 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1530 | `node_modules/.bin/mocha --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1527 | `nyc mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1525 | `mocha --recursive` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1524 | `TEST=all mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1522 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1520 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1515 | `mocha -u tdd` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1485 | `mocha test/**/*.spec.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1482 | `mocha -R spec` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1448 | `mocha --check-leaks --require @babel/register` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1447 | `mocha test.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1446 | `mocha test/unit` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1441 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1439 | `NODE_ENV=test mocha tests/*.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1434 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1431 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1425 | `mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1422 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1417 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1413 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1411 | `npm run lint && mocha && karma start --single-run` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1407 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1399 | `mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1398 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1417 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1413 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1411 | `npm run lint && mocha && karma start --single-run` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1407 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1403 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1399 | `mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1398 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1392 | `mocha -R spec ./test/unit/**` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1392 | `istanbul cover _mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1383 | `npm run build && mocha -r should` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1383 | `mocha tests/test-*` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1382 | `./node_modules/mocha/bin/mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1379 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1379 | `mocha ./test/test*.js --reporter spec` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1372 | `mocha --opts test/opts/mocha.opts` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1367 | `standard && istanbul cover _mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1367 | `standard && istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1365 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1361 | `mocha --reporter dot` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1359 | `cross-env NODE_ENV=test nyc mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1349 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1347 | `mocha --recursive` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1346 | `npm run lint && npm run mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1338 | `./node_modules/.bin/mocha test` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1338 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1335 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1333 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1333 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1327 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1320 | `NODE_PATH=. mocha **/*.spec.js` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1316 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1314 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1307 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1305 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1303 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1303 | `mocha-phantomjs tests/index.html` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1299 | `mocha` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1297 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1296 | `mocha spec/exec.js` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1295 | `mocha --recursive test/bin` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1291 | `mocha --timeout 60000 test/` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1289 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1288 | `mocha --check-leaks --reporter spec --bail test/` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1280 | `mocha --recursive test` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1278 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1275 | `mocha test/*.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1274 | `npm run prepublishOnly && mocha test/test.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1270 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1265 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1264 | `mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1263 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1260 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1253 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1252 | `mocha tests` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1249 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1247 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1243 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1242 | `mocha src/test.js` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1239 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1238 | `npm run lint && npm run mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1236 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1232 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1231 | `istanbul test _mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1229 | `mocha --compilers js:babel-core/register` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1227 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1221 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1221 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1215 | `mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1214 | `mocha test/test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1211 | `mocha --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1210 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [variety/variety](https://github.com/variety/variety) | 1210 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1209 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1208 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1207 | `node ./node_modules/mocha/bin/mocha tests` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1207 | `webpack && npm run lint && npm run mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1187 | `npm run lint && mocha --require @babel/register` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1185 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1183 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1182 | `npm run mocha:istanbul` | 
| [router5/router5](https://github.com/router5/router5) | 1175 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1169 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1167 | `mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1166 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1156 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1151 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1156 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1151 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1140 | `mocha --timeout 20000` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1136 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1135 | `istanbul cover _mocha test/*.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1134 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1133 | `xo && mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1132 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1131 | `mocha $(find test -name '*.test.js') --exit` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1126 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1106 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1097 | `webpack && mocha test/unit` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1090 | `mocha test --compilers js:babel-core/register` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1087 | `mocha --check-leaks -t 20000` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1086 | `mocha --reporter spec --bail --check-leaks test/` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1085 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1084 | `npm-run-all test:jest test:server:mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1082 | `mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1080 | `mocha --compilers js:babel-register` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1080 | `mocha` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1080 | `mocha` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1072 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1070 | `mocha --recursive --bail --reporter spec test` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1087 | `mocha --check-leaks -t 20000` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1086 | `mocha --reporter spec --bail --check-leaks test/` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1085 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1084 | `npm-run-all test:jest test:server:mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1082 | `mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1080 | `mocha --compilers js:babel-register` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1080 | `mocha` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1080 | `mocha` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1072 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1070 | `mocha --recursive --bail --reporter spec test` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1070 | `standard && mocha -b` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1068 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1063 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1063 | `mocha test/tests.js` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1013 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1008 | `mocha --recursive test/unit/` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 993 | `mocha -R list` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 991 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 986 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 985 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 985 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 985 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 979 | `mocha` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 993 | `mocha -R list` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 992 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 991 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 986 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 985 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 985 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 985 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 979 | `mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 973 | `mocha --reporter spec` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 970 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 964 | `mocha --reporter spec --bail --check-leaks test/` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 963 | `mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 963 | `mocha test` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 959 | `mocha "client.test" --compilers js:babel-register` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 957 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 953 | `mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 952 | `mocha --compilers js:babel-register test/*.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 948 | `npm run lint && mocha -R spec` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 947 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 943 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 942 | `mocha --timeout 5000` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 929 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 929 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 929 | `mocha spec/*.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 923 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 917 | `mocha test` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 916 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 916 | `mocha -t 600000` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 903 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 903 | `./node_modules/.bin/mocha -R spec` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 903 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 902 | `nyc --check-coverage mocha test/*.test.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 902 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 901 | `mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 898 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 895 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 892 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 890 | `nyc mocha specs` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 889 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 889 | `node_modules/.bin/mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 887 | `./node_modules/.bin/mocha --globals angular,require` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 886 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 898 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 895 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 892 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 891 | `mocha --recursive ./test/*_spec.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 891 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 890 | `nyc mocha specs` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 889 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 889 | `node_modules/.bin/mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 888 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 888 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 887 | `./node_modules/.bin/mocha --globals angular,require` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 886 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 886 | `mocha test --compilers js:babel-register` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 880 | `npm run lint && npm run mocha:no-functional` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 878 | `istanbul cover -- _mocha --reporter spec` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 877 | `mocha -t 5000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 877 | `standard && standard ./bin/* && mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 875 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 871 | `mocha --timeout 200000` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 870 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 869 | `node_modules/.bin/mocha test/spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 866 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 866 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 862 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 858 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 857 | `eslint test && mocha --compilers js:babel/register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 854 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 845 | `mocha --check-leaks -t 20000` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 843 | `mocha --compilers js:@babel/register --reporter spec test/**/*.test.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 842 | `npm run lint && mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 842 | `mocha test` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 842 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 834 | `mocha --reporter spec --bail --check-leaks test/` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 834 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 833 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 832 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 831 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 830 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 827 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 826 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 826 | `mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 826 | `mocha && ember test` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 778 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 774 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 769 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 769 | `nyc mocha` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 765 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 765 | `mocha --recursive -s 15 test/` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 764 | `mocha --ui tdd --require ./test/__setup` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 764 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 763 | `mocha test` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 761 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 799 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 797 | `npm run mocha-test test/integration` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 796 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 796 | `mocha -R spec tests/` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 794 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 792 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 792 | `mocha -u tdd` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 792 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 790 | `mocha -r should --reporter spec test/*.js` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 787 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 787 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 785 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [developit/decko](https://github.com/developit/decko) | 784 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 782 | `xo && mocha -R spec` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 792 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 792 | `mocha -u tdd` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 792 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 790 | `mocha -r should --reporter spec test/*.js` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 787 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 787 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 785 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [developit/decko](https://github.com/developit/decko) | 784 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 782 | `xo && mocha -R spec` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 779 | `mocha test` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 778 | `mocha --no-timeouts` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 749 | `mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 748 | `npm run lint && npm run mocha` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 747 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 746 | `babel-node node_modules/.bin/_mocha -- test` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 746 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 741 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 740 | `mocha --harmony tests/**` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 739 | `nyc mocha` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 739 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 738 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 738 | `npm run-script jshint && npm run-script mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 735 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 735 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 734 | `mocha` | 