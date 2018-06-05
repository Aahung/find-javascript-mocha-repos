# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:12 06/05/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 41922 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40650 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38616 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29619 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24075 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23371 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 22724 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22338 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 18985 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18406 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16301 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15896 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14390 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14124 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13475 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12736 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12487 | `mocha 'test/**/*.spec.js'` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 12334 | `mocha --reporter spec` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12314 | `./node_modules/.bin/mocha test/` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12151 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12092 | `mocha --reporter spec test/*-test.js` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11869 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11144 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11016 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10554 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10416 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9979 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9719 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9710 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9688 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9660 | `set NODE_ENV=test && mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9234 | `mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9158 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 8941 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8843 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8780 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 8741 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8478 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8373 | `mocha test/test.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8336 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8295 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8221 | `grunt clean:test && mocha --exit` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8218 | `mocha test/src` | 
| [amark/gun](https://github.com/amark/gun) | 8165 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8032 | `mocha tests/*.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8016 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7943 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7745 | `npm run eslint && npm run mocha` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7745 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7587 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7569 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7513 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7502 | `./node_modules/.bin/mocha test` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7438 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7333 | `npm run build && istanbul cover _mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7070 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7038 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6876 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 6875 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6863 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6813 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6778 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6700 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6606 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6307 | `npm run lint -s && npm run mocha -s` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6145 | `npm run jshint && mocha test/` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6126 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6111 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 6111 | `npm run build-cli && mocha` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 6087 | `mocha test node-test --recursive` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6029 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5938 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5868 | `mocha --exit --require babel-core/register` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5835 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5833 | `mocha test/test.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5725 | `mocha tests/node.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5672 | `mocha; jshint *.js lib` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5619 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5597 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5522 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5404 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5381 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5340 | `mocha` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5278 | `mocha --timeout 10000 && npm run lint` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5258 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5161 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5153 | `mocha --color` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5082 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4953 | `standard && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4932 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4932 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4897 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4815 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4717 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4694 | `mocha -R spec 'tests/app'` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4681 | `mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4671 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4650 | `gulp build; mocha;` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4617 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4597 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4555 | `mocha ./test/runner.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4541 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4497 | `mocha test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4496 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4416 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4355 | `mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4323 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4322 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4221 | `mocha -R spec ./test --recursive` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4219 | `NODE_ENV=test mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4203 | `mocha --recursive && make test` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4177 | `nyc mocha --exit` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4099 | `nyc mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4098 | `npm run lint && npm run mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3969 | `mocha --require test/babel-hook test/*.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3943 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3914 | `mocha -R spec ./test` | 
| [tj/ejs](https://github.com/tj/ejs) | 3897 | `mocha --require should --reporter spec` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3883 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3875 | `export TESTING=true; mocha --reporter list` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3865 | `npm run lint && npm run mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3860 | `npm run lint ; mocha && mocha test/individual` | 
| [erming/shout](https://github.com/erming/shout) | 3803 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3796 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3785 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3769 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3695 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3662 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3618 | `standard && mocha --timeout 60000 test/test.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3605 | `mocha --check-leaks --reporter spec --bail` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3600 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [primus/primus](https://github.com/primus/primus) | 3589 | `npm run build && mocha test/*.test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3560 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3497 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3482 | `node_modules/.bin/mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3468 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3464 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3454 | `nyc mocha "test/**/*.test.js"` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3448 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3430 | `node_modules/.bin/mocha test/lib/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3429 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3421 | `mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 3420 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3404 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3385 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3354 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3350 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3332 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3276 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3276 | `node_modules/.bin/mocha test/tests.js` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 3088 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3081 | `nyc mocha && tsc` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3042 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3034 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3005 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3002 | `NODE_ENV=test mocha --exit` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2991 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2984 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2938 | `mocha test/index.js && npm run demo` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2873 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2854 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2846 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2838 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3005 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3002 | `NODE_ENV=test mocha --exit` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2991 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2984 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2975 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2953 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2940 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2938 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2898 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2895 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2873 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2865 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2854 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2846 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2841 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2838 | `mocha -R spec --recursive src/test` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2838 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2810 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2791 | `istanbul cover _mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2776 | `mocha --require should --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2772 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2766 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2762 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2759 | `mocha --opts mocha.opts` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2757 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2741 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2741 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2739 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2734 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2723 | `mocha` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2712 | `export TESTING=true; mocha --reporter list` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2711 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2695 | `npm run mocha && npm run lint` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2692 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2678 | `xo && mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2672 | `mocha --require babel-register --recursive spec` | 
| [css/csso](https://github.com/css/csso) | 2669 | `mocha --reporter dot` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2660 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2660 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2625 | `mocha --timeout 100000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2602 | `mocha-phantomjs ./test/index.html` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2596 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2589 | `mocha --recursive --watch` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2587 | `node_modules/.bin/mocha --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2557 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2545 | `mocha -R landing test/index` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2544 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2542 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2528 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2525 | `export TESTING=true; mocha --reporter list` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2507 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2490 | `npm run build && cd test && mocha . --reporter dot` | 
| [mde/ejs](https://github.com/mde/ejs) | 2482 | `mocha --require should --reporter spec` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2458 | `mocha --reporter=spec test/*-test.js` | 
| [json5/json5](https://github.com/json5/json5) | 2451 | `nyc --reporter=html --reporter=text mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2445 | `nyc mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2425 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2412 | `mocha test` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2407 | `mocha test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2406 | `mocha "test/**/*-test.js"` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2406 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2402 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2388 | `mocha test/src/**/*.unit.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2373 | `mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2354 | `mocha test/unit --require mochahook` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2354 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2349 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2341 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2338 | `grunt jshint && mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2328 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2299 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2294 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2286 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2257 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2252 | `mocha -R spec` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2244 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2240 | `nyc --reporter=html --reporter=text mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2234 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1961 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1958 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1948 | `mocha --require=test/test_helper.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 1937 | `mocha --require babel-core/register './specs/**/*.spec.js'` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1922 | `mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1921 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1917 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1916 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1914 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1907 | `mocha --reporter spec --timeout 5000` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1906 | `mocha --compilers js:babel-core/register __tests__` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1898 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1896 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1880 | `mocha --require ./test/common --growl test/expect.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1879 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2083 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2065 | `mocha --compilers js:babel-register` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2036 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [Qix-/color](https://github.com/Qix-/color) | 2018 | `mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2014 | `standard && mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2008 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2004 | `mocha test/index.js --reporter dot` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1997 | `mocha test/ --no-timeouts` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1977 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1967 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1961 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1958 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1948 | `mocha --require=test/test_helper.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 1937 | `mocha --require babel-core/register './specs/**/*.spec.js'` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1922 | `mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1921 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1917 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1916 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1914 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1907 | `mocha --reporter spec --timeout 5000` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1898 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1896 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1880 | `mocha --require ./test/common --growl test/expect.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1879 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1875 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1871 | `nyc npm run _mocha` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1865 | `mocha tests.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1864 | `mocha && eslint *.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1857 | `./node_modules/.bin/mocha && npm run jshint` | 
| [then/promise](https://github.com/then/promise) | 1856 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1849 | `npm run lint && mocha -R dot && npm run cover` | 
| [kach/nearley](https://github.com/kach/nearley) | 1834 | `mocha test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1828 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1815 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1812 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1811 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1807 | `mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1801 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1798 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1783 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1780 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1779 | `mocha --reporter spec && npm run test-typescript` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1777 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1768 | `npm run lint && mocha --reporter spec test/*.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1766 | `npm run mocha && npm run karma` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1764 | `mocha -R spec spec spec/reporters` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1754 | `mocha test` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [pahen/madge](https://github.com/pahen/madge) | 1736 | `npm run lint && npm run mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1674 | `xo && mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1657 | `mocha test -u bdd -R spec` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1651 | `npm run lint && mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1647 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1642 | `mocha test --timeout 600000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1640 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1638 | `mocha test/*.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1635 | `mocha ./test/basic.js -t 5000` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1634 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1628 | `mocha --expose-gc --slow 300` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1620 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1619 | `mocha tests/test.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1619 | `mocha --compilers js:babel-register` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1615 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1610 | `mocha && size-limit` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1594 | `npm run lint && npm run mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1592 | `mocha test/* --reporter spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1587 | `mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1551 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1545 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1542 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1527 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1594 | `npm run lint && npm run mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1592 | `mocha test/* --reporter spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1587 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1579 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1551 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1545 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1542 | `./node_modules/mocha/bin/mocha -R spec` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1505 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1503 | `npm run test:lint && npm run test:mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1496 | `eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1489 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1481 | `mocha -u tdd` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1480 | `node_modules/.bin/mocha --recursive` | 
| [zeit/ms](https://github.com/zeit/ms) | 1477 | `mocha tests.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1473 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1472 | `mocha -R spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1469 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1468 | `mocha test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1465 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1465 | `mocha test/setup.js test/spec/*.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1457 | `mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1457 | `mocha test/**/*.spec.js` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1481 | `mocha -u tdd` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1480 | `node_modules/.bin/mocha --recursive` | 
| [zeit/ms](https://github.com/zeit/ms) | 1477 | `mocha tests.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1473 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1472 | `mocha -R spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1469 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1468 | `mocha test.js` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1465 | `nyc mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1465 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1465 | `mocha test/setup.js test/spec/*.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1457 | `mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1457 | `mocha test/**/*.spec.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1451 | `mocha --check-leaks --reporter spec --bail` | 
| [samccone/drool](https://github.com/samccone/drool) | 1449 | `mocha test/tests.js --timeout=10000` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1445 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1441 | `mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1437 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1384 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1369 | `./node_modules/mocha/bin/mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1364 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1358 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1356 | `istanbul cover _mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1354 | `mocha test` | 
| [noble/bleno](https://github.com/noble/bleno) | 1350 | `mocha -R spec test/*.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1349 | `cross-env NODE_ENV=test nyc mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1369 | `./node_modules/mocha/bin/mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1364 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1358 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1356 | `istanbul cover _mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1354 | `mocha test` | 
| [noble/bleno](https://github.com/noble/bleno) | 1350 | `mocha -R spec test/*.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1349 | `cross-env NODE_ENV=test nyc mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1329 | `npm run build && mocha -r should` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1328 | `mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1320 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1315 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1314 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1298 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1297 | `mocha --check-leaks --require @babel/register` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1294 | `mocha-phantomjs tests/index.html` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1292 | `nyc mocha --timeout=20000 test.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1291 | `./node_modules/.bin/mocha test` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1291 | `istanbul cover _mocha test -- --timeout 20000` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1280 | `mocha --recursive` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1279 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1278 | `mocha` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1277 | `mocha spec/exec.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1269 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1264 | `mocha test/unit` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1269 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1264 | `mocha test/unit` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1262 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1251 | `eslint src && mocha && karma start --single-run` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1250 | `mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1249 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1247 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1242 | `mocha --timeout 60000 test/` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1237 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1237 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1236 | `mocha test/*.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1229 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1229 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1229 | `mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1228 | `standard && istanbul cover _mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1227 | `mocha tests` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1226 | `mocha --reporter dot` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1224 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1223 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1218 | `mocha tests/test-*` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1217 | `mocha test/test.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1226 | `mocha --reporter dot` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1224 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1223 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1218 | `mocha tests/test-*` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1217 | `mocha test/test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1213 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1210 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1205 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1193 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1190 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1189 | `node ./node_modules/mocha/bin/mocha tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1188 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1187 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1187 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1187 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1185 | `mocha test` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1185 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1184 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1177 | `mocha src/test.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1172 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1170 | `mocha --reporter spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1166 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1161 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1160 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1160 | `npm run lint && npm run mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1160 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1157 | `mocha --check-leaks --reporter spec --bail test/` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1155 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1145 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1144 | `TEST=all mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1138 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1137 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1136 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1133 | `mocha -R spec ./test/unit/**` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1131 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1128 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1123 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1117 | `NODE_ENV=test mocha tests/*.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1115 | `mocha ./test/test*.js --reporter spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1113 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1110 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1110 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1108 | `npm run prepublishOnly && mocha test/test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1105 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1103 | `mocha --recursive test` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1102 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1102 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1101 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1098 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1098 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1098 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1097 | `mocha $(find test -name '*.test.js')` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1090 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1089 | `xo && mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1086 | `npm run lint && npm run mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1083 | `mocha test/*` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1082 | `mocha --check-leaks -t 20000` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1080 | `istanbul cover _mocha test/*.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1079 | `NODE_PATH=. mocha **/*.spec.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1079 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1078 | `nodeunit test; mocha test` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1077 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1076 | `mocha --compilers js:babel-core/register` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1073 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1073 | `mocha --compilers js:babel-register` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1069 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1069 | `mocha --recursive test/bin` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1069 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1056 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1055 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1053 | `istanbul test _mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1050 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1049 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1048 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1046 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1045 | `mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1045 | `webpack && npm run lint && npm run mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1042 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1040 | `mocha --reporter spec --timeout 3000` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1036 | `standard && mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1036 | `mocha test/tests.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1034 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1031 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1029 | `mocha` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1027 | `mocha --recursive --bail --reporter spec test` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1025 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1022 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [jas/playground](https://github.com/jas/playground) | 1021 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [electron/asar](https://github.com/electron/asar) | 1015 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1014 | `mocha --check-leaks -R dot` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1011 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1009 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1000 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 998 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 997 | `mocha --colors ./test/*.spec.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 995 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 993 | `mocha --reporter spec --bail --check-leaks test/` | 
| [tomas/needle](https://github.com/tomas/needle) | 989 | `mocha test` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 989 | `mocha` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 988 | `mocha --recursive test/unit/` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 986 | `npm run lint && mocha --require @babel/register` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 986 | `standard && mocha -b` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 979 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 976 | `mocha --async-only` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 974 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 973 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 969 | `mocha -R list` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 956 | `npm run mocha:istanbul` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 949 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 948 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 947 | `mocha --timeout 5000` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 940 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 927 | `npm run convertto:es5 && npm run mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 924 | `mocha "client.test" --compilers js:babel-register` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 919 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 918 | `mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 917 | `npm-run-all test:jest test:server:mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 912 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 911 | `mocha ./test/index.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 910 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 909 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 909 | `mocha --compilers js:babel-register test/*.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 902 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 902 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 902 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 897 | `npm run lint && mocha -R spec` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 896 | `mocha -R spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 890 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 888 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 886 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 880 | `mocha tests` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 870 | `node_modules/.bin/mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 868 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 865 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 864 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 862 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 862 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 861 | `mocha -t 600000` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 861 | `mocha --timeout 200000` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 861 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 860 | `npm run lint && npm run mocha:no-functional` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 859 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 859 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 859 | `mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 852 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 851 | `eslint test && mocha --compilers js:babel/register` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 850 | `node_modules/.bin/mocha test/spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 849 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 841 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 839 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 838 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 837 | `mocha -t 5000` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 835 | `mocha --check-leaks -t 20000` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 833 | `mocha --reporter spec` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 833 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 832 | `mocha spec/*.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 831 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 830 | `standard && standard ./bin/* && mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 828 | `mocha test --compilers js:babel-register` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 825 | `./node_modules/.bin/mocha -R spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 824 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 823 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 822 | `istanbul cover -- _mocha --reporter spec` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 821 | `mocha test --compilers js:babel-core/register` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 821 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 819 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 815 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 813 | `npm run lint && mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 813 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 807 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 807 | `mocha --reporter spec --bail --check-leaks test/` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 804 | `mocha --reporter list` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 803 | `mocha --require babel-register` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 802 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 800 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 799 | `mocha` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 796 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 796 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 795 | `./node_modules/.bin/mocha --reporter spec` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 793 | `cake build && mocha ./test/mocha/*.coffee` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 790 | `mocha --timeout 30000 --recursive ./tests` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 789 | `mocha --async-only` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 788 | `mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 787 | `mocha test` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 784 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 783 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [edsu/anon](https://github.com/edsu/anon) | 782 | `mocha --colors --reporter spec test.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 782 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 778 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 776 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 773 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 771 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 769 | `xo && mocha -R spec` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 768 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 766 | `nyc --check-coverage mocha test/*.test.js` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 765 | `mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 764 | `npm run mocha-test test/integration` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 764 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 763 | `mocha test/index.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 760 | `mocha --ui tdd --require ./test/__setup` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 759 | `mocha --recursive ./test/*_spec.js` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 759 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 758 | `mocha --harmony --full-trace --check-leaks` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 742 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 742 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 741 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [developit/decko](https://github.com/developit/decko) | 739 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 737 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 736 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 734 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 732 | `mocha test` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 731 | `mocha --reporter spec` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 730 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 730 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 729 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 710 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 710 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 707 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 705 | `mocha -r should --reporter spec test/*.js` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 704 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 703 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 703 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 702 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 698 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 696 | `babel-node node_modules/.bin/_mocha -- test` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 695 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 695 | `mocha` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 693 | `./node_modules/.bin/mocha -t 60000` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 692 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 691 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 691 | `mocha --reporter spec build/test/index.js` | 