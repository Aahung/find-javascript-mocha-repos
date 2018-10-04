# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:13 10/04/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43754 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41420 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40415 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30396 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 26979 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24688 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 24650 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23753 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20253 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19290 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17485 | `npm run test:lint && npm run test:mocha` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17077 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17039 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15633 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14406 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14240 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13997 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13402 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13016 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12744 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12467 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12264 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12201 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11716 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11556 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11530 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10759 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10435 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10352 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10336 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10154 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10113 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10070 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 9670 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9469 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9430 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9290 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9248 | `mocha -b -r esm` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 9119 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9078 | `grunt mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8945 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 8918 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8891 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8612 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8556 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8471 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8357 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8277 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8243 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8119 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7943 | `npm run eslint && npm run mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7883 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7772 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7552 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7474 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7444 | `mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7429 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7417 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7409 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7328 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7277 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [almende/vis](https://github.com/almende/vis) | 7164 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7132 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6967 | `mocha $HARMONY_OPTS` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 6930 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6828 | `mocha; jshint *.js lib` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6815 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6688 | `mocha --exit --require @babel/register` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6648 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6590 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6368 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6344 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6282 | `npm run test:mocha:src` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6066 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6059 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6054 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6017 | `mocha tests/node.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5894 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5823 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5793 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5789 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5775 | `mocha && eslint lib/**` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5734 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5488 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5483 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5482 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5416 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5268 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5223 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5189 | `mocha src/**/*Tests.js --harmony` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5171 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5148 | `mocha --color` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5139 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5027 | `gulp lint && mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4920 | `mocha test` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4869 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4814 | `gulp build; mocha;` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4793 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4791 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4767 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4757 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4698 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4684 | `./node_modules/.bin/mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4634 | `mocha --recursive` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4568 | `mocha ./test/runner.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4562 | `npm run lint && npm run mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4542 | `mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4538 | `nyc mocha --exit` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4450 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4445 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4408 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4385 | `nyc mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4338 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4252 | `mocha -R spec src` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4205 | `mocha -R spec ./test --recursive` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4186 | `node_modules/.bin/mocha test/tests.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4184 | `nyc mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4172 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4139 | `mocha --timeout=15000 tests/*.test.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4086 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4082 | `npm run lint ; mocha && mocha test/individual` | 
| [teambit/bit](https://github.com/teambit/bit) | 4081 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4080 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4054 | `mocha --require test/babel-hook test/*.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4025 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [tj/ejs](https://github.com/tj/ejs) | 4017 | `mocha --require should --reporter spec` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3975 | `mocha --check-leaks --reporter spec --bail` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3950 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3902 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3871 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3803 | `nyc mocha "test/**/*.test.js"` | 
| [erming/shout](https://github.com/erming/shout) | 3798 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3720 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [primus/primus](https://github.com/primus/primus) | 3685 | `npm run build && mocha test/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3675 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3663 | `npm run jshint && npm run mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3634 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3597 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3577 | `mocha tests/javascript` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3573 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3566 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3554 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3554 | `mocha --reporter spec --timeout 3000` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3548 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3521 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3470 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3462 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3470 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3469 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3462 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3445 | `mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3372 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3358 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3319 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3298 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3269 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3243 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3191 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3176 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3169 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3166 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3148 | `./node_modules/.bin/mocha test/test.*.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3140 | `mocha test/*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3138 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3137 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3134 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3129 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3128 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3119 | `mocha test/index.js && npm run demo` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3091 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3085 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3081 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3064 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3057 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [mde/ejs](https://github.com/mde/ejs) | 2836 | `mocha --require should --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2831 | `istanbul cover _mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2829 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2822 | `mocha -R spec spec spec/reporters` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2820 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2812 | `mocha --require babel-register --recursive spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2806 | `node_modules/.bin/mocha --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2782 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2773 | `mocha --require should --reporter spec` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2771 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2758 | `mocha test.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2723 | `xo && mocha` | 
| [tj/should.js](https://github.com/tj/should.js) | 2716 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2705 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2667 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2651 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2641 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2622 | `nyc mocha --timeout=10000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2612 | `mocha-phantomjs ./test/index.html` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2608 | `mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2592 | `nyc mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2573 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2566 | `mocha "test/**/*-test.js"` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2524 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2511 | `mocha test/unit --require mochahook` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2507 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2506 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2501 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2482 | `mocha --reporter=spec test/*-test.js` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2478 | `mocha test/src/**/*.unit.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2466 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2659 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2653 | `mocha --timeout 100000` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2651 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2641 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2622 | `nyc mocha --timeout=10000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2612 | `mocha-phantomjs ./test/index.html` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2608 | `mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2592 | `nyc mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2573 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2566 | `mocha "test/**/*-test.js"` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2524 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2511 | `mocha test/unit --require mochahook` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2507 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2506 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2501 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2524 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2511 | `mocha test/unit --require mochahook` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2507 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2506 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2501 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2482 | `mocha --reporter=spec test/*-test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2482 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2478 | `mocha test/src/**/*.unit.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2466 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2447 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2417 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2417 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2399 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2373 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2370 | `mocha test/index.js --reporter dot` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2367 | `mocha test && npm run lint` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2356 | `mocha -R spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2354 | `grunt jshint && mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2341 | `mocha && eslint .` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2311 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2288 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2285 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2280 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [noble/noble](https://github.com/noble/noble) | 2278 | `mocha -R spec test/*.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2164 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2160 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2151 | `cross-env BABEL_ENV=test mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2140 | `standard && mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2136 | `nyc npm run _mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2129 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2126 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2116 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2112 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2094 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2089 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2062 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2062 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2059 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2058 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2051 | `mocha && eslint *.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2037 | `npm run lint && npm run mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2035 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2021 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2008 | `mocha --compilers js:babel-core/register __tests__` | 
| [slate/slate](https://github.com/slate/slate) | 1999 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1994 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1976 | `./node_modules/.bin/mocha && npm run jshint` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1971 | `mocha --require=test/test_helper.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1969 | `mocha --reporter spec --timeout 5000` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1930 | `mocha --require ./test/common --growl test/expect.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1924 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1915 | `npm run mocha && npm run karma` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1911 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1889 | `mocha --compilers js:babel-register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1885 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1884 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1848 | `mocha --reporter spec test/*.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1843 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1834 | `mocha tests --require @babel/register` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1823 | `mocha test` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1852 | `mocha && npm run lint` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1848 | `mocha --reporter spec test/*.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1843 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1834 | `mocha tests --require @babel/register` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1829 | `npm run lint && mocha --reporter spec test/*.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1819 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1814 | `mocha test/**/*.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1811 | `mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1809 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1800 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1797 | `mocha test -u bdd -R spec` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1785 | `npm run lint && npm run mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1759 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1819 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1818 | `mocha --reporter spec --grep .` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1816 | `mocha test` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1814 | `mocha test/**/*.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1811 | `mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1809 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1800 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1797 | `mocha test -u bdd -R spec` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1785 | `npm run lint && npm run mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1759 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1751 | `mocha ./test/basic.js -t 5000` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1744 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1679 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1674 | `mocha` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1672 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1671 | `mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1652 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1644 | `mocha spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1638 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1632 | `mocha tests/test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1620 | `mocha tests.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1616 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1608 | `mocha` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1672 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1671 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1667 | `mocha test/setup.js test/spec/*.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1662 | `xo && mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1652 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1644 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1640 | `mocha && size-limit` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1638 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1638 | `eslint --cache . && tsc && mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1633 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1632 | `mocha tests/test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1620 | `mocha tests.js` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1620 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1616 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1608 | `mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1607 | `mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1605 | `standard "./src/*.js" && mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1589 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1584 | `./node_modules/mocha/bin/mocha -R spec` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1580 | `mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1577 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1575 | `mocha --check-leaks --reporter spec --bail` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1569 | `mocha --reporter spec` | 
| [retejs/rete](https://github.com/retejs/rete) | 1568 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1563 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1557 | `mocha test.js` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1555 | `./node_modules/.bin/mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1549 | `nyc mocha --timeout=20000 test.js` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1543 | `npm run test:lint && npm run test:mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1541 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1539 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1530 | `node_modules/.bin/mocha --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1527 | `nyc mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1524 | `mocha --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1522 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1520 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1515 | `TEST=all mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1513 | `mocha -u tdd` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1458 | `mocha --timeout 10000 ./tests/lib.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1454 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1448 | `mocha test.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1445 | `mocha --check-leaks --require @babel/register` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1441 | `mocha test/unit` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1436 | `NODE_ENV=test mocha tests/*.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1434 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1433 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1427 | `mocha -R spec test/*.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1425 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1422 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1422 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1417 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1411 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1448 | `mocha test.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1445 | `mocha --check-leaks --require @babel/register` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1441 | `mocha test/unit` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1436 | `NODE_ENV=test mocha tests/*.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1434 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1433 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1427 | `mocha -R spec test/*.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1425 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1422 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1422 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1417 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1411 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1408 | `npm run lint && mocha && karma start --single-run` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1407 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1400 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1400 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1399 | `mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1394 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1392 | `istanbul cover _mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1385 | `mocha -R spec ./test/unit/**` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1383 | `npm run build && mocha -r should` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1383 | `mocha tests/test-*` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1382 | `./node_modules/mocha/bin/mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1376 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1372 | `mocha --opts test/opts/mocha.opts` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1370 | `mocha ./test/test*.js --reporter spec` | 
| [electron/devtron](https://github.com/electron/devtron) | 1364 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1364 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1359 | `mocha --reporter dot` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1359 | `cross-env NODE_ENV=test nyc mocha` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1349 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1349 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1346 | `mocha --recursive` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1339 | `npm run lint && npm run mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1338 | `./node_modules/.bin/mocha test` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1338 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1335 | `mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1330 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1328 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1327 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1320 | `NODE_PATH=. mocha **/*.spec.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1314 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1310 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1302 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1302 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1301 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1300 | `mocha-phantomjs tests/index.html` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1297 | `mocha` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1296 | `mocha spec/exec.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1294 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1294 | `mocha --recursive test/bin` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1288 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1287 | `mocha --timeout 60000 test/` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1286 | `mocha --check-leaks --reporter spec --bail test/` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1276 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1276 | `mocha --recursive test` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1274 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1274 | `mocha test/*.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1271 | `npm run prepublishOnly && mocha test/test.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1270 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1265 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1263 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1262 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1258 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1252 | `mocha tests` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1250 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1247 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1246 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1244 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1242 | `mocha src/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1237 | `npm run lint && npm run mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1233 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1230 | `istanbul test _mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1226 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1226 | `mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1225 | `mocha --compilers js:babel-core/register` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1220 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1218 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1213 | `mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1213 | `mocha test/test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1211 | `mocha --reporter spec` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1210 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1209 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1209 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1208 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1206 | `node ./node_modules/mocha/bin/mocha tests` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1205 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1199 | `webpack && npm run lint && npm run mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1198 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1198 | `mocha test` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1196 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1196 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1126 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1124 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1118 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1117 | `mocha test/*` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1112 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1110 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1109 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1109 | `mocha --timeout 30000 --recursive ./tests` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1106 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1096 | `webpack && mocha test/unit` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1096 | `mocha --reporter spec --bail --check-leaks test/` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1088 | `mocha --check-leaks -t 20000` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1088 | `mocha test --compilers js:babel-core/register` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1085 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1083 | `mocha --reporter spec --bail --check-leaks test/` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1137 | `istanbul cover _mocha test/*.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1137 | `mocha --timeout 20000` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1136 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1133 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1131 | `xo && mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1130 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1130 | `mocha $(find test -name '*.test.js') --exit` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1126 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1124 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1118 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1117 | `mocha test/*` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1112 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1110 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1109 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1109 | `mocha --timeout 30000 --recursive ./tests` | 
| [tomas/needle](https://github.com/tomas/needle) | 1037 | `mocha test` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1034 | `mocha --reporter spec --timeout 3000` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1032 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1031 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1025 | `npm run convertto:es5 && npm run mocha` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1022 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1021 | `mocha $(find test -name '*.test.js')` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1014 | `mocha --recursive -r tests/setup tests` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1009 | `mocha --check-leaks -R dot` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1005 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 999 | `mocha --colors ./test/*.spec.js` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1072 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1071 | `mocha --recursive --bail --reporter spec test` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1070 | `standard && mocha -b` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1068 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1063 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1063 | `mocha test/tests.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1055 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1052 | `mocha && standard` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1048 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1041 | `eslint src test && mocha --compilers babel-register` | 
| [tomas/needle](https://github.com/tomas/needle) | 1037 | `mocha test` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1034 | `mocha --reporter spec --timeout 3000` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1032 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1031 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1029 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1025 | `npm run convertto:es5 && npm run mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1022 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1022 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1021 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1021 | `mocha $(find test -name '*.test.js')` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1014 | `mocha --recursive -r tests/setup tests` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1009 | `mocha --check-leaks -R dot` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1007 | `mocha --recursive test/unit/` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1005 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 999 | `mocha --colors ./test/*.spec.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 992 | `mocha -R list` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 992 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 991 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 985 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 985 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 984 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 978 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 977 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 975 | `npm run rollup-cjs && mocha test/test.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 973 | `mocha --reporter spec` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 970 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 964 | `mocha --reporter spec --bail --check-leaks test/` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 963 | `mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 963 | `mocha test` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 958 | `mocha "client.test" --compilers js:babel-register` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 957 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 953 | `mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 951 | `mocha --compilers js:babel-register test/*.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 949 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 948 | `npm run lint && mocha -R spec` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 929 | `mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 928 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 928 | `mocha tests` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 918 | `mocha test` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 915 | `mocha -t 600000` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 910 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 905 | `./node_modules/.bin/mocha --reporter spec` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 903 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 901 | `./node_modules/.bin/mocha -R spec` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 901 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 910 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 905 | `./node_modules/.bin/mocha --reporter spec` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 903 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 901 | `./node_modules/.bin/mocha -R spec` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 901 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 901 | `mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 900 | `nyc --check-coverage mocha test/*.test.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 900 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 897 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 896 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 893 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 892 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 893 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 892 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 891 | `mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 890 | `mocha --recursive ./test/*_spec.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 889 | `node_modules/.bin/mocha` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 887 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 887 | `nyc mocha specs` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 887 | `./node_modules/.bin/mocha --globals angular,require` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 886 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 885 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 882 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 880 | `npm run lint && npm run mocha:no-functional` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 880 | `mocha test --compilers js:babel-register` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 878 | `istanbul cover -- _mocha --reporter spec` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 876 | `mocha -t 5000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 875 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 870 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 870 | `mocha --timeout 200000` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 876 | `mocha -t 5000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 876 | `standard && standard ./bin/* && mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 875 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 870 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 870 | `mocha --timeout 200000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 869 | `node_modules/.bin/mocha test/spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 866 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 866 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 859 | `mocha` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 858 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 857 | `eslint test && mocha --compilers js:babel/register` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 829 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 826 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 825 | `mocha && ember test` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 824 | `mocha` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 823 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 821 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 819 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 819 | `npm run build && istanbul test _mocha test/test.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 818 | `./node_modules/.bin/mocha test/**/*` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 814 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 811 | `mocha --harmony --full-trace --check-leaks` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 811 | `mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 809 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 824 | `mocha` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 823 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 821 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 821 | `mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 819 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 819 | `npm run build && istanbul test _mocha test/test.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 818 | `./node_modules/.bin/mocha test/**/*` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 814 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 814 | `mocha --async-only` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 814 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 811 | `mocha --harmony --full-trace --check-leaks` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 811 | `mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 809 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 809 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 781 | `xo && mocha -R spec` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 781 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 779 | `mocha test` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 778 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 774 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 768 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 765 | `mocha --recursive -s 15 test/` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 764 | `mocha --ui tdd --require ./test/__setup` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 764 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 763 | `nyc mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 762 | `mocha test` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 760 | `mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 791 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 790 | `mocha -r should --reporter spec test/*.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 790 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 787 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [developit/decko](https://github.com/developit/decko) | 785 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 784 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 781 | `xo && mocha -R spec` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 781 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 779 | `mocha test` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 778 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 774 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 