# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:12 05/31/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 41819 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40627 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38546 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29581 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24059 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23321 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 22634 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22289 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 18918 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18373 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16279 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15863 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14339 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14119 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13447 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12719 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12460 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12292 | `./node_modules/.bin/mocha test/` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 12204 | `mocha --reporter spec` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12146 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12076 | `mocha --reporter spec test/*-test.js` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11809 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11120 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10970 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10517 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10386 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9956 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9699 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9699 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9666 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9639 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9151 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 8910 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 8894 | `mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8831 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8767 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 8702 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8409 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8364 | `mocha test/test.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8319 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8299 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8220 | `grunt clean:test && mocha --exit` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8200 | `mocha test/src` | 
| [amark/gun](https://github.com/amark/gun) | 8151 | `mocha` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8013 | `mocha --compilers js:babel-register test/test.js` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7990 | `mocha tests/*.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7930 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7548 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7514 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7486 | `./node_modules/.bin/mocha test` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7435 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7333 | `npm run build && istanbul cover _mocha` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 7155 | `nyc mocha test/**/* -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7051 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6999 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6861 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 6858 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6838 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6790 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6767 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6679 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6569 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5939 | `mocha` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5869 | `mocha test node-test --recursive` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5835 | `mocha --exit --require babel-core/register` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5827 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5713 | `mocha tests/node.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5602 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5590 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5509 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5407 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5368 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5304 | `mocha` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5275 | `mocha --timeout 10000 && npm run lint` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5713 | `mocha tests/node.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5612 | `mocha; jshint *.js lib` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5602 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5590 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5509 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5407 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5368 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5304 | `mocha` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5275 | `mocha --timeout 10000 && npm run lint` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5225 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5161 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5154 | `mocha --color` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4885 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [santinic/how2](https://github.com/santinic/how2) | 4719 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4693 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4674 | `mocha --reporter spec -t 8000` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4661 | `mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4591 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4586 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4555 | `mocha ./test/runner.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4507 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4492 | `./node_modules/.bin/mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4479 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4352 | `mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4555 | `mocha ./test/runner.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4507 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4492 | `./node_modules/.bin/mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4479 | `mocha test` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4416 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4352 | `mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4323 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4321 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4221 | `mocha -R spec ./test --recursive` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4202 | `NODE_ENV=test mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4195 | `mocha --recursive && make test` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4158 | `nyc mocha --exit` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 4105 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4092 | `nyc mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4083 | `npm run lint && npm run mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3968 | `mocha --require test/babel-hook test/*.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3924 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3905 | `mocha -R spec ./test` | 
| [tj/ejs](https://github.com/tj/ejs) | 3899 | `mocha --require should --reporter spec` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3887 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3875 | `export TESTING=true; mocha --reporter list` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3859 | `npm run lint ; mocha && mocha test/individual` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3832 | `npm run lint && npm run mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3803 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3787 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3771 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3763 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3698 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3661 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3618 | `standard && mocha --timeout 60000 test/test.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3587 | `mocha --check-leaks --reporter spec --bail` | 
| [primus/primus](https://github.com/primus/primus) | 3582 | `npm run build && mocha test/*.test.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3561 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3535 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3499 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3481 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3461 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3449 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3441 | `nyc mocha "test/**/*.test.js"` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3440 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3431 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3419 | `mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3418 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3406 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3388 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3361 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3339 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3332 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3330 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3261 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3181 | `NODE_ENV=test mocha test/**/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3153 | `node_modules/.bin/mocha test/tests.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3120 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3116 | `./node_modules/.bin/mocha test/test.*.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3113 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3112 | `mocha` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 3076 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3074 | `mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3074 | `nyc mocha && tsc` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3041 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3027 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3023 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2731 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2731 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2724 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2723 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2715 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2698 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2690 | `npm run mocha && npm run lint` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2678 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2678 | `xo && mocha` | 
| [css/csso](https://github.com/css/csso) | 2669 | `mocha --reporter dot` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2658 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2653 | `mocha --require babel-register --recursive spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2650 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2589 | `mocha --recursive --watch` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2586 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2579 | `node_modules/.bin/mocha --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2554 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2540 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2804 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2790 | `istanbul cover _mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2776 | `mocha --require should --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2769 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2761 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2756 | `mocha --opts mocha.opts` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2753 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2744 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2731 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2731 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2724 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2723 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2715 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2698 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2690 | `npm run mocha && npm run lint` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2678 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2678 | `xo && mocha` | 
| [css/csso](https://github.com/css/csso) | 2669 | `mocha --reporter dot` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2658 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2320 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2293 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2256 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2249 | `mocha -R spec` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2242 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2237 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2216 | `nyc --reporter=html --reporter=text mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2191 | `mocha --compilers js:babel-register` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2499 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2485 | `npm run build && cd test && mocha . --reporter dot` | 
| [mde/ejs](https://github.com/mde/ejs) | 2469 | `mocha --require should --reporter spec` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2457 | `mocha --reporter=spec test/*-test.js` | 
| [json5/json5](https://github.com/json5/json5) | 2445 | `nyc --reporter=html --reporter=text mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2441 | `nyc mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2426 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2408 | `mocha test` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2400 | `mocha "test/**/*-test.js"` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2387 | `mocha test/src/**/*.unit.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2386 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2384 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2381 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2372 | `mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2353 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2346 | `mocha test/unit --require mochahook` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1955 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1948 | `mocha --require=test/test_helper.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1936 | `mocha test/index.js --reporter dot` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1920 | `mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1919 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1915 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1914 | `mocha --bail --reporter spec --check-leaks test/` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1905 | `mocha --reporter spec --timeout 5000` | 
| [teambit/bit](https://github.com/teambit/bit) | 1892 | `mocha --require babel-core/register './specs/**/*.spec.js'` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1891 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1888 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1881 | `mocha --require ./test/common --growl test/expect.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1872 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1869 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1867 | `mocha tests.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1913 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1905 | `mocha --reporter spec --timeout 5000` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1901 | `mocha --compilers js:babel-core/register __tests__` | 
| [teambit/bit](https://github.com/teambit/bit) | 1892 | `mocha --require babel-core/register './specs/**/*.spec.js'` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1888 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1881 | `mocha --require ./test/common --growl test/expect.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1872 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1869 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1862 | `nyc npm run _mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1857 | `mocha && eslint *.js` | 
| [then/promise](https://github.com/then/promise) | 1853 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [share/sharedb](https://github.com/share/sharedb) | 1852 | `./node_modules/.bin/mocha && npm run jshint` | 
| [kach/nearley](https://github.com/kach/nearley) | 1832 | `mocha test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1823 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1815 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1803 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2052 | `mocha --compilers js:babel-register` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2032 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2012 | `standard && mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2012 | `mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2009 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1977 | `mocha test/ --no-timeouts` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1974 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1959 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1956 | `mocha -c test/index.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1955 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1920 | `mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1919 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1915 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1914 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1913 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1905 | `mocha --reporter spec --timeout 5000` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1901 | `mocha --compilers js:babel-core/register __tests__` | 
| [teambit/bit](https://github.com/teambit/bit) | 1892 | `mocha --require babel-core/register './specs/**/*.spec.js'` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1888 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1881 | `mocha --require ./test/common --growl test/expect.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1888 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1881 | `mocha --require ./test/common --growl test/expect.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1872 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1869 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1867 | `mocha tests.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1862 | `nyc npm run _mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1857 | `mocha && eslint *.js` | 
| [then/promise](https://github.com/then/promise) | 1853 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [share/sharedb](https://github.com/share/sharedb) | 1852 | `./node_modules/.bin/mocha && npm run jshint` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1842 | `npm run lint && mocha -R dot && npm run cover` | 
| [kach/nearley](https://github.com/kach/nearley) | 1832 | `mocha test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1823 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1815 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1803 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1801 | `mocha --timeout 5000` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1798 | `mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1797 | `mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1797 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1793 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1783 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1777 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1773 | `mocha --reporter spec && npm run test-typescript` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1771 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1766 | `npm run lint && mocha --reporter spec test/*.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1761 | `npm run mocha && npm run karma` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1760 | `mocha -R spec spec spec/reporters` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1754 | `mocha test` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [pahen/madge](https://github.com/pahen/madge) | 1732 | `npm run lint && npm run mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1663 | `mocha test/**/*.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1644 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1639 | `mocha test --timeout 600000` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1638 | `mocha test/*.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1636 | `mocha ./test/basic.js -t 5000` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1634 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1630 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1627 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1620 | `mocha tests/test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1613 | `mocha spec` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1611 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1608 | `mocha && size-limit` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1606 | `mocha --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1651 | `mocha test -u bdd -R spec` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1648 | `npm run lint && mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1644 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1639 | `mocha test --timeout 600000` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1638 | `mocha test/*.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1636 | `mocha ./test/basic.js -t 5000` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1634 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1631 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1630 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1627 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1620 | `mocha tests/test.js` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1615 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1613 | `mocha spec` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1611 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1608 | `mocha && size-limit` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1606 | `mocha --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1568 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1551 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1540 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1536 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1527 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1514 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1512 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1511 | `mocha --reporter spec` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1501 | `npm run test:lint && npm run test:mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1499 | `mocha compiled_tests/` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1494 | `eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1482 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1479 | `node_modules/.bin/mocha --recursive` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1476 | `standard "./src/*.js" && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1473 | `mocha tests.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1472 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1471 | `mocha -R spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1464 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1461 | `nyc mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1458 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1458 | `mocha test/setup.js test/spec/*.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1457 | `mocha test/**/*.spec.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1340 | `mocha test` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1327 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1327 | `npm run build && mocha -r should` | 
| [electron/devtron](https://github.com/electron/devtron) | 1316 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1310 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1309 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1299 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1297 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1294 | `mocha --check-leaks --require @babel/register` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1287 | `./node_modules/.bin/mocha test` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1285 | `nyc mocha --timeout=20000 test.js` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1282 | `istanbul cover _mocha test -- --timeout 20000` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1395 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1384 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1368 | `./node_modules/mocha/bin/mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1362 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1356 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1353 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1348 | `cross-env NODE_ENV=test nyc mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1344 | `mocha -R spec test/*.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1205 | `mocha tests/test-*` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1205 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1202 | `mocha test/**/*Spec.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1188 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1188 | `node ./node_modules/mocha/bin/mocha tests` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1187 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1186 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1183 | `mocha test` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1181 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1175 | `mocha src/test.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1169 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1166 | `mocha --reporter spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1166 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1161 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1158 | `npm run lint && npm run mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1158 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1153 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1153 | `mocha --check-leaks --reporter spec --bail test/` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1146 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1144 | `mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1136 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1136 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1131 | `mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1131 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1125 | `mocha -R spec ./test/unit/**` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1125 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1123 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1119 | `TEST=all mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1093 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1087 | `xo && mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1083 | `mocha test/*` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1083 | `npm run lint && npm run mocha` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1080 | `mocha --check-leaks -t 20000` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1080 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1078 | `NODE_PATH=. mocha **/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1075 | `istanbul cover _mocha test/*.js` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1072 | `mocha --compilers js:babel-register` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1070 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1069 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1067 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1052 | `istanbul test _mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1052 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1049 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1078 | `NODE_PATH=. mocha **/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1075 | `istanbul cover _mocha test/*.js` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1072 | `mocha --compilers js:babel-register` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1070 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1069 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1067 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1060 | `mocha --compilers js:babel-core/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1052 | `istanbul test _mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1052 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1049 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1028 | `mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1023 | `mocha --recursive --bail --reporter spec test` | 
| [jas/playground](https://github.com/jas/playground) | 1021 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1020 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1019 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1014 | `mocha --check-leaks -R dot` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1011 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1003 | `mocha $(find test -name '*.test.js')` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1000 | `mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 998 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 998 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 996 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 993 | `mocha --reporter spec --bail --check-leaks test/` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 987 | `mocha --recursive test/unit/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 987 | `mocha --reporter spec --bail --check-leaks test/` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 985 | `standard && mocha -b` | 
| [tomas/needle](https://github.com/tomas/needle) | 984 | `mocha test` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 906 | `mocha --compilers js:babel-register test/*.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 902 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 901 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 892 | `mocha -R spec` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 891 | `./node_modules/.bin/mocha --globals angular,require` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 880 | `mocha tests` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 953 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 948 | `npm run mocha:istanbul` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 948 | `mocha --timeout 5000` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 948 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 944 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 940 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 923 | `mocha "client.test" --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 944 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 940 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 923 | `mocha "client.test" --compilers js:babel-register` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 922 | `npm run convertto:es5 && npm run mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 918 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 916 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 838 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 838 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 833 | `mocha --check-leaks -t 20000` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 830 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 830 | `istanbul cover _mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 830 | `standard && standard ./bin/* && mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 826 | `mocha spec/*.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 824 | `nyc mocha specs` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 821 | `istanbul cover -- _mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 820 | `./node_modules/.bin/mocha -R spec` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 892 | `npm run lint && mocha -R spec` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 892 | `mocha -R spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 891 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 891 | `./node_modules/.bin/mocha --globals angular,require` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 888 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 884 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 880 | `mocha tests` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 869 | `node_modules/.bin/mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 838 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 838 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 834 | `mocha -t 5000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 834 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 833 | `mocha --check-leaks -t 20000` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 830 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 830 | `istanbul cover _mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 830 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 830 | `standard && standard ./bin/* && mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 828 | `mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 827 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 826 | `mocha test --compilers js:babel-register` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 826 | `mocha spec/*.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 824 | `nyc mocha specs` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 824 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 823 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 821 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 821 | `istanbul cover -- _mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 820 | `./node_modules/.bin/mocha -R spec` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 819 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 816 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 813 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 810 | `mocha test --compilers js:babel-core/register` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 805 | `mocha --reporter spec --bail --check-leaks test/` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 802 | `mocha --require babel-register` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 804 | `mocha --reporter list` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 803 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 802 | `mocha --require babel-register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 800 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 797 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 797 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 793 | `cake build && mocha ./test/mocha/*.coffee` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 790 | `npm run lint && mocha` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 790 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 788 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 787 | `./node_modules/.bin/mocha --reporter spec` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 787 | `mocha --async-only` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 783 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 782 | `mocha --colors --reporter spec test.js` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 781 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 779 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 777 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 776 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 773 | `mocha --timeout 30000 --recursive ./tests` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 771 | `mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 771 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 770 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 763 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 762 | `npm run mocha-test test/integration` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 761 | `mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 760 | `nyc --check-coverage mocha test/*.test.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 760 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 758 | `mocha --ui tdd --require ./test/__setup` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 757 | `mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 756 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 756 | `mocha test` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 756 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 755 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 755 | `mocha --harmony --full-trace --check-leaks` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 755 | `mocha -R spec src/**/*_test.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 753 | `mocha --recursive ./test/*_spec.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 749 | `npm run build && istanbul test _mocha test/test.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 749 | `mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 753 | `mocha --recursive ./test/*_spec.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 749 | `npm run build && istanbul test _mocha test/test.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 749 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 748 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 747 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 744 | `mocha --recursive -s 15 test/` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 744 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 743 | `mocha test/index.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 742 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 741 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [developit/decko](https://github.com/developit/decko) | 738 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 738 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 737 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 736 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 736 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 707 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 704 | `mocha -r should --reporter spec test/*.js` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 700 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 699 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 697 | `mocha ./test/index.js` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 696 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 691 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 691 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 691 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 718 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 717 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 713 | `npm run lint && npm run mocha` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 712 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 712 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [webpack-contrib/webpack-serve](https://github.com/webpack-contrib/webpack-serve) | 711 | `nyc npm run mocha` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 711 | `npm run bundle && mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 711 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 710 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 710 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 709 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 707 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 704 | `mocha -r should --reporter spec test/*.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 698 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 697 | `mocha ./test/index.js` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 696 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 693 | `babel-node node_modules/.bin/_mocha -- test` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 693 | `./node_modules/.bin/mocha -t 60000` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 691 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 691 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 691 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 690 | `mocha` | 
| [scality/S3](https://github.com/scality/S3) | 688 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 688 | `./bin/selenium-standalone install && mocha` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 652 | `mocha` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 650 | `mocha` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 648 | `mocha --recursive --compilers js:babel-core/register` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 648 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 648 | `mocha --bail test/` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 647 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 644 | `mocha --compilers js:babel-register src/**/*.spec.js src/*.spec.js` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 643 | `./node_modules/.bin/mocha` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 643 | `./node_modules/.bin/mocha --bail` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 640 | `mocha --compilers js:babel-register` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 638 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 674 | `./node_modules/.bin/mocha test/**/*` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 672 | `mocha -b -R spec test/*` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 672 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [substance/data](https://github.com/substance/data) | 669 | `mocha -R spec tests/run.js` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 667 | `mocha` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 666 | `mocha $(find test -name '*.test.js')` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 665 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 664 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 662 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 661 | `nyc mocha` | 