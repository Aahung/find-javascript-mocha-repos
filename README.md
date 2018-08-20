# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:41 08/20/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43233 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41151 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39747 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30137 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 25868 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23214 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19794 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18985 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16808 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16586 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16808 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16586 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15214 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14330 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13976 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13514 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13149 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12725 | `./node_modules/.bin/mocha test/` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12645 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12323 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12237 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11820 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11493 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11202 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11166 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10470 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10157 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10118 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10115 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10034 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9963 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9642 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9389 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 9366 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9115 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9075 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9002 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8728 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8714 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8675 | `mocha tests/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8496 | `mocha test/test.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8468 | `mocha test/src` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8440 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8322 | `grunt clean:test && mocha --exit` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8301 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8171 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8065 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8001 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7899 | `npm run eslint && npm run mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7826 | `mocha --opts mocha.opts` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7712 | `./node_modules/.bin/mocha test` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7611 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7439 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7427 | `npm run build && istanbul cover _mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7239 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7224 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7218 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7050 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7048 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 7002 | `mocha --compilers js:babel-core/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6891 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6877 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6696 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6469 | `mocha; jshint *.js lib` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6462 | `npm run jshint && mocha test/` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6382 | `mocha --exit --require babel-core/register` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6260 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6223 | `mocha test/test.js` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6222 | `npm run test:mocha:src` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6219 | `mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6052 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5973 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5933 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5912 | `mocha tests/node.js` | 
| [shipshapecode/shepherd](https://github.com/shipshapecode/shepherd) | 5826 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5818 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5723 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5707 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5656 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5641 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5621 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5412 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5340 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5304 | `standard && mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5231 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5178 | `mocha src/**/*Tests.js --harmony` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5162 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5148 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5088 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5003 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4974 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4968 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4841 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4755 | `mocha test` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4752 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4740 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4737 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4735 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4694 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4629 | `./node_modules/.bin/mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4574 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4572 | `mocha ./test/runner.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4468 | `mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4439 | `mocha --recursive` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4435 | `nyc mocha --exit` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4434 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4419 | `npm run lint && npm run mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4407 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4162 | `mocha -R spec src` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4145 | `nyc mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4125 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4080 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4023 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4010 | `mocha --require test/babel-hook test/*.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4009 | `npm run lint ; mocha && mocha test/individual` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4007 | `mocha --timeout=15000 tests/*.test.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 3979 | `mocha --require should --reporter spec` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3921 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3895 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3880 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3856 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3841 | `mocha --check-leaks --reporter spec --bail` | 
| [teambit/bit](https://github.com/teambit/bit) | 3814 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [erming/shout](https://github.com/erming/shout) | 3805 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3668 | `standard && mocha --timeout 60000 test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3662 | `npm run build && mocha test/*.test.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 3627 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3577 | `mocha tests/javascript` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3552 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3527 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3527 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3521 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3527 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3527 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3521 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3466 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3466 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3465 | `node_modules/.bin/mocha test/lib/` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3455 | `NODE_ENV=test mocha test/**/*.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3441 | `mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3438 | `NODE_ENV=test mocha --exit` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3399 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3362 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3250 | `nyc mocha && tsc` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3248 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3247 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3226 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3191 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3173 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3160 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3145 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3143 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3128 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3094 | `mocha test/*.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3072 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2906 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2896 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2895 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2885 | `mocha -R spec --recursive src/test` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2880 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2867 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2866 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2855 | `mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2830 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2827 | `mocha -R landing test/index` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2825 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2812 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2809 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2779 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2771 | `mocha -R spec spec spec/reporters` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2771 | `mocha --require should --reporter spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2764 | `mocha test-node` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2867 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2866 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2855 | `mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2830 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2827 | `mocha -R landing test/index` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2827 | `istanbul cover _mocha` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2827 | `npm run mocha && npm run lint` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2825 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2812 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2809 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2779 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2771 | `mocha -R spec spec spec/reporters` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2771 | `mocha --require should --reporter spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2764 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2762 | `mocha --require babel-register --recursive spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2738 | `node_modules/.bin/mocha --reporter spec` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2450 | `mocha test/src/**/*.unit.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2448 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2445 | `mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2426 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2409 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2382 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2370 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2352 | `grunt jshint && mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2346 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2313 | `mocha test && npm run lint` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2310 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2307 | `mocha test/index.js --reporter dot` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2284 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2283 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2283 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2272 | `mocha && eslint .` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2233 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2228 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [gajus/swing](https://github.com/gajus/swing) | 2221 | `mocha --compilers js:babel-register` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2193 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2155 | `mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2352 | `grunt jshint && mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2346 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2323 | `mocha -R spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2307 | `mocha test/index.js --reporter dot` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2284 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2283 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2272 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2256 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [gajus/swing](https://github.com/gajus/swing) | 2221 | `mocha --compilers js:babel-register` | 
| [noble/noble](https://github.com/noble/noble) | 2195 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2193 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2155 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2146 | `cross-env BABEL_ENV=test mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2126 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2110 | `standard && mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2109 | `mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2095 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2146 | `cross-env BABEL_ENV=test mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2126 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2110 | `standard && mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2109 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2108 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2095 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2085 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2058 | `nyc npm run _mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2058 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2051 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2032 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2021 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [slate/slate](https://github.com/slate/slate) | 2004 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1986 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1981 | `mocha && eslint *.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1980 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1969 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1968 | `mocha -c test/index.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 1960 | `npm run lint && npm run mocha` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1946 | `mocha --reporter spec --timeout 5000` | 
| [share/sharedb](https://github.com/share/sharedb) | 1941 | `./node_modules/.bin/mocha && npm run jshint` | 
| [share/sharedb](https://github.com/share/sharedb) | 1941 | `./node_modules/.bin/mocha && npm run jshint` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1930 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1929 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1927 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1919 | `npm run lint && mocha -R dot && npm run cover` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1917 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1913 | `mocha --require ./test/common --growl test/expect.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1892 | `mocha test/*.test.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1883 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1878 | `mocha tests.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1868 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1851 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1841 | `mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1840 | `npm run mocha && npm run karma` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1838 | `mocha --reporter spec && npm run test-typescript` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1834 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1814 | `mocha --reporter spec test/*.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1813 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1811 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1806 | `mocha && npm run lint` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1804 | `mocha tests --compilers js:babel-core/register` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1800 | `mocha test` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1799 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1794 | `npm run lint && mocha --reporter spec test/*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1793 | `mocha --compilers js:babel-register` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1784 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1784 | `mocha --reporter spec --grep .` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1732 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1730 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1727 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1727 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1712 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1709 | `mocha ./test/basic.js -t 5000` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1707 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1698 | `mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1690 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1688 | `mocha test --timeout 600000` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1687 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1683 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1677 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1673 | `npm run lint && npm run mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1666 | `mocha test/* --reporter spec` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1658 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1606 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1602 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1601 | `mocha test` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1599 | `mocha test/setup.js test/spec/*.js` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1593 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1590 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1578 | `mocha tests.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1571 | `eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1571 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1570 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1562 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1551 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1545 | `npm run test:lint && npm run test:mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1638 | `mocha spec` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1636 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1632 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1629 | `mocha tests/test.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1626 | `mocha && size-limit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1606 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1602 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1601 | `mocha test` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1599 | `mocha test/setup.js test/spec/*.js` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1593 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1590 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1578 | `mocha tests.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1571 | `eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1571 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1570 | `./node_modules/mocha/bin/mocha -R spec` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1565 | `standard "./src/*.js" && mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1562 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1551 | `./node_modules/.bin/mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1546 | `mocha --reporter spec` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1545 | `npm run test:lint && npm run test:mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1538 | `mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1534 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1534 | `mocha test.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1533 | `nyc npm run mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1505 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1503 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1501 | `nyc mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 1494 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1487 | `mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1484 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1474 | `mocha test/**/*.spec.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1462 | `nyc mocha --timeout=20000 test.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1455 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1454 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1484 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1474 | `mocha test/**/*.spec.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1462 | `nyc mocha --timeout=20000 test.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1455 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1454 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1439 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1401 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1397 | `mocha --check-leaks --require @babel/register` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1387 | `istanbul cover _mocha` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1384 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1383 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1381 | `./node_modules/mocha/bin/mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1380 | `mocha test/unit` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1380 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1374 | `TEST=all mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1369 | `npm run build && mocha -r should` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1368 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1361 | `cross-env NODE_ENV=test nyc mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1356 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1354 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1354 | `npm run lint && mocha && karma start --single-run` | 
| [electron/devtron](https://github.com/electron/devtron) | 1350 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1344 | `mocha --opts test/opts/mocha.opts` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1343 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1340 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1338 | `istanbul cover _mocha test -- --timeout 20000` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1334 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1333 | `mocha tests/test-*` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1332 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1329 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1327 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1322 | `./node_modules/.bin/mocha test` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1322 | `standard && istanbul cover _mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1321 | `mocha --recursive` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1311 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1307 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1275 | `mocha ./test/test*.js --reporter spec` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1275 | `mocha --timeout 60000 test/` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1273 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1272 | `mocha -R spec ./test/unit/**` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1266 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1264 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1258 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1256 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1253 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1252 | `mocha test/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1250 | `mocha tests` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1248 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1241 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1236 | `mocha --recursive test/bin` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1262 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1258 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1258 | `npm run lint && npm run mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1256 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1253 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1253 | `mocha --check-leaks --reporter spec --bail test/` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1252 | `mocha test/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1250 | `mocha tests` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1248 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1247 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1241 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1236 | `mocha --recursive test/bin` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1233 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1225 | `mocha src/test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1225 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1224 | `npm run prepublishOnly && mocha test/test.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1222 | `mocha` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1210 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1210 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1209 | `npm run lint && npm run mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1204 | `mocha --reporter spec` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1202 | `mocha test` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1201 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1201 | `node ./node_modules/mocha/bin/mocha tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1201 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1193 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1192 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1192 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1192 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [variety/variety](https://github.com/variety/variety) | 1189 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1187 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1187 | `mocha --recursive test` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1186 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1181 | `mocha --compilers js:babel-core/register` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1118 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1117 | `istanbul cover _mocha test/*.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1115 | `npm run mocha:istanbul` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1105 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1105 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1103 | `mocha test/*` | 
| [poooi/poi](https://github.com/poooi/poi) | 1098 | `mocha --recursive --harmony --require ./test/babelhook` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1098 | `mocha --timeout 20000` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1096 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1082 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1081 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1081 | `mocha --compilers js:babel-register` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1076 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1071 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1071 | `webpack && mocha test/unit` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1069 | `mocha --recursive --bail --reporter spec test` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1125 | `mocha $(find test -name '*.test.js')` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1122 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1118 | `xo && mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1115 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1105 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1105 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1103 | `mocha test/*` | 
| [poooi/poi](https://github.com/poooi/poi) | 1098 | `mocha --recursive --harmony --require ./test/babelhook` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1098 | `mocha --timeout 20000` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1096 | `mocha` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1091 | `mocha --check-leaks -t 20000` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 945 | `mocha "client.test" --compilers js:babel-register` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 944 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 940 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 939 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 935 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 917 | `mocha tests` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 915 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 914 | `mocha spec/*.spec.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 913 | `mocha test` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 912 | `mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1042 | `mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1038 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1038 | `mocha --reporter spec --timeout 3000` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1035 | `mocha --timeout 30000 --recursive ./tests` | 
| [electron/spectron](https://github.com/electron/spectron) | 1027 | `mocha && standard` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1023 | `eslint src test && mocha --compilers babel-register` | 
| [tomas/needle](https://github.com/tomas/needle) | 1022 | `mocha test` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1020 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1020 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1018 | `mocha $(find test -name '*.test.js')` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1013 | `mocha --check-leaks -R dot` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1011 | `mocha --recursive test/unit/` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1038 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1038 | `mocha --reporter spec --timeout 3000` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1035 | `mocha --timeout 30000 --recursive ./tests` | 
| [electron/spectron](https://github.com/electron/spectron) | 1027 | `mocha && standard` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1023 | `eslint src test && mocha --compilers babel-register` | 
| [tomas/needle](https://github.com/tomas/needle) | 1022 | `mocha test` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1020 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1020 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1018 | `mocha $(find test -name '*.test.js')` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1013 | `mocha --check-leaks -R dot` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1011 | `mocha --recursive test/unit/` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1009 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1004 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1003 | `mocha --async-only` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 999 | `mocha --colors ./test/*.spec.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 993 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 993 | `mocha test --compilers js:babel-core/register` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 987 | `mocha -R list` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 987 | `npm run convertto:es5 && npm run mocha` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 984 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 979 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 978 | `npm-run-all test:jest test:server:mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 976 | `npm run rollup-cjs && mocha test/test.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 976 | `npm run rollup-cjs && mocha test/test.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 974 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 974 | `mocha --reporter spec` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 972 | `mocha` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 971 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 955 | `mocha` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 955 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 953 | `mocha --recursive -r tests/setup tests` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 945 | `mocha "client.test" --compilers js:babel-register` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 944 | `mocha --reporter spec --bail --check-leaks test/` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 944 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 943 | `mocha --compilers js:babel-register test/*.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 941 | `mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 940 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 940 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 939 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 935 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 929 | `npm run lint && mocha -R spec` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 922 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 917 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 917 | `mocha tests` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 915 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 914 | `mocha spec/*.spec.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 913 | `mocha test` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 912 | `mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 907 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 906 | `mocha spec/*.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 902 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 898 | `mocha -t 600000` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 894 | `mocha test` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 890 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 889 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 888 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 886 | `node_modules/.bin/mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 884 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 884 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 880 | `nyc mocha specs` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 878 | `mocha` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 877 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 876 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 876 | `mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 871 | `./node_modules/.bin/mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 869 | `./node_modules/.bin/mocha -R spec` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 868 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 867 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 867 | `mocha --timeout 200000` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 865 | `mocha -t 5000` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 865 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 864 | `npm run lint && npm run mocha:no-functional` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 863 | `istanbul cover -- _mocha --reporter spec` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 862 | `node_modules/.bin/mocha test/spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 861 | `mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 858 | `standard && standard ./bin/* && mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 857 | `mocha test --compilers js:babel-register` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 857 | `eslint test && mocha --compilers js:babel/register` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 855 | `nyc --check-coverage mocha test/*.test.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 855 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 852 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 848 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 848 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 846 | `mocha --recursive ./test/*_spec.js` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 844 | `istanbul cover _mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 843 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 843 | `mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 842 | `mocha --reporter spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 841 | `mocha --check-leaks -t 20000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 838 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 838 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 837 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 837 | `mocha --reporter list` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 835 | `npm run lint && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 833 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 831 | `nyc mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 820 | `mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 818 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 818 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 816 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 815 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 813 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 813 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 813 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 813 | `mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 811 | `mocha --async-only` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 806 | `cake build && mocha ./test/mocha/*.coffee` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 806 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 811 | `mocha --async-only` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 806 | `cake build && mocha ./test/mocha/*.coffee` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 806 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 803 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 799 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 798 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 798 | `mocha --harmony --full-trace --check-leaks` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 797 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 766 | `mocha --no-timeouts` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 764 | `mocha --ui tdd --require ./test/__setup` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 763 | `mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 761 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 760 | `./node_modules/.bin/mocha test/**/*` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 759 | `mocha -r should --reporter spec test/*.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 759 | `mocha --recursive -s 15 test/` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 755 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 750 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 750 | `mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 777 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 777 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 777 | `xo && mocha -R spec` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 775 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [developit/decko](https://github.com/developit/decko) | 771 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 770 | `mocha test` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 766 | `mocha --no-timeouts` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 764 | `mocha --ui tdd --require ./test/__setup` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 763 | `mocha` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 763 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 761 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 760 | `./node_modules/.bin/mocha test/**/*` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 759 | `mocha -r should --reporter spec test/*.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 759 | `mocha --recursive -s 15 test/` | 