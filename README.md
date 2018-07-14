# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:56 07/14/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 42703 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40951 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39219 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29874 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 24346 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24299 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23846 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22786 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19392 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18704 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16575 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16279 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14829 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14248 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13743 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13070 | `mocha --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12960 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12576 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12540 | `./node_modules/.bin/mocha test/` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 12478 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12215 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12206 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11524 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11331 | `nyc grunt mocha-and-karma` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10863 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10833 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10230 | `mocha test/index.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9931 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 9924 | `mocha --harmony` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9908 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9887 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9846 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9453 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9298 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9273 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 9076 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8941 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8907 | `grunt mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8799 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8529 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [amark/gun](https://github.com/amark/gun) | 8468 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8440 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8405 | `mocha --check-leaks -R dot` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8370 | `mocha tests/*.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8347 | `mocha test/src` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8258 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8111 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8012 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7854 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7822 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7813 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7609 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7538 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7488 | `mocha --opts mocha.opts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7441 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7378 | `npm run build && istanbul cover _mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7333 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 7101 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7072 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7048 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6936 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 6863 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6856 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6836 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6605 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6348 | `npm run jshint && mocha test/` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6183 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6172 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6128 | `mocha --exit --require babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6090 | `mocha; jshint *.js lib` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6043 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6013 | `mocha test/test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5940 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5916 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5815 | `mocha tests/node.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5720 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5712 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5675 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5641 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5488 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5475 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5408 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5361 | `mocha --timeout 10000 && npm run lint` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5356 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5207 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5172 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5156 | `mocha --color` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5142 | `standard && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5017 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4924 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4833 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4831 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4814 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4813 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4723 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4723 | `mocha test` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4704 | `gulp build; mocha;` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4687 | `mocha --reporter spec -t 8000` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4672 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4652 | `mocha test` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4570 | `mocha ./test/runner.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4546 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4427 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4426 | `mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4389 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4371 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4322 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4312 | `mocha --recursive && make test` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4307 | `nyc mocha --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4280 | `npm run lint && npm run mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4216 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4127 | `nyc mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4046 | `npm run lint && npm run mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4037 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4029 | `nyc mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3990 | `mocha --require test/babel-hook test/*.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 3990 | `mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3943 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3941 | `npm run lint ; mocha && mocha test/individual` | 
| [tj/ejs](https://github.com/tj/ejs) | 3941 | `mocha --require should --reporter spec` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3927 | `node_modules/.bin/mocha test/tests.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3907 | `mocha --timeout=15000 tests/*.test.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3888 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3880 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3802 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3731 | `mocha --check-leaks --reporter spec --bail` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3711 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3669 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3650 | `standard && mocha --timeout 60000 test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3620 | `npm run build && mocha test/*.test.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3573 | `mocha tests/javascript` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3601 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3582 | `nyc mocha "test/**/*.test.js"` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3573 | `mocha tests/javascript` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3567 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3561 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [expressjs/session](https://github.com/expressjs/session) | 3542 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3526 | `mocha --reporter spec --timeout 3000` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3518 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3515 | `node_modules/.bin/mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 3512 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3496 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3468 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3455 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3444 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3433 | `mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3418 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3403 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3365 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3336 | `NODE_ENV=test mocha test/**/*.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3238 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3237 | `NODE_ENV=test mocha --exit` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3176 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3160 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3160 | `nyc mocha && tsc` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3150 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3135 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3134 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3133 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3123 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3087 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3067 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3055 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3020 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3018 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3009 | `mocha test/*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2992 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2985 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2980 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2979 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2962 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2960 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2935 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2913 | `export TESTING=true; mocha --reporter list` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2785 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2772 | `mocha --require should --reporter spec` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2764 | `npm run mocha && npm run lint` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2750 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2717 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2707 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2696 | `xo && mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2686 | `mocha -R landing test/index` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2681 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2636 | `mocha --timeout 100000` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2620 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2615 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2605 | `mocha --recursive --watch` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2605 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2604 | `mocha-phantomjs ./test/index.html` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2583 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2620 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [mde/ejs](https://github.com/mde/ejs) | 2618 | `mocha --require should --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2605 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2604 | `mocha-phantomjs ./test/index.html` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2583 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2573 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2567 | `nyc mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2548 | `npm run build && cd test && mocha . --reporter dot` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2531 | `mocha test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2530 | `export TESTING=true; mocha --reporter list` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2489 | `nyc mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2467 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2466 | `mocha --reporter=spec test/*-test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2466 | `mocha "test/**/*-test.js"` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2567 | `nyc mocha` | 
| [json5/json5](https://github.com/json5/json5) | 2560 | `nyc --reporter=html --reporter=text mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2555 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2548 | `npm run build && cd test && mocha . --reporter dot` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2531 | `mocha test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2530 | `export TESTING=true; mocha --reporter list` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2512 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2489 | `nyc mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2467 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2466 | `mocha --reporter=spec test/*-test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2466 | `mocha "test/**/*-test.js"` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2438 | `mocha test` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2433 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2417 | `mocha test/src/**/*.unit.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2406 | `mocha test/unit --require mochahook` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2401 | `mocha` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2401 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2392 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2375 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2370 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2370 | `node node_modules/mocha/bin/_mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2344 | `grunt jshint && mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2342 | `mocha --no-colors --reporter spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2337 | `nyc --reporter=html --reporter=text mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2323 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2296 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2291 | `mocha -R spec` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2271 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2266 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2253 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2248 | `mocha test && npm run lint` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2231 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2225 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2220 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2219 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2209 | `mocha test/index.js --reporter dot` | 
| [gajus/swing](https://github.com/gajus/swing) | 2208 | `mocha --compilers js:babel-register` | 
| [noble/noble](https://github.com/noble/noble) | 2156 | `mocha -R spec test/*.js` | 
| [noble/noble](https://github.com/noble/noble) | 2156 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2131 | `mocha --compilers js:babel-register` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2130 | `cross-env BABEL_ENV=test mocha` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2114 | `mocha test/ --no-timeouts` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2103 | `mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2095 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2094 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2083 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2064 | `standard && mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2061 | `mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2043 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2021 | `mocha test/runner.js --reporter spec` | 
| [slate/slate](https://github.com/slate/slate) | 2008 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2004 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1998 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1972 | `nyc npm run _mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1964 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1962 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1956 | `mocha --require=test/test_helper.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1953 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1942 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1940 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1928 | `mocha --reporter spec --timeout 5000` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1925 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1923 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1920 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1920 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1914 | `mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1910 | `mocha && eslint *.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1900 | `./node_modules/.bin/mocha && npm run jshint` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1897 | `mocha --require ./test/common --growl test/expect.js` | 
| [then/promise](https://github.com/then/promise) | 1890 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1887 | `npm run lint && mocha -R dot && npm run cover` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1883 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1873 | `mocha tests.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1869 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [kach/nearley](https://github.com/kach/nearley) | 1858 | `mocha test/*.test.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 1851 | `npm run lint && npm run mocha` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1847 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1839 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1826 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1817 | `mocha --reporter spec && npm run test-typescript` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1807 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1799 | `npm run mocha && npm run karma` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1792 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1790 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1785 | `npm run lint && mocha --reporter spec test/*.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1781 | `mocha -R spec spec spec/reporters` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1769 | `mocha test` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1765 | `mocha && npm run lint` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1761 | `mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1759 | `mocha --reporter spec test/*.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1759 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1751 | `mocha --reporter spec --grep .` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1745 | `mocha tests --compilers js:babel-core/register` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1742 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1739 | `npm run lint && npm run mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1725 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1723 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1722 | `mocha test/**/*.js` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1722 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1721 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1717 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1709 | `mocha test -u bdd -R spec` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1706 | `mocha --compilers js:babel-register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1706 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1697 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1696 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1677 | `npm run lint && mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1672 | `xo && mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1671 | `mocha test --timeout 600000` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1670 | `mocha ./test/basic.js -t 5000` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1667 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1660 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1657 | `mocha test/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1649 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1645 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1573 | `mocha compiled_tests/` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1571 | `mocha` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1566 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1560 | `./node_modules/mocha/bin/mocha -R spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1545 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1539 | `npm run test:lint && npm run test:mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1537 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1533 | `eslint --cache . && tsc && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1532 | `mocha tests.js` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1529 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1528 | `mocha test/setup.js test/spec/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1533 | `eslint --cache . && tsc && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1532 | `mocha tests.js` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1529 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1528 | `mocha test/setup.js test/spec/*.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1523 | `standard "./src/*.js" && mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1517 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1498 | `mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1497 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1497 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1495 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1492 | `mocha --check-leaks --reporter spec --bail` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1492 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1490 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1485 | `node_modules/.bin/mocha --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1483 | `nyc mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1481 | `mocha -R spec` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1480 | `mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1498 | `mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1497 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1497 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1495 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1492 | `mocha --check-leaks --reporter spec --bail` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1492 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1490 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1485 | `node_modules/.bin/mocha --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1483 | `nyc mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1481 | `mocha -R spec` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1480 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1473 | `nyc npm run mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1464 | `mocha test/**/*.spec.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1459 | `mocha --recursive` | 
| [samccone/drool](https://github.com/samccone/drool) | 1452 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1447 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1473 | `nyc npm run mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1464 | `mocha test/**/*.spec.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1459 | `mocha --recursive` | 
| [samccone/drool](https://github.com/samccone/drool) | 1452 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1447 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1439 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1410 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1400 | `mocha --timeout 10000 ./tests/lib.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1393 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1392 | `nyc mocha --timeout=20000 test.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1386 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1383 | `mocha -R spec test/*.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1378 | `istanbul cover _mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1374 | `./node_modules/mocha/bin/mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1358 | `cross-env NODE_ENV=test nyc mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1351 | `npm run build && mocha -r should` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1349 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1346 | `mocha --check-leaks --require @babel/register` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1345 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [electron/devtron](https://github.com/electron/devtron) | 1336 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1332 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1325 | `mocha test/unit` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1320 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [retejs/rete](https://github.com/retejs/rete) | 1317 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1316 | `mocha --opts test/opts/mocha.opts` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1313 | `mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1311 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1311 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1311 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1307 | `./node_modules/.bin/mocha test` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1306 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1305 | `mocha-phantomjs tests/index.html` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1305 | `mocha --recursive` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1304 | `mocha` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1303 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1295 | `eslint src && mocha && karma start --single-run` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1291 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1291 | `mocha spec/exec.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1289 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1288 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1277 | `TEST=all mocha` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1275 | `mocha tests/test-*` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1275 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1273 | `mocha --reporter dot` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1263 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1258 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1257 | `mocha --timeout 60000 test/` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1251 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1249 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1249 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1243 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1242 | `mocha test/*.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1239 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1239 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1237 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1236 | `mocha tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1234 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1231 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1220 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1198 | `mocha --check-leaks --reporter spec --bail test/` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1197 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1195 | `mocha -R spec ./test/unit/**` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1194 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1194 | `mocha ./test/test*.js --reporter spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1194 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1193 | `mocha test` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [normalize/mz](https://github.com/normalize/mz) | 1187 | `mocha --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1186 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1181 | `npm run lint && npm run mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1181 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1178 | `npm run lint && npm run mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1178 | `mocha --recursive test/bin` | 
| [variety/variety](https://github.com/variety/variety) | 1169 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1168 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1166 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1163 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1162 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1161 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1161 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1159 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1169 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1168 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1166 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1165 | `npm run prepublishOnly && mocha test/test.js` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1163 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1162 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1161 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1161 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1159 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1156 | `mocha --recursive test` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1153 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1150 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1148 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1145 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1140 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1140 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1135 | `mocha --compilers js:babel-core/register` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1134 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1122 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1114 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1114 | `mocha $(find test -name '*.test.js')` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1113 | `mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1106 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1105 | `xo && mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1104 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1103 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1102 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1100 | `istanbul cover _mocha test/*.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1098 | `mocha test/*` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1096 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1095 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1094 | `NODE_PATH=. mocha **/*.spec.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1092 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1089 | `mocha --check-leaks -t 20000` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1085 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1081 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1078 | `istanbul test _mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1078 | `mocha --compilers js:babel-register` | 
| [router5/router5](https://github.com/router5/router5) | 1078 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1076 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1062 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1053 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [electron/asar](https://github.com/electron/asar) | 1051 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1047 | `mocha --recursive --bail --reporter spec test` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1045 | `mocha test/tests.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1041 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1040 | `npm run mocha:istanbul` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1039 | `webpack && mocha test/unit` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1038 | `mocha --reporter spec --timeout 3000` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1037 | `mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1036 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1028 | `mocha --reporter spec --bail --check-leaks test/` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1022 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 995 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 990 | `mocha --async-only` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 990 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 982 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 979 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 978 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 973 | `npm run rollup-cjs && mocha test/test.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 972 | `mocha -R list` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 965 | `mocha --reporter spec` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 962 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 965 | `mocha --reporter spec` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 962 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 955 | `npm-run-all test:jest test:server:mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 954 | `mocha --timeout 30000 --recursive ./tests` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 947 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 939 | `mocha "client.test" --compilers js:babel-register` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 930 | `mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 929 | `mocha --compilers js:babel-register test/*.js` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 926 | `mocha -R spec` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 925 | `mocha --reporter spec --bail --check-leaks test/` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 922 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 921 | `mocha test --compilers js:babel-core/register` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 918 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 916 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 915 | `mocha ./test/index.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 907 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 905 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 902 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 902 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 898 | `mocha tests` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 889 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 888 | `mocha spec/*.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 883 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 883 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 883 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 889 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 888 | `mocha spec/*.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 883 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 883 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 883 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 879 | `node_modules/.bin/mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 879 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 877 | `mocha -t 600000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 876 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 873 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 868 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 865 | `mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 847 | `standard && standard ./bin/* && mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 841 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 840 | `./node_modules/.bin/mocha --reporter spec` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 839 | `istanbul cover -- _mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 837 | `istanbul cover _mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 837 | `mocha test` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 836 | `mocha --reporter spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 836 | `mocha --check-leaks -t 20000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 833 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 823 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 822 | `mocha && ember test` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 840 | `./node_modules/.bin/mocha --reporter spec` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 839 | `istanbul cover -- _mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 837 | `istanbul cover _mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 837 | `mocha test` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 836 | `mocha --reporter spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 836 | `mocha --check-leaks -t 20000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 833 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 832 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 823 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 823 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 822 | `mocha && ember test` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 820 | `mocha --reporter list` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 819 | `mocha --reporter spec --bail --check-leaks test/` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 819 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 819 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 816 | `npm run lint && mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 816 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 812 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 809 | `mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 807 | `nyc --check-coverage mocha test/*.test.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 806 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 805 | `mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 804 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 804 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 803 | `mocha test/index.js` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 803 | `mocha --require babel-register` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 802 | `cake build && mocha ./test/mocha/*.coffee` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 802 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 802 | `mocha --recursive ./test/*_spec.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 800 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 797 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 796 | `mocha --async-only` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 795 | `mocha -u tdd` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 794 | `mocha test` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 793 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 793 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 789 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 786 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 785 | `mocha --colors --reporter spec test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 784 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 781 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 781 | `mocha --harmony --full-trace --check-leaks` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 776 | `mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 776 | `npm run build && istanbul test _mocha test/test.js` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 776 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 776 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 775 | `xo && mocha -R spec` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 774 | `npm run mocha-test test/integration` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 774 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 772 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 772 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 752 | `mocha test` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 750 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 749 | `mocha --no-timeouts` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 749 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 749 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 740 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 740 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 739 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 735 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 735 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 735 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 734 | `mocha test` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 735 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 735 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 735 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 734 | `mocha test` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 731 | `npm run lint && npm run mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 731 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 730 | `mocha test.js` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 729 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 728 | `mocha tests/*.mocha.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 725 | `mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 724 | `mocha` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 723 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [scality/S3](https://github.com/scality/S3) | 722 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 