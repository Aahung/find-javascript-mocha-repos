# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:07 05/24/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 41630 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40574 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38437 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29520 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24010 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23253 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 22459 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22179 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 18836 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18326 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16234 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15798 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14260 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14103 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13400 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12687 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12402 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12252 | `./node_modules/.bin/mocha test/` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12137 | `mocha` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 12117 | `mocha --reporter spec` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12043 | `mocha --reporter spec test/*-test.js` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11714 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11085 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10903 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10451 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10312 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9903 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9680 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9677 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9625 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9598 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9138 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 8848 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8814 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8741 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 8635 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 8414 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8317 | `mocha test/test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8316 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8290 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8285 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8213 | `grunt clean:test && mocha --exit` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8181 | `mocha test/src` | 
| [amark/gun](https://github.com/amark/gun) | 8104 | `mocha` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8001 | `mocha --compilers js:babel-register test/test.js` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7937 | `mocha tests/*.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7915 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7729 | `npm run eslint && npm run mocha` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7648 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7566 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [dthree/cash](https://github.com/dthree/cash) | 7511 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7511 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7467 | `./node_modules/.bin/mocha test` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7438 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7320 | `npm run build && istanbul cover _mocha` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 7095 | `nyc mocha test/**/* -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7010 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6952 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6831 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 6824 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6811 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6762 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6750 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6653 | `mocha --compilers js:babel-core/register` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5823 | `mocha test node-test --recursive` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5786 | `mocha test/test.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5704 | `mocha tests/node.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5581 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5577 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5510 | `mocha; jshint *.js lib` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5488 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5405 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5337 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5269 | `mocha --timeout 10000 && npm run lint` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5191 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5157 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5156 | `mocha --color` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5704 | `mocha tests/node.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5581 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5577 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5510 | `mocha; jshint *.js lib` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5488 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5405 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5337 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5269 | `mocha --timeout 10000 && npm run lint` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5246 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5191 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5157 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5156 | `mocha --color` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5008 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4913 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4899 | `standard && mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4889 | `gulp lint && mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4834 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4811 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4715 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4687 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4672 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4639 | `gulp build; mocha;` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4635 | `mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4568 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4565 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4552 | `mocha ./test/runner.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4484 | `./node_modules/.bin/mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4449 | `mocha test` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4413 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4410 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4340 | `mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4320 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4315 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4221 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4187 | `mocha --recursive && make test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4173 | `NODE_ENV=test mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4128 | `nyc mocha --exit` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4087 | `nyc mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 4062 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4056 | `npm run lint && npm run mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3968 | `mocha --require test/babel-hook test/*.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3913 | `nyc mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3889 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3889 | `mocha -R spec ./test` | 
| [tj/ejs](https://github.com/tj/ejs) | 3886 | `mocha --require should --reporter spec` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3868 | `export TESTING=true; mocha --reporter list` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3841 | `npm run lint ; mocha && mocha test/individual` | 
| [erming/shout](https://github.com/erming/shout) | 3803 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3795 | `npm run lint && npm run mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3767 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3762 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3762 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3692 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3659 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3617 | `standard && mocha --timeout 60000 test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3578 | `npm run build && mocha test/*.test.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3563 | `mocha --check-leaks --reporter spec --bail` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3559 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3559 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3496 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3475 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3457 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3449 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3457 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3449 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3428 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3419 | `mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3418 | `nyc mocha "test/**/*.test.js"` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3400 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3400 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3386 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3375 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3330 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3327 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3325 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3292 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3239 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3153 | `NODE_ENV=test mocha test/**/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3119 | `node_modules/.bin/mocha test/tests.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3113 | `mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3112 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3112 | `./node_modules/.bin/mocha test/test.*.js` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3071 | `mocha` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 3059 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3054 | `nyc mocha && tsc` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3015 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3004 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3002 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3002 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2984 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2839 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2835 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2833 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2832 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2830 | `mocha -R spec --recursive src/test` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2830 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2798 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2787 | `istanbul cover _mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2765 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2759 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2745 | `mocha --opts mocha.opts` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2739 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2722 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2717 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2712 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2712 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2682 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2675 | `npm run mocha && npm run lint` | 
| [css/csso](https://github.com/css/csso) | 2662 | `mocha --reporter dot` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2660 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2648 | `export TESTING=true; mocha --reporter list` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2642 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2635 | `mocha --require babel-register --recursive spec` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2602 | `mocha-phantomjs ./test/index.html` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2586 | `mocha --recursive --watch` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2562 | `node_modules/.bin/mocha --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2560 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2550 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2540 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2522 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2515 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2504 | `mocha -R landing test/index` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2490 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2472 | `npm run build && cd test && mocha . --reporter dot` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2586 | `mocha --recursive --watch` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2562 | `node_modules/.bin/mocha --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2560 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2550 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2540 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2528 | `export TESTING=true; mocha --reporter list` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2522 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2515 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2504 | `mocha -R landing test/index` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2490 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2458 | `mocha --reporter=spec test/*-test.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 2454 | `mocha --require should --reporter spec` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2431 | `nyc mocha` | 
| [json5/json5](https://github.com/json5/json5) | 2430 | `nyc --reporter=html --reporter=text mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2425 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2472 | `npm run build && cd test && mocha . --reporter dot` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2458 | `mocha --reporter=spec test/*-test.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 2454 | `mocha --require should --reporter spec` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2431 | `nyc mocha` | 
| [json5/json5](https://github.com/json5/json5) | 2430 | `nyc --reporter=html --reporter=text mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2425 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2398 | `mocha test` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2389 | `mocha "test/**/*-test.js"` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2383 | `mocha test/src/**/*.unit.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2375 | `mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2367 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2362 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2356 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2351 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2340 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2338 | `grunt jshint && mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2337 | `mocha test/unit --require mochahook` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2082 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2080 | `mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2065 | `eslint . && mocha -t 5000` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2038 | `mocha --compilers js:babel-register` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2029 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [slate/slate](https://github.com/slate/slate) | 2010 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2005 | `standard && mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 1999 | `mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1967 | `mocha test/runner.js --reporter spec` | 
| [gajus/swing](https://github.com/gajus/swing) | 2185 | `mocha --compilers js:babel-register` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2154 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2142 | `mocha test && npm run lint` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2135 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2128 | `mocha && eslint .` | 
| [noble/noble](https://github.com/noble/noble) | 2105 | `mocha -R spec test/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2101 | `cross-env BABEL_ENV=test mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2092 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2082 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2080 | `mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1917 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1915 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1908 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1902 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1901 | `mocha --reporter spec --timeout 5000` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1879 | `mocha --require ./test/common --growl test/expect.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1878 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1870 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1867 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1866 | `mocha tests.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1864 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1853 | `nyc npm run _mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 1852 | `mocha --compilers js:babel-core/register './specs/**/*.spec.js'` | 
| [then/promise](https://github.com/then/promise) | 1848 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [share/sharedb](https://github.com/share/sharedb) | 1842 | `./node_modules/.bin/mocha && npm run jshint` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1841 | `mocha && eslint *.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1837 | `npm run lint && mocha -R dot && npm run cover` | 
| [kach/nearley](https://github.com/kach/nearley) | 1831 | `mocha test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1819 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1815 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1801 | `mocha --timeout 5000` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1796 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1795 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1795 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1786 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1786 | `mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1777 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1775 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1766 | `mocha --reporter spec && npm run test-typescript` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1766 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1761 | `npm run lint && mocha --reporter spec test/*.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1757 | `mocha -R spec spec spec/reporters` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1757 | `npm run mocha && npm run karma` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1750 | `mocha test` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [pahen/madge](https://github.com/pahen/madge) | 1724 | `npm run lint && npm run mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1723 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1718 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1715 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1711 | `mocha && npm run lint` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1702 | `mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1699 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1699 | `npm run lint && npm run mocha` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1694 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1691 | `mocha --reporter spec test/*.js` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1690 | `./node_modules/.bin/mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1686 | `mocha --reporter spec --grep .` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1655 | `mocha test/**/*.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1648 | `mocha test -u bdd -R spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1643 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1642 | `npm run lint && mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1636 | `mocha test/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1634 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1633 | `mocha test --timeout 600000` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1630 | `mocha ./test/basic.js -t 5000` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1625 | `mocha --expose-gc --slow 300` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1625 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1620 | `mocha tests/test.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1608 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1606 | `mocha && size-limit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1604 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1601 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1600 | `mocha spec` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1620 | `mocha tests/test.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1610 | `mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1608 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1606 | `mocha && size-limit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1604 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1601 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1600 | `mocha spec` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1591 | `mocha --compilers js:babel-register` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1589 | `mocha test/* --reporter spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1588 | `mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1581 | `npm run lint && npm run mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1557 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1548 | `./node_modules/.bin/mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1547 | `mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1538 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1527 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1523 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1513 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1509 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1508 | `mocha --reporter spec` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1500 | `npm run test:lint && npm run test:mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1442 | `mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1432 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1421 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1420 | `mocha --recursive` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1416 | `mocha test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1394 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1384 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [samccone/drool](https://github.com/samccone/drool) | 1447 | `mocha test/tests.js --timeout=10000` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1446 | `mocha test/setup.js test/spec/*.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1442 | `mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1434 | `mocha --check-leaks --reporter spec --bail` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1432 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1427 | `mocha` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1421 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1420 | `mocha --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1418 | `nyc npm run mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1416 | `mocha test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1394 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1384 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1368 | `./node_modules/mocha/bin/mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1350 | `istanbul cover _mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1349 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1348 | `mocha --timeout 10000 ./tests/lib.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1347 | `cross-env NODE_ENV=test nyc mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1341 | `mocha -R spec test/*.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1327 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1322 | `npm run build && mocha -r should` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1321 | `mocha test` | 
| [electron/devtron](https://github.com/electron/devtron) | 1312 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1305 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1304 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1298 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1298 | `mocha-phantomjs tests/index.html` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1291 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1284 | `./node_modules/.bin/mocha test` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1278 | `mocha` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1277 | `istanbul cover _mocha test -- --timeout 20000` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1274 | `mocha --check-leaks --require @babel/register` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1274 | `mocha spec/exec.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1274 | `mocha --recursive` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1269 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1263 | `nyc mocha --timeout=20000 test.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1260 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1260 | `mocha --opts test/opts/mocha.opts` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1256 | `mocha test/unit` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1252 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1245 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1244 | `mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1240 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1240 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1238 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1238 | `mocha test/*.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1235 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1232 | `eslint src && mocha && karma start --single-run` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1227 | `mocha tests` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1223 | `mocha` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1220 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1218 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1216 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1215 | `mocha --reporter dot` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1215 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1213 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1210 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1209 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1206 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1202 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1200 | `mocha test/**/*Spec.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1191 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1190 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1187 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1185 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1185 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1185 | `mocha tests/test-*` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1184 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1183 | `mocha test` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1183 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1180 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1174 | `mocha src/test.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1173 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1170 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1169 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1165 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1160 | `mocha --reporter spec` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1120 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1109 | `mocha -R spec ./test/unit/**` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1105 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1098 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1098 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1097 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1095 | `npm run prepublishOnly && mocha test/test.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1091 | `mocha $(find test -name '*.test.js')` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1089 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1089 | `NODE_ENV=test mocha tests/*.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1086 | `xo && mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1085 | `mocha test/*` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1084 | `mocha --recursive test` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1083 | `mocha ./test/test*.js --reporter spec` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1080 | `mocha` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1079 | `mocha --check-leaks -t 20000` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1079 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1078 | `NODE_PATH=. mocha **/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1073 | `istanbul cover _mocha test/*.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1098 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1098 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1097 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1095 | `npm run prepublishOnly && mocha test/test.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1091 | `mocha $(find test -name '*.test.js')` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1089 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1089 | `NODE_ENV=test mocha tests/*.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1086 | `xo && mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1085 | `mocha test/*` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1083 | `mocha ./test/test*.js --reporter spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1082 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1080 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1080 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1079 | `mocha --check-leaks -t 20000` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1079 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1078 | `NODE_PATH=. mocha **/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1073 | `istanbul cover _mocha test/*.js` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1072 | `mocha --compilers js:babel-register` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1070 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1066 | `npm run lint && npm run mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1065 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1082 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1080 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1080 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1079 | `mocha --check-leaks -t 20000` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1079 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1078 | `NODE_PATH=. mocha **/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1073 | `istanbul cover _mocha test/*.js` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1072 | `mocha --compilers js:babel-register` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1066 | `npm run lint && npm run mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1065 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1060 | `TEST=all mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1059 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1056 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1050 | `istanbul test _mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1048 | `mocha --compilers js:babel-core/register` | 
| [poooi/poi](https://github.com/poooi/poi) | 1047 | `mocha --recursive --harmony --require ./test/babelhook` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1045 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1045 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1042 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1040 | `mocha --reporter spec --timeout 3000` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1038 | `mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1038 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1035 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1031 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1031 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1031 | `webpack && npm run lint && npm run mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1030 | `mocha test/tests.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1027 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1026 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1020 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1020 | `standard && mocha` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1019 | `mocha --recursive --bail --reporter spec test` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1018 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1017 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1013 | `mocha --check-leaks -R dot` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1010 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1006 | `webpack && mocha test/unit` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1006 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [electron/asar](https://github.com/electron/asar) | 1005 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 998 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 997 | `mocha --colors ./test/*.spec.js` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 997 | `mocha $(find test -name '*.test.js')` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 996 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 994 | `mocha` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 993 | `mocha -t 120000 test/*.test.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 988 | `mocha --reporter spec --bail --check-leaks test/` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 985 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 984 | `mocha --recursive test/unit/` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 984 | `standard && mocha -b` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 980 | `mocha --reporter spec --bail --check-leaks test/` | 
| [tomas/needle](https://github.com/tomas/needle) | 979 | `mocha test` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 979 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 978 | `mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 974 | `mocha --async-only` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 973 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 971 | `mocha && standard` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 971 | `npm run lint && mocha --require @babel/register` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 968 | `mocha -R list` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 960 | `eslint src test && mocha --compilers babel-register` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 960 | `mocha --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 957 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 942 | `mocha --timeout 20000` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 942 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 941 | `mocha --recursive test/bin` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 938 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 938 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 937 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 931 | `npm run mocha:istanbul` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 920 | `npm run convertto:es5 && npm run mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 920 | `mocha "client.test" --compilers js:babel-register` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 915 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 920 | `npm run convertto:es5 && npm run mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 920 | `mocha "client.test" --compilers js:babel-register` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 915 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 914 | `mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 912 | `mocha spec/*.spec.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 910 | `npm-run-all test:jest test:server:mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 906 | `mocha --compilers js:babel-register test/*.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 905 | `mocha --reporter spec --bail --check-leaks test/` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 901 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 898 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 894 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 891 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 891 | `./node_modules/.bin/mocha --globals angular,require` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 888 | `npm run lint && mocha -R spec` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 886 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 885 | `mocha -R spec` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 884 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 875 | `mocha tests` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [jvalen/pixel-art-react](https://github.com/jvalen/pixel-art-react) | 870 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js 'test/**/*.@(js|jsx)'` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 868 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 867 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 866 | `node_modules/.bin/mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 862 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 861 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 860 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 859 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 858 | `mocha --timeout 200000` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 857 | `mocha` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 857 | `mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 855 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 854 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 850 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 850 | `eslint test && mocha --compilers js:babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 848 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 847 | `mocha -t 600000` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 843 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 838 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 834 | `mocha -t 5000` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 832 | `mocha` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 831 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 830 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 830 | `standard && standard ./bin/* && mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 830 | `mocha --check-leaks -t 20000` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 828 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 828 | `mocha --reporter spec` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 826 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 824 | `mocha spec/*.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 823 | `mocha test --compilers js:babel-register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 822 | `nyc mocha specs` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 822 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 820 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 818 | `./node_modules/.bin/mocha -R spec` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 816 | `istanbul cover -- _mocha --reporter spec` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 813 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 813 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 811 | `mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 806 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 803 | `mocha --reporter spec --bail --check-leaks test/` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 801 | `mocha --require babel-register` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 800 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 799 | `mocha --reporter list` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 798 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 797 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 796 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 795 | `mocha test --compilers js:babel-core/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 794 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 793 | `cake build && mocha ./test/mocha/*.coffee` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 789 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 783 | `mocha --async-only` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 782 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 781 | `mocha --colors --reporter spec test.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 781 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 779 | `./node_modules/.bin/mocha --reporter spec` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 777 | `npm run lint && mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 776 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 774 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 774 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 772 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 772 | `mocha test` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 770 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 770 | `xo && mocha -R spec` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 770 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 758 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 757 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 757 | `npm run mocha-test test/integration` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 756 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 756 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 755 | `mocha --ui tdd --require ./test/__setup` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 754 | `mocha -R spec src/**/*_test.js` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 752 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 752 | `nyc --check-coverage mocha test/*.test.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 752 | `mocha --harmony --full-trace --check-leaks` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 752 | `mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 750 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 749 | `mocha test` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 748 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 747 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 747 | `npm run build && istanbul test _mocha test/test.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 747 | `mocha --recursive ./test/*_spec.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 746 | `mocha --timeout 30000 --recursive ./tests` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 744 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 744 | `mocha` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 744 | `mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 743 | `mocha --recursive -s 15 test/` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 724 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 723 | `mocha --no-timeouts` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 722 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 719 | `mocha tests/*.mocha.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 719 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 716 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 711 | `npm run bundle && mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 711 | `npm run lint && npm run mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 711 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 710 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 702 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 700 | `mocha -r should --reporter spec test/*.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 699 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 698 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 698 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 695 | `mocha ./test/index.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 695 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 694 | `mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 691 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 691 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 691 | `./node_modules/.bin/mocha -t 60000` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 688 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 